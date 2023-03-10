# 本周 PyDev:Pawe Piotr Przeradowski

> 原文：<https://www.blog.pythonlibrary.org/2017/04/10/pydev-of-the-week-pawel-piotr-przeradowski/>

本周，我们欢迎 Pawe Piotr Przeradowski([@ squeaky _ pl](https://twitter.com/squeaky_pl))成为我们本周的 PyDev！Pawel 是 [Japronto](https://github.com/squeaky-pl/japronto) 背后的创意头脑，这是一个基于 uvloop 和 picohttpparser 集成流水线 HTTP 服务器的 *Python 3.5+ web 微框架。Pawel 在 Github 上还有一些其他有趣的项目。*

让我们花一些时间来了解 Pawel！

![](img/31fe8d1322a313189a023c02c74960a3.png)

你能告诉我们一些关于你自己的情况吗(爱好、教育等)

我出生在波兰西北部的一个小镇，距离德国边境大约 60 公里。我很幸运，很早的时候家里就有一台电脑。了解事物在幕后是如何运作的，一直是我非常感兴趣的事情。8 岁的时候，我开始用 BASIC 语言做一些小程序。我通过修改家里的 Commodore 64 手册中的例子来学习编程。12 岁时，我们拥有了第一台个人电脑。我玩了一会儿 DOS 附带的 QBASIC，然后我决定我需要学习一些更严肃的东西。我买了第一本关于 C 的书，并在 13 岁时开始玩 Borland C++编译器。15 岁时，我决定学习 x86 汇编程序来编写自己的引导加载程序和原始的实模式操作系统。当我 16 岁的时候，我对 web 开发产生了兴趣，并学习了 PHP。19 岁时，我在大学开始学习计算机，但很快就厌倦了，在毫不费力地完成第一年的学业后，我找到了第一份工作，成为一名网页开发员，并决定不再继续学业。我也是在那个时候对 Python 感兴趣的，但是因为当时在波兰没有就业市场，所以它只限于我自己的私人项目。在做了两年程序员之后，我决定去荷兰，并在那里做一名网页开发员。大约 5 年前，我搬到了西班牙，从那以后，我一直生活在西班牙和巴西之间。在过去的几年里，我一直只做 Python 和 DevOps。

除了编程，我还喜欢学习自然语言，我对比较语法和词源有很大的热情。我能说很好的葡萄牙语和西班牙语。我主要用英语工作，当然我的母语是波兰语。目前我正在努力学习法语。我非常喜欢数码摄影，曾经拥有几台专业级相机。这些天我没有时间去利用它们，所以我把它们都卖了。我也喜欢旅游，通过接触当地人来了解文化。

**你为什么开始使用 Python？**
 *Python 的表现力和优雅同时令我惊叹不已。我曾经用低级编程语言工作过一段时间，然后我学习了 PHP 来做这项工作，但它有一个可怕的设计错误的过去。Python 的制作非常仔细，平衡了过程性、功能性和面向对象的特性，使得编程非常愉快。最近，它还获得了一种非常有吸引力的异步编程方式，同时不强迫您使用它。如今，Python 在世界范围内的许多领域得到了广泛应用，对于你的职业生涯来说，它也是一个安全的赌注。它也有一个充满活力和非常热情的社区。*

你还知道哪些编程语言，你最喜欢哪一种？

当然 Python 是我的最爱。我也喜欢低级 C 和 x86 汇编程序。我曾经做过，现在仍然可以做 PHP，但是我绝对不会去做。我也有一些冒险经历。NET 和 C#还有 Windows 刚出现的时候。当 Android 发布时，为移动设备编程变得如此有趣，以至于我学习 Java 就是为了做这件事。因为我做了很多 DevOps 工作，所以我也很擅长 shell 脚本。是的，我们都做 SQL。

我真的对 Rust 很感兴趣，但对于大多数东西来说，Python 确实更适合。

你现在在做什么项目？

我有一个项目最近火了。它被称为 [Japronto](https://github.com/squeaky-pl/japronto) ，并且它正在努力实现快速优雅的 HTTP 服务器，与一个最小的 web 框架紧密集成。我现在正在做一个重大的重组，并做了大量的概念验证工作。我希望很快能有一个支持中间件的更好的路由器实现。然后我很可能会尝试攻击 web sockets 和 HTTP/2 植入。添加 synchronous、WSGI 和 gevent 工人也是我感兴趣的事情。之后我还想调查 gRPC。

我维护的另一个项目是 [Portable PyPy binaries](https://github.com/squeaky-pl/portable-pypy) ,这是一种在许多 Linux 发行版上安装 PyPy Python 实现的方法，无需经历库之间 API/ABI 不兼容的痛苦。

哪些 Python 库是你最喜欢的(核心或第三方)？

我想这些天我离不开 ipython。它使得管理许多小片段和尝试事情变得轻而易举。我也是 pytest 测试框架的忠实粉丝，它可以让你去掉大部分你原本需要的锅炉板。CFFI 是集成 C 和 Python 的好方法，因为它可以自动解析典型的 C 头文件样式代码。我非常喜欢 Gevent，因为它以简单而强大的方式用 Python 进行异步编程。Asyncio 最近被集成到 Python 标准库中，这可能是一种前进的方式。我希望它能随着时间的推移变得更好，但在我看来，它可以更简单，缺乏良好的文档。

作为一门编程语言，你认为 Python 将何去何从？

如今，Python 变得越来越强大，我们正在正确的道路上保持 Python 的相关性。我们已经度过了“Python 3 破坏了我的代码”的难关，CPython 3 已经比 CPython 2.7 快了。在我看来，Python 实现的真正未来是 PyPy。我们最近收到了 PyPy 团队的 3.5 兼容版本，从我代表 PyPy 团队进行的基准测试中可以看出，它看起来很棒[https://morepypy . blogspot . com . es/2017/03/async-http-benchmarks-on-PyPy 3 . html]。PyPy 还改进了他们与 CPython 的兼容性，现在他们可以运行 NumPy 和 Pandas 代码。Python 一直是安全的赌注，它在科学、数据分析和人工智能领域保持指数增长。它肯定会继续成为一种伟大的粘合语言，将底层技术连接在一起。

非常感谢你接受采访！