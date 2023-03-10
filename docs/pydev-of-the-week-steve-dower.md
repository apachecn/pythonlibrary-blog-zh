# 本周 PyDev:史蒂夫·道尔

> 原文：<https://www.blog.pythonlibrary.org/2018/12/10/pydev-of-the-week-steve-dower/>

本周，我们欢迎史蒂夫·道尔( [@zooba](https://twitter.com/zooba) )成为我们本周的 PyDev！Steve 是 Python 语言本身的核心开发人员，他负责开发 Windows 版本和安装程序。他也为微软工作。他有一个[博客](https://stevedower.id.au/blog/)，不经常更新，但还是很有趣。你可以通过 [Github](https://github.com/zooba) 在开源世界看到他正在做的一些事情。让我们花一些时间来更好地了解史蒂夫！

你能告诉我们一些关于你自己的情况吗(爱好、教育等)

我在澳大利亚学习机电一体化、软件工程和计算机科学，然后在 2012 年移居美国，在微软工作。从那以后，我一直是微软最令人讨厌的人之一，告诉人们应该使用 Python，并试图给他们所有他们需要的借口，开始看到这种回报真的很令人兴奋。我们现在有成千上万的人在积极使用 Python，团队默认为他们的工具构建 Python 库(有时甚至在他们编写。NET 版本！)，我们有一个充满活力的社区，有聚会和内部会议，每个人似乎都在谈论 Python。

**你为什么开始使用 Python？**

我在学习期间的一份暑期工作是为一家初创公司设计医疗诊断设备。他们有这个神奇的定制的类似 MATLAB 的应用程序来控制他们的原型，所有的脚本都是用 Python 编写的。所以我花了一个夏天的时间驾驶水泵和马达，用 Python 阅读传感器，然后回到大学，再也没有真正回头！

你还知道哪些编程语言，你最喜欢哪一种？

我已经开发了很长时间(我不会说有多长时间，但我会说我在开始上大学之前就已经知道汇编语言了)，所以我遇到了很多语言。我真的很喜欢 C++，尤其是模板元编程，因为像 Python 一样，它让库开发者做了很多用户永远不知道的事情。我最喜欢的一个例子是 pybind11 为这种简单的声明生成的代码数量惊人。类似地，Python 3.4 中添加的 Enum 类背后有一些令人印象深刻的魔力，在简单使用它时，您不必知道或关心。

你现在在做什么项目？

我希望我能更多地谈论它们，但是发布和披露日期到处都是。这些天，我与微软的许多团队合作，帮助他们提高 Python 能力，无论是通过为他们做设计和代码审查，贡献或引导项目，还是在我们的共享工具中找到“差距”(例如，持续集成)，并确保它们被填补。我们的计划是确保你总能在 https://aka.ms/python 找到它们

哪些 Python 库是你最喜欢的(核心或第三方)？

我本质上是一个库开发者，所以任何让我编写更强大的库的东西都是一个好的开始。我是 Cython 和 pybind11 的超级粉丝，虽然我不常使用它们，但我也非常喜欢 [BeeWare](https://pybee.org) 工具，尤其是用于将应用打包到特定平台安装程序中的公文包。我也永远不会失去对请求的热爱，没有请求，我永远也不会尝试编写任何 REST API。

您有没有提交过或者在源代码中看到过的最喜欢的代码片段？

每当我们使用或分发开源软件时，我们都会出于知识产权的原因进行深度代码扫描，主要是为了确保所有声称受许可证保护的代码实际上都受该许可证保护。这里检测到的最常见的问题之一是代码从 StackOverflow(当时它仍然是 Creative Commons 许可的)复制到一个库中，并在未经许可的情况下被重新许可(专业提示:如果您获得了许可，请添加一条注释说明这一点)。每次 Python 进行这些扫描时，我们都会发现据称取自 StackOverflow 的代码片段，但是经过进一步的调查，StackOverflow 上的代码实际上取自 Python，并且通常是在十年或更早以前编写的！这些是我最喜欢的，因为它提醒人们 Python 已经存在了多长时间，每当我为这样一个强大而有影响力的项目做贡献时，它确实给人一种强烈的敬畏感。

你是如何成为 Python 语言的核心开发人员的？

老实说，时机很好。在主要的 Windows 专家打算退休的时候，我对帮助 Windows 支持，特别是安装程序很感兴趣。因此，当我开始接触我在 PyCon 已经认识的核心开发人员，并计划更新和改进安装程序时，他们非常乐意让我这样做，并将其视为一种贡献。我还将 Windows 版本转移到了更新更稳定的 C 运行时，这是当时最大的问题之一，并且能够利用我在微软的影响力来确保 Python 可以使用正确的工具和编译器，这让我们大大简化了[开发人员指南](https://devguide.python.org/setup/#windows)中的设置说明。

你还有什么想说的吗？

能够成为 Python 社区的一员，并在一个我可以帮助其发展的地方，我感到非常荣幸。我认为世界上没有任何一个技术社区像它一样。我还想公开感谢 Guido 在担任 BDFL 期间为英语所做的一切，并祝愿他退休后一切顺利。

史蒂夫，谢谢你接受采访！