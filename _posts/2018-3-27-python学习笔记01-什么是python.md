---
layout:     post
title:      "python学习笔记01"
subtitle:   "什么是python？"
date:       2018-3-27 17:17:00
author:     "DG"
header-img: "img/post-python.jpg"
tags:
    - python学习笔记
    - python基础内容
---
# 什么是python
&ensp;&ensp;&ensp;&ensp;本篇博客内容主要介绍我对python的认识，简单地陈述说明[什么是python](#bui1)、[学习python的原因](#bui2)、[学习python的过程](
#bui3)。
---
<p id = "bui1"></p>
## 什么是python
&ensp;&ensp;&ensp;&ensp;什么是python？作为小白我也不敢妄下定义，[维基百科](https://zh.wikipedia.org/wiki/Python"前往维基百科")中的解释是通用型编程
语言、解释型编程语言。对此我看了一些相关介绍后依然一头雾水，但是随着不断地学习、练习，我对python语言有了一些个人理解：“通用型”是说python的应用范围广，比
如python可以做web开发、游戏编程、系统运维等，而“解释型”则是说python的编程过程不需要编译为机器码，而是由解释器“翻译”成机器码并逐句运行。这里要和java等编
译语言相对比,打个比方：python和java是两个中国人，他们遇到外国人的时候，python通过自带的翻译人员，直接说中文即可与老外交流，而java没有翻译人员，他自身懂
外语，直接就能与老外交流。所以python这种解释型语言的有点是开发速度快，他不需要考虑“外语”怎么说，直接就可以进行“交流”，而java等编译语言的优点是执行速度快，
他无需等待“翻译”的过程。这个例子仅是个人理解，并不是权威解释。
---
<p id = "bui2"></p>
## 学习python的原因
&ensp;&ensp;&ensp;&ensp;python是当下十分流行的编程语言，也是一种功能强大的编程语言，其广泛应用于系统编程、网络爬虫、人工智能、科学计算、web开发、系统
运维、大数据、云计算、金融以及图形计算等各个方面，其中我们熟知的YouTube、Instagram、Facebook、豆瓣、知乎甚至大型游戏如EVE、文明4等都有python的身影出现。
python的应用范围广泛，其各个岗位薪资也毫不逊色其他编程语言，当然，这些都不是我学习python的主要原因，学习python只有一个原因：简洁！在大学期间我接触过的编
程语言有C、C++、JAVA、PHP,其他类型的语言比如html、matlab、汇编等，虽然都没有深入学习，但仅仅是最基础的内容就足以证明一句调侃——从入门到放弃——绝非空谈啊。
相比于其他语言，python的数据类型不用声明、没有乱七八糟的括号和符号、依靠缩进来区别各个代码块的特性简直可以称得上小白佳品，其学习体验了令人十分愉悦。
&ensp;&ensp;&ensp;&ensp;python程序员中有一句话叫做“人生苦短，我学python”恰恰说明了python易学易懂的特性，很多黑python的人说python简单，在我看来这不是
缺点，而是最大的有点，正如[python之禅](#zen"The Zen of Python")所言，大道至简，最简才是最优。比如所有编程学习者入门要做的第一件事：输出"hello,world"
python的代码简单明了，代码如下：
>    print("hello,world")
就是这么直接，就是这么任性~
---
<p id = "bui3"></p>
## 学习python的过程
&ensp;&ensp;&ensp;&ensp;python目前有两个版本：python 2.x 以及python 3.x，由于2.x版本在2020年将停止支持，所以我学习的是python3。python3的学习资源
相对2来说少了很多，我刚开始是选择[W3Cschool](https://www.w3cschool.cn/python3/index.html"跳转到W3Cschool")的python3教程，后来发现内容较少由根据
知乎大佬们的推荐看了[廖雪峰大佬的教程](https://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000"跳转到教程")，当然
大佬的教程跳跃性比较大，学到后面就很难跟上“课后练习”的难度了，需要不断的去百度一些知识点加深理解。刷完所有练习后，我开始看一些python书籍，这里推荐
《python编程快速上手——让繁琐工作自动化》这本书，跟着学习的时候敲一些小项目代码会很有成就感。
---
<p id = "zen"></p>
## 附：python之禅
>    The Zen of Python
>>Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!
