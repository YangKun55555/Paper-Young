# 数据结构与算法分析--Java

[TOC]

## 递归

> 递归：一个函数用自己来定义。
>
> 基准情况：函数的值可以直接算出而不用求助于递归。
>
> 循环推理：定义一个方法用的是这个方法本身，对递归而言，并没有用方法本身定义一个该方法的特定实例。即：通过 f(5)计算得到 f(5)是循环推理，但在递归中，是通过 f(4)得到f(5)，因此，递归不是循环推理。
>
> 递归的基本法则：基准情况+不断推进（递归调用必须总能向着一个基准情况推进）。

## 泛型

（实现代码重用，实现方式）

1. 使用 Object 基础超类来作为泛型的参数类型。
2. 使用接口实现泛型