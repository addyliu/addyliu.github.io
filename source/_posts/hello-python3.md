---
title: 初识 python3
---

官方文档: https://docs.python.org/zh-cn/3.8/tutorial/index.html

## 数字

pytho运算符的运用和大部分语言差不多

有几个小特点需要记一下:

###  / 返回的永远是浮点类型，如果需要返回整数，请使用 //

``` bash
$ >>> 12/2
6.0
$ >>> 12//2
6

```

### 使用 ** 计算乘方

``` bash
$ >>> 4**2
16

```

### 和许多语言一样， 多种昆和类型运算会把结果转换为浮点型

### 交互模式下的_，可以被当作临时变量引用

``` bash
$ >>> a = 2 * 2
>>> b = 100.28
>>> a + b
104.28
>>> _ + b
204.56
>>> _ + b
304.84000000000003

```

这里进行的第二次计算(_ + b)，结果并非预想的304.84，原因简单来说是计算机采用的二进制对浮点数无法准确表示，只能取近似值存储。指路官方解释: https://docs.python.org/zh-cn/3.8/faq/design.html?highlight=%E6%B5%AE%E7%82%B9#why-are-floating-point-calculations-so-inaccurate

解决办法:
  详细的解决办法在【浮点算术：争议和限制】一节中记录了 地址: https://docs.python.org/zh-cn/3.8/tutorial/floatingpoint.html#tut-fp-issues







