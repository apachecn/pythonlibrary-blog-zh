# 本周 PyDev:蒂姆·戈登

> 原文：<https://www.blog.pythonlibrary.org/2015/01/19/pydev-of-the-week-tim-golden/>

本周的 PyDev 是 Tim Golden。他是 Python 软件基金会的成员，也是 Python 核心开发人员。Tim 还是几个 Python 邮件列表的版主或所有者。2013 年 4 月，Tim 获得了 [Python 社区服务奖](https://www.python.org/community/awards/psf-awards/)，“以表彰他在支持 Python 中的 Windows 管理界面以及在 comp.lang.python 上支持该代码和 Windows 用户方面所做的工作。”他[不时会写博客](http://ramblings.timgolden.me.uk/)，我建议查看他的文章。最后，Tim 是几个用于 Windows 的 Python 模块的作者，你可以在这里阅读关于[的内容。](http://timgolden.me.uk/python/)

让我们花些时间更好地了解他。

你能告诉我们一些关于你自己的情况吗(爱好、教育等)

我出生在伦敦南部的温布尔登地区。我在曼彻斯特的 UMIST 攻读计算机科学，然后搬回伦敦工作。我的第一份工作碰巧是在 VAX/VMS & Oracle 上，从那以后我就一直呆在关系数据库世界里。

我在伦敦工作了 25 年，我参与了伦敦西南部的青少年工作。我也足够幸运，能够凭听觉来弹钢琴，这使得娱乐人们变得容易，并且可以成为破冰者。我一直是阅读和公共图书馆的粉丝，我仍然经营着一个名为 goodtoread.org 的书评网站(既然你问了，那就是 Flask & Sqlalchemy ),但在过去的几年里，我真的没有时间去支持它。

**你为什么开始使用 Python？**

在 UMIST，我最后一年的项目是用 Modula-2 编写的，我很喜欢它，后来在伦敦南部的一个俱乐部教了一段时间编程。我去寻找一个更新的编译器，发现了 Python(1 . 5 . 2)——如你所知，它的灵感之一是 Modula-2。它就这么一拍即合，我真的没有回头。

你还知道哪些编程语言，你最喜欢哪一种？

我的基本工作是 SQL(微软的 T-SQL 方言)。你可以争论它是否是一种编程语言，但是如果你在数据操作领域工作，它肯定是很有能力的。出于这个原因，我不喜欢简单样板文件之外的 ORM:对我来说，它们只是学习做我已经能做的事情的另一种语言。(很明显，关于跨平台/数据库工作等有很好的论据。但是我主要在一个堆栈中工作)。

我可以用 C 语言编程(这对 Python 核心开发工作来说很方便)，但它从来不是我的第一语言；更像是一门称职的第二语言。这些年来，我做了一点这个，做了一点那个(Java，Cobol，Javascript 等等。)因为工作需要，但是虽然我对 Javascript 还不太精通，但我并不要求我对它们中的任何一个都很熟悉。真的，Python 把我惯坏了。

有些人提倡一年学习一门新语言，我很乐意有这个机会。当我听到朋友或阅读博客引用新语言中的好功能时，我总是很感兴趣(例如 Rust，Go，Dart，Pike，D &c)。不幸的是，我的时间已经过多了，所以我真的没有理由花那么多时间去学习新东西。

你现在在做什么项目？

在工作中，我主要关注的是数据仓库以及我们的系统和第三方系统之间的数据交换，我们刚刚将部分业务外包给了第三方。像往常一样，尽管这两个系统都是基于微软的工具栈(SSIS、SSAS、BizTalk)，Python 却在给轮子上油。我们有一个(stdlib-WSGI + pyodbc) web 应用程序，它为我们的日志记录表提供了一个简单的 web 接口；我们有一个(pyodbc，winsys & Pillow) Windows 服务，它可以拾取传入的图像，在将它们发送到 FTP 服务器以供拾取之前，对它们进行代码转换并调整大小；我们有一个(pyodbc + winsys + threading)可插拔监控服务，它可以监视各种活动，如新文件的到达、尚未迁移的数据库更新、传入的错误通知&等，并将它们记录到我们的日志表中。稍后阶段将添加系统日志通知到我们的内部系统日志服务器。

此外，我们的服务台系统完全是用 Python 编写的。(cherrypy + pyodbc +内部库)。我处理电子邮件的接收和通知、定时闹钟、网络访问以及其他我们处理的事情。它很棒，因为我们可以很容易地改变或添加东西。当然，这从来不是官方的优先事项，所以我们总是不得不围绕其他创收工作。

在工作之外，我努力寻找足够的空闲时间来做一些 Windows 核心开发工作。让史蒂夫·道尔和扎克·威尔重做 Windows 构建基础设施并修复问题是非常棒的。

我还试图制定一个计划，在那里我可以使用 RaspberryPi，Lego Mindstorms & Python 来吸引俱乐部的小伙子们。坦率地说，这并不容易，因为他们中很少有人天生就感兴趣，所以你必须在前面非常努力地工作，以便在短时间内得出一个可实现的结果，并且你可以在以后的基础上继续努力。

哪些 Python 库是你最喜欢的(核心或第三方)？

我想我很喜欢自己的库:wmi、active_directory、winshell、winsys 等等。尽管我很少使用它们中的一些，以至于我不得不重温我自己的源代码&文档来记住如何做某事！

除此之外，我不知道什么是“最喜欢的”,但是 pywin32 库和 pyodbc 一直是我工作工具的核心部分。虽然我自己现在很少用它，但我总是很乐意推广 Irmen de Jong 的 Pyro:它很成熟；它只适用于简单的情况，并且可以很好地扩展到更复杂的情况；它有很好的文档记录和很好的支持，而且使用起来很有趣。如果我想运行一个多机器、多进程的例子，我从 Pyro 开始。

是什么让你决定做“一屏 Python”这个项目？你能告诉我们更多吗？

*真的，这是 2013 年& 2014 年 PyConUK 的教育赛道。在这两种情况下，我们都有一群小学&中学老师试图解释什么能在课堂上帮助他们。我们听说，对于一个普通的中学班级来说，在典型的 45 分钟的课程中，一屏的代码就是老师所能完成的全部内容。显然，这一屏必须产生一些有形的东西，即使它是一些更大的项目的一部分。所以我开始考虑制作一些可以通过 github 分享的视频。*

从与老师的交谈中可以清楚地看到，他们在一个比我们开发人员可能想象的更受限制的环境中工作。在很多意义上:教师自身的能力和经验；学生理解事物的能力；它们运作的时间框架；他们可以使用的设施和工具，包括锁定的计算机和网络以及阻碍他们的系统管理员。因此，我自我强加的一部分职责是将第三方库保持在最低限度，但不是重新发明它们。有的老师可以随手安装第三方代码；其他人可以在经过官僚程序后这样做。例如，仅仅为了强调第三方代码而重新实现 PIL/枕头是没有意义的。

当然，现实是，现实生活已经开始，而我却无法给予它我想要的关注。但是这个项目仍然存在；它有自己的 github 组织,欢迎任何人投稿。我正在和我的公司讨论给我一些时间去学校帮忙；我不知道它是否会成功，但我真的希望能做些什么来帮助老师和孩子们。

你还有什么想说的吗？

*有人是多年的核心开发者和 PSF 会员；拥有或管理各种 Python 邮件列表的人；回复网站管理员@和星球@地址的人；管理和整理 python.org 基础设施的人；在各地组织代码道场和其他聚会的人；组织会议的人，例如英国 PyCon，我们在那里举办了两年的教育和儿童跟踪活动；获得 Python 社区服务奖的人；更多的人除了做更多的工作来使 Python 社区工作。不仅仅是语言本身，核心开发，而是围绕它的整个生态系统。*

不仅仅是 PSF 拥有或运营的方面，还有 python.org 的东西。还有广受好评的第三方工具，如 pip 工具链、pywin32 库、readthedocs、IPython 和 SciPy 社区，以及通过 PyPI 提供的许许多多的软件包。偶尔我会浏览一下 PyPI 提要，以便对围绕这种语言的大量活动有所了解。

我想说的最后一点是，我一直对 Python 社区的普遍尊重和礼貌印象深刻。当然，事情时不时会爆发，人们会变得激动。我们有很多非常聪明的人，他们有很多伟大的想法；肯定会有冲突。但一次又一次，我看到人们试图保持平衡，后退，回来为一时的爆发道歉，认识到除了他们自己还有其他有效的意见。在我看来，这种自我控制和自我意识的证据尤其重要，因为当前的热点话题之一是开发人员中一种不受控制的有害攻击。

**谢谢！**

### 前一周的 PyDevs

*   道格·赫尔曼
*   玛格丽塔·迪利奥博士
*   [马里亚诺·莱因加特](https://www.blog.pythonlibrary.org/2014/12/29/pydev-of-the-week-mariano-reingart/)
*   巴斯卡尔·乔德里
*   蒂姆·罗伯茨
*   汤姆·克里斯蒂
*   史蒂夫·霍尔登
*   卡尔查看
*   迈克尔·赫尔曼
*   布莱恩·柯廷
*   卢西亚诺·拉马拉
*   沃纳·布鲁欣
*   浸信会二次方阵
*   本·劳什