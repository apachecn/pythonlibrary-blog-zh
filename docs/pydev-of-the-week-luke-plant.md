# 本周 PyDev:Luke Plant

> 原文：<https://www.blog.pythonlibrary.org/2017/03/13/pydev-of-the-week-luke-plant/>

本周我们欢迎卢克·普兰特成为本周的 PyDev。Luke 是 Django(一个非常流行的 Python web 框架)的核心开发人员之一。卢克写了一个博客，里面有很多关于姜戈的文章。如果你想看看卢克的一些贡献，那么你很快就会想去看看他的 [Github 简介](https://github.com/spookylukey)。让我们花几分钟时间来更好地了解 Luke！

![](img/208755bde00146d8cefa1b42056fc05d.png)

你能告诉我们一些关于你自己的情况吗(爱好、教育等)

我在英国长大，目前与妻子和儿子住在土耳其，第二个孩子也在路上！【他指的是二胎，不是二奶——老婆】。目前，我最大的“爱好”是学习土耳其语，这是一项非常艰苦的工作，但也非常值得。我也喜欢弹吉他(虽然不是很高的标准！).

关于学习编程，我主要是自学的:小时候我爸爸买的是 8 位、64K 的 Oric Atmos(这太棒了——有一本无价的[高级用户手册](http://www.48katmos.freeuk.com/br5.htm)告诉了你关于它的几乎所有东西，包括完整的 ROM 反汇编列表)，后来我开始摆弄 VBA 和微软 Office。我父亲对摆弄电脑的兴趣意味着我们是我所知道的第一批经常使用电子邮件和网络的家庭之一。

我去大学学习物理/自然科学，但是在那里的第一周，我的科学生涯就被打乱了，因为我的一个朋友在我还不知道他在做什么之前就决定在我的 Windows 机器上安装 Linux。谢天谢地，他把 Windows 也留在了那里，而不是只擦我的硬盘！但这让我接触到了开源世界，重新点燃了我之前对编程的兴趣，从那以后，开源编程背后的乐趣和理念对我产生了重大影响。谢天谢地，虽然我学的是科学而不是编程，但我能够做相当数量的编程相关项目——其中一个我最近很开心[用 IPython 笔记本重新实现了](https://lukeplant.me.uk/blog/posts/ipython-notebook-essentials-review/)。

**你为什么开始使用 Python？**

我想我开始迷上它的部分原因是因为工作上无事可做！大学毕业几年后，我开始了一份新工作，但一个招聘时间上的错误让我在最初的几个月里无事可做。我想就是从这个时候开始玩 Python 的。不久之后，我被用更好的东西取代一个破旧的 PHP 网站的需求所激励，然后发现了 Django(大约在 2005 年夏天，它才刚刚被开源)。这可能是我的第一个严肃的 Python 项目，但它仍然进展顺利。想要为 Django 做贡献意味着我必须学习更多。我在恰当的时间出现了——当项目规模更小、流动性更强的时候——并且成功地加入了 Django 的核心团队，而这只是其他更有价值的开发人员所需要的工作的一小部分！

你还知道哪些编程语言，你最喜欢哪一种？
 *按历史顺序——BASIC，6502 汇编，VBA，C，对 C++，Perl，PHP，Javascript，Python，Haskell 一知半解。然而，除了 Python 和 Javascript，这些我真的不擅长。我很感激我可以使用很多 Python，我很喜欢。我也非常喜欢 Haskell 和类似的语言，但通常只是在实验的层面上使用它们。*

你现在在做什么项目？

我主要为我的客户 Wolf & Badger 做一个 Django 项目，并维护其他一些 Django 项目，包括 learnscripture.net 的 [CCIW](https://www.cciw.co.uk/) 和[。这不可避免地意味着我已经创建、参与或维护了各种其他 Python/Django 项目，例如](https://learnscripture.net/dashboard/) [django-functest](https://github.com/django-functest/django-functest/) 和 [django-paypal](https://github.com/spookylukey/django-paypal/) 。

哪些 Python 库是你最喜欢的(核心或第三方)？

我认为这是一个很难回答的问题——最好的库和工具往往是那些你几乎不会注意到的，但它们总是在那里，做着它们应该做的事情。还有一些因其卓越而脱颖而出。可能有很多我不知道的，但是我知道使用很多，或者印象非常深刻的一些是:

*   [争辩](https://docs.python.org/2/library/argparse.html) (stdlib)
*   [IPython](http://ipython.org/)
*   熊猫
*   (现在是我所有项目中不可或缺的一部分)
*   [绝地](https://pypi.python.org/pypi/jedi)(经由[emacs-绝地](https://github.com/tkf/emacs-jedi))

另一个我刚刚开始使用的是[假设](https://pypi.python.org/pypi/hypothesis)，它看起来设计得非常好，我想我将来会用得更多。当然还有 Django，但我认为这是理所当然的，而且公平地说，尽管有一个相当进步的弃用政策，我们向后兼容的态度意味着有相当多的代码不再是最好的了。我猜就它的年龄来说，它做得还不错！

作为一门编程语言，你认为 Python 将何去何从？

看来异步编程的故事越来越精彩了，如果它能把我们从 Node 中拯救出来，那就太好了！我预计那个领域会有很大的增长。似乎也有向静态/渐进打字发展的趋势。我对这带来的改进持怀疑态度——这可能主要是对数字密集型代码的性能提示。就我个人而言，我更感兴趣的是强静态类型系统可以带来的其他好处，而你不能仅仅通过添加一些类型提示来获得这些好处。此外，Python 的一个主要特点是，对于科学家和其他不是程序员的人来说，它非常容易理解。我认为这限制了 Python 的发展。另一方面，Python 在数据科学、天文学、生物学等领域的流行。将有望鼓励符合 Python 核心优势的方向的增长。

你对当前的 Python 程序员市场有什么看法？

从我有限的视角来看，我认为 Python 的就业市场形势良好，尤其是在高薪机会和你喜欢从事的项目方面。随着数据科学角色的爆炸式增长，以及 Python 在这方面的出色表现，我认为 Python 程序员在这方面的前景相当光明。

你还有什么想说的吗？

回想我上面的一些回答，让我想起了我读过的一篇关于运气在生活中的关键作用的文章。虽然作为一名基督徒，我不相信运气，但我确实非常幸运，我认为这是一件非常重要的事情。