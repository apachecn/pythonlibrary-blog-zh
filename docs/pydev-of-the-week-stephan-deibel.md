# 本周 PyDev:斯蒂芬·德贝尔

> 原文：<https://www.blog.pythonlibrary.org/2015/06/08/pydev-of-the-week-stephan-deibel/>

本周，我们欢迎斯蒂芬·德贝尔成为我们的本周 PyDev。他是流行的 Python IDE Wing 的开发者 Wingware 的联合创始人之一。我相信几年前我在 PyCon 见过 Stephan 一次，虽然我很怀疑他是否还记得。不管怎样，作为一个 Wing 的快乐用户，我发现他和他的员工的帮助是无价的。我希望你和我一样喜欢了解他。

**你为什么开始使用 Python？**

我第一次使用 Python 是在 1998 年，当时我为一个临床工作站开发了一个 GUI 原型。我很快就被 Python 比 C、C++或 Object Pascal 多得多的生产力所打动，我已经用了 8 年多了。在那段时间里，我也尝试过 Java，当时它还很新，并且用 VB 做了一些咨询工作。

从这段在相当短的时间内用几种 *语言进行实际工作的经历中，我清楚地意识到，我已经浪费了太多的时间来对抗糟糕的语言设计。Python 是一个启示，随着时间的推移，它真的改变了我的生活，使我能够完成比没有它多得多的事情。*

当然，我确实经历了担心语法空白和缺少静态类型的常见阶段。我很快克服了空白，但花了几个月担心类型检查，直到我最终发现这根本不是一个问题。

你还知道哪些编程语言，你最喜欢哪一种？

我也曾用 C、C++、对象和非对象 Pascal、VB、Javascript、Java、Basic、Assembly、Lisp、Prolog、SQL、PL/C、Natural2 和一些其他专有语言编程，这些语言的名字我都不记得了。Python 是我最喜欢的，在这一点上，我尽量避免写其他东西。出于性能原因，我仍然必须维护许多年前编写的各种 C 扩展模块，但是在这一点上，当 CPython 的实际性能确实是一个问题时，Cython 是一种方法。是的，抱歉，我关注的是 CPython，而不是其他优秀的 Python 实现，因为大多数人仍然使用 CPython。

Javascript 似乎是另一种我无法避免的语言，即使有 Brython 和各种 Python 可供 Javascript 编译器使用。到目前为止，我对此没什么意见，主要是因为我想用 Javascript 写的东西显然都已经写好了，而且可以在网上找到，而且是免费的。

你现在在做什么项目？

自 1998 年以来，我一直在从事 [Wing IDE](http://wingware.com/) 的工作，这是一个用于 Python 的商业集成开发环境。Wing IDE 主要是用 Python 写的，自己开发，测试，调试。这其实很好玩。我通常运行当前的源代码，并很快受益于添加到产品中的新特性。

Wing IDE 意识到 Python 比其他语言更高效。1998 年的想法是，如果有一个真正的 IDE，更多的人会转向 Python(而不是 VB)，所以我和 John Ehresman 共同创建了 Wingware。我们很快发现(咄！)写一个 IDE 是相当困难的，17 年后，我们仍然对未来有很多想法。尽管有时会令人畏惧，但开发一个服务于大量不同用户群的产品是一件非常有趣的事情。我喜欢与来自世界各地的用户互动，他们中的许多人都有有趣的故事要讲，并有改进产品的好主意。

做所有这些真的定义了我的生活，让我在生活地点、工作时间和方式以及工作内容上有了很大的灵活性。套用 Paul Everitt 的话，Python 是使这成为可能的秘方。我非常感谢所有从事 Python 工作的人。

哪些 Python 库是你最喜欢的(核心或第三方)？

最近我一直在用 Flask 做一些工作，我真的很喜欢它。它的安装速度非常快，而且我只需要做很少的事情就可以得到一个工作网页。我也很喜欢使用 reportlab 生成 PDF 文件，我对几年前使用 Beautiful Soup 有一些美好的回忆。

虽然我没有在实际工作中使用过它(除了支持用户之外),但我也对 web2py 印象深刻。我喜欢他们的模板语言制造假的 Python 堆栈框架，这样你就可以用任何 Python 调试器来调试模板。

在标准库中，itertools 是不可或缺的，collections 模块有一些有趣的数据类型，在需要时非常有用。

作为一门编程语言，你认为 Python 将何去何从？

我认为这个世界还没有真正理解 Python。它被越来越广泛地使用，并且经常出现在新闻中。但是大多数程序员仍然在浪费大量的时间与设计糟糕的语言斗争，因为他们认为 Python 太慢或者不是线程友好的(因为 GIL)，或者对于生产应用来说不够健壮，或者仅仅因为他们的公司要求他们使用其他东西。很有可能，对 Python 3 的困惑、恐惧和怀疑大大减缓了 Python 的发展。

我认为这一切都将改变。我们将看到软件开发行业作为一个整体从笨重的编译语言向更有生产力的解释型交互语言迈出坚实的一步。Python 健壮而成熟，很有可能在 10 年后成为大多数人都会使用的语言。

几年前在 PyCon 上，[tummy.com](http://tummy.com)的创始人之一 Sean Reifschneider 给了我一个笔记本电脑贴纸，上面写着“Python 将拯救世界。我不知道如何，但它会的。”希望是真的！

你还有什么想说的吗？

我不喜欢软件业对神童、一夜成名和数十亿美元想法的关注。事实上，创造伟大的软件仍然需要长时间的努力。对我来说，Python 体现了这一点。它充满了伟大的想法，许多是从其他人那里借来的，但通过精心设计和充满热情的贡献者的尊重社区的精心照顾，组合成了一个高质量的整体。

非常感谢！

### 一周的最后 10 个 PyDevs

*   安娜·奥索斯基
*   加布里埃尔·佩蒂尔
*   [瓦苏德夫拉姆](https://www.blog.pythonlibrary.org/2015/05/18/pydev-of-the-week-vasudev-ram/)
*   [朱利安·丹朱](https://www.blog.pythonlibrary.org/2015/05/11/pydev-of-the-week-julien-danjou/)
*   马特·哈里森
*   阿迪娜·豪
*   [诺亚礼物](https://www.blog.pythonlibrary.org/2015/04/20/pydev-of-the-week-noah-gift/)
*   道格拉斯·斯塔内斯
*   [可降解的脊椎动物](https://www.blog.pythonlibrary.org/2015/04/06/pydev-of-the-week-lennart-regebro/)
*   迈克·弗莱彻