# 本周的 PyDev:或者 Carmi

> 原文：<https://www.blog.pythonlibrary.org/2020/08/03/pydev-of-the-week-or-carmi/>

本周我们欢迎 Carmi([@ lilight](https://twitter.com/liiight))成为我们的本周 PyDev！或者是[通知者](https://github.com/liiight/notifiers)的创造者和维护者。通过查看他的 [Github 简介](https://github.com/liiight)，你可以知道他还在做什么。

让我们花些时间去了解或者更好！

你能告诉我们一些关于你自己的情况吗(爱好、教育等)

我叫卡尔米。我 38 岁，住在以色列，已婚，有 4 个男孩。我有 2 只狗，4 只猫，一只非洲灰鹦鹉，一只兔子和一只白头翁(查一下？？？？).我目前在 Proofpoint 担任高级 QA 自动化工程师。

当我还是个孩子的时候，我开始学习编程，当时我的父亲是一名为银行工作的程序员，他教我 GW basic。2 年级的时候学了 Logo，这是 python 的乌龟库所基于的。我在高中也继续学习计算机。我试图获得一个工程学位，但我无法在学术界赢得与多动症的斗争。

**你为什么开始使用 Python？**

在了解到一个叫作 [Flexget](https://flexget.com/) 的神奇工具之后，我对 python 产生了兴趣。我想调整它以符合我的需要，并进入它的代码。它的维护人员非常友好和专业，帮助我解决我的任何问题，无论是 python 还是代码库。在为它做了几年贡献之后，我成为了它团队的一员，并且一直为它工作到今天

你还知道哪些编程语言，你最喜欢哪一种？

以前，我对 C#和 Ruby 略有涉猎，但我职业生涯的绝大部分时间都在使用 Python，这是我最喜欢的语言。

你现在在做什么项目？

我是[通知程序](https://github.com/liiight/notifiers)的创建者和维护者，也是 [Flexget](https://github.com/Flexget/Flexget) 的维护者，尽管这些天我很少有时间从事 OSS 方面的工作，这让我非常沮丧。

哪些 Python 库是你最喜欢的(核心或第三方)？

对于核心库，我是 pathlib、functools 和 itertools 的忠实粉丝。#第三方的有 pytest，glom，uplink，httpx，pendulum 和 pydantic。

**Python 通告包是怎么来的？**

当我在开发 Flexget 的时候，我想添加一些通知插件。我很快就明白了，所有这些都遵循一种非常特定的模式，即使用特定的模式发送有效载荷并获得响应。然而，每个通知程序的 API 在命名、用法、标题、响应等方面都有很大的不同。他们中的一些人添加了他们自己的 SDK，但那只是添加了 dep，并没有真正提供一个公共接口。我构建了通告程序来解决这个问题，在许多通告程序的抽象之上有一个超级友好的界面。我写了一篇关于这件事的博文[这里](https://dev.to/liiight/an-easy-and-unified-way-to-send-notifications-1eaj)。

**最难包装的供应商是哪家？**

我认为直到今天，mailgun 有最多的选择，但是 statuspage V1 API 有一些最奇怪的方法来命名和使用它的有效载荷属性。它需要很多自己的定制代码(尽管他们在最新的 API 版本中修复了很多这种东西)。

你还有什么想说的吗？

通过使用 OSS 和为 OSS 做贡献，我基本上学会了成为一名开发人员，特别是 python 开发人员。由于我的多动症，我无法强迫自己忍受学术界的严格结构，但当我通过为 OSS 做贡献来学习时，我有很高的动力和成功，这给了我成功的职业生涯。我不能低估自学和大量数据的力量。对于那些可能正在阅读这篇文章并觉得他们需要遵循一条非常具体的成功之路的人来说，那不一定是真的。OSS 让你创造自己的道路，里面有很多优秀的、聪明的、知识渊博的人。只要你努力工作并渴望学习，任何有互联网接入的人都可以获得成功所需的所有工具！

感谢您接受采访，否则！