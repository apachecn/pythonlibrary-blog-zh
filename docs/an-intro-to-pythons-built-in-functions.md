# Python 内置函数介绍

> 原文：<https://www.blog.pythonlibrary.org/2021/02/17/an-intro-to-pythons-built-in-functions/>

内置是 Python 中有点被忽视的部分。你每天都在使用它们，但是有一些被忽视了，或者只是没有充分发挥它们的潜力。本文不会涵盖 Python 中的所有内置功能，而是将重点放在那些您可能不会每天使用的功能上。

#### 任何()

内置的 **any()** 接受一个 iterable，如果 iterable 中的任何元素为 True，将返回 True。让我们来看一个例子:

```py
>>> any([0,0,0,1])
True
```

在这种情况下，您传递给 **any()** 一个由 0 和 1 组成的列表。因为那里有一个，它返回 True。你可能想知道你什么时候会用到这个内置的。一开始我也是。在我的一份工作中出现的一个例子涉及到一个非常复杂的用户界面，我必须在那里测试各种功能。我需要测试的一个项目是，某个小部件列表是否在不应该显示或启用的时候显示或启用了。内置的 **any()** 对此非常有用。

这里有一个例子可以说明我所说的内容，尽管这不是我实际使用的代码:

```py
>>> widget_one = ''
>>> widget_two = ''
>>> widget_three = 'button'
>>> widgets_exist = any([widget_one, widget_two, widget_three])
>>> widgets_exist
True

```

在本例中，您将查询用户界面，询问是否存在部件 1 到部件 3，并将响应放入一个列表中。如果它们中的任何一个返回 True，那么就会产生一个错误。

您可能想要检查 Python 的所有内置功能，因为它具有类似的功能，除了只有当 iterable 中的每一项都为 True 时，它才会返回 True。

#### 枚举()

你是否曾经需要遍历一个列表，并且需要知道你在列表中的位置？您可以添加一个在循环时递增的计数器，或者使用 Python 内置的 **enumerate()** 函数！让我们用绳子试一下！

```py
>>> my_string = 'abcdefg'
>>> for pos, letter in enumerate(my_string):
...     print (pos, letter)
... 
0 a
1 b
2 c
3 d
4 e
5 f
6 g
```

在本例中，您有一个 6 个字母的字符串。在循环中，将字符串包装在枚举调用中。这将返回 iterable 中每一项的位置以及值。你把它们都打印出来，这样你就能看到发生了什么。我个人发现了很多 **enumerate()** 的用例。我相信你也会的。

#### eval()

内置的 **eval()** 在 Python 社区中颇具争议。原因是 eval 接受字符串并运行它们。如果您允许用户输入任何要被 eval 解析和评估的字符串，那么您就犯了一个严重的安全漏洞。但是，如果使用 eval 的代码不能被用户交互，只能被开发人员交互，那么就可以使用。有些人会认为它仍然不安全，但是如果你有一个流氓开发人员，他们做其他事情会比使用 eval 造成更多的伤害。

让我们看一个简单的例子:

```py
>>> var = 10
>>> source = 'var * 2'
>>> eval(source)
20
```

这里，您创建了两个变量。第一个被赋予整数 10。第二个有一个字符串，和你刚刚定义的变量有相同的字母，看起来你要把它乘以 2。然而，它只是一个字符串，所以它不做任何事情。但是有了 **eval()** ，就可以让它做点什么了！你可以在下一行看到它的运行，你把字符串传递给 eval，得到一个结果。这就是为什么人们认为 eval 可能是危险的。

还有一个内置函数叫做 **exec()** ，支持 Python 代码的动态执行。这也是一个有点“危险”的内置，但它没有 **eval()** 的坏名声。这是一个简洁的小工具，但要小心使用。

#### 过滤器()

**filter()** 内置函数将接受一个函数和一个 iterable，并为 iterable 中那些传入函数返回 True 的元素返回一个迭代器。这句话听起来有点令人费解，所以让我们来看一个例子:

