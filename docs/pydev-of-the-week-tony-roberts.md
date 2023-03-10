# 本周 PyDev:托尼·罗伯茨

> 原文：<https://www.blog.pythonlibrary.org/2021/09/27/pydev-of-the-week-tony-roberts/>

本周，我们欢迎托尼·罗伯茨成为我们本周的 PyDev！Tony 是 PyXLL 的创建者和维护者，这是一个微软 Excel 的付费插件，允许你使用 Python 编程语言编写 Excel。你可以在 [GitHub](https://github.com/tonyroberts) 上看到托尼还在做什么。托尼在[媒体](https://pyxll.medium.com/)和[上为数据科学网站](https://towardsdatascience.com/)撰稿。

![Tony Roberts](img/eee70ee4080aba61274cf8183472eb41.png)

让我们花些时间来更好地了解托尼！

你能告诉我们一些关于你自己的情况吗(爱好、教育等)？

当然可以！我从小就在以这样或那样的形式写软件。从小到大，我一直对编程感兴趣，但我想象自己会从事一些更基于硬件的工作，因为我更喜欢电子学。我在大学学习期间对软件开发变得更加认真，对计算机图形学最感兴趣。毕业后，我很幸运地找到了一份工作，和一些非常棒的开发者一起开发视频游戏。虽然这些天我花了很多时间在 Python 上，但我仍然对低级编程情有独钟。

后来我搬到了伦敦，在一家对冲基金的一个小团队里找到了一份工作。从视频游戏转到金融行业感觉是一个巨大的变化，我一点也不确定我是否在做正确的事情，但这是一个令人难以置信的团队，我非常喜欢与他们一起工作。从那时起，我开始意识到 Excel 对许多人的工作是多么重要，这也是我开始创建 Python Excel 插件 PyXLL 的原因。

我也很喜欢激流皮划艇。我从事这项工作的时间可能和我写代码的时间一样长！这是一项伟大的运动，它带我去过世界上一些令人惊叹的地方，比如赞比亚、厄瓜多尔和尼泊尔。我很幸运，距离英国的奥林匹克激流回旋球场只有很短的车程，虽然它与异国的偏远河流不一样，但它是一个很棒的训练设施，我经常利用它。

**你为什么开始使用 Python？**

当我还在上大学的时候，我在为一个客户开发一个 web 应用程序，我想大概是在 1999 年或者 2000 年。那是在每个网站都在使用 LAMP stack 的时候，Python 并没有真正引起很多人的注意。我参加了一个开发者大会，听到了一个关于 Python 的演讲，这是我第一次感兴趣的地方。我确实用 Perl 完成了应用程序的后端，因为不值得花费额外的时间和精力在中途切换语言，但是在业余时间，我开始用 Python 做一些业余项目。

几年后，当我发现自己在伦敦的一家对冲基金从事金融工作时，我才真正开始以专业的身份使用 Python。我参与的第一个大型项目是将基金从母银行继承的遗留系统迁移到新的第三方系统。这个第三方系统选择 Python(当时是 2.3)作为他们的脚本语言。所以，我们开始越来越多地使用 Python，直到我们创造的几乎所有新东西都是用 Python 写的。

真正让我震惊的是 Python 的可扩展性有多好。还有其他语言(可以说)也具有同样的表达能力或与 Python 兼容的特性，但没有多少语言能像 Python 那样简单地下降到 C 语言中来与本地库集成。我知道编写 C 扩展实际上是相对小众的，但这是我最喜欢的 Python 特性之一。

你还知道哪些编程语言，你最喜欢哪一种？

那是一个困难的问题！这些年来，我使用了很多不同的语言，从汇编语言到 Java 语言，以及介于两者之间的所有语言。他们都有自己的长处和短处。诀窍是决定哪种语言适合每项任务。我认为除了了解编程语言，我真正喜欢的是学习新的语言。学习一门新语言真的会让你思考你已经知道的其他语言。看到不同的人和社区如何对待事物是很有趣的。如果你只使用一种语言，我觉得你真的限制了自己作为一个开发者的能力。

我一遍又一遍反复学习的一种语言是 C++。当与 Python 开发人员谈论最喜欢的语言时，提起 C++似乎令人惊讶，但我真的很喜欢它。看着 C++进化和转变真是令人着迷。它与 10 年前的语言相去甚远，这令人震惊(以一种非常好的方式！).我的 Python Excel 插件 PyXLL 实际上大约有 80%是 C++语言，剩下的是 Python 语言(还加入了一些汇编语言！).

TypeScript 是我最近经常使用的一种，我真的很喜欢它。一开始我持怀疑态度，非常想继续使用普通的旧 Javascript。我很高兴我没有。一旦你进入这种语言，它真的令人印象深刻，围绕它的工具和反应意味着一旦你掌握了基本知识，你会有惊人的生产力。

你现在在做什么项目？

可以想象，运行 PyXLL 本身就是一项全职工作！在过去的几年里，我们真的成长了很多，我花了很多时间与用户交谈，了解他们如何工作以及他们需要 PyXLL 提供什么。我仍然做很多实际的产品开发，了解人们喜欢什么和不喜欢什么对我来说很重要，这样产品才能不断改进。

就在最近，PyXLL 增加了对“自定义任务窗格”的支持。这使您可以使用 PySide、PyQt、wxPython 或 Tkinter 等 Python GUI 工具包之一编写用户界面，然后 PyXLL 会在原生 Excel 任务窗格中无缝地托管它。这是 PyXLL 用户长期以来的要求，也是一个非常复杂的项目，有一些真正的技术挑战。一旦它准备好了，我就想到 Jupyter 笔记本可以在任何浏览器上运行，而 Qt 有一个浏览器插件...因此，使用这个新功能，Juypyter 笔记本可以托管在 Excel 任务窗格中！然后，将一切与同样运行在 Excel 中的底层 Python 内核挂钩就变得非常简单了。现在，您可以用 Python 编写代码，编写 Excel 函数和宏，并在 Python 和 Excel 之间移动数据，而无需离开 Excel。我仍然喜欢使用 Python IDE 来编写大量的代码，但是能够在 Excel 中用 Python 交互式地发挥创意和尝试一些东西真的很酷。

有趣的是，一个想法常常会像这样引出另一个想法。Excel 中的 Jupyter 笔记本并不是真正计划好的，它只是因为任务窗格功能而产生的。

哪些 Python 库是你最喜欢的(核心或第三方)？

除了通常的熊猫、小狗、熊猫等。有几个我会提到的，可能不太明显，在我看来，有时被低估了。pywin32 包对我职业生涯中的许多不同任务都非常有用。SqlAlchemy 也一直给我留下深刻的印象。

Mark Hammond 对 pywin32 包所做的工作令人难以置信。你可能会说，随着 ctypes 的加入，它不再像以前那样重要了，但它仍然是从 Python 访问 Windows APIs 的最简单的方法。win32com 包是经过深思熟虑的。即使对于 COM 的憎恨者来说，它也让编写 Windows 应用程序的脚本变得如你所希望的那样简单！

每当我用 Python 做数据库工作时，我都会使用 SqlAlchemy。我越深入了解它，我就越欣赏它的设计和它的工作原理。我喜欢“建筑的一部分”这个说法。它对于按需构建复杂的查询非常强大。

我可以继续命名我非常欣赏的 Python 包，但是我想我最感激的是存在的多样性和不断构建它的 Python 社区。我参与了许多开源项目，已经记不清参加了多少会议。Python 社区是非常独特的。

Python Excel 插件 PyXLL 是如何产生的？

2004 年左右，当我搬到伦敦时，我的职业发生了变化，从视频游戏转向了金融。我以前从未真正关注过 Excel，但显然，我知道它是什么。我真的很幸运，我和一些很棒的人一起工作，花了很多时间和交易员、量化分析师和开发团队之外的其他人一起工作。这些人是 Excel 大师，在 Excel 中生活和呼吸。我们构建的所有东西都是用 Python 编写的，所以这意味着任何对他们真正有用的东西都需要一种从 Excel 导入和导出的方法。

在那份工作中，我花了一些时间弄清楚 Python 和 Excel 如何通过 COM 进行交互。您可以用 Python 编写 Excel 可以使用的 COM 控件，也可以使用 Python 中的 COM 编写 Excel 脚本。这在一定程度上是可行的，但是它总是局限于你可以通过它的 COM API 使用 Excel 做的事情，而且非常慢。

我用 C#编写了 Excel 插件，这比使用 Python 和 COM 提供了更好的集成水平，我认为应该有更好的方法用 Python 来做同样的事情。

离开那家公司后，我不能放弃这个想法，想出了一种将 Python 嵌入 Excel 的方法，这种方法可以将 Python 函数动态地反映到 Excel 中。这需要一些非常复杂的代码来实现，但是我已经证明了这是可能的！我给几个人看了第一个版本，其中一个人当时负责伦敦 Python meetup，建议我在那里展示。在最初的几个星期和几个月里，我得到的反应是惊人的，我全身心地投入到构建第一个版本中，让它进入一些用户的手中。我认为我最满意的一件事是，那些第一批客户在 10 年后仍然是 PyXLL 的用户，我非常感谢他们的支持。

是什么让 PyXLL 比其他 Python Excel 包更好，比如 XLWings 或 OpenPyXL？

这些软件包确实非常不同，但这确实经常会引起混淆，因为从表面上看，它们似乎在处理同一类问题。

PyXLL 是唯一一个将 Python 解释器作为 Excel 插件嵌入到 Excel 中的工具。它允许您用 Python 编写 Excel 加载项。这就是你如何从 Excel 中直接调用 Python 函数，而不需要任何 VBA 或 COM 之类的东西。PyXLL 适用于那些想要编写自己的 Excel 插件来向 Excel 用户公开 Python 代码的人。通常，他们自己也是 Excel 用户，并且发现在 Excel 中使用 Python 函数库的组合对他们来说效果很好，但是经常是开发团队向非开发团队交付功能。例如，许多 PyXLL 用户是银行和对冲基金的交易团队，他们在 Excel 中工作，但需要访问 Python analytics。我总是喜欢说，有了 PyXLL，你可以像使用 web 浏览器一样使用 Excel 它只是让用户访问你的 Python 代码的前端。使用 PyXLL，Excel 用户通常甚至不知道他们正在做的是用 Python 编写的，因为一切都无缝地集成到 Excel 中。

OpenPyXL 是完全不同的东西。这是一个很棒的包，也是我经常向人们推荐的包。它用于读取和写入 Excel 文件，而不是扩展或使用 Excel 的实时实例。对于许多任务来说，这正是你想要的。如果您正在运行一个通宵批处理过程，必须通过电子邮件向团队发送报告，那么您真的不希望在 Windows 服务器上运行 Excel！OpenPyXL 理解 Excel 的文件格式，并直接处理这些格式，而不是处理 Excel 应用程序本身。

Xlwings 又不一样了。Xlwings 旨在用于编写 Excel 脚本，在 Windows 上使用 Excel COM API，在 macOS 上使用 AppleScript API。如果您需要与正在运行的 Excel 应用程序进行交互，例如，从实时电子表格中读取一些值或粘贴一些值，您可以通过 Excel 的 COM API 来完成。Xlwings 在此基础上提供了更高层次的抽象，但这并不等同于编写一个本机的高性能 Excel 插件，以 PyXLL 的方式将 Python 集成到 Excel 中。

PyXLL 被各行各业的公司和个人广泛使用。最常见的主题或用例是，人们正在开发或已经拥有一些 Python 代码，他们需要向 Excel 公开这些代码，以便作为某些分析的一部分进行交互调用。如果他们将 Excel 作为工作流的一部分，有时是为了他们自己，或者有时是为了在整个组织中推广以服务于所有 Excel 用户。例如，交易员用来进行实时决策的金融分析。据我所知，这不是任何其他产品都可以做到的。就在今天早上，我收到了一封电子邮件，有人告诉我 PyXLL 在为他们的房子重新融资时帮了我多大的忙！我永远不会厌倦听到 PyXLL 是如何被使用的，通常它与我开始时所设想的大相径庭。

托尼，非常感谢你接受采访！