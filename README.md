# HUSTCSE-Algebra
华中科技大学2023年代数学作业

## 环境要求

- python3
- Jupyter记事本
- 以下pip第三方库

```shell
pip install sympy tqdm numpy matplotlib
```

## T2 - 练习一

![图片](https://github.com/6QHTSK/HUSTCSE-Algebra/assets/62872488/8a691993-95d2-4f45-9c7f-761f1352709f)

对应文件：[gnfs.ipynb](gnfs.ipynb)

运行时间：约40分钟跑出一个skew或者$c_4$的COUNT，全部跑完大概要一天晚上。

这部分的代码大部分来自于『是Yu欸』的[【代数学作业1完整版-python实现GNFS一般数域筛】构造特定的整系数不可约多项式：涉及素数、模运算和优化问题](https://blog.csdn.net/wtyuong/article/details/135102439)，遵循 CC 4.0 BY-SA 版权协议。

没有附带测 $` c_4 `$的代码，如有需要可以自己找到一个比较好的skew，然后把记事本里面的代码拉出来，额外开一个python文件，给$c_4$不同取值去测以下趋势就行。

## T7 - 大整数分解

给定 $` n=1234268228312430759578090015472355712114804731217710966738223 `$ ，试用数域筛法对其进行分解，要求写出详细过程并附代码。

对应文件：[Quadratic.ipynb](Quadratic.ipynb)

运行时间：约20~30分钟，单线程。

这部分的代码很大部分来自于[MattInglisWhalen/FastFactor](https://github.com/MattInglisWhalen/FastFactor)，遵循 MIT 版权协议。

我使用了它的代码，并利用`sympy`减少了它的代码复杂度。

P.S. 想问一下有谁用GNFS的方法写出来的，我卡在怎么用$`b^4f(a/b)`$与$`bg(a/b)`$构造平方数上了，如果有人写出来了烦请赐教。

## 题外话

<img src="https://github.com/6QHTSK/HUST-Compilers-Principles-Task/blob/b482d56085c79c0911a6a1e51d81d0f562fb2e1d/assets/meme1.jpeg" alt="meme" style="width: 5cm;">
