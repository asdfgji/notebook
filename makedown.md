# makedown快速笔记

---

## 1.代码块

```java
//代码块语法
​```java
    
​```shell
```

C语言示意

```C
#include "stdio.h"
void main()
{
    print("hello!");
}
```

## 2. 标题

```C
//六级标题
# 一级标题
## 二级标题
## 三级标题
```

# 一级标题

## 二级标题

### 三级标题

## 3.字体

```C
//加粗
**加粗**
//高亮
==高亮==
//删除线
~~删除线~~
//斜体
*斜体*
```

**加粗**
==高亮==
~~删除线~~
*斜体*

## 4. 引用

```C
//引用语法
>引用1
>>引用2
```

>引用1
>
>>引用2

## 5.分割线

```C
//分割线
---
//分割线
***
```

---

***

## 6.图片

```java
//本地图片、在线图片
![图片名](图片地址){:width="100px" height="100px"}
<img src="图片地址" alt="图片" style="zoom:30%;" alt="图片替换文本" width="200" height="300" align="right"  />

```

![我的图片](https://ss0.bdstatic.com/70cFuHSh_Q1YnxGkpoWK1HF6hhy/it/u=1819216937,2118754409&fm=26&gp=0.jpg)

![猫猫](image/a.jpg)

<img src="http://upload-images.jianshu.io/upload_images/1503319-c696a9cd1495d68f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240"/> 

<center>    <img src="http://upload-images.jianshu.io/upload_images/1503319-c696a9cd1495d68f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/200"  width="140" height="100"> </center>

<img src="http://p1-ks3.532106.com/33f925f1f92649678221088fdfb531a1.jpg" alt="图片替换文本" width="200" height="300" align="middle" />

## 7.超链接

```java
//超链接语法
[百度](https://www.baidu.com/)
```

[百度](https://www.baidu.com/)

## 8.列表

```java
//无序列表
-目录1
-目录2
```

- 目录1
  - 目录2

## 9.表格

| 表头1 | 表头2 | 表头3 |
| ----- | ----- | ----- |
|       |       |       |
|       |       |       |
|       |       |       |

按住ctrl+/可以看出所写源码

## 10.数学公式

### 1.常用符号公式

```java
''反引号中的内容会显示为原来的内容
$ $用来包含行内公式
$$ $$ 独立公式
```

| 名称 | 示意    | 代码      |
| ---- | ------- | --------- |
| 加法 | $x+y=z$ | `$x+y=z$` |
|乘法x|$x \times y $|`$x \times y $`|
|乘法'*'|$x \ast y$|`$x \ast y$`|
|除法|$x \div y$|`$x \div y$`|
|分数|$\frac{x}{y}$|`$\frac{x}{y}$`|
|上标|$x^y$|`$x^y$`|
|下标|$x_y$|`$x_y$`|
|开二次方|$\sqrt x$|`$\sqrt x$`|
|开方|$\sqrt[x][y^4+3y-1]$|`$\sqrt[x][y^4+3y-1]$`|
|加减|$x \pm y$|`$x \pm y$`|
|减加|$x \mp y$|`$x \mp y$`|
|不等于|$\neq$|`$\neq$`|
|小于等于|$\leq$|`$\leq$`|
|大于等于|$\geq$|`$\geq$`|
|对数|$\log_2(x)$|`$\log_2(x)$`|
|极限|$\lim_{x\to3}$|`$\lim_{x\to3}$`|
|极限|$\lim_{x\rightarrow3}$|`$\lim_{x\rightarrow3}$`|
|块公式|$\displaystyle \lim_{x\to\infty}$|`$\displaystyle \lim_{x\to\infty}$`|
|求和|$\sum_x^\infty$|`$ \sum_x^\infty$`|
|求积|$\prod x^2$|`$ \prod x^2$`|
|积分|$\int_0^\infty x^2\times tanx {\rm d}x$|`$\int_0^\infty x^2\times tanx {\rm d}x$`|
|省略号|$\cdots \ddots \vdots$|`$\cdots \ddots \vdots$`|
|矢量|$\vec{a}\cdot \vec{b} =0$|`$\vec{a}\cdot \vec{b} =0$`|
|矩阵|$\left[ \begin{matrix} a & b & c & d & e\\ f & g & h & i & j \\ k & l & m & n & o \\ p & q & r & s & t \end{matrix} \right]$|`\left[ \begin{matrix} a & b & c & d & e\\ f & g & h & i & j \\ k & l & m & n & o \\ p & q & r & s & t \end{matrix} \right]`|
|矩阵|$A= \left\{ \begin{matrix} a & b & \cdots & e\\ f & g & \cdots & j \\ \vdots & \vdots & \ddots & \vdots \\ p & q & \cdots & t \end{matrix} \right\}$|`A= \left\{ \begin{matrix} a & b & \cdots & e\\ f & g & \cdots & j \\ \vdots & \vdots & \ddots & \vdots \\ p & q & \cdots & t \end{matrix} \right\}`|
|矩阵|$A= \left\{ \begin{array}{cccc|c} a & b & c & d & e\\ f & g & h & i & j \\ k & l & m & n & o \\ p & q & r & s & t \end{array} \right\}$|`A= \left\{ \begin{array}{cccc|c} a & b & c & d & e\\ f & g & h & i & j \\ k & l & m & n & o \\ p & q & r & s & t \end{array} \right\}`|
|大括号|$ f(x)=\left\{\begin{aligned}x & = & \cos(t) \\y & = & \sin(t) \\z & = & \frac xy\end{aligned}\right.$|`$ f(x)=\left\{\begin{aligned}x & = & \cos(t) \\y & = & \sin(t) \\z & = & \frac xy\end{aligned}\right.$`|

==实例==

$$\displaystyle \lim_{x\to\infty} x^2[arctan(1+\frac{1}{x})-arctan(1+\frac{1}{x+1})]$$

`$$\displaystyle \lim_{x\to\infty} x^2[arctan(1+\frac{1}{x})-arctan(1+\frac{1}{x+1})]$$`

### 2.其他函数



## 11.希腊字母

| 大写 | 代码 | 小写 | 代码 |
| ---- | ---- | ---- | ---- |
|   $A$   | `$A$` |   $\alpha$   | `$\alpha$` |
|   $B$   | `$B$` |   $\beta$   | `$\beta$` |
|   $\Gamma$   | `$\Gamma$` |   $\gamma$   | `$\gamma$` |
|   $\Delta$   | `$\Delta$` |   $\delta$   | `$\delta$` |
|   $E$   | `$E$` |   $\epsilon$   | `$\epsilon$` |
|||$\varepsilon$   | `$\varepsilon$` |
|   $Z$   | `$Z$` |   $\zeta$   | `$\zeta$` |
|   $H$   | `$H$` |   $\eta$   | `$\eta$` |
|   $\Theta$   | `$Theta$` |   $\theta$   | `$\theta$` |
|   $K$   | `$K$` |   $\kappa$   | `$\kappa$` |
|   $\Lambda$   | `$\Lambda$` |   $\Lambda$   | `$\Lambda$` |
|   $M$   | `$M$` |   $\mu$   | `$\mu$` |
|   $N$   | `$N$` |   $\nu$   | `$\nu$` |
|   $\Xi$   | `$\Xi$` |   $\xi$   | `$\xi$` |
|   $P$   | `$P$` |   $\rho$   | `$\rho$` |
|   $\Sigma$   | `$\Sigma$` |   $\sigma$   | `$\sigma$` |
|   $T$   | `$T$` |   $\tau$   | `$\atu$` |
|   $\Upsilon$   | `$\Upsilon$` |   $\upsilon$   | `$\upsilon$` |
|   $\Phi$   | `$\Phi$` |   $\phi$   | `$\phi$` |
|    |  |   $\varphi$   | `$\varphi$` |
|   $X$   | `$X$` |   $\chi$   | `$\chi$` |
|   $\Psi$   | `$\Psi$` |   $\psi$   | `$\psi$` |
|   $\Omega$   | `$\Omega$` |   $\omega$   | `$\omega$` |

## 12.字体字号颜色

```java
指定字体类型： <font face="黑体">我是黑体字</font>
指定字体大小： <font size=12>我是12号字</font>
指定字体颜色：<font color=#0099ff>我是蓝色字</font> #0099ff 为颜色的16进制代码
指定字体颜色、字号、字体类型<font color=#0099ff size=12 face="黑体">黑体</font>
```

指定字体类型： <font face="黑体">我是黑体字</font>
指定字体大小： <font size=5>我是5号字</font>
指定字体颜色：<font color=#0099ff>我是蓝色字</font>
指定字体颜色、字号、字体类型<font color=#0099ff size=12 face="黑体">黑体</font>

## 13.参考文献

> [Markdown公式编辑学习](https://www.cnblogs.com/q735613050/p/7253073.html)
>
> [Markdown公式二](https://www.cnblogs.com/q735613050/p/7474449.html)