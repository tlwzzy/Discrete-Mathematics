## 数学函数、指数函数、对数函数

### 上、下取整函数

x的下取整，表示小于x的最大整数(floor)

x的上取整，表示大于x的最小整数(ceil)

### 取整函数和绝对值函数

**取整函数** 设x为任意实数，x的取整函数，记作LNT(x)，由删去小数点后的部分将x变为一个整数。

**绝对值** 字数x的绝对值记作ABS(x) 或 |x|，定义为 x 或 -x 中的较大者。

### 余数函数与模算术

设k为任意整数，M为一个正整数，则
$$
k \pmod{M}
$$

（读作k模M）为以M除k的整数余数。即，k(mod M)是唯一的整数r满足：
$$
k = Mq + r , 0 <= r < M
$$

mod术语也用于数学中的同余关系，定义如下：
$$
a \equiv b \pmod{M} 当且仅当 M 整除 b - a
$$

其中M称为模，而 a \equiv b(mod M) 读作“a与b模M同余”。以下的同余形式将常常用到。
$$
0 \equiv M \pmod M, a \pm M \equiv a\pmod{M}
$$

### 指数函数


### 对数函数

对数是与指数相关的函数，设b为正整数，任意正数x的以b为底的对数记作

$$
\log_{b} x
$$

表示可以得到x的b的指数，即：
$$
y = \log_{b} x, b^y = x
$$

**常用对数** 以10为底的对数, \log_{10} x, \log x, \lg x
**自然对数** 以e为底的对数, \log_{e} x, \ln x
**二进制对数** 以2为底的对数, \log_{2} x

#### 指数函数与对数函数的关系

指数函数与对数函数之间是互逆关系：
$$
f(x) = b^x, g(x) = \log_{b} x
$$

他们在图上是关于线性函数 h(x) = x (y = x)对称。所以：

g(c) < h(c) < f(c)
