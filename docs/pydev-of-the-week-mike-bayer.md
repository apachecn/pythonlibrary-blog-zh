# 本周 PyDev:迈克·拜尔

> 原文：<https://www.blog.pythonlibrary.org/2016/02/15/pydev-of-the-week-mike-bayer/>

本周，我们欢迎 Mike Bayer ( [@zzzeek](https://twitter.com/zzzeek) )成为我们本周的 PyDev。Mike 是广受欢迎的 SQLAlchemy 项目的创建者。他有一个有趣的 Python [博客](http://techspot.zzzeek.org/)，并为许多 [Python 项目](https://bitbucket.org/zzzeek/)做出了贡献。我见过 Mike 在 PyCon 上介绍 SQLAlchemy 的教程，他也经常在那里做演讲(这里有一个 2014 年的[例子)。让我们花点时间更好地了解他！](https://www.youtube.com/watch?v=P141KRbxVKc)

你能告诉我们一些关于你自己的情况吗(爱好、教育等)

上世纪七八十年代，我在纽约市东部的郊区长岛长大。我第一次接触计算机是在 1980 年，当时我 12 岁，像当时所有进入“家用计算机”的人一样，我花了很多时间学习基本编程语言。最终，我在 80 年代中期选择了 Atari 800 作为我的平台，我甚至设法用它做了一些基本的汇编语言。在高中，我设法通过早期的互联网拨号形式上网，如公告牌和 Compuserve，后来我在高中学习了 Pascal，在大学里，我有一段时间主修计算机工程，在那里我学习了更多的过程编程和数据结构理论，以及 Modula III 等语言，根据最近查看我的旧笔记，显然还有一点 Lisp。但是在我的大学时代，我真的一点也不想和计算机扯上关系，所以我最终在伯克利音乐学院主修音乐，我也辍学了，只是搬到了城市，成为了一名鼓手。在城市里，我的打字速度和电脑技能让我进入办公室做文字处理的临时工作，即使是最底层的工作，工资也远远高于任何饥饿的音乐家，所以直到今天我几乎没有机会打鼓。在很多这样的工作中，我最终以编写代码来取代他们交给临时工的大量重复性工作而告终，到那时，“互联网”突然想在任何地方雇佣所有只会编写五行代码的人，所以这是进入 90 年代末纽约巨大的互联网泡沫中为代理机构工作的自然之举。

**你为什么开始使用 Python？**

我在美国职业棒球大联盟做了很多 Perl 工作，在花了很多年时间用 Java 做面向对象的工作后，我真的渴望有一种具有良好面向对象特性的脚本语言。Python 似乎一直都很喜欢，但是我 *却无法摆脱空白。在 MLB，我们推出了 CMS 解决方案的一部分，给一个名为 WinCVS 的 CVS 客户端访问，我们需要为它做一些脚本；脚本语言是 Python，它迫使我用 Python 工作了足够长的时间(20 分钟),才意识到空白的东西很棒，剩下的就是历史了。*

你还知道哪些编程语言，你最喜欢哪一种？

Python 无疑是我一直以来的最爱，我也使用过很多 Java，主要是早期版本，我也花了很多年使用 Perl，当然还有不可避免的 Javascript。这些是我有多年专业经验的人。除此之外，我偶尔学过相当程度的 C 语言，学过非常少量的 C++，也在大学和早期工作中接触过所有的旧语言，如 Fortran、Rexx、Pascal、Modula III、Scheme、6809 / 68000 汇编等。这些我今天都不知道怎么用。

你现在在做什么项目？

我在 Red Hat 有一份超级棒的工作，这是我第一份我们制作的东西不是“网站”的工作。我使用 Openstack 产品，我一直面临的挑战是 *弄清楚如何获得 Openstack，它根据架构可以旋转数百个 Python 进程，以处理有时数千个到数据库的连接，在我们的情况下，这通常是一个名为 Galera 的* *多主 MySQL 变体，以这样的方式，我们不会浪费资源，不会耗尽连接，并且如果各种数据库节点或服务突然变得不可用，也永远不会停机。所有这些都必须打包，以便当客户第一次安装 Red Hat 的 Openstack 发行版时，它可以自动运行。*

和往常一样，我也在努力让 SQLAlchemy 向前发展，现在是 1.1 版本。从架构上、文档上和特性上来说。

哪些 Python 库是你最喜欢的(核心或第三方)？

我用得最多并投入巨资的库包括 mock、argparse、py.test 和 sphinx。我也非常欣赏 gevent。我也鼓励人们更多地使用 curses 库； *它的风格必然有点老套，但丰富多彩的主机应用程序令人敬畏。*

  **是什么启发了你创建 SQLAlchemy？**

我一直想拥有一个“终极编程平台”，多年来，我似乎一直想拥有一套可以在 Java 中使用的优秀函数库，那时候 Java 还是个新生事物，没有太多的东西可以使用，但是 Java 很快就失去了它的光芒。当我进入 Python 时，它似乎是最终构建这个平台的一个很好的地方，并且让基本的 web 框架东西运行起来是我的第一个目标，然后是关系数据库访问。我之前已经写了十几个关系数据库外观，所以当我决定做 SQLAlchemy 时，我对它应该有什么有了很多想法。有一些我在各种工作中研究出的模式，我想作为一个一流的库来展示，这样我就不必再在每一个新的工作中编写数据库访问层了。

你能告诉我们你在使用 Python 社区创建像 SQLAlchemy 这样的包时学到了什么吗？

令我惊讶的是，尽管我在开始 SQLAlchemy 时已经有了十年的工作经验，但我仍然在各方面完全不成熟；尽管我在一些工作中担任过技术经理，但我仍然不知道如何与社区、其他开源开发者、其他开源项目或用户互动，或者如何编写真正的测试，如何编写和维护好的 API，任何事情。我必须根据我在 Python 社区的经验来解决所有问题，从这个可怕的模板引擎 Myghty 开始，我在那里解决了各种不能再犯的错误，然后在 SQLAlchemy 版本的前几年，我也积累了一个不能再犯的错误的深度目录，包括在代码发布领域以及与他人的交互方面。

将 SQLAlchemy 从这个学习曲线的余波中拯救出来的智慧是，我一直打算让它自己花十年时间变得真正坚如磐石，这就是为什么我花了那么长时间才觉得可以称它为 1.0。通过在适当的时候不过度销售它，只是等待它非常深入和缓慢地成熟，并以有机的方式获得追随者，该项目没有成为嘲笑和仓促决策的目标，如果在 2007 年的会议上人们被给予“SQLAlchemy 0.3”杯子，它肯定会成为目标。那个版本非常糟糕。现在情况好多了。

非常感谢你接受采访！