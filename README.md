# Python的91个建议 笔记

## 1.理解Pythonic概念
> Python之禅

```python
import this

The Zen of Python, by Tim Peters

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.a
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!
```

## 2.编写Pythonic代码

- 避免只用大小写来区分不同的对象
- 避免使用容易引起混淆的名称
- 不要害怕过长的变量名

## 3.理解Python与C语言的不同之处

## 4.在代码中适当添加注释


## 5.通过适当添加空行使代码布局更为优雅、合理

## 6.编写函数的4个原则
- 函数设计要尽量短小, 嵌套层次不宜过深
- 函数申明应该做到合理、简单、易于使用
- 函数参数设计应该考虑向下兼容
- 一个函数只做一件事，尽量保证函数语句粒度的一致性

## 7.将常量集中到一个文件

## 8.利用assert语句来发现问题

## 9.数据交换值的时候不推荐使用中间变量

## 10.充分利用 Lazy evaluation的特性
- 避免不必要的计算，带来性能的提升
- 节省空间，使得无限循环的数据结构成为可能

## 11.理解枚举替代实现的缺陷

## 12.不推荐使用type来进行类型检查

## 13.尽量转换为浮点类型再做除法

## 14.警惕eval()的安全漏洞

## 15.使用enumerate()获取序列迭代的索引和值

## 16.分清 == 与 is 的适用场景

## 17.考虑兼容性，尽可能使用Unicode

## 18.构建合理的包层次来管理module

## 19.有节制的使用 from ... import 语句

## 20.优先使用absolute import 来导入模块

## 21. i+=1 不等于 ++i

## 22. 使用with自动关闭资源

## 23.使用else字句简化循环(异常处理)

## 24. 遵循异常出来的几点基本原则

## 25. 避免finally 中可能发生的陷阱

## 26. 深入理解 None, 正确判断对象是否为空

## 27.连接字符串应优先使用join而不是 +

## 28. 格式化字符串时尽量使用.format方式而不是%

## 29. 区别对待可变对象和不可变对象

## 30. []、()、{} 一致的容器初始化形式

## 31. 记住函数传参既不是传值也不是传引用

## 32. 警惕默认参数潜在的问题

## 33. 慎用变长参数

## 34. 深入理解 str() 和 repr() 的区别

## 35. 分清staticmethod 和  classmethod的适用场景

## 36. 掌握字符串的基本用法

## 37. 按需选择 sort() 或者 sorted()

## 38. 使用 copy模块深拷贝对象

## 39. 使用 Counter 进行计数统计

## 40. 深入掌握 ConfigParser

## 41. 使用 argparse 处理命令行参数

## 42. 使用pandas 处理大型csv文件

## 43. 一般情况使用 ElementTree 解析XML

## 44. 理解模块 pickle 优劣

## 45. 序列化另一个不错的选择 JSON

## 46. 使用traceback 获取栈信息

## 47. 使用logging记录日志信息

## 48. 使用 threading 模块编写多线程程序

## 49. 使用Queue是多线程编程更安全

## 50. 利用模块实现单例模式

## 51. 利用mixin 模式让程序更加灵活

## 52. 利用发布订阅模式实现松耦合

## 53. 利用状态模式美化代码

## 54. 理解built-in objects

## 55. __init__() 不是构造方法

## 56. 理解名字查找机制

## 57. 为什么需要self参数

## 58. 理解MRO与多继承

## 59. 理解描述符机制

## 60.  区别 __getattr__() 和 __getattribute__() 方法

## 61. 使用更安全的 property

## 62. 掌握 metaclass

## 63. 熟悉Python对象协议

## 64. 利用操作符重载实现中缀语法

## 65. 熟悉 Python的迭代器协议

## 66. 熟悉Python的生成器

## 67. 基于生成器的协程及greenlet

## 68. 理解GIL的极限性

## 69. 对象的管理与垃圾回收

## 70. 从PyPI安装包

## 71. 使用pip和yolk安装、管理包

## 72. 做 paster 创建包

## 73. 理解单元测试概念

## 74. 为包编写单元测试

## 75. 利用测试驱动开发提高代码可测性

## 76. 使用 Pylint 检查代码风格

## 77. 进行高效的代码审查

## 78. 将包发布到PyPI

## 79. 了解代码优化的基本原则

## 80. 借助性能优化工具

## 81. 利用 cProfile 定位性能瓶颈

## 82. 使用 memory_profilter 和 objgraph 剖析内存使用

## 83. 努力降低算法复杂度

## 84. 掌握循环优化的基本技巧

## 85. 使用生成器提高效率

## 86. 使用不同的数据结构优化性能

## 87. 充分利用 set 的优势

## 88. 使用 multiprocessing 客服 GIL 的缺陷

## 89. 使用线程池提高效率

## 90. 使用 C/C++模块扩展提高性能

## 91. 使用 Cython编写扩展模块
