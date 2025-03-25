# The Python Tutorial

Python是一种易于学习且功能强大的编程语言。它具有高效的高级数据结构，以及一种简单但有效的面向对象(OOP)编程方法。Python优雅的语法和动态类型，再加上其解释性特性，使其成为在大多数平台上许多领域进行脚本编写和快速应用程序开发的理想语言。

Python解释器及其广泛的标准库可以从Python官方网站（https://www.python.org/） 免费获取，以源代码或者二进制形式提供，适用于所有的主要平台，并且可以自由分发。该网站还包含许多免费的第三方Python模块、程序和工具的分发版本及链接，以及额外的文档。

Python解释器也可以轻松地通过用C或C++（或其他可从C调用的语言）实现的新函数和数据类型进行扩展。Python也是和作为可定制应用程序的扩展语言。

本教程以非正式的方式向读者介绍Python语言和系统的基本概念和特性。手边有一个Python解释器会很有助于实践体验，但所有示例都是自包含的，因此本教程也可以离线阅读。

要了解标准对象和模块的描述，请参阅《Python标准库》。 《Python语言参考》提供了对语言的更正式定义。要用C或C++编写扩展，请阅读《扩展和嵌入Python解释器》和《Python/C API参考手册》。 还有几本深入介绍Python的书籍。

本教程并非旨在覆盖Python的每一个功能，甚至也不是每一个常用功能。相反，它介绍了Python许多最值得注意的特性，让你对这门语言的风格和特点有一个很好的了解。读完之后，你将能够阅读和编写Python模块和程序，并且准备好进一步学习《Python标准库》中描述的各种Python模块。

术语表也值得一看.

# Python 3.13 教程目录

## 1. 开胃菜 (Whetting Your Appetite)

## 2. 使用 Python 解释器 (Using the Python Interpreter)
- 2.1 调用解释器 (Invoking the Interpreter)
- 2.2 解释器及其环境 (The Interpreter and Its Environment)

## 3. Python 简介 (An Informal Introduction to Python)
- 3.1 使用 Python 作为计算器 (Using Python as a Calculator)
  - 3.1.1 数字 (Numbers)
  - 3.1.2 字符串 (Strings)
  - 3.1.3 列表 (Lists)
- 3.2 迈出编程第一步 (First Steps Towards Programming)

## 4. 更多控制流工具 (More Control Flow Tools)
- 4.1 `if` 语句 (if Statements)
- 4.2 `for` 语句 (for Statements)
- 4.3 `range()` 函数 (The range() Function)
- 4.4 `break` 和 `continue` 语句，以及循环中的 `else` 子句 (break and continue Statements, and else Clauses on Loops)
- 4.5 `pass` 语句 (pass Statements)
- 4.6 `match` 语句 (match Statements)
- 4.7 定义函数 (Defining Functions)
- 4.8 更多关于定义函数的内容 (More on Defining Functions)
  - 4.8.1 默认参数值 (Default Argument Values)
  - 4.8.2 关键字参数 (Keyword Arguments)
  - 4.8.3 特殊参数 (Special Parameters)
  - 4.8.4 任意参数列表 (Arbitrary Argument Lists)
  - 4.8.5 解包参数列表 (Unpacking Argument Lists)
  - 4.8.6 Lambda 表达式 (Lambda Expressions)
  - 4.8.7 文档字符串 (Documentation Strings)
  - 4.8.8 函数注解 (Function Annotations)
- 4.9 插曲：编码风格 (Intermezzo: Coding Style)

## 5. 数据结构 (Data Structures)
- 5.1 更多关于列表的内容 (More on Lists)
  - 5.1.1 将列表用作栈 (Using Lists as Stacks)
  - 5.1.2 将列表用作队列 (Using Lists as Queues)
  - 5.1.3 列表推导式 (List Comprehensions)
  - 5.1.4 嵌套列表推导式 (Nested List Comprehensions)