```py
>>> def less_than_ten(x):
...     return x < 10
... 
>>> my_list = [1, 2, 3, 10, 11, 12]
>>> for item in filter(less_than_ten, my_list):
...     print(item)
... 
1
2
3
```

这里您创建了一个简单的函数来测试您传递给它的整数是否小于 10。如果是，则返回**真**；否则，返回**假**。接下来，创建一个包含 6 个整数的列表，其中一半小于 10。最后，使用 **filter()** 过滤掉大于 10 的整数，只打印小于 10 的整数。

你可能还记得 **itertools** 模块有一个类似于这个叫做 **filterfalse** 的功能。那个函数与这个函数相反，只在函数返回 **False** 时返回 iterable 的元素。

#### 地图()

内置的 **map()** 也接受一个函数和一个 iterable，并返回一个迭代器，迭代器将函数应用于 iterable 中的每一项。让我们看一个简单的例子:

```py
>>> def doubler(x):
...     return x * 2
... 
>>> my_list = [1, 2, 3, 4, 5]
>>> for item in map(doubler, my_list):
...     print(item)
... 
2
4
6
8
10
```

你定义的第一件事是一个函数，无论传递给它什么，它都会加倍。接下来，你有一个整数列表，1-5。最后，为创建一个**循环，该循环遍历用我们的函数和列表调用 map 时返回的迭代器。循环中的代码将打印出结果。**

map 和 filter 函数基本上复制了 Python 3 中生成器表达式的特性。在 Python 2 中，它们复制了列表理解的功能。您可以将上面的代码缩短一点，让它返回一个列表，如下所示:

```py
>>> list(map(doubler, my_list))
[2, 4, 6, 8, 10]
```

但是你可以用列表理解做同样的事情:

```py
>>> [doubler(x) for x in my_list]
[2, 4, 6, 8, 10]
```

所以你想用哪个真的取决于你。

#### zip()

内置的 zip()接受一系列 iterables，并从每个 iterables 中聚合元素。让我们看看这意味着什么:

```py
>>> keys = ['x', 'y', 'z']
>>> values = [5, 6, 7]
>>> zip(keys, values)
<zip object at 0x7fc76575a548>
>>> list(zip(keys, values))
[('x', 5), ('y', 6), ('z', 7)]
```

在本例中，您有两个大小相同的列表。接下来，使用 zip 函数将它们压缩在一起。这只是返回一个 zip 对象，所以您将它包装在对内置 list 的调用中，以查看结果。你最终会得到一个元组列表。您可以在这里看到，zip 按照位置匹配每个列表中的条目，并将它们放入元组中。

zip()最流行的一个用例是获取两个列表，并将它们转换成一个字典:

```py
>>> keys = ['x', 'y', 'z']
>>> values = [5, 6, 7]
>>> my_dict = dict(zip(keys, values))
>>> my_dict
{'x': 5, 'y': 6, 'z': 7}
```

当你将一系列元组传递给 Python 的 **dict()** 内置时，它会创建一个字典，如上图所示。我在自己的代码中经常使用这种技术。

#### 包扎

虽然这是一个简短的旅程，但我希望它能让您很好地了解 Python 的内置功能给了您多大的力量。还有很多其他你每天都在用的，比如 list，dict 和 dir。你在本章中学到的内置函数可能不会每天都用到，但在某些情况下会非常有用。实际上，我用了整整一章来介绍一种叫做 super 的特殊内置功能，你可以在本书的后面读到。享受这些乐趣，并确保查找文档，看看还有什么其他的珠宝存在。

#### 相关阅读

*   Python 101 - [了解字典](https://www.blog.pythonlibrary.org/2020/03/31/python-101-learning-about-dictionaries/)
*   Python 101 - [了解列表](https://www.blog.pythonlibrary.org/2020/03/10/python-101-learning-about-lists/)
*   Python 101 - [了解元组](https://www.blog.pythonlibrary.org/2020/03/26/python-101-learning-about-tuples/)