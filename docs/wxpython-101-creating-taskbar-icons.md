# wxPython 101:创建任务栏图标

> 原文：<https://www.blog.pythonlibrary.org/2011/12/13/wxpython-101-creating-taskbar-icons/>

你有没有想过如何在 Windows 系统托盘中创建那些通常出现在屏幕右下角的小状态图标？wxPython 工具包提供了一种非常简单的方法来实现这一点，本文将带您完成这一过程。

## 编写代码

出于我不太明白的原因，我们想要的 wx 组件是 wx.TaskBarIcon，我假设之所以这么叫是因为系统托盘是任务栏的一部分，或者可能他们没有区分其他操作系统中的任务栏和托盘区域。无论如何，首先你需要一个图标来使用。你可以在任何你喜欢的地方得到你的图像。在这个例子中，我们将使用一个“信封”图像，我使用 wxPython 的 img2py 实用程序将它转换成 Python 代码。当您通过 img2py 运行一个图像时，您将得到如下结果:

```py

#----------------------------------------------------------------------
# This file was generated by img2py.py
#
from wx import ImageFromStream, BitmapFromImage
from wx import EmptyIcon
import cStringIO, zlib

def getData():
    return zlib.decompress(
'x\xda\x01\x86\x01y\xfe\x89PNG\r\n\x1a\n\x00\x00\x00\rIHDR\x00\x00\x00 \x00\
\x00\x00 \x08\x06\x00\x00\x00szz\xf4\x00\x00\x00\x04sBIT\x08\x08\x08\x08|\
\x08d\x88\x00\x00\x01=IDATX\x85\xed\x97[\x9a\x83 \x0c\x85Ol\xf7\x1566#\xec\
\xac,\xace\x1e\xe4b \xfa\xa9\xa3\xe5\xc5A\
\x94|\xdd\x81E\x80)y~|(\x17\xd6\xa2\x15"0\x87\xe8`\xc9\xdf\x00@\xd9v\x19\xb2\
\xf0|}-
图像数据都在 **getData** 函数中。我将把这个文件命名为“email_ico.py”。我们将把它导入到我们的主程序中，并调用它的 **getIcon** 方法来获取我们想要使用的图标。现在让我们来看看主要的应用程序:

```

import wx
from mail_ico import getIcon

########################################################################
class MailIcon(wx.TaskBarIcon):
    TBMENU_RESTORE = wx.NewId()
    TBMENU_CLOSE   = wx.NewId()
    TBMENU_CHANGE  = wx.NewId()
    TBMENU_REMOVE  = wx.NewId()

    #----------------------------------------------------------------------
    def __init__(self, frame):
        wx.TaskBarIcon.__init__(self)
        self.frame = frame

        # Set the image
        self.tbIcon = getIcon()

        self.SetIcon(self.tbIcon, "Test")

        # bind some events
        self.Bind(wx.EVT_MENU, self.OnTaskBarClose, id=self.TBMENU_CLOSE)
        self.Bind(wx.EVT_TASKBAR_LEFT_DOWN, self.OnTaskBarLeftClick)

    #----------------------------------------------------------------------
    def CreatePopupMenu(self, evt=None):
        """
        This method is called by the base class when it needs to popup
        the menu for the default EVT_RIGHT_DOWN event.  Just create
        the menu how you want it and return it from this function,
        the base class takes care of the rest.
        """
        menu = wx.Menu()
        menu.Append(self.TBMENU_RESTORE, "Open Program")
        menu.Append(self.TBMENU_CHANGE, "Show all the Items")
        menu.AppendSeparator()
        menu.Append(self.TBMENU_CLOSE,   "Exit Program")
        return menu

    #----------------------------------------------------------------------
    def OnTaskBarActivate(self, evt):
        """"""
        pass

    #----------------------------------------------------------------------
    def OnTaskBarClose(self, evt):
        """
        Destroy the taskbar icon and frame from the taskbar icon itself
        """
        self.frame.Close()

    #----------------------------------------------------------------------
    def OnTaskBarLeftClick(self, evt):
        """
        Create the right-click menu
        """
        menu = self.CreatePopupMenu()
        self.PopupMenu(menu)
        menu.Destroy()

########################################################################
class MyForm(wx.Frame):

    #----------------------------------------------------------------------
    def __init__(self):
        wx.Frame.__init__(self, None, wx.ID_ANY, "Tutorial", size=(500,500))
        panel = wx.Panel(self)
        self.tbIcon = MailIcon(self)
        self.Bind(wx.EVT_CLOSE, self.onClose)

    #----------------------------------------------------------------------
    def onClose(self, evt):
        """
        Destroy the taskbar icon and the frame
        """
        self.tbIcon.RemoveIcon()
        self.tbIcon.Destroy()
        self.Destroy()

#----------------------------------------------------------------------
# Run the program
if __name__ == "__main__":
    app = wx.App(False)
    frame = MyForm().Show()
    app.MainLoop()       

```py

第一个类基本上是直接从 wxPython 演示中复制出来的，并进行了一些简化。如果你需要一个更完整的例子，你可以去那里看看。总之，我们在子类 TaskBarIcon 中绑定了两个事件，分别允许我们关闭应用程序和显示菜单。您还会注意到，我们设置了在 **__init__** 中创建的图标，只需调用它的 **SetIcon** 方法并为它的工具提示传入一个字符串。
在 close 方法中，我们直接调用希望它关闭的框架。更好的方法是在这里使用 pubsub。如果你想停下来读一下 pubsub，我也写了一篇关于它的小文章。代码的其余部分非常简单明了。
现在我们可以继续到 wx。框架子类。这里我们基本上只是实例化了我们之前创建的 TaskBarIcon 类，并将框架绑定到**EVT _ 关闭**。你可能会对此感到疑惑。在 Windows 上使用任务栏图标有一些问题。如果我只是告诉框架关闭，它关闭得很好，但图标仍然存在，Python 只是挂在 lala land。如果你只允许用户使用任务栏图标的右键菜单来关闭，那么你可以添加一个 **RemoveIcon** 方法和一个 self。Destroy()就可以了(出于某种原因，RemoveIcon 不足以摆脱 TaskBarIcon，所以你也需要告诉它自我销毁)但是如果你允许用户按右上角的小“x”，那么你就需要抓住**EVT _ 关闭**并适当地处理它。当你抓住这个事件时，你不能仅仅调用 **self。Close()** 否则会陷入无限循环，这就是我们称 **self 的原因。反而破坏()**。
包扎
现在，您应该能够创建自己的 TaskBarIcon 应用程序了。我强烈建议看看 wxPython 演示，看看还能做些什么。我认为添加一个图标可以为你的应用程序增添一点光彩，特别是当你需要让它隐藏一段时间，然后在用户的命令下让它弹出来的时候。
进一步阅读

```

*   [创建一个闪烁的任务栏图标](http://wiki.wxpython.org/FlashingTaskbarIcon)
*   另一个博客的谈到了这个话题
*   TaskBarIcon [文档](http://www.wxpython.org/docs/api/wx.TaskBarIcon-class.html)

## 来源

*   [TBI_src.tar](https://www.blog.pythonlibrary.org/wp-content/uploads/2011/12/TBI_src.tar)
*   [TBI_src.zip](https://www.blog.pythonlibrary.org/wp-content/uploads/2011/12/TBI_src.zip)