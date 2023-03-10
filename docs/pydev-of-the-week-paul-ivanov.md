# 本周 PyDev:保罗·伊万诺夫

> 原文：<https://www.blog.pythonlibrary.org/2019/10/07/pydev-of-the-week-paul-ivanov/>

本周，我们欢迎保罗·伊万诺夫([@伊万诺夫](https://twitter.com/ivanov))成为我们本周的 PyDev！Paul 是 IPython 和 Jupyter 的核心开发人员。他还是[软件木工](https://software-carpentry.org/)的讲师。你可以在保罗的[网站](https://pirsquared.org/index.html)上了解更多关于他的信息。你也可以通过访问他的 [Github 简介](https://github.com/ivanov)来了解他在开源方面都做了些什么。让我们花些时间来了解保罗！

![Paul Ivanov (courtesy of Robert Sexton)](img/3e1761bfab282cbf5281b1f8b24f34b5.png)

你能告诉我们一些关于你自己的情况吗(爱好、教育等)

我在莫斯科长大，10 岁时随家人移居美国。从那以后，我一直住在北加州。我在加州大学戴维斯分校获得了计算机科学学位。之后，我在加州大学伯克利分校攻读视觉科学博士学位。

我真的很喜欢计算的许多不同方面，无论是修补硬件(尤其是微控制器)还是尝试不同的操作系统和编程语言。除了键盘以外，我的主要爱好是耐力自行车。我有一辆带前车筐的旅行自行车，我骑了十几次 200 公里、两次 300 公里、两次 400 公里和一次 600 公里。我也写日记(纸笔类)，有时会变成诗歌，其中一些我已经上传到我的网站上。

**你为什么开始使用 Python？**

在大学里，我的室友菲利普·纽斯特伦和我的兄弟迈克·伊万诺夫开始了戴维斯维基(T1)，它是基于用 Python 实现的维基软件[moin moin(T3)开始的..我记得自己做了一些小的修补，尽管不懂这门语言，但还是取得了一些进展。它是如此直观和不言自明。](https://moinmo.in/)

当时，我正在学习计算机科学，所以我已经习惯了需要编译周期的“神职”语言，比如 C++、C 和 Java。我也曾通过我上的生物信息学课接触过 Perl，但其中有一大堆神秘的语法，除非有人向你解释，否则你无法理解。相比之下，Python 非常简单。

那是我第一次接触它，大约是在 2004-2005 年，但是我直到读研究生才开始经常使用它。我在学年还剩两个季度的时候提前完成了大学学业，申请了几所研究生院，几个月后我才得到回复。在此期间，作为后备计划，我在一家 Java 商店找了份工作。

在等待我正在开发的大型整体 Java2EE 项目启动或重新加载时(花了三到八分钟研磨所有这些企业 beans)，我开始使用 Ruby on Rails。与编译语言相比，它的交互体验令人耳目一新。再说一次，它很容易使用，尽管它有一点太多的魔力。比如为一个“人”建立模型，创建了一个叫“人”的表？！

2006 年，我开始在加州大学伯克利分校读研究生。我在杰克·格兰特的神经科学实验室的第一次实验室轮换是我第一次真正接触 Matlab，远远超过了我在线性代数入门课上学到的反斜线求解。同样，这是一种能够快速编写代码并进行交互实验的类似感觉，尤其是对于矩阵。但是对于与文件系统交互、尝试构建 GUI 或与数据库交互之类的事情来说，这是(现在仍然是)相当大的退步。我还对意外出现的内存不足错误感到沮丧，并且它的许可要求是不可行的。

我想拥有超越学术界的技能。Matlab 许可证对学生来说很便宜。当时我可以通过校园交易得到一个，但我知道这将是一个不同的行业故事。这是第一批双核笔记本电脑开始出现的时候，我当然想利用这一点。但是对于 Matlab，我需要每个处理器一个许可证！

Gallant 实验室的某个人有 Travis Oliphant 的“NumPy 指南”的 PDF 文档，所以我在[红杉理论神经科学中心](https://redwood.berkeley.edu/)的下一轮工作中开始使用 Python，最终我加入了 [Bruno Olshausen 的](https://redwood.berkeley.edu/people/bruno-olshausen/)实验室。幸运的是，在实验室和脑成像中心，有一些其他人也在使用 Python，我们和脑成像中心共用了一段时间的办公室。

你还知道哪些编程语言，你最喜欢哪一种？

我用 C、C++、Java、Go、JavaScript、TypeScript、Elm、Idris 和 Haskell 写过严肃的代码。当我为了乐趣而写代码时，让我感到特别头晕的是 Elm、Go 和 Idris。

我真的很喜欢 Elm，因为它最终提供了一条定期使用函数式语言的途径，并且简化了前端代码。Elm 架构已经通过 React with Redux 得到推广。这是我后来在 Go、Idris 和 Haskell 中开发基于个人用户界面的项目时使用的模式。它也是一种故意放慢速度的语言。我将 JavaScript 和现在的 TypeScript 视为“跑步机”语言——你必须坚持使用它们并不断向前跑，以跟上当前的实践，否则你将会落后。我很感激能够在六到八个月后回到埃尔姆，而在此期间整个世界都不在我的掌控之下。这有助于它是一个较小的社区，但我喜欢它感觉更安静。

Go 语言崇尚简单，反对聪明的解决方案。它附带的工具棒极了——从格式化到修正代码以解释 API 的变化，到能够通过改变一些环境变量来为多种架构*和*操作系统交叉编译二进制文件。没有什么比这更好的了。喜欢 Java(或 Clojure 或 Scala)等 JVM 语言的人可能会反对，因为编译过一次的同一个可执行 JAR 通常可以使用 Java 运行时在任何地方运行。然而，普通 Python 代码也是如此——它可以在任何有 Python 解释器的地方运行。使用 Go，您运行“GOOS=openbsd GOARCH=386 go build”的结果将是您的程序的可执行文件，它将在旧的 32 位硬件上的 openbsd 上运行。句号。无论您是在 Debian、Windows 还是 macOS 上运行该命令都没有关系。不管您的底层架构是 386、AMD64、ARM 还是其他受支持的架构。这是可行的，因为二进制文件不链接任何 C 库；它只是直接对内核进行系统调用。因此，您得到的是真正的独立二进制文件！

伊德里斯是最不同的。写代码你和电脑之间有对话。你会得到有用的反馈和模板生成，这是分形的:通过写下类型签名，你可以让编译器填充一个大的图片草图，放大一个块，并要求编译器填充更多的骨架。依赖类型给了我一种思考编程的新方法。这是我希望编程的未来走向。但是，在某些方面，Idris 是我所知道的语言中最不成熟和最学术性的。编译时间可能会很慢(尽管这种情况在正在进行的 Idris 2 中有了明显的改善)。而且这个社区相当小，所以没有大量现成的接口库。

因此，对我来说，Idris 可能同时是最有趣的，但也是最低效的编码方式。但是，这和我骑自行车的癖好很相似。在 A 点和 b 点之间旅行有很多种方式。你可以开车，你可以乘坐公共交通工具(无论是公共汽车还是火车)，或者你可以骑自行车，做些运动，听听风吹过头发时鸟儿的鸣叫。

很抱歉这种以美国为中心的旅行类比(撇开环境足迹和交通堵塞的现实)，但对我来说，在许多方面，Python 就像是驾驶我自己的汽车。通常，从 A 点到 b 点对我来说是最实际的选择。它会很快，我可以以可预测的速度走得很远。但是，实际可能会有点无聊。一开始肯定不是。我 18 岁就拿到驾照了，至今还记得开车有多好玩。旅程的目的地是次要的。

你现在在做什么项目？

在彭博的同事们的帮助下，我在过去的一年里每三个月在我们的旧金山工程办公室组织和主持一次为期两天的活动，以鼓励和促进 Jupyter 生态系统中的实验。我们称之为“开放工作室日”当前维基百科对“开放工作室”的总结抓住了我们希望在技术社区中更加突出的精神:“一个所有人都可以进入的工作室或工作室，在这里可以共同观看和创作艺术或创意作品。开放式工作室旨在培养创造力，鼓励在文化交流、对话、鼓励和自由表达的氛围中进行实验。”与 sprint 或 hackathon 不同，在 sprint 或 hackathon 中，目标是在最后产生一些具体的东西，我们努力的重点是强调有时我们只需要通过相互教学、进行讨论或只是分享我们可能有的一些感受和想法来探索和参与。

我也在帮助组织今年的 NumFOCUS 峰会。这是一个机会，来自开源项目的人们可以聚在一起，互相学习我们一直在做的事情，并找出如何发展我们的项目和社区。

我也有一段时间没有提交 Matplotlib 了。虽然我最近在那里不太活跃，但我确实在今年早些时候帮助汤姆·卡斯维尔发布了两个版本(2.2.4 和 3.0.3)，并在今年夏天发布了我的第一个个人版本(3.1.1)。在此之前，Tom 已经独自完成了几年的发布工作。我的计划是继续处理这些，我是 Matplotlib 3.2.0 的发布经理，该版本将于 9 月发布。

我还有六个尚未发布的个人项目，我在后台推进这些项目。我这样说并不是要戏弄或拒绝他们，而是要让新开发人员知道，拥有不与他人共享的辅助项目是可以的，甚至是值得的。我认为这是一项公共服务，这些年来我没有发布一堆半生不熟的代码，尽管有一些确实漏了出来。

**您喜欢使用哪些非 Python 开源项目？**

有太多的名字，但我想我必须从某处开始。不管我用的是什么操作系统，我都更喜欢 Vim 文本编辑器——尽管必要时普通的 vi 也不错。我使用 Debian、OpenBSD 和 FreeBSD 操作系统，GIMP 和 Inkscape 创建图形，用 Go、Idris、Elm 和 Haskell 编写代码。

你是如何加入 Jupyter 和 Matplotlib 社区的？

十几年前，在科学 Python (SciPy)生态系统中使用工具绝对是一件反文化的事情。一些边缘是锋利的，所以“出血边缘”在当时绝对是一个恰当的描述。

我提到了我如何在 2006 年开始读研，并在 2007 年开始使用 Python。一年后，IPython 的创始人 Fernando Perez 出现在校园里。那时，红杉中心已经搬到了校园里的另一栋大楼，所以我们不再与校园里的其他科学 Python 用户共享空间。这一举措的一个主要好处是，我们现在可以使用一种珍贵的、很难得到的商品:我们自己的会议室。所以，我们开始每周聚在一起，组成一个 py4 科学小组。我们会教对方如何编写 C 扩展，NumPy 和 SciPy、Matplotlib、SWIG 和 Weave 的不同子模块。

在 GitHub、Stack Overflow 和 Discourse 出现之前，邮件列表是大多数社区活动发生的地方。有一段时间，我在 Matplotlib 邮件列表上非常活跃。有一次，有人问是否有可能使用 Matplotlib 事件处理代码来支持多个后端中的交互性。我写了一个 Pong 的克隆来说明这确实是可能的——太疯狂了 [pipong.py](https://matplotlib.org/gallery/event_handling/pipong.html) 现在已经 10 多岁了！

你还有什么想说的吗？

回到我的“Python 就像开车”的比喻，我希望我没有劝阻任何人学习 Python 或继续使用它。无论如何，请做，我也会继续下去。我只是希望提醒人们，还有其他的交通方式可以利用:你可以驾驶船只，驾驶飞机，驾驶火箭，或者只是去散步。它们都有价值。

保罗，谢谢你接受采访！