# 2 月 5 日- 2009 年平壤会议总结

> 原文：<https://www.blog.pythonlibrary.org/2009/02/06/feb-5th-2009-pyowa-meeting-wrap-up/>

在我们昨晚的聚会上，除了我之外，我们还有 7 个新成员。考虑到过去几天有 5 个人退出，我认为这是一个很好的出席率。我们谈了一点关于我们自己的 Python 日，但是我们并没有提出太多。因此，我在征求意见，并希望为我们的下一次会议收集这些意见，这样我们就可以确定一个日期。

会议的其余时间都花在解决我遇到的前几个愚蠢的电脑问题上。我们有三个团队在研究它们，我们有相当多的种类。我用函数，另一个用类接口完全面向对象。我们只是把摄氏温度转换成华氏温度，反之亦然。第二个程序是将一系列数字转换成文本，例如:

如果用户输入:123，那么输出应该是“一二三”。为了让事情变得更困难，我们还需要一种处理负数的方法。有一种方法可以做到:

```py

numberDict = {0:"zero", 1:"one", 2:"two", 3:"three", 4:"four",
5:"five", 6:"six", 7:"seven", 8:"eight", 9:"nine"}
```

value = raw_input("请输入要转换为文本的一个数字或一系列数字: ")

对于 val in value:
if is instance(val，str) and val == "-":
打印" minus "，
else:
try:
#只打印可以转换为整数类型的字符
打印 numberDict[int(val)]，
除:
pass

当然，这种实现方式存在很多问题。例如，异常处理的方式不多，如果不重新运行脚本，就没有办法再次运行它。作为一个函数或一个类会更好，但是我将把那些任务留给读者作为练习。

我们的下一次会议将于 2009 年 3 月 2 日在马歇尔郡治安官办公室举行。我希望在那里见到你！