- 5.2 `del` 语句 (The del Statement)
- 5.3 元组与序列 (Tuples and Sequences)
- 5.4 集合 (Sets)
- 5.5 字典 (Dictionaries)
- 5.6 循环技巧 (Looping Techniques)
- 5.7 更多关于条件的内容 (More on Conditions)
- 5.8 比较序列和其他类型 (Comparing Sequences and Other Types)

## 6. 模块 (Modules)
- 6.1 更多关于模块的内容 (More on Modules)
  - 6.1.1 以脚本方式执行模块 (Executing Modules as Scripts)
  - 6.1.2 模块搜索路径 (The Module Search Path)
  - 6.1.3 “编译” Python 文件 (“Compiled” Python Files)
- 6.2 标准模块 (Standard Modules)
- 6.3 `dir()` 函数 (The dir() Function)
- 6.4 包 (Packages)
  - 6.4.1 从包中导入 * (Importing * From a Package)
  - 6.4.2 包内引用 (Intra-Package References)
  - 6.4.3 多目录中的包 (Packages in Multiple Directories)

## 7. 输入与输出 (Input and Output)
- 7.1 格式化输出 (Fancier Output Formatting)
  - 7.1.1 格式化字符串字面量 (Formatted String Literals)
  - 7.1.2 字符串的 format() 方法 (The String format() Method)
  - 7.1.3 手动格式化字符串 (Manual String Formatting)
  - 7.1.4 旧式字符串格式化 (Old String Formatting)
- 7.2 读写文件 (Reading and Writing Files)
  - 7.2.1 文件对象的方法 (Methods of File Objects)
  - 7.2.2 使用 json 保存结构化数据 (Saving Structured Data with json)

## 8. 错误与异常 (Errors and Exceptions)
- 8.1 语法错误 (Syntax Errors)
- 8.2 异常 (Exceptions)
- 8.3 处理异常 (Handling Exceptions)
- 8.4 抛出异常 (Raising Exceptions)
- 8.5 异常链 (Exception Chaining)
- 8.6 用户定义的异常 (User-defined Exceptions)
- 8.7 定义清理操作 (Defining Clean-up Actions)
- 8.8 预定义清理操作 (Predefined Clean-up Actions)
- 8.9 在异常后执行代码 (Running Code After an Exception)

## 9. 类 (Classes)
- 9.1 关于名称和对象的说明 (A Word About Names and Objects)
- 9.2 Python 作用域与命名空间 (Python Scopes and Namespaces)
  - 9.2.1 作用域与命名空间示例 (Scopes and Namespaces Example)
- 9.3 初识类 (A First Look at Classes)
  - 9.3.1 类定义语法 (Class Definition Syntax)
  - 9.3.2 类对象 (Class Objects)
  - 9.3.3 实例对象 (Instance Objects)
  - 9.3.4 方法对象 (Method Objects)
- 9.4 随机说明 (Random Remarks)
- 9.5 继承 (Inheritance)
  - 9.5.1 多重继承 (Multiple Inheritance)
- 9.6 私有变量 (Private Variables)
- 9.7 杂项 (Odds and Ends)
- 9.8 迭代器 (Iterators)
- 9.9 生成器 (Generators)
- 9.10 生成器表达式 (Generator Expressions)

## 10. 标准库简介 (Brief Tour of the Standard Library)
- 10.1 操作系统接口 (Operating System Interface)
- 10.2 文件通配符 (File Wildcards)
- 10.3 命令行参数 (Command Line Arguments)
- 10.4 错误输出重定向与程序终止 (Error Output Redirection and Program Termination)
- 10.5 字符串模式匹配 (String Pattern Matching)
- 10.6 数学 (Mathematics)
- 10.7 互联网访问 (Internet Access)
- 10.8 日期与时间 (Dates and Times)
- 10.9 数据压缩 (Data Compression)
- 10.10 性能测量 (Performance Measurement)
- 10.11 质量控制 (Quality Control)
- 10.12 自带电池 (Batteries Included)

