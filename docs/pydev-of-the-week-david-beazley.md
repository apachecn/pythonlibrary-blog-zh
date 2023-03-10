# 本周 PyDev:大卫·比兹利

> 原文：<https://www.blog.pythonlibrary.org/2015/06/29/pydev-of-the-week-david-beazley/>

本周，我们欢迎大卫·比兹利([@达贝斯](https://twitter.com/dabeaz))成为我们本周的 PyDev！大卫是 [Python 基本参考](http://www.amazon.com/gp/product/0672329786/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=0672329786&linkCode=as2&tag=thmovsthpy-20&linkId=T6Y5MZTY3GM62UGL)的作者，也是 [Python 食谱](http://www.amazon.com/gp/product/1449340377/ref=as_li_tl?ie=UTF8&camp=1789&creative=390957&creativeASIN=1449340377&linkCode=as2&tag=thmovsthpy-20&linkId=WME3BUVQPQO24XSN)第三版的合著者。他还有一个[博客](http://www.dabeaz.com/blog.html)，那是我第一次学习 Python 时喜欢的，尽管我认为它已经不再更新了。不过，你可能会对他的 [Python 对话](http://www.dabeaz.com/talks.html)感兴趣。让我们花些时间去更好地了解他吧！

你能告诉我们一些关于你自己的情况吗(爱好、教育等)

在过去的 17 年里，我一直住在芝加哥地区，和我的妻子、孩子在那里扎根。我目前是自由职业者，大部分时间都在从事各种 Python 相关的项目，包括培训、咨询和写书。除了编程，我还喜欢演奏音乐、在商店工作和骑自行车。最近，我一直试图在气温低至零下 25 度的芝加哥冬季骑自行车外出。关于这一点有很多事情不太对劲，但它以其独特的方式带来了很多乐趣。至少，从整天盯着电脑屏幕中解脱出来是个不错的休息。

关于我的教育，大约从六年级开始，我就一直在玩电脑编程。我本科学习数学，但最终获得了计算机科学博士学位。作为一名大学教授，我还教授了大约七年的各种计算机科学课题。

**你为什么开始使用 Python？**

当我开始使用 Python (1996 年)时，我正致力于让计算物理学家更容易与运行在超级计算机上的模拟软件进行交互。标准做法是向系统提交非交互式批处理作业，在几个小时后卸载生成的数据，然后尝试使用运行在桌面上的各种数据分析工具来思考发生了什么。唯一的问题是，所有这些都没有真正发挥作用——或者肯定没有发挥出应有的效率(通常要花数周时间来做最简单的实验)。大约在 1995 年，我一直在尝试将脚本语言直接整合到我们的物理软件中，这样用户就可以更直接地与它交互。我熟悉诸如 MATLAB 和 IDL 之类的工具，并且一直在尝试根据我们的具体问题(分子动力学)定制一些东西。我甚至创建了一种自己开发的脚本语言和代码生成工具，后来被称为 Swig(是的，就是那个 Swig)。创建我自己的编程语言的想法不太符合我的博士委员会，他们建议我考虑一些替代方案。因此，我开始探索其他选项，包括 Tcl、Perl 和 Guile。我发现 Python 纯属偶然，因为我在 Paul Dubois 在《计算机物理学》中写的一篇文章中提到了它。作为题外话，Paul 一直在思考完全相同类型的问题(使物理软件可编程)，并积极参与许多工具的开发，这些工具后来成为 NumPy 和 SciPy 的前身。

没多久就在 Python 上把我卖了。我喜欢简单的语法，交互式 REPL 正是我想在我们的物理软件中拥有的那种东西。不仅如此，C 语言的实现非常简洁，易于使用。我最早的一个项目涉及到移植 Python 来运行在 Connection Machine 5 和克雷 T3D 大规模并行系统上。这有点疯狂——您可以像现在这样坐在交互式 Python 提示符下，但是无论您键入什么，都会在 1024 个 CPU 上同时执行。真正打动人们的是，我的小 Python 黑客可以解决以前需要 5-6 个小时才能解决的问题，并将它们减少到 4 秒左右。头脑被炸了。请记住，这远在 NumPy、SciPy、Pandas 或任何 Python 程序员现在认为理所当然的高级数据分析工具出现之前。对于那些对此类问题有强烈看法的人来说，在超级计算机上安装一种慢速解释语言并与数据进行交互的想法在很多层面上都是错误的。

你还知道哪些编程语言，你最喜欢哪一种？

我认为自己在 C 和汇编编程方面相当流利。我对其他语言有不同程度的经验，包括 C++、Objective C、Java、Perl、Tcl、Scheme、ML、PHP 和 Javascript，尽管如果我不得不做一些有用的事情，你可能会发现我埋头于书本或栈溢出。我最近发现自己在摆弄 Java，因为我的孩子一直在烦我制作 Minecraft mods。我可以到处走走，但是我不认为在可预见的将来我会去找一份 Java 程序员的工作。我真的需要探索一个更 Pythonic 化的解决方案。

至于喜欢的语言，那就难了。对于日常任务，Python 绝对是我的首选工具。然而，如果我不得不在我的整个职业生涯中选择一种最喜欢的语言，我认为它可能是汇编语言。我的第一份工作是为显卡编写设备驱动程序。我还花了很多时间埋头于汇编语言，学习如何在我的 Apple 2 上对街机游戏进行 mod 和逆向工程。汇编语言有一种原始的简单和美丽。还有一些不寻常的挑战，比如只能通过使用闪烁的灯或哔哔声来调试代码。这需要毅力和独创性的某种结合。然而，当你弄清楚的时候，看到你的代码最终工作了，这也是非常令人满意的。通过汇编编程，你还可以更深入地了解计算机和算法是如何工作的。

你现在在做什么项目？

我目前正处于将 Python 基础参考书更新到新版本的早期阶段。在过去的两年里，我也一直在为一家初创公司做一些软件开发。大部分代码都是非常典型的东西，包括数据库、web 服务、测试等等。我不认为自己是一名网络程序员，所以我实际上已经通过工作学到了很多新东西。

哪些 Python 库是你最喜欢的(核心或第三方)？

一般来说，我最喜欢的是内置库。很难指出最喜欢的，但我认为它可能是收藏模块。我觉得集合是这个秘密武器，让我解决各种棘手的数据处理问题。如果你不使用它，你可能会错过。纯粹为了好玩，我也喜欢多重处理.连接子模块。这里有一些巧妙的东西，可以用来在不同机器上运行的 Python 解释器之间建立经过认证的网络连接，在这些机器之间传递 Python 对象，以及做其他有趣的分布式计算之类的事情。

对于第三方模块，我最近大部分时间都在使用 SqlAlchemy、Pandas 和 requests。所有这些都很棒。我还花了相当多的时间使用与 Redis、ZeroMQ、AWS 和相关技术相关的模块。

你为什么决定写关于 Python 的书？

当别人问我“不”的时候，我拒绝说“不”,从而开始写书。我曾在 1998 年担任 Python 会议的项目主席，会议结束后不久，New Riders publishing(后来并入 Pearson)的一名编辑联系我，询问我写一本 Python 书籍的可能性。当时，其他 Python 书籍屈指可数。在过去的编程工作中，我从诸如著名的 Kernighan 和 Ritche 的《C 编程语言》以及 W. Richard Stevens 的关于高级 Unix 编程的书籍中发现了很大的用处。我认为尝试以类似的方式写一本 Python 书籍可能会很有趣。所以，这最终导致了 Python 基本参考的出版。

最近的 Python 食谱(O'Reilly)有一个稍微不同的解释。我越来越被所有关于使用 Python 3 的借口和道歉所困扰。因此，对于这本书，我决定尽最大可能拥抱 Python 3，并尽我所能写一本最现代的 Python 书——而不关心 Python 2。这样做有一定的风险，但是如果 Python 有一个光明的未来，我觉得它应该由前瞻性的书籍来服务。

作为一门编程语言，你认为 Python 将何去何从？

鉴于围绕 Python 2 和 3 的普遍混乱，这是一个有趣的问题。使用 Python 3 已经六年了，它有很多非常棒的地方值得我喜欢。然而，它在一些关键领域也有很大的不同——如果人们选择使用它，他们将不得不接受这一点。尽管肯定会有一些项目永远不会迁移到 Python 2，但是没有理由为什么您现在不能开始在 Python 3 中创建新项目。总的来说，编程的世界总是充满了混乱和烦人的问题——这是 Python 一直擅长的事情。出于这个原因，我真的不认为它会很快消失。

你对当前的 Python 程序员市场有什么看法？

我并不太关注 Python 的就业市场。然而，我不知道有失业的 Python 程序员，所以这可能是一个好迹象。

你还有什么想说的吗？

Python 一直是一门实用而有趣的语言——用它编程应该是令人愉快的。如果没有，你可能做错了什么。

### 一周的最后 10 个 PyDevs

*   升降杆
*   塔里克·齐亚德
*   斯蒂芬·德贝尔
*   安娜·奥索斯基
*   加布里埃尔·佩蒂尔
*   [瓦苏德夫拉姆](https://www.blog.pythonlibrary.org/2015/05/18/pydev-of-the-week-vasudev-ram/)
*   [Julien Danjou](https://www.blog.pythonlibrary.org/2015/05/11/pydev-of-the-week-julien-danjou/)
*   马特·哈里森
*   阿迪娜·豪
*   [诺亚礼物](https://www.blog.pythonlibrary.org/2015/04/20/pydev-of-the-week-noah-gift/)