# Python语言概述

Python是一种解释性、面向对象、动态数据类型的高级程序设计语言。接下来分别对这几个方面对比Java做详细介绍。

## 解释性语言 vs 编译性语言
1. Python是一种解释性语言，也称为脚本语言，这意味着开发过程中没有编译的环节。Python语言由解释器逐行解释执行。
2. Java是编译性语言，Java程序经过编译后，由虚拟机（JVM）执行。

虽然本质上是完全不同的两种语言，但这两种语言都是很好的跨平台语言。Java程序只要有适合的JVM就可以在任何机器上执行，同时Python只要有合适的解释器也可以在任何机器上执行。

## 动态数据类型 vs 静态数据类型
1. Python的变量是动态的，意味着在Python中创建变量并不需要指定变量的数据类型，也意味着我们可以随意给已经存在的变量赋任何类型的值，甚至可以在程序的任何地方直接加入新变量使用，因为Python并不需要预先知道变量的类型。
2. Java是变量是静态的。Java中创建变量必须明确变量的类型（Java1.8以前），这样JVM才能根据类型在内存中为变量分配地址空间。同时，变量一旦创建以后，其数据类型不可再改变。

## 面向对象的差异

Python与Java一样都是面向对象编程语言。但是二者依然存在很多差异。
  * Java语言有着更严格的限制。Java以类文件（AAA.java）作为基本构成模块，类文件中必须包含有与文件名相同的类名。模块中可以定义变量，函数以及可执行的代码，但是，变量，函数必须定义在类中，可执行的代码则必须定义在方法内部。类以外不能创建任何元素。另外，只有包含了静态main方法的类，可有执行的入口，否则只能作为类文件用于创建对象。在模块引入上，Java以类作为最基本单位，除了静态成员变量意外，其他所有内容都需要通过创建类对象的方式引入。
  * Python的要求则宽松和自由很多。Python的文件都以.py来命名，而一个.py文件就构成了一个模块。在一个模块中，只要符合语法格式，可以在任意位置定义变量，函数，类以及写入可执行代码。在模块引用上，Python同样非常自由。只要有了import+模块名语句，就可以直接引用该模块中的类和方法，即使没有创建该模块的任何对象。这与Java同样有着本质上的不同。
