# 本周 PyDev:奥列格·布罗伊特曼

> 原文：<https://www.blog.pythonlibrary.org/2017/01/09/pydev-of-the-week-oleg-broytman/>

本周，我们欢迎 Oleg Broytman ( [@phd_ru](https://twitter.com/phd_ru) )成为我们本周的 PyDev。Oleg 是 [SQLObject](http://sqlobject.org/) 项目的维护者。根据他们的网站"*" SQL Object 是一个流行的对象关系管理器，为你的数据库提供一个对象接口，以表为类，以行为实例，以列为属性。*”。你还可以看到 Oleg 是 via [Github](https://github.com/phdru) 和他的[网站](http://phdru.name/)的一部分。让我们花点时间来更好地了解 Oleg！

你能告诉我们一些关于你自己的情况吗(爱好、教育等)

我出生在苏联的中亚地区。我搬到了俄罗斯的莫斯科，在莫斯科国立大学计算机科学系学习计算机科学。我在 IBM PC 时代之前开始编程，我的第一台计算机是苏联的 [PDP-11](https://en.wikipedia.org/wiki/SM_EVM) 和 [IBM/360](https://en.wikipedia.org/wiki/ES_EVM) 的克隆体。

在我的专业工作之外，我花了很多时间和计算机在一起，参与自由软件项目。

除此之外，我过着平常的生活，和家人在一起，看书，听音乐，看视频。

**你为什么开始使用 Python？**

在 DOS 时代结束的时候，我已经习惯了写很多巨大的 bat 文件来自动化我用电脑做的每一件日常事务。我使用了许多助手程序和许多不同的命令行解释器(command.com 显然不能满足我的需求)。有一次，我的一个朋友和同事越过我的肩膀看到了那些剧本。他建议我应该尝试 Unix 中的 shell 脚本。

大约在 1995/96 年，当所有人都从 DOS 转到 Windows 95 时，我开始转到 Unix(最初是 BSD/OS 和 SunOS，后来是 Linux 和 FreeBSD)。我学习了 shell 脚本和所有那些小的子语言(awk、grep、sed 等等)。这真的很好，但我需要更多的东西，所以我尝试了一些更大更复杂的语言。大多数我都不喜欢。Perl 4.036 特别难；当然不是我喜欢的语言。

96 年 9 月另一个朋友建议我试试 Python。我开始观察它，发现它比我以前尝试的任何东西都更适合我的大脑。10 月，吉多·范·罗苏姆发布了 1.4 版本，我被说服了。我订阅了邮件列表@cwi.nl，剩下的就是历史了。20 年后我还活着。

你还知道哪些编程语言，你最喜欢哪一种？

*帕斯卡，尤指宾语帕斯卡。在切换到 Python 之前，我使用了许多不同的编译器(记住，我使用的是不同的 IBM 之前的 PC 架构和操作系统)。在 DOS 时代，主要是 Borland/Turbo Pascal。如果我现在放弃 Python，除了 web，我会使用 FreePascal。*

作为一名 web 开发人员，我编写了很多客户端 JavaScript。如果没有 Python，我会使用全栈 JS (NodeJS +客户端 JavaScript)进行 web 开发。

我依然热爱 shell 脚本，每天写大大小小的脚本。

你现在在做什么项目？

在职业上，我是一名从事医疗保健的程序员。最初这是偶然的，但现在我很高兴事情变成了那样。自 1990 年以来，我一直在国家研究外科中心的[远程医疗实验室](http://tele.med.ru/stat_pub.htm)工作(抱歉，我们的网站大部分在俄罗斯)。

在 20 世纪 90 年代，我使用 Turbo Pascal 开发计算机监控程序，该程序在心脏直视手术期间监控患者的状态，收集信息，将其呈现给麻醉师并保存到数据库中。大约在 1996/97 年，我开始使用 Python 来实现数据库的 web 接口。我仍在研究它——包括 Pascal 程序和 Python web 界面。

不幸的是，工资很低，所以我经常不得不找兼职来为我的家人赚钱。目前我正参与开发另一个认证机构。它不是自由软件，但我们发布了许多自由软件库:

*   https://github.com/SmartTeleMax
*   https://github.com/riffm
*   https://pypi.python.org/pypi/pygost

在自由软件的前沿，我是 SQLObject 的维护者。我在 2004 年开始使用它，大约在 2006 年加入开发团队，现在我仍然支持它。

哪些 Python 库是你最喜欢的(核心或第三方)？

不完全是库，而是开发工具。

虚拟环境。virtualenv 和 virtualenvwrapper。最近我在 virtualenvwrapper 中修复了 bash 完成的一个小问题，现在我推荐每个人都来试试。结合 setuptools 的强大功能和 pip 的便利性。

派斯特。我对它的技巧(重写断言)、详细的回溯和错误消息感到惊讶。

毒性测试。我使用它已经有一段时间了，但是直到最近我才开始理解它的声明式编程的强大之处。

斯芬克斯。flake8 我通过 vim-flake8 插件使用它。lxml(终于有库了！)

作为一门编程语言，你认为 Python 将何去何从？

向所有可能的方向。Python 用于科学和工业、医疗保健和 web 开发、密码学和数据库编程、大数据和深度学习神经网络、桌面、服务器、移动平台、GUI、命令行、守护程序、w32 服务、数百万个第三方库，可用于任何任务。Python 在很少领域是不合适的语言。

你对当前的 Python 程序员市场有什么看法？

糟糕，这次我必须承认我不知道。我很少换工作。自从 1990 年以来，我一直在 NRSC 工作。当我做承包商的时候，我通常工作很长时间——10-12 年。

但是当我寻找一份新合同时，我找到了，而且通常很快。

感谢您接受采访！