## 11. 标准库简介 - 第二部分 (Brief Tour of the Standard Library — Part II)
- 11.1 输出格式化 (Output Formatting)
- 11.2 模板 (Templating)
- 11.3 使用二进制数据记录布局 (Working with Binary Data Record Layouts)
- 11.4 多线程 (Multi-threading)
- 11.5 日志 (Logging)
- 11.6 弱引用 (Weak References)
- 11.7 列表操作工具 (Tools for Working with Lists)
- 11.8 十进制浮点运算 (Decimal Floating Point Arithmetic)

## 12. 虚拟环境与包 (Virtual Environments and Packages)
- 12.1 简介 (Introduction)
- 12.2 创建虚拟环境 (Creating Virtual Environments)
- 12.3 使用 pip 管理包 (Managing Packages with pip)

## 13. 下一步做什么？ (What Now?)

## 14. 交互式输入编辑与历史记录替换 (Interactive Input Editing and History Substitution)
- 14.1 制表符补全与历史记录编辑 (Tab Completion and History Editing)
- 14.2 交互式解释器的替代品 (Alternatives to the Interactive Interpreter)

## 15. 浮点运算：问题与限制 (Floating Point Arithmetic: Issues and Limitations)
- 15.1 表示误差 (Representation Error)

## 16. 附录 (Appendix)
- 16.1 交互模式 (Interactive Mode)

---

# 1.开胃菜

这一章是 Python 教程的引言，旨在激发读者对 Python 的兴趣。主要内容包括：

Python 的特点：介绍了 Python 作为一种简单、易学且功能强大的编程语言的优势，适合初学者和专业开发者。
应用场景：Python 可用于快速开发脚本、构建大型应用程序、处理数据、自动化任务等。
学习动机：鼓励读者通过教程探索 Python，强调其“自带电池”（丰富的标准库）和跨平台特性。
目标：为后续章节奠定基础，让读者对 Python 的潜能有个初步印象，而不是深入技术细节。

# 2.使用Python解释器
这一章介绍了如何启动和使用 Python 解释器，是动手操作的第一步。主要内容包括：

## 2.1 调用解释器（Invoking the Interpreter）

启动方式：在命令行输入 python 或 python3（视系统而定）启动解释器。示例：运行后显示版本信息和提示符 >>>。

参数：可以带命令行参数，如 python -c "print('Hello')" 执行单行代码，或 python script.py 运行文件。

交互模式：直接输入代码并立即看到结果，适合实验和学习。

## 2.2 解释器及其环境 (The Interpreter and Its Environment)

输入与退出：输入代码后按回车执行，输入 quit() 或 Ctrl+D（Unix）/Ctrl+Z（Windows）退出。

环境配置：

     PYTHONPATH：设置模块搜索路径，类似于系统 PATH。
     编码：默认使用 UTF-8 处理源代码，支持其他编码（通过文件顶部声明）。

错误处理：解释器会显示语法错误或异常信息，帮助调试。

脚本执行：可以将代码保存为 .py 文件，通过 python 文件名.py 执行。

# 3. Python 简介 (An Informal Introduction to Python)

## 3.1 使用 Python 作为计算器 (Using Python as a Calculator)

### 3.3.1 数字（Numbers）

解释器可以作为一个简单的计算器：你可以在其中输入任何一个表达式，它会返回计算结果。表达式的语法很简单：运算符+、-、* 和 / 可用于执行算术运算；括号 (()) 可用于分组。例如：

```Py
>>> 2+2
4
>>> 50-5*6
20
>>> (50-5*6) / 4
5
>>> 8/5  # 除法返回的是一个浮点数
1.6

```

整数（例如2、4、20）的类型是`int`，带有小数部分（例如5.6、1.6）的类型是`float`。我们将在教程的后续部分详细了解更多关于数字类型的内容。

