# 本周 PyDev:布莱恩·奥克利

> 原文：<https://www.blog.pythonlibrary.org/2015/03/02/pydev-of-the-week-bryan-oakley/>

本周，我们欢迎布莱恩·奥克利成为本周的 PyDev！我在各种 Python 相关的论坛和开发人员在线聚会上见过 Bryan 几次。他是 Tkinter 的大师，回答了很多关于它(和 Python)的问题，以及 StackOverflow 和其他地方的问题。我希望你能像我一样喜欢了解更多的东西。

你能告诉我们一些关于你自己的情况吗(爱好、教育等)

我认为对极客来说唯一重要的是 vi/emacs 和 windows/linux/osx，对吗？🙂

emacs 还是 vi？Emacs。我用同一个编辑器快 30 年了。

Windows/Mac/Linux？Mac，但仅略高于 linux。OSX 是编写必须在所有平台上工作的软件的实际选择。另外，在家里，我发现 Mac 的维护成本非常低。

从 20 世纪 80 年代中期起，我就开始专业地编写软件。我开始是一名 FORTRAN 程序员，学会了 C，然后是 perl、awk、sed、bourne shell，所有常用的 unix 工具。在接触 Python 之前，我成为了一名死忠的 Tcl/tk 程序员长达十多年。过去六年左右，我一直在使用 Python。我做了一年左右的 Java 工作。

我目前住在芝加哥郊区，但在成长过程中，我大部分时间都是在稍往南的俄克拉荷马州和阿肯色州度过的，只在得克萨斯州和科罗拉多州短暂停留过。我有几个孩子，最小的一个今年即将高中毕业。我是一个超级影迷，尤其是独立电影迷。我喜欢玩弹球。我大部分时间都倾向于穿夏威夷衬衫(这就是为什么我的 stackoverflow 图标是夏威夷衬衫)，如果天气(以及我目前演出的着装要求)允许，我会每天穿短裤和凉鞋。

**你为什么开始使用 Python？**

2009 年，我在芝加哥的 Orbitz 得到了一份工作，他们把我安排到了一个使用 Python 的团队。当时我不知道 Python，但对 Perl 和 Tcl 相当流利，所以我想他们认为我可以掌握它。有趣的事实:这是我做的第三份工作，我不知道我被雇佣使用的语言。我当时不知道的其他语言是 Tcl 和 Java。我一直有使用脚本语言的天赋，或者至少我很擅长在面试中让人们相信这一点。

Orbitz 的团队正在开发一个测试工具，这让我走上了我一直走的路，那就是在 QA 中编写软件工具(或者用我喜欢的说法，编写软件来测试软件)。自从 Orbitz 之后，我还做过另外两份工作，在一个支持自动化测试的团队中担任架构师和首席开发人员。

你还知道哪些编程语言，你最喜欢哪一种？

我已经接触了几种:FORTRAN、C、Perl、Tcl。我过去也写过几千行 LISP，以及 Ruby、Groovy、Java、C++和 Objective-C 的一知半解，还有常见的 unixy 嫌疑人如 bash、awk、sed 等。最近我写了相当多的 javascript。其中，FORTRAN、C、Tcl 和 Python 是我在职业生涯中使用最多的。

至于有喜欢的吗？很难说。简单的答案是 Python，因为这是我现在正在使用的。Python 和大量可用的模块有很多让人喜欢的地方。不过，老实说，即使经过几年的不断使用，我仍然不喜欢使用空白来定义代码块。我听到了所有的论据，但我不相信。好了，这会给你的读者一些评论！🙂

我仍然非常喜欢 Tcl 语言。这是一种后天习得的味道，大多数人从未习得，但在我使用过的所有语言中，Tcl 是最适合我大脑的一种。它是一种美丽的小语种。学习它花了我大约半天的时间，然后我就去参加比赛了。然而，Tcl 的社区如此之小，与 python 相比，它的软件包库相对较小，而且 Tcl 的工作数量很快接近于零，因此它在我的工具箱中变得越来越无关紧要。另外，它对 OO 的支持远不如 Python 好。

我希望有机会专业地使用 LISP，也希望使用 Groovy。我几乎没有使用过 Groovy，但是当我第一次遇到它的时候，我立刻就爱上了它。

你现在在做什么项目？

我正在为测试自动化构建工具。无论我的日常工作需要什么，为软件开发编写工具一直是我一直在做的事情。像所有优秀的(阅读:懒惰的)程序员一样，我喜欢编写工具来使我的工作变得更容易。

