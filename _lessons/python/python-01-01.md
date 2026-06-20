---
title: "Lecture 1-1 - Python 基础"
collection: lessons
series: python
index: 1
permalink: /lessons/python/python-01-01/
layout: single
author_profile: true
---

# 1. Python 介绍

## 1.1 Python 发展史

* Python的作者是荷兰人 Guido von Rossum ，他 1982 年从阿姆斯特丹大学获得了数学和计算机硕士学位

* Guido 希望有一种语言，既能像 C 语言那样，能够全面调用计算机的功能接口，又可以像 shell 那样，可以轻松地编程。于是就发明了 Python 语言

* 1989 年 Guido 为了打发圣诞节假期，开始用 C 语言编写 Python 语言编译器

* 1991 年，第一个 Python 编译器诞生

## 1.2 Python 的特点

### (1) Python 的优点

* 解释性语言，不需要编译，用 python 解释器就可以运行

* 编程简单，将精力从语言本身上解放出来（**人生苦短，我用 python**）

* 免费、开源

* 高层语言，不用考虑底层细节

* 可移植性强，已在许多平台上得到支持

* 面向对象

* 可扩展性强，如果某段代码对性能要求高，可用 C/C++ 编写，然后用 python 调用它

* 丰富的库

* 代码规范，采用强缩进方式，可读性强

### (2) Python 的缺点

* 运行速度慢

* 构架选择太多，没有官方推荐框架

## 1.3 Python 应用场景

* Web 应用

* 操作系统管理、服务器运维的自动化脚本

* 科学计算：Numpy，、SciPy、Matplotlib 等科学计算库

* 桌面软件：PyQt、PySide、wxPython、PyGTK等桌面程序利器

* 服务器软件（网络软件）

* 游戏：编写游戏的逻辑

* 构思实现产品早期原型和迭代



# 2. Python 程序

## 2.1 Python 的两种执行模式

### (1) Python 的

```bash
# 编写 python 代码并保存
vi test.py
# 执行 python 文件
python test.py
```

### (2) Python 的交互模式

```bash
# 直接在命令行敲 python 或者 ipython 打开 python 的交互模式
python
python3
# ipython 是 python 语法加上 shell 脚本语法
ipython
ipython3
```

## 2.2 Python 的注释

* 解释代码，增强代码可读性

### (1) 行注释

井号开头，井号后面的一行内容就是注释内容

```python
# 这是一个行注释
```

### (2) 块注释

包含在一组三单引号或三双引号之间的内容就是注释内容

```python
'''
这是块注释
'''

"""
这是块注释
"""
```
