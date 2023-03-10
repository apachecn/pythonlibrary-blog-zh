# 本周 PyDev:乔·考菲尔德

> 原文：<https://www.blog.pythonlibrary.org/2022/12/26/pydev-of-the-week-joe-kaufeld/>

本周我们欢迎乔·考菲尔德成为我们的本周 PyDev！乔已经做了十多年的会议组织者，并共同创立了 TranscribersOfReddit。Joe 活跃在 Python 社区中，并且已经使用这种语言很多年了。

让我们花些时间更好地了解乔！

## 你能告诉我们一些关于你自己的情况吗(爱好、教育等)？

一般介绍时间！我是一名自学成才的开发人员，住在印第安纳州的印第安纳波利斯。当我不思考代码的时候，你通常会发现我浑身是木屑或者在一堆猫下面。

我拥有波尔州立大学的信息系统和运营管理学士学位，这为我从事顾问这一辉煌的职业做好了准备。毕业后做了咨询师，很快意识到自己*讨厌* it！我转变成了一个 IT 服务台的角色，并一步步升到了现在的职位:高级开发人员。一路走来，我发起了一些附带项目，包括一个国际非营利组织和一个非常活跃的 3D 打印塑料参考图书馆。(稍后将详细介绍这两者！)

我和我的好伴侣以及三只猫住在这个城市一个相对安静的角落里。

## 你为什么开始使用 Python？

在大学期间，我偶然发现了商学院的一个无人问津的房间，这个房间自 2003 年以来就没人动过。它致力于一个学生项目，利用废弃的大学设备创建一个贝奥武夫集群。在我找到负责这个房间的教授后，我问我是否可以使用它，他基本上是把门钥匙扔给我，并说“玩得开心！”。我将所有设备更换为新的(大约 2012 年)硬件，这些硬件是从校园内的其他部门拆除的，丢弃了所有旧的硬件，并在 CentOS 5 上构建了一个 115 节点的集群。