除法（`/`）总是返回一个浮点数（float）。如果想进行地板除法并得到整数结果，可以使用`//`运算符；如果想计算余数，可以使用`%`运算符：

```Py
>>> 17 / 3
5.666666666666667
>>> 17 // 3
5
>>> 17 % 3
2
>>> 5 * 3 +2 
17
```

在python中，可以使用`**`运算符来计算幂：

```Py
>>> 5 ** 2 
25
>>> 2 ** 7
128
```

等哈（`=`）用于将一个值赋给变量。赋值后，在下一个交互提示符出现之前不会显示任何结果：

```Py
>>> width = 20
>>> height = 5*9
>>> width * height
900
```

如果一个变量未被定义（即未被赋值），尝试使用它会产生错误：
![img.png](img.png)

Python完全支持浮点数运算；当运算符的操作数类型混合时，整数操作数会被转换为浮点数：
```Py
>>> 4 * 3.75 - 1
14.0
```
在交互模式下，最后打印的表达式会被赋值给变量`_`。这意味着，当你将Pytho当作桌面计算器是，继续进行计算会变得更加方便，例如：

![img_1.png](img_1.png)

用户应将这个变量是为只读。不要显式地给它赋值-这样做会创建一个同名的独立局部变量，掩盖具有特殊行为的内值变量。

除了支持`int`和`float`，Python还支持其他类型的数字，例如`Decimal`和`Fraction`。Python还内置了对复数的支持，并使用`j`或`J`后缀来表示虚部（`3+5j`）。

### 3.1.2 字符串 (Strings)

Python可以操作文本（由`str`类型表示，称为“字符串”）以及数字。这包括字符“！”、单词“rabbit”、名称“Paris”、句子“Got your back”等等。它们可以用双引号（“...”）或单引号（‘...’）括起来，结果相同。

```Py
>>> 'spam eggs'
'spam eggs'
>>> "Paris rabbit got your back :)! Yay!"
'Paris rabbit got your back :)! Yay!'
>>> '1975'
1975
```
要引用一个引号，我们需要通过在它前面`\`来转移它。或者，我们可以使用另一种类型的引号：

```Py
>>> 'dosen\'t'  
"doesn't"
>>> "dosen't"
"dosen't"
```

在Python shell中，字符串的定义和输出字符串可能看起来不同。`print()`函数会生成更易读的输出，它会省略包围的引号，并打印转义字符和特殊字符：

```Py
>>> s = 'First line. \nSecond line.'
>>> s
'First line. \nSecond line.'
>>> print(s)
First line. 
Second line.
```

如果你不希望以`\`开头的字符被解释为特殊字符，可以通过在第一个引号前添加r来使用原始字符串：
```Py
>>> print('C:\some\name')
C:\some
ame
>>> print(r'C:\some\name')
C:\some\name
```

原始字符串有一个微妙的细节：原始字符串不能以奇数个`\`字符结尾；有关更多信息和解决方法，请参阅FAQ条目。

字符串字面量可以跨越多行。一种方法是使用三重引号："""..."""或'''...'''。行尾字符会自动包含在字符串中，但可以通过在行尾添加\来阻止这种行为。在下面的例子中，初始的换行符不会被包含：

![img_2.png](img_2.png)

字符串可以用`+`运算符连接，并用`*`运算符重复：

```Py
>>> 3 * 'hq' + 'fp'
'hqhqhqfp'
>>> 'Hq' 'love' 'fp'  # 两个或多个相邻的字符串字面量（即用引号括起来的字符串）会自动连接在一起。
'Hqlovefp'
```
这个特性在你想拆分长字符串时特别有用：

![img_3.png](img_3.png)

这种连接方式不能用于变量或者表达式，若是想连接可以用`+`

字符串可以被索引（下标访问），第一个字符的索引为0。没有单独的字符类型；一个字符只是一个长度为一的字符串：

![img_4.png](img_4.png)

-0也是0,复数索引从-1开始。