在 Orbitz，我开始研究测试自动化工具，并意识到这是一个非常缺乏像样工具的领域。当时大多数 QA 工具是用于管理测试用例，而不是编写它们；编写测试的实际过程是填写表格或创建工作文档。呸！一个. NET 程序员有 Visual Studio，ReSharper，一百万个工具供他们使用。Linux 和 OSX 开发者拥有类似的丰富工具。测试人员有什么？微软 Word？不过，随着 easyb、cucumber、specflow 等工具的出现，这种情况开始发生变化。

我已经把尽自己的一份力量来解决这个问题当成了一个小小的个人使命。从 Orbitz 开始，一直到我现在的工作，我们使用了一个叫做机器人框架(robotframework.org)的工具来进行自动化测试。这是一个很棒的框架，它使得编写对人类友好的测试用例成为可能，但是它背后有 python 的强大功能，所以你可以用它测试几乎任何东西。我写了一篇非常简短的博文，介绍我为什么喜欢这里:[http://boakley . github . io/2014/07/02/what-is-the-robot-framework](http://boakley.github.io/2014/07/02/what-is-the-robot-framework)。

即使机器人框架已经成熟，并且正在由一个非常小的团队积极开发，但官方 IDE 在我看来并不是很好。我见过很多人尝试使用它，然后切换并尝试使用标准文本编辑器(测试文件都是纯文本，所以您可以使用任何您想要的东西)。前一阵子我为 IDE 写了一些插件，了解了很多关于开发高质量测试的人们想要和需要的东西。

我有一个为严肃的测试人员构建在框架之上的专业级工具的愿景，并且我正在朝着这个愿景努力。我在上一个雇主那里取得了一些进展，但是他们不让我开源，所以我离开了。我现在的雇主，Echo Global Logistics([echo.com](http://www.echo.com))非常慷慨地让我将这些项目作为开源项目。我用 javascript 为奇妙的括号编辑器([括号. io](http://brackets.io/) )编写了一个机器人扩展，我还在开发一个 linter、一个查看测试文档的网站和一个收集测试环境中测试结果的仪表板，所有这些都是用 python 编写的。

哪些 Python 库是你最喜欢的(核心或第三方)？

并列第一名。我不得不说我用得最多的是机器人框架。它不仅是一个测试工具，而且它的大部分都以模块的形式提供，这使我有可能构建新的工具来处理机器人测试文件。

我第二喜欢的是 Tkinter，虽然更多的是出于感情的原因。我很少在工作中使用它。当我第一次学习 python 的时候，我刚刚用 Tcl/Tk 进行了十年的 UI 开发。我认为深入学习 python 的最好方法之一是回答技术问题。因为我是一名传统知识专家，所以我决定利用这一点，成为一名传统知识专家。所以，我开始回答尽可能多的关于栈溢出的 Tkinter 问题。当我回答我的第一个 Tkinter 问题时，我从未真正使用过 Tkinter。

我认为 Tkinter 是一个非常棒的 GUI 库，尤其是结合了 Python 面向对象的特性。许多人嘲笑它古老、丑陋、难学。在使用了几十年的 GUI 工具包后，我开始意识到大多数都是错误的，错误的并不重要。我永远不会使用 tkinter 来创建下一个 photoshop 或 itunes，但是对于大多数人编写的绝大多数 GUI 来说，它已经足够好了。

最近我也在一些内部网站和网络服务中使用 flask。我不是一个很好的 web 开发人员，但是 flask 使得将 web ui 和 restful 服务放在一起变得非常容易，而不必太担心管道问题。它让我将大部分精力集中在服务的实际数据业务逻辑上。

你还有什么想说的吗？

我真的很感谢你给我机会成为你博客的一部分。如果你的读者想要或者需要进入测试自动化，我强烈建议他们去看看 robot framework。不要让机器人 IDE 吓跑你——忽略它，使用括号或你选择的编辑器。

非常感谢！

### 一周的最后 10 个 PyDevs

*   [足球妈妈](https://www.blog.pythonlibrary.org/2015/02/23/pydev-of-the-week-maciej-fijalkowski/)
*   安东·诺沃西约洛夫
*   杰西·戴维斯
*   伊夫林·德米罗夫
*   [Andrea Gavana](https://www.blog.pythonlibrary.org/2015/01/26/pydev-of-the-week-andrea-gavana/)
*   蒂姆·戈登
*   道格·赫尔曼
*   玛格丽塔·迪利奥博士
*   [马里亚诺·莱因加特](https://www.blog.pythonlibrary.org/2014/12/29/pydev-of-the-week-mariano-reingart/)
*   巴斯卡尔·乔德里