鉴于我对如何让软件在 monstrosity 上运行有完全的自由，我花了很多时间评估不同的选项和语言。最终，我登陆了 Python 2.7.0 和[并行 Python](https://www.parallelpython.com/) ，一个基于 HTTP 的多处理库。我用它开发了一个叫做 ClusterBuster 的系统，这是一个速度惊人的 Windows NTLM 密码破解程序。

开发的绝对便捷对我来说是一个游戏改变者；我以前的经验是 QBASIC 和 FORTRAN，与这些相比，Python 是一股我不知道自己需要的新鲜空气。

## 你还知道哪些编程语言，你最喜欢哪一种？

我的第一次是 QBASIC:当我 11 岁的时候，我爸爸让我坐在一台 Windows 95 机器前，打开 QBASIC 熟悉的蓝屏，按 F1 键调出帮助菜单，然后让我自己处理带有爱普生点阵打印机的设备。我用这些知识说服(贿赂)了我的数学老师，让我用我的 QBASIC 程序交换工作表，这个程序完成了当天的数学作业。既然我可以向计算机解释如何解决这个问题，那么我就清楚地知道这个作业应该包括什么。那个借口今天可能不会飞！

我在高中时学了一些 FORTRAN 语言，因为我觉得无聊，但老实说，我从未喜欢过它。Myspace 时代让我接触到了 HTML 和 CSS，不久之后我就对 JS 产生了适当的厌恶。我仍然做相当数量的 JS，但是我在期间和之后的痛苦抱怨没有改变。一旦我接触了 Python，一切都变得清晰了——我发现了一种对我和我的大脑如何工作有意义的语言。

从那以后，我尝试过其他语言——c++、Rust、Ruby、Crystal，还想到过 Java 但我对编程的热爱仍然是 Python。

## 你现在在做什么项目？

我的日常工作是作为一名 Python 开发人员用 Django 构建 API，但围绕这一点，我运行 [FilamentColors.xyz](https://filamentcolors.xyz) ，一个用于 3D 打印机细丝的颜色匹配工具。这是或多或少在不断发展的东西，因为我总是想以最好的方式展示这个系列，并尽可能使它有用。我们有大约 880 个细丝被编目和发布，另外大约 800 个正在进行中，因为我不得不暂停工作来刷新 UI。

除了 FilamentColors，我还是 Grafeas Group 的总裁和联合创始人，这是一个 501c3 组织，致力于提高互联网的可访问性。(你可能已经在[连线](https://www.wired.com/story/online-altruists-are-making-reddit-more-accessible/)上看到过我们的特写！)通过全球约 5800 名志愿者，我们将图像、视频和音频转换成一种人人都能访问的格式:文本。该非营利组织监管 Reddit 上一个名为[的社区，这是一个任何人都可以加入的“工作板”。我们提供与 Reddit 上的主要盲人和视障人士社区](https://www.reddit.com/r/transcribersOfReddit/wiki/index/) [r/Blind](https://www.reddit.com/r/Blind/) 密切合作设计的模板和指南。你可能已经看到我们的工作以评论的形式散布在 Reddit 上，以“图像转录:”开始，以“我是一名人类志愿者内容转录者，你也可以！”中间写下链接内容的完整描述。到目前为止，我们已经在 Reddit 上完成了超过 267，500 次转录，并计划做更多！

## 哪些 Python 库是你最喜欢的(核心或第三方)？

我真的把“对 Django 了解很多”变成了一项事业，所以我非常感谢 Django 的核心团队和所有帮助它成为今天的贡献者。除此之外，我真的很喜欢和以下人一起工作(绝对没有特别的顺序):

*   诗歌(刚刚工作的依赖管理器):[https://python-poetry.org/](https://python-poetry.org/)
*   httpx(你需要的最后一个 http 客户端):[https://github.com/encode/httpx](https://github.com/encode/httpx)
*   shiv (python zipapps，但支持 venv):[https://github.com/linkedin/shiv](https://github.com/linkedin/shiv)
*   权利(Reddit API 包装器):[https://权利. readthedocs . io/en/稳定/](https://praw.readthedocs.io/en/stable/)
*   Django-HTMX(Django 视图中的本地[HTMX](https://htmx.org/)支持):https://github.com/adamchainz/django-htmx
*   布莱克(不妥协的代码格式化者):[https://github.com/psf/black](https://github.com/psf/black)

外面有这么多令人惊奇的包和库；在我经常使用的所有工具中，Django 无疑是最受欢迎的(尽管它在技术上是一个框架，而不是一个库)，所以本着回答这个问题的精神，我真的不得不说出诗歌和黑色；当开始一个新项目时，我运行的第一个命令是:

诗 init
诗加黑-组开发

## TranscribersOfReddit 是怎么来的？

回到 2014 年，我有一部*真的*烂手机。它很小，几乎没有合理的功能，而且(最重要的是)不能很好地放大图像。我曾经是(并将继续是)一个 [r/DnDGreentext](https://www.reddit.com/r/DnDGreentext/) 的狂热读者，这是 Reddit 上的一个社区，全是关于角色扮演小组做傻事的，通常是以打破游戏规则的方式。偶尔会有来自网络上不同地方的游戏故事的大量截图被贴在一起，每当我发现其中一张，我就会把它保存在手机上，并在午休时在我的电脑上打印出来。当时我把它作为打字练习，我想，“嘿，也许有人和我一样，因为这样或那样的原因看不懂这些。我只是把工作放在那里，这样如果有人需要，它就在那里。”

随着时间的推移，我最终开始收到其他读者的 pings，主要是问我什么时候能有一份供阅读的转录，因为事实证明，即使在桌面上操作这些巨大的截图有时也不会那么好。

更多的时间过去了，然后奇怪的事情发生了:有人开始和我赛跑，每当这些截图出现时，我就把它们转录下来。我想，“这太奇怪了，我不知道为什么其他人也想这么做，”所以我暂时忽略了他们。我们最终聊了起来，发现他是一个无聊的大学生，而我是一个无聊的服务台技术人员。在讨论了我们学到的一些东西后，我们决定建立一个 subreddit 和一些基本的脚本(Python 和 PRAW 来拯救！)创建一种工作公告板，这样我们就可以知道其他人在做什么，而不会重复工作。

当我建造最初的机器人时，我一直在想，“我想知道是否有其他人也会这样做？”。我们决定宣布我们的小系统开放，激动得都没查日期:2017 年 4 月 1 日正式开放。

这并没有阻止人们加入；在第一天结束的时候，我们有 30 个人注册了，r/Blind 的首席版主发来了一条非常严肃的信息，基本上可以归结为“你知道这是一个怎样改变生活的工具吗？”我们立即开始密切合作，以确保我们能够融合这两种愿景，现代转录 fReddit 诞生了！

## 你从创建 TranscribersOfReddit 中学到的最重要的三件事是什么？

在我的职业生涯中，我犯了很多错误(我们都犯过)，我很幸运，我在 transcriptorsofreddit(ToR)上犯了一些更严重的错误，而不是在我的日常工作中！这些是立即浮现在脑海中的情景和事情:

*   设计符合需求和团队的项目
    *   当我们发布 ToR 的时候，我们真的没有打算让任何人加入我们。因此，在编写驱动 subreddit 的机器人时，我走了很多捷径。当我们需要处理更多的流量时，这一点很快变得很明显，我使用一种更微服务 y 的设计来重建东西，因为我根本不知道我们需要处理多少流量，这是我在财富 500 强公司担任开发人员时熟悉的用法。事实证明，微服务基本上是一个全志愿者团队的死刑判决，开发进度基本上停滞不前，直到我们将我们的系统“去微服务化”成一个核心的 Django monolith，机器人作为它周围的服务。我们从一个月一次的部署(因为它需要几个人、仔细的时间安排和粗制滥造的文档)发展到一个全自动的过程，这个过程可以每天部署多次，而不需要团队中的任何人反复思考。
*   你不能在泡沫中发展一个社区
    *   如果只有我们两个，我知道 ToR 不会像现在这样成长。凭借我们出色的行业人脉和出色的团队(根据一年中的不同时间，人数在 17 至 23 人之间)帮助保持一切正常运转，没有一个想法不会立即引起“嗯，X 或 Y 怎么样？”这几乎肯定是我们其他人没有考虑过的事情，能够进行这些讨论意味着这个特性或想法会更强大、更有用。如果我们从来没有从 r/Blind 那里得到这个消息，我们绝对不会有今天。
*   它需要一个村庄
    *   我对自己试图承担一个项目的每个方面感到内疚(我们中的许多人都是如此)，有一件事一直困扰着我，那就是我根本无法独自完成这件事。太多了。Grafeas 董事会和我们出色的 ToR mods 团队是不可或缺的。没有团队，就没有 ToR。没有志愿者，就没有 ToR。没有读者，就没有 ToR。这需要如此多的人和愿景来实现，我非常感谢他们每一个人。

## 你还有什么想说的吗？

我非常感谢更广泛的 Python 社区，因为我构建的东西是建立在巨人的肩膀上的。我喜欢 Python 的生态系统，喜欢它的多样性——以及它的开放性——这绝对是一种享受。致迈克:非常感谢你给我机会成为这个系列的一部分！

乔，谢谢你接受采访！