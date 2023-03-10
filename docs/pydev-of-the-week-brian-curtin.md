# 本周 PyDev:布莱恩·柯廷

> 原文：<https://www.blog.pythonlibrary.org/2014/11/10/pydev-of-the-week-brian-curtin/>

本周，我们邀请布莱恩·科廷([@布莱恩 _ 科廷](https://twitter.com/brian_curtin))作为我们本周的 PyDev。他是 Python 语言的核心开发者，也是 Python 软件基金会博客的主要编辑。让我们花些时间来更多地了解布莱恩。

[![briancurtin](img/9d18eb2fdf136eb2223921a49aca5e97.png)](https://www.blog.pythonlibrary.org/wp-content/uploads/2014/11/briancurtin.jpg)

你能告诉我们一些关于你自己的情况吗(爱好、教育等)

我来自芝加哥，后来去了匹兹堡外的大学学习计算机科学，回到芝加哥，最近搬到了圣安东尼奥。作为一名球迷、球员和裁判，棒球是我生活中相当重要的一部分。我参加过很多比赛，在大学期间都参加过，从 11 岁起就开始担任裁判，在过去的 6 年里我一直称之为大学比赛。当我不写代码或做棒球运动的时候，我会作为一名竞技举重运动员进行训练

**你为什么开始使用 Python？**

有趣的故事:我父亲是贝尔实验室的 UNIX 黑客，后来进入了金融领域，他在 90 年代末进入了 Python。他偶尔会收到图书出版商的技术评论请求，并在 1998 年或 1999 年收到了 Alan Gauld 的《使用 Python 学习编程》的提前版本。我做了一些需要惩罚的事情，所以我必须读这本书，在爸爸的笔记本电脑上运行一些代码，并就此写一两页报告，他将报告连同他的书面报告一起发回给出版商。他们给了他 200 美元，最后他给了我，我买了一个很棒的棒球棒。那本书是我第一次接触任何编程，所以我第一次接触 Python 在技术上是一种惩罚。多么大的惩罚。

至于我真正开始使用 Python 的原因，是在 2004 年，在一门大学课程的一部分中，Python 与 Prolog 和 Java 一起被用于不同类型的编程语言，所以我开始学习一些基础知识。第二年夏天，我进行了一次实习，涉及到用 web 前端将一堆 Excel 文件转换成数据库，因此我了解了 pywin32 的 win32com 包，并做了一堆其他文本处理。

你还知道哪些编程语言，你最喜欢哪一种？

*我大学的大部分课程都是用 C++教的，然后我的第一份工作* *出校门就是一个大的 C++环境。那份工作中有一些 C# GUI* *工具，我开始使用它们，我真的很喜欢。*

*通过在 CPython 上工作，我写了一堆 C 语言，这是我最喜欢在 Python 后面使用的* *，我做的大部分 C 语言工作都是在 Windows 上完成的* *。我仍然有种奇怪的冲动，想拿出我的 Windows* *笔记本电脑，启动 Visual Studio 来破解 Win32 上的东西，就像我不久前做的一个小的* *项目，让解释器编写它的* *崩溃转储，用于事后调试。*

你现在在做什么项目？

太多了，但我主要在做两件事。

在 Rackspace，我正与几个人合作开发 OpenStack SDK，这是一个旨在改善 OpenStack 云贡献者、供应商和消费者体验的新项目。现在这种局面有点支离破碎，我们希望一个新的尝试将允许我们建立一些对每个人来说都更容易建立的东西。在 https://github.com/stackforge/python-openstacksdk 完全是 Python 和 100%开放的，这是我第一次与其他公司合作做日常工作项目。

另一个是我很久以来就想坐下来做的项目，但我已经开始和停止了很多次，我终于为它腾出时间了。美国职业棒球大联盟的高级媒体集团提供了大量的比赛数据，如自 2008 年以来每一次投球的速度和坐标。我写了所有的 scraper 和 parser 的东西，把它们都扔进了一个数据库，现在我只是在摆弄这些数据，看看我能找到什么，然后在[https://github.com/briancurtin/gd](https://github.com/briancurtin/gd)围绕这些数据开发一些工具。作为裁判，我真的很想看看我能从这些数据中得到什么。

哪些 Python 库是你最喜欢的(核心或第三方)？

我的大部分生活都是在标准图书馆里度过的。itertools 或者任何有 Raymond Hettinger 名字的东西都是我的最爱。像 configparser、argparse 和 unittest 这样的东西似乎是很多人向第三方寻求的，但它们对我来说都很好。在我心中有着永久位置的是 zipfile。我用它做一些事情，发现它不支持上下文管理器，所以这是我对标准库的第一个非文档贡献。不过，我想从那以后我就没用过它了。

我最近经常使用的一个第三方库是 sqlalchemy，用于我的棒球项目。它让事情变得简单多了，学习起来也很棒——我研究的所有东西都有很好的文档记录，这非常令人耳目一新。

感谢您的加入！

### 前一周的 PyDevs

*   卢西亚诺·拉马拉
*   沃纳·布鲁欣
*   浸信会二次方阵
*   本·劳什