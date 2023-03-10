# 本周 PyDev:詹姆斯·贝内特

> 原文：<https://www.blog.pythonlibrary.org/2017/04/17/pydev-of-the-week-james-bennett/>

本周，我们欢迎詹姆斯·贝内特成为我们本周的 PyDev！James 是 Django web 框架的核心开发人员之一。他还是 [Django 软件基金会](https://www.djangoproject.com/foundation/)的董事会成员。詹姆斯维护着一个[博客](http://www.b-list.org/)，并且在 [Github](https://github.com/ubernostrum) 上有几个有趣的项目值得一试。现在让我们花些时间来更好地了解我们的蟒蛇同伴！

你能告诉我们一些关于你自己的情况吗(爱好、教育等)

我在弗吉尼亚的一所小文理学院攻读了哲学学位。直到我上了大学，我才有机会经常接触电脑或互联网，我在一个周末自学了 HTML，因为一位教授让我选择写一篇 20 页的论文或建立一个 5 页的网站来展示一些研究，我很懒。然后人们开始付钱给我，让我为他们做网站(那是 90 年代，当人们发现你懂 HTML，他们就会这么做！)，事情就这样开始了。我从未上过任何计算机科学课程，但在决定如何排版我的论文时，我确实学过 DocBook 和 LaTeX。

大学毕业后，我四处漂泊，在办公室工作了一段时间，积攒了一些积蓄，然后开始做全职合同工作，做网页开发员。后来，在 Django 发行后不久，我尝试并爱上了它，这导致我搬到了堪萨斯州，并在最初开发 Django 的公司工作。当我在那里工作的时候，我学会了提交，并成为了发布经理。五年后，我去了 Mozilla，在那里，我作为团队成员花了四年时间建立了 Mozilla 开发者网络平台。

这些天我住在旧金山湾区，在 Clover Health 工作，在那里我们试图让医疗保险变得更好。我还保留了一个[博客](http://www.b-list.org/)，在那里我偶尔会写一些关于 Django、Python 或者其他我想到的东西。

我那令人难以忍受的书呆子般的非技术爱好是魔术:聚会，它最初是在我上中学的时候出现的。从那以后，我断断续续地打比赛，在过去的七年里，我还在半职业和职业巡回赛中担任比赛官员(是的，有职业比赛)。通过这种方式，我认识了很多很酷的人，也去过很多地方；有一次，在一场顶级职业锦标赛中，我得到了一次去夏威夷的免费旅行，因为比赛是在那里举行的。

在那次会议和技术会议之间，我结束了大量的旅行，并且(直到 2015 年)成为一名远程员工，这也让我不可避免地成为了一名航空极客，对飞机、机场和常旅客计划了解得太多了。

**你为什么开始使用 Python？**

当我在做合同 web 开发工作时，主要是用 PHP 和 Perl 语言，我重新拾起了 Python，并对这些语言中的大量死记硬背和不一致感到沮丧。我不断听到关于 Python 的好消息，所以我阅读了网络版的“深入 Python ”,并且迷上了它。不过，在那之后的一段时间里，我无法开始用 Python 做有偿工作，因为我不了解 Zope，而且那时 Zope 是 Python 中大部分网络开发合同资金的来源。

在 Django 最初发布后不久，我第一次开始专业地使用 Python，我的第一份全职 Python 工作是在最初开发 Django 的堪萨斯小报社(Lawrence Journal-World)工作。

你还知道哪些编程语言，你最喜欢哪一种？

我已经写了相当多的 PHP 和 Perl，虽然已经过了很长时间，所以我不确定我是否还“了解”它们。我一直在关注 JavaScript，我不得不说它是一种比以前好得多的语言(浏览器环境也比以前好得多),那时我们称它为“DHTML ”,只是用它来制作图像翻转和烦人的东西，当你试图点击它们时它们就会消失。我感觉核心语言越来越好了，真的，但它迫切需要有人为它提供一个坚实的标准库。

除此之外，我知道足够多的 C 语言，足以对自己构成一定的威胁，如果手边有一个库参考，我可以编写 Java 或 C#(在我职业生涯的早期，它们似乎是“安全”的备份语言)，我知道足够多的 Bash，知道我不应该编写 Bash，我有一些 Emacs Lisp，这是因为我将它作为日常编辑器使用了大约 18 年，然后还有一些其他东西。

我试图偶尔为一门新语言做一个教程，看看是否有一些我错过的很酷的想法或范例。在过去的几年里，我尝试了几种函数式语言(OCaml 和 F#看起来不错)，当我在 Mozilla 工作时，我尝试了 Rust。我在使用一门新语言方面最大的障碍通常是缺少一些我想要并且有时间用一门新语言写的东西，因为我的编码时间都花在了我的日常工作和我现有的开源承诺上。

我最喜欢的语言还是 Python，毫无疑问。我从 Python 中获得的可读性和简洁性的结合是我在其他语言中从未发现过的。它似乎真的很适合我的大脑，当你将它与标准库、第三方内容的巨大生态系统和令人敬畏的社区结合起来时，我觉得我可以做任何我需要用 Python 做的事情。

你现在在做什么项目？

与我第一次得到承诺时相比，我现在不那么直接参与 Django 了；现在，我把自己在这个项目中的角色描述为“脾气暴躁的老头”，尽管我认为其他几个人会向我挑战这个头衔。我仍然在 Django 的安全团队中，自从 Jacob Kaplan-Moss 和 Adrian Holovaty 正式辞去 Django 的联合 BDFLs 职务以来，我一直在技术委员会中担任某些类型决策的最终决胜局，我还是 Django 软件基金会的董事会成员。

我仍然维护着一些与 Django 相关的包，我总是在某种程度上对它们进行修补，现在我正准备在 Django 1.11 发布时发布新的版本。我也一直在考虑写另一本书(我曾经写过两个版本的 Django 入门书)，但是我知道最好不要公开承诺这样的事情。如果我去做，我可能会在业余时间写，不告诉任何人，然后当我找到一种方法让它出版时宣布它。

哪些 Python 库是你最喜欢的(核心或第三方)？

我应该先说我喜欢无聊的软件。当我使用这个术语时，我不是指“不有趣”，而是指“不令人惊讶”。我对无聊软件的理想是安静可靠地完成工作，不会给我带来任何令人讨厌的惊喜。我曾经是一个在周日凌晨 3 点接到电话的人，因为一些重要的服务刚刚中断，这是我生活中不需要的惊喜。

所以在标准库中，我会选择 csv 模块。我可能比 Python 附带的任何其他模块获得了更多的收益，它是“无聊”的缩影(从好的方面来说！)一段代码:可能没有人会用它来登上黑客新闻的头版，但它只是做了自己的事，让生活变得更容易。

第三方如果我说姜戈我想我是在作弊，所以我会选 BeautifulSoup。这是又一个乏味但非常有用的代码，我不认为我可以开始估计这些年来它为我节省了多少时间和工作。

作为一门编程语言，你认为 Python 将何去何从？

我想重复一下我上面说的关于无聊软件的话，无聊是一件好事，因为我认为 Python 就是无聊软件。它已经经历了一定程度的时尚和新闻价值，但感觉那已经过去了，我们回到了它只是一个可靠的，体面的流行语言，被正在做事情的人使用。

Python 3 清除了语言中许多积累的缺陷，async/coroutine 的加入看起来状态良好，所以我不知道这种语言真正缺少的是什么。关于 Python，我一直喜欢的一点是每个版本都有多少小而合理的改进，每次都让程序员的生活变得轻松一点。

在这一点上，我希望大事件发生在工具和库的生态系统中，而不是语言本身。例如，包装已经比过去好了很多，但是我很高兴看到在这个领域仍然在进行的工作，以真正使工具和基础设施变得更好。

你对当前的 Python 程序员市场有什么看法？

*我觉得现在是了解 Python 的好时机。当我第一次开始学习它时，Python(在它自己的社区之外)可能被不喜欢 Perl 的人视为一种边缘 Unix 脚本语言。现在，它无处不在，许多公司都在它的基础上构建各种东西。*

举个例子:我在一家健康保险公司工作。从接收、解析和分类数据，到处理和分析管道，到实现我们的业务逻辑并与供应商互操作的应用程序，我们都用 Python 端到端地完成。当然，我们处于一个高度监管的空间，在这个空间中，法规和需求会不断变化，所以 Python 对我们来说是一个很大的优势:我们可以实现复杂的需求，或者适应甚至一些相当大的变化，这比我们基于更传统的企业空间语言和工具要快得多。

能够做到这一点是 Python 的一大卖点，这转化为对 Python 程序员的大量需求。我读到的一切都表明需求很大。

你还有什么想说的吗？

我们整个领域目前面临的最大风险之一是我们自己的精英主义和我们根深蒂固的信念，即我们以某种方式选择或奖励“优点”。事实是，我们让人们经受一连串的戏弄仪式和陈词滥调；奖励运气和傲慢；把侮辱和嘲笑混淆为诚实和直率。

结果是一种危险的平庸混蛋的单一文化——我们不是选择那些表现出技术优势的人(这种优势有多种形式),而是把选择的权力放在那些“优势”是愿意忍受所有这些垃圾以便有一天成为向他人分发垃圾的人手中。所以很自然地，他们最终会招募像他们一样的人，并延续这种循环。

在这个过程中，我们赶走了很多能够并且愿意写出好代码的人，只要我们在他们起步时给他们一点帮助和善意，这是很难容忍的，因为公司总是不顾一切地寻找拥有良好技术技能的人，而贡献者总是不顾一切地让开源项目继续下去。回到我之前提到的航空怪癖，我可以打个比方:美国的航空公司已经为威胁他们行业的“飞行员短缺”问题焦虑了一段时间，但问题并不在于缺乏能成为优秀飞行员的人。问题是航空公司对待他们的初级飞行员很糟糕，关于这一点的消息已经传开了，所以没有足够的人愿意再忍受它，航空公司不能保持他们的队伍。软件业感觉它正走向一个非常相似的情况。

这不容易解决，但我们必须解决它，否则它将对我们的行业和开源生态系统构成生存威胁。我们必须在很多地方修正它:我们必须在邮件列表和论坛上修正它，我们必须在会议上修正它，我们必须在面试和招聘过程中修正它，我们必须在办公室文化中修正它，我们必须在所有地方和所有过程中修正它。

Python 社区已经在这方面迈出了很大的步伐，但是我们还有很多工作要做。为了成功，需要我们所有人的努力。如果你不确定自己能做什么，最好的办法就是善待他人，假设新员工很聪明，如果有机会学习，就有能力做好工作，而不是因为从第一天起就不是专家而被赶走。当我开始的时候，我当然不是专家，其他人也不是！

感谢您接受采访！