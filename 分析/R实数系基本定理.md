[toc]

## 有理数基本性质


## 戴特金分割

### 无理数的定义
有理数域内的分划的概念是无理数定义的基础．

若将**有理数**全体所成的集合分拆为两个非空集合$A,A'$.我们把这样的分拆叫做分划，只要满足条件：
(1)任何一个有理数，必在且仅在$A，A'$二哥集合之一内出现
(2)集合A的任一数$\alpha$必小于集合$A'$内的任一数$\alpha'$.
集合$Ａ$称为分划的下组，集合$A'$称为上组$A|A'$.

由分划的定义推得，小于下组内的数$\alpha$的一切有理数也这都属于下组，仿照此，大于上组内的数$\alpha'$的一切有理数亦都属于上组．

需要注意的是，第一，这个分划是定义在有理数域的$Q$；第二，要定义分划必须定义序，即大小关系．

[**例题**]
［1］$A=\{x \in Q  | x < 1\},A'=\{x \in Q |x \ge 1\}$
解：
很显然此分化是有理数域的一个分划$A|A'$.数１是属于$A'$组，且显然是其中最小的数．另一方面的是，在Ａ组内并无最大的数，因为不论从我们的Ａ内取怎么的数$\alpha$,当然必然有$\alpha <1$,根据有理数的稠密性，可以知道的必然存在另外的有理数$\alpha_1$且有$\alpha < \alpha_1 < 1$,因此它有属于下组$A$,那么可见$\alpha$不可能是下组中最大的数．

［２］
取小于或等于１的一切有理数$\alpha ,\alpha \le 1$,将这样的数归为下组$A$,取大于１的一切有理数$\alpha',\alpha >1$归入上组$A'$．
解：
毫无疑问的是，这个定义了一个有理数域内的分划，并且上组里面并无最大数，但是下组里面有最大数．


［３］$A=\{x \in Q | x^2 < 2\},A'=\{x \in Q | x^2 >2\}$
$A=\{x \in Q | x^2 < 2\},A'=\{x \in Q | x^2 \ge 2\}$

解：
因为知道$\sqrt{2}$不是有理数，所以上面的两种情况都是有理数域的一个分划，但是这样的分化会造成一个与前面不一样的点，那就是$A$是无最大有理数，$A'$组内是无最小有理数的．
不妨假设$\alpha$是$A$内的最大有理数，当然有$\alpha^2 <2$．

可是当ｎ取合适的正整数的时候有，$\alpha + \frac{1}{n} \in A$.
$$
(\alpha + \frac{1}{n})^2 < 2 \Leftrightarrow \frac{1}{n^2} + \frac{2\alpha}{n} < 2-\alpha^2
$$
因为$n \ge 1$,所以必然有$\frac{1}{n^2} \le \frac{1}{n}$.
从而有$\frac{1}{n^2} + \frac{2\alpha}{n} \le \frac{1}{n} + \frac{2\alpha}{n}$
也就是说如果有$\frac{1}{n} + \frac{2\alpha}{n} < 2-\alpha^2$必然有$(\alpha + \frac{1}{n})^2 < 2$.

要有$\frac{1}{n} + \frac{2\alpha}{n} < 2-\alpha^2$只需要$n > \frac{2\alpha +1}{2-\alpha^2} \in Q$.

很显然这样的正整数是存在的．

因为$\alpha + \frac{1}{n} > \alpha$这意味着$\alpha$不可能是Ａ组中最大的数．
同理可知$A'$中无最小有理数．


[**推论**]
对于有理数域的分划$A|A'$,不可能$A$内有最大有理数的同时$A'$内存在最小的有理数．
proof:

假设$A$内最大数为$\alpha$,　$A'$内最小的数为$\alpha'$.按照分划的性质，知道必然有$\alpha < \alpha'$.按照有理数域的稠密性，可以知道的是，存在$\alpha_0$满足$\alpha < \alpha_0 < \alpha'$.

从$\alpha_0　> \alpha$的情况，可以知道$\alpha_0$不可属于下组$A$.
同时又有$\alpha_0 < \alpha'$,则说明$\alpha_0$也不可能属于上组　$\alpha'$，那就存在矛盾，与$A|A'$是有理数域的分划矛盾．

$\blacksquare$


从前面的例子和分析可以知道的是，有理数域的分划只会产生三种情况．
（１）在下组Ａ内无最大有理数，而在上组$A'$内有最小有理数$r$
（２）在上组无最小有理数，而在下组内有最大有理数$r$
（３）在上组内无最小有理数，而在下组内无最大有理数．

第一和第二种情况，分划有有理数ｒ产生，称为$r$为$A,A'$分划的界数．当然也可以说分划定义了有理数ｒ．

在第三种情况下，分划并不定义任何有理数，让我们约定，第三种情况的有理数域的分划$A|A'$定义了某一个无理数$\alpha$.这个数来替代缺少的界数，我们好像把它插入在$A$组的一切有理数和$A'$组的一切有理数的中间．而对应例３可知$\alpha = \sqrt{2}$,它就是由分划确定出来的无理数．

所以，我们总是把无理数$\alpha$理解为有理数域中确定它的某一个分划$A|A'$.只是这个分划需要具有在上组内无最小有理数，而在下组内无最大有理数的特点．

为了统一起见，对于任意给定的有理数$r$,可以说起对应了分划$A=\{x \in Q |x< r\},A'=\{x \in Q | x \ge r\}$.按照约定，一般将界数放在上组内．


有理数及无理数总称为实数．

### 实数域的序

有了上面有理数于的分划作为基础，实数域内的任意数，不管其是有理数还是无理数，它都对应了有理数域内的一个分划$A|A'$.

有了这个基础，我们就可以利用这个基础来，定义实数域内的序．

不妨定义$\alpha = A|A'$表示一个由有理数域分划$A|A'$确定的实数$\alpha$．

那么记$\alpha = A|A',\beta = B|B'$.
可以定义
$\alpha > \beta \Leftrightarrow A' \subsetneqq B'或 B \subsetneqq A $

$\alpha = \beta \Leftrightarrow A'= B'或 B=A $

$\alpha < \beta \Leftrightarrow B' \subsetneqq A'或 A \subsetneqq B $

其中$\alpha,\beta$为有理数，无理数，上面的定义都是适用的．


但是当无理数$\alpha$和有理数$\beta$比较时候会变得更加的简单．
假设无理数$\alpha$对应有理数域的分划$\alpha =A |A'$.我们可以认为无理数$\alpha$大于下组$\alpha$的一切有理数，也认为$\alpha$小于上组$A'$中的一切有理数．因为$\beta$必然会属于$A$或者$A'$,故其与$\alpha$的大小关系也就是确定的．

### 实数的基本性质
１．有序性
２．序的传递性
３．稠密性
[**引理**]
$\alpha,\beta \in R,\alpha > \beta$则必然存在有理数$r$满足$\alpha < r < \beta$(实际上，这种有理数r有无穷个)．
proof:



$\blacksquare$

### 实数的无限小数表示


### 实数的算术运算


### 实数集的运算性质


### 实数域的分划/实数的完备性
在考察有理数域的分划时，我们已经看到，有时有这样的分划存在，使得在有理数域内并无产生此分划的界数，我们称为有理数域的不完备性，即在有理数之间是有空隙的，所以才需要引入无理数．

如果将有理数域分划的规则引入到实数域来，则会有所变化．

考察**实数域**$R$的分划，即将实数域分拆为两个非空的集合$\bold{A},\bold{A'}$,使得他们能够满足一下两个条件
(1)每一个实数必在且仅在两个集合$\bold{A},\bold{A'}$中的一个．
(2)集合$\bold{A}$中的每一个数$\alpha$都小于集合$\bold{A'}$中的每一个数$\alpha'$.

那么问题来了，在实数域内如此定义的分划$\bold{A}|\bold{A'}$还会出现在实数域内不存在产生这个分划的界数吗，是不是还会像有理数域一样，出现没有界数的分划呢．

事实上，如此定义的分划，爱实数域内无空隙存在．

一定要注意的是，这里引入的分划是定义在实数域内，第二是，前面我们利用有理数域的分划，定义了实数域内数与数之间的序，这个为定义实数域的分划提供了基础，否则无法在实数域内定义分划，因为分划是需要有序作为基础的．

当然如果默认实数域内的有序性，稠密性等性质是实数域内的公里，则实数域的完备性，可从实数域的分划开始研究．

［**戴特金定理－实数的完备性/连续性**］
对于实数域内的任意分划$\bold{A} | \bold{A'}$必然有产生这个分划的实数$\beta$存在(1)要么$\beta$是下组$\bold{A}$内最大的实数，要么(2)　$\beta$是上组$\bold{A'}$内最小的实数．

proof:

将属于$\bold{A}$的有理数记为$A$,将属于$\bold{A'}$的有理数记为$A'$,很显然的是$A|A'$会形成有理数域内的一个分划，我们知道有理数域的任意一个分划定义了一个实数．这个就证明了$\beta$的存在性．

如果$\beta \in \bold{A}$,假设$\beta$不是$\bold{A}$中最大的实数，那么必然存在其他实数$\beta_0 \in \bold{A}$且有$\beta_0 > \beta$.根据实数的稠密性，可知，必然存在有理数$\alpha$满足$\beta < \alpha < \beta_0$.根据$\alpha < \beta_0，\beta_0 \in \bold{A}$可以知道$\alpha \in \bold{A},\alpha \in Q$,那么就有$\alpha \in A$.那么前面我们讲过$\beta = A|A'$,因为$\alpha \in A$,那么必然有$\beta \ge \alpha$.这个就与前面讲的矛盾．所以$\beta \in \bold{A}$确实是$\bold{A}$中最大的实数．


如果$\beta \in \bold{A'}$,假设$\beta$不是$\bold{A'}$中的最小值，那么必然存在$\beta_0 \in \bold{A'}$且有$\beta_0 < \beta$.根据实数的稠密性，可以知道必然存在有理数$\alpha \in Q,\beta_0 < \alpha < \beta$.毫无疑问的是必然有$\alpha >\beta_0 ,\beta_0 \in \bold{A'}$那么$\alpha \in \bold{A'},\alpha \in A'$.我们知道$\beta =A|A'$,　$\beta$就是这个分划确定的界数，那么必然有$\beta \le \alpha$.这个就与前面讲的$\beta > \alpha$矛盾．可见$\beta$确是$\bold{A'}$中的最小数．

$\blacksquare$

［**推论**］
对于实数域的分划$\bold{A}|\bold{A'}$,不可能$\bold{A}$内有最大实数的同时$\bold{A'}$内存在最小的实数．
proof:

实数的分划$\bold{A}|\bold{A'}$.假设$\bold{A}$有最大实数$\alpha_0$，$\bold{A'}$中有最小的实数$\alpha_1$.必然有$\alpha_0 < \alpha_1$.也就是存在有理数$\beta$满足$\alpha_0 < \beta < \alpha_1$.

因为$\alpha_0 < \beta$那么$\beta$肯定不能在下组$\bold{A}$中
$\beta < \alpha_1$那么$\beta$肯定不能在上组$\bold{A'}$中这个就引出了矛盾，存在实数不在这个分划中，与$\bold{A}|\bold{A'}$是分划矛盾．

$\blacksquare$

## 确界原理
当集合是有限集的时候很多问题都是确定简单的．

对于实数域内的任一无限集$\xi$.
例如$\xi =\{x \in R | 0 < x < 1\}$,$\xi =\{x \in R | sinx =\frac{1}{2}\},\xi =\{ x \in R | x \in Q\}$

考察集合$\{x\}$,如果存在$M$,使得$x \le M,\forall x \in \{x\}$,我们就说集合$\{x\}$是上有界的的，$M$就说集合$\{x\}$的上界．

如果存在$m$,使得$x \ge m,\forall x \in \{x\}$则称集合$\{x\}$是下有界的，数$m$称为集合$\{x\}$的下界．


需要注意的是，如果一个数集不上有界，则可以认为广义的数$+\infty$为它的上界．如果一个数集不下有界，则可以认为广义的数$-\infty$为其下界．不过需要注意的是$\infty$不是真是的实数．


若数集上有界，即有有限的上界$M$,则同时可知这种上界必有无数个多（任何大于Ｍ的数，都是集合的上界），在一切上界内，最小的上界，它称为**上确界**，记作$\sup\{x\}$.

如果数集下有界，则一切下有界的最大者，便称为**下确界**,记为$\inf\{x\}$.


对于上无界集，可以认为$\sup\{x\} =+\infty$,这个实际上意味着$\forall M > 0,\exist x' \in \{x\},x > M$

对于下无界集，可以认为$\inf\{x\} =-\infty$,这个实际上意味着$\forall M < 0,\exist x' \in \{x\},x < M$

这里有一个问题就是，上有界的数集是否永远有上确界存在呢？实际上，当数集是有限集的时候，这个问题很好回答，如果集合是无限集合的时候，可能并不能在无限数集中找到最大值，例如$\xi = \{ x \in R |0 <x < 1\}$．

无限集合中有可能并不能找到最大值或者最小值这个特性会引出很多问题．
如果集合既有上界，也有下界，则称集合是有界的．

[**定理**]$E \subset R$有界的充分必要条件是$\exist M >0,|x| \le M,\forall x \in E$.


对于集合$E \subset R$,如果有$\sup E \in E$,则记$\sup E$可记为$\max E$,这时集合的上确界记为Ｅ中的最大数．如果$\inf E \in E$，则$\inf E$可记为$\min E$,这时下确界即为Ｅ的最小数．


[**确界存在定理**]
若集合$E = \{x\}，x \in R$上有界，则它必有上确界；如果集合$E=\{x\}，x \in R$下有界，则它必有下确界．
proof:
如果集合是一个有限集，那么集合里面肯定存在最大值$\max E$，那个最大值$\max E$就是其上确界,即$\sup E=\max E$．

如果集合$\{x\}$是一个无限集合，但是如果集合里面存在最大值$\max E$，那么$\max E$就是其上确界,即$\sup E=\max E$．

如果集合$\{x\}$是一个无限集合，但是集合里面不存在最大值，题设告诉我们其是一个上有界的集合，即存在$M ,x \le M,\forall x \in \{x\}$.

构造集合$\bold{A'}=\{x' \in R | x' > x,\forall x \in \{x\}\}$,很显然集合$\bold{A'}$里面的任何一个元素都是集合$\{x\}$的上界．

（一般来说，对于上界组成的集合应该表述为$\bold{A'}=\{x ' \in R | x' \ge x,\forall x \in \{x\}\}$,但是前面已经假设了集合$\{x\}$是取不到最大值的，那意味着等号是不能成立的，等号成立，意味着集合$\{x\}$里面可以取到最大值．）

记$\bold{A}=R \setminus \bold{A'}$.
很显然，对于任意的$\alpha \in R$,必然属于$\bold{A}$或者$\bold{A'}$.

毫无疑问的是$\{x\}$中的所有元素肯定是属于下组$\bold{A}$.并且有上组$\bold{A'}$中的任何一个数都大于下组$\bold{A}$中的任何一个数．

因为任意$\beta \in \bold{A'}$,必然有$\beta > x,\forall x \in \{x\}$.对于任意的$\alpha \in \bold{A}$要么$\alpha \in \{x\}$,要么$a < x,\forall x \in \{x\}$,不管是那种，都有$\beta > \alpha$.

通过这些，可知$\bold{A}|\bold{A'}$是实数域内的一个划分．

戴特金基本定理告诉我们，实数域内的任意划分，必有产生此分划的实数$\beta$存在．这个数，实际上就是划分的界数，$\forall x ' \in \bold{A},x' \le \beta$.那么$\beta$必然是集合$\{x\}$的一个上界，按照划分具体的定义，即$\{x\}$的上解，划分到上组$\bold{A'}$,可认为$\beta \in \bold{A'}$.戴特金基本定理告诉我们，如果界数$\beta$属于上组$\bold{A'}$，那么必然是上组里面最小的数，这个也就证明了$\beta$是一切上界中最小的数，故其是$\{x\}$的上确界．故有$\beta = \sup E$.

同理可以证明定理的后半段．

$\blacksquare$


确界存在定理，在有理数域内并不能保证存在，并且一定要注意的是，这个上确界，实际上是可以属于集合，也可以不属于集合的．所以这个也反映了实数的连续性和稠密性；

###　确界的性质
１．记$E=\{x\}$是数集$E$的上确界$M$．那么必然有两个性质
(1)$\forall x \in E,x \le M$
(2)$\forall \varepsilon >0,\exist x \in E,M-\varepsilon < x \le M$.
proof:
（１）
第一条性质是必然，因为上确界，也是上界，这个是上界的基本性质．
（２）

不妨用反证法，写出其否命题，那意味着对于某个特定的$\varepsilon_0$,那么$\forall x \in E,x \le M-\varepsilon_0$.

那么意味着$M-\varepsilon_0$也是数集$E$的一个上界，并且有$M -\varepsilon_0 < M$,这个显然与$M$是数集$E$的上确界矛盾．

那么意味着$\forall \varepsilon >0,\exist x \in E,M-\epsilon < x \le M$.

$\blacksquare$

[**推论**]
记$E=\{x\}$是数集$E$的下确界$m$．那么必然有两个性质
(1)$\forall x \in E,x \ge m$
(2)$\forall \varepsilon >0,\exist x \in E,m \le  x < m + \epsilon$.


实际上根据上面的证明，可以给出上下确界的精确描述.
设$E \subset R$为一个非空数集，如果$M \in R$满足
（１）M是Ｅ的一个上界，即$\forall x \in E,x \le M$;
(2)对于$\varepsilon >0$,存在$x' \in E$,使得$x' > M-\varepsilon$．
则称$M$为Ｅ的上确界，即$M=\sup E$


设$E \subset R$为一个非空数集，如果$m \in R$满足
（１）m是Ｅ的一个下界，即$\forall x \in E,x \ge m$;
(2)对于$\varepsilon >0$,存在$x' \in E$,使得$x' < m+\varepsilon$．
则称$m$为Ｅ的下确界，即$m=\inf E$

２．对于数集$E=\{x\}$,如果有$\forall x < M$,那么必然有$\sup\{x\} \le M$;同理,如果有$\forall x > m$,那么必然有$\inf\{x\} \ge m$.
proof:
(1)不妨假设$\sup\{x\} > M$.取$\varepsilon = \sup\{x\} - M >0 $,那么利用确界的性质，知道$\exist x \in E,x > \sup\{x\} - \varepsilon = M$.这个显然是矛盾的，故有$\sup\{x\} \le M$.

例如集合$\Chi =\{x \in R | 0 < x < 1\}$的上确界为１，但是显然有$\forall x \in \Chi,x < 1$.

(2)仿照（１）进行证明即可．

$\blacksquare$

## 单调有界数列一定有极限
若序列$\{x_n\}$满足$x_n \le x_{n+1},\forall n \in \N$则称$\{x_n\}$是单调递增的序列．
若序列$\{x_n\}$满足$x_n \ge x_{n+1},\forall n \in \N$则称$\{x_n\}$是单调递减的序列．

若将序列看成定义在$\N$上的函数$f(x)$，则序列的单调性即使函数$f(x)$的单调性．

[**单调收敛原理**]单调有界序列必然收敛．
proof:
只证明单调上升的情形．

设$\{x_n\}$单调上升，而且有上界，即
$$
x_1 \le x_2 \le ...\le x_n \le x_{n+1} \le ...\\
x_n  \le M ,\forall n \in \N
$$
其中Ｍ是一个正数，M是其上界．

现考虑集合$E=\{x_n :n \in \N \}$,则Ｅ是一个非空有上界的集合，故有确界定理，Ｅ必有上确界，令$a =\sup\{x_n\}$.由上确界的定义,$a$满足:
(1)$x_n \le a,\forall n \in \N$
(2)$\forall \varepsilon >0 ,\exist x_{N},使得 a -\varepsilon < x_{N}$.
这样，$\varepsilon >0$,当$n > N$,有
$a -\varepsilon < x_{N} \le x_n \le a$

因此有$|x_n -a| < \varepsilon$
这就证明了$\lim\limits_{n \to \infty}x_n =a =\sup\{x_n\}$.

$\blacksquare$


容易证明：若$\{x_n\}$单调上升无上界，则$\lim\limits_{n \to \infty}x_n = +\infty$;
若$\{x_n\}$单调下降无下界，则$\lim\limits_{n \to \infty}x_n = -\infty$.

我们知单调序列总是广义收敛．并且有
(1)若$\{x_n\}$单调上升，则$\lim\limits_{n \to \infty}x_n = \sup\{x_n\}$
(2)若$\{x_n\}$单调下降，则$\lim\limits_{n \to \infty}x_n = \inf\{x_n\}$

[**推论**]对一个单调递增序列$\{x_n\}$,若记$A=\lim\limits_{n \to \infty}x_n$,存在$N >0$,使得$\forall n > N,x_n=x_{N}=A$.或者$x_n < A,\forall n > 0$.
proof:

假设存在$x_{N'} > A$,那么利用序列的单调递增性质，知道当$n > N'$时有$x_n \ge x_{N'} > A$.

利用极限的保序性，知道$\lim\limits_{n \to \infty}x_{n} \ge x_{N'} > A$.
这个就与题设矛盾．

所以我们知道$\forall n \in \N, x_n \le A$.

如果存在$x_N = A$,因为序列的单调递增性质，我们知道$n > N,x_n \ge x_{N}=A$,前面又证明了$x_n \le A$, 所以当$n > N$时必然有$x_n =A$.


如果不存在$x_N =A$,根据$\forall n \in \N,x_n \le A$,可以知道$\forall n \in \N,x_n < A$.


$\blacksquare$


## 闭区间套定理
[**闭区间套定理**]
设$\{[a_n,b_n]\}$是一系列的闭区间套，并且满足(1)$[a_n,b_n]\supset [a_{n+1},b_{n+1}],n=1,2,...$(2)$\lim\limits_{n \to \infty}(b_n -a_n)=0$
则存在唯一的点$\xi \in R$,使得$c \in [a_n,b_n],n=1,2,...$即$\{\xi\}=\cap_{n=1}^{\infty}[a_n,b_n]$

proof:
根据$[a_{n+1},b_{n+1}] \subset [a_n,b_n]$那么必然有
$a_n \le a_{n+1} \le b_{n+1} \le b_{n}$.
那么可见$\{a_n\}$是一个单调递增序列．而$\{b_n\}$是一个单调递减的序列．
又因为$\forall n \in \N ,a_{n+1} \le b_{n+1} \le b_{n} \le ...\le b_1$.可见序列$\{a_n\}$是一个有上界的序列，同理可知$\{b_n\}$是一个下有界的序列$b_n \ge a_1,\forall n \in \N$．

利用单调有界序列收敛的法则知道$\lim\limits_{n \to \infty}a_n,\lim\limits_{n \to \infty}b_n$都是存在的．

根据$\lim\limits_{n \to \infty}(a_n-b_n)=0$可知必然有$\lim\limits_{n \to \infty}a_n =\lim\limits_{n \to \infty}b_n = \xi$.


根据单调序列的收敛性质，我们知道$a_n \le \xi \le b_n,\forall n \in \N$.

假设还存在另外的一个点$\xi' \in [a_n,b_n],\forall n \in \N$.不妨假设$\xi' \ne \xi$.

那很显然有$b_n -a_n \ge |\xi - \xi'|>0$
那么必然有$\lim\limits_{n \to \infty}(a_n -b_n) \ge |\xi -\xi'| >0$矛盾．
从而有
可知确实存在一个点$\xi$满足题设要求．

$\blacksquare$
闭区间的条件是重要的，若开区间是开的，则定理的结论不一定成立．

不妨考察$(0,\frac{1}{n}),n=1,2,...$显然满足区间套定理的两个条件，但是区间不是闭的．很显然有$0 \le 0 < \frac{1}{n}$
可是$0 \notin (0,\frac{1}{n}),\forall n \in \N.$可见$\cap_{n=1}^{\infty}(0,\frac{1}{n})=\emptyset$.


对于开区间序列$\{(a_n,b_n)\}$如果满足(1)$a_n < a_{n+1} < b_{n+1} < b_n ,n=1,2...$(2)$\lim\limits_{n \to \infty}(b_n -a_n)=0$,那么依然存在唯一$\xi \in \cap_{n=1}^{\infty}(a_n,b_n)$．


如果闭区间套定理的（２）不满足，即$\lim\limits_{n \to \infty}(a_n-b_n) \ne 0$,则此时$\cap_{n=1}^{\infty}[a_n,b_n]=[a,b],这里\lim\limits_{n \to \infty}a_n= a,\lim\limits_{n \to \infty}b_n=b$.

## 有限覆盖定理
设$A$是$R$中的子集$\{E_\lambda\}_{\lambda \in \Lambda}$是$R$中的一族子集组成的集合，其中$\Lambda$是一个指标集．若$A \subset \cup_{\lambda \in \Lambda}E_\lambda$,则称$\{E_{\lambda}\}_{\lambda \in \Lambda}$是$A$的一个覆盖．

如果$\forall \lambda \in \Lambda,E_{\lambda}$都是开区间，则称$\{E_{\lambda}\}_{\lambda \in \Lambda}$是$A$的一个开覆盖．

如果$\{E_{\lambda}\}_{\lambda \in \Lambda}$是$A$的一个覆盖，而且$\Lambda$里面的元素只有有限个，则称$\{E_{\lambda}\}_{\lambda \in \Lambda}$是$A的一个有限覆盖．



［**有限覆盖定理**］设$[a,b]$是一个闭区间，$\{E_{\lambda}\}_{\lambda \in \Lambda}$是$[a,b]$的任意（$\Lambda$是无限或有限集）一个开覆盖，则必然存在$\{E_{\lambda}\}_{\lambda \in \Lambda}$一个子集构成$[a,b]$的一个有限覆盖，即在$\{E_{\lambda}\}_{\lambda \in \Lambda}$中必有有限个开区间$E_1,E_2,...,E_N$使得$[a,b] \subset \cup_{j=1}^{N}E_j$
proof:
如果不对，我们将$[a,b]$ 等分为两个闭区间,则其中必有一个不能被$\{E_{\lambda}\}_{\lambda \in \Lambda}$中的有限多个开区间所覆盖．记其为$[a_1,b_1]$;再将$[a_1,b_1]$等分称两个闭区间，则必有其中一个不能被$\{E_{\lambda}\}_{\lambda \in \Lambda}$中的有限多个开区间所覆盖，即其为$[a_2,b_2]$,如此进行下去，就可以得到一列$[a_n,b_n]$满足
(1)$[a_{n+1} ,b_{n+1}] \subset [a_n,b_n]$
(2)$b_n - a_n =\frac{b-a}{2^n} \to 0$
(3)$\forall n,[a_n,b_n]$不能被$\{E_{\lambda}\}_{\lambda \in \Lambda}$中的有限多个开区间所覆盖．

由闭区间套定理，存在$\xi \in [a_n,b_n],\forall n \in \N$.由于$\xi \in [a,b]$而$\{E_{\lambda}\}_{\lambda \in \Lambda}$是$[a,b]$的开覆盖，必然存在某一个开区间$E_{\lambda_0}=(c,d)$,满足$\xi \in E_{\lambda_0}$.由于$E_{\lambda_0}$是一个开区间,我们知道$a_n \le \xi \le b_n ,\forall n \in \N$.又因为$c < \xi < d$那么必然当Ｎ充分大的时候$[a_n,b_n] \subset E_{\lambda_0}$.
这个是因为$\lim\limits_{n \to \infty}a_n =\xi =\lim\limits_{n \to \infty}b_n$,而$c < \xi < d$，那么利用极限的保序性，必然有$\exist N_1,n > N_1,c < a_n \le \xi$.另外必然$\exist N_2,n > N_2,\xi \le b_n < d$,所以只需要$n  > \max\{N_1,N_2\}$则有$[a_n,b_n] \subset (c,d)$.

这个就与上面讲的条件３死是矛盾的，那么定理是成立的．

$\blacksquare$

（１）不能将闭区间改为开区间$(\frac{1}{n},\frac{2}{n}),n=1,2,...$是$(0,1)$的一个开覆盖，但是没有有限覆盖．
解：$\alpha \in (0,1),\frac{1}{n} < \alpha < \frac{2}{n}$这个只需要$\frac{1}{\alpha} < n < \frac{2}{\alpha}$.
而$\frac{2}{\alpha}-\frac{1}{\alpha}=\frac{1}{\alpha} >1$,开见在区间$(\frac{1}{\alpha} ,\frac{2}{\alpha})$里面必然存在正整数．所以可以被一个区间覆盖．

（２）
特别注意的是，对于闭区间的任意一个开覆盖必然可以从中找出有限多个开区间就可以将该闭区间覆盖，而并不是说，任意一个闭区间都可被有限多个开区间覆盖．若是这样，$(a-1,b+1)$总是$[a,b]$的一个有限开覆盖．


在今后的应用中，常可根据函数的局部性质得到一些开区间，然后通过有限覆盖定理而得到函数的在区间的整体性质．

［**例题**］
设函数$f(x)$在$[a,b]$上有定义，且对任意的$x \in [a,b]$,都存在邻域$U(x,\delta(x)),\delta(x) >0$,使得$f(x)$在$U(x,\delta(x)) \cap [a,b]$上有界,则$f(x)$在$[a,b]$上有界.
proof:

$\forall x \in [a,b]$,有题设存在$U(x,\delta(x))$使得$f(x)$在$U(x,\delta(x)) \cap [a,b]$上有界,记其界为$M_x >0$,即
$|f(t)| \le M_x,\forall t \in U(x,\delta(x)) \cap [a,b]$
令
$F = \{U(x,\delta(x)) = (x-\delta(x),x+ \delta(x)) : x \in [a,b]\}$

显然$F$是区间$[a,b]$的一个开覆盖,有闭区间的的有限覆盖定理,可以知道,存在$F$的有限个开区间$U(x_1,\delta(x_1)),U(x_2,\delta(x_2)),U(x_3,\delta(x_3))...,U(x_N,\delta(x_N))$
使得$[a,b] \subset \cup_{k=1}^{N}U(x_i,\delta(x_i))$

如果令$M=\max\{M_{x_1},M_{x_2},...,M_{x_N}\}$

对对于任意的$x \in [a,b]$必然有$\exist x_k,x \in U(x_k,\delta(x_k))$从而$|f(x)| \le M_{x_k} \le M$.
这个表明$f(x)$在$[a,b]$上有界.

$\blacksquare$


[**推论**]如果$f(x)$在$[a,b]$上无界,则存在$\xi  \in [a,b]$使得$\forall \delta >0$,$f(x)$在$U(\xi,\delta) \cap [a,b]$上均无界.

这里的a,b的数值是有限值.



[例题]无论用什么方法都不可能将[0,1]区间上的全体实数排列成一个序列.
proof:

不妨假设$[0,1]=\{x_1,x_2,....,x_n,...\},x_n \in [0,1]$
取$0 < \varepsilon < 1/4$.
那么很显然$F=\{U(x_n,\frac{\varepsilon}{2^n}):n \in \N \}$
是区间$[0,1]$的一个开覆盖,有有限覆盖定理,可以知道$F$中存在有限个开区间$U(x_{n1},\frac{\varepsilon}{2^{n1}}),U(x_{n2},\frac{\varepsilon}{2^{n2}}),...,U(x_{nl},\frac{\varepsilon}{2^{nl}})$它们可将$$[0,1]$区间覆盖,既然它们覆盖了$[0,1]$前,那么这l个区间的长度和必然大于1.令$m=\max\{n1,n2,...,nl\}$
那么$2\sum_{k=1}^{l}\frac{\varepsilon}{2^{nk}} < 2\varepsilon \sum_{k=1}^{m}\frac{\varepsilon}{2^{k}} =2\varepsilon\frac{1-1/2^{m+1}}{1-1/2} < 4\varepsilon <1$
故矛盾.
可见[0,1]里面的实数无法排成一个序列.


$\blacksquare$
若一个数集E中只有有限个元素或可以将他的所有元素排成一个序列,则称其为一个可数集.

## 聚点原理

[**定义**]设E是R中的一个子集,若$x_0 \in R(x_0不一定属于E)$满足$\delta >0,\hat{U}(x_0,\delta) \cap E \ne \emptyset$,则称$x_0$是E的一个聚点.

需要注意的是$x_0$是E的聚点与$x_0$是否属于E无关.

[**定理**]
有聚点的定义可知,下面三个命题是等价的:
a.$x_0$是E的聚点
b.$\forall \delta >0$,在$U(x_0,\delta)$有$E$的无穷多个点
c.存在E中互异的点组成的序列$\{x_n\}$,使得$\lim\limits_{n \to \infty}x_n = x_0$

[**定义**]
如果$x_0 \in E$,但是它不是E的聚点,则称$x_0$是E的一个孤立点.
有定义可以知道,x_0是孤立点,意味着存在$\delta >0$,满足$U(x_0,\delta) \cap E=\{x_0\}$.

[例题]
1.设$E=\{1,1/2,1/3,1/4,...,1/n,...\}$很显然0是其唯一的聚点,而且$0 \notin E$,而任意的$\frac{1}{n} \in E$都是E的孤立点.

2.设$E$是$[0,1]$中所有有理数组成的集合,则E的聚点是全体的$[0,1]$,而E中没有孤立点.注意,此时E是它的聚点集$[0,1]$的真子集.

很显然一个有限点集里面的点都是孤立点.

[**聚点原理**]R中的任何一个有界无穷子集E至少有一个聚点.
proof:
设E是R的一个有界无穷子集,必然有$E\subset [a,b]$.
这里需要注意的是,聚点是分布在整个R上的,不需要限定在E内.

利用反证法,不妨假设E一个聚点也没有,那当然在闭区间$[a,b]$上也没有E的聚点.

利用不是聚点的定义,可以知道$\forall x \in [a,b],\exist \delta_x,st. \quad U(x,\delta_x) \cap E$最多只有一个点x本身.
显然$F=\{U(x,\delta_x):x \in [a,b]\}$必然是[a,b]的一个无限开覆盖,利用有限覆盖定理,我们知道,必然从中间挑选处,有限个开覆盖$U(x_1,\delta_{x_1}),U(x_2,\delta_{x_2}),...,U(x_N,\delta_{x_N})$
使得$[a,b] \subset \cup_{j=1}^{N}U(x_j,\delta_{x_j})$.

需要注意的是$E \subset [a,b]$,而每个$U(x_j,\delta_{x_j})$至多只有E的一个点,我们变可以推断处E中至多只有N个点,这个很显然与E是R的无穷子集矛盾.所以E必然是有聚点的.

$\blacksquare$


proof:
$E \subset [a,b]$, 那么$[a,b]$分拆为两个闭子区间,必然有一个子区间内有E的无穷多项,设其为$[a_1,b_1]$,将$[a_1,b_1]$分成两个闭子区间,必然在其一个闭子区间里面必然有E的无穷多项,记其为$[a_2,b_2]$.继续下去,可知
1.$[a_{n+1},b_{n+1}] \subset [a_n,b_n]$
2.$|a_{n}-b_{n}| = \frac{b-a}{2^n} \to 0$ 
3.$[a_n,b_n]$里面都含有$E$的无穷多项.

利用闭区间套定理,可以知道存在$\xi \in [a,b]$,有$\lim\limits_{n \to \infty}a_n = \lim\limits_{n \to \infty}b_n =\xi$.


利用极限的定义可以知道,不论$\varepsilon >0$,必然存在$N,n > N,a_n \in U(\xi,\varepsilon),b_n \in U(\xi,\varepsilon)$
因为$[a_n,b_n]$中有$E$的无穷多项,那么必然有$U(\xi ,\varepsilon)\cap E \ne \emptyset$.可知$\xi$就是E的聚点.

$\blacksquare$

## Bolzano-Weierstrass定理
任何有界无穷序列必有收敛的子列

proof:
不妨设$E=\{x_n\}$,E是R上的一个有界无穷子集,有聚点原理可以知道,其至少有一个聚点$a$.根据聚点的定义,我们知道不管$\delta$取多少,$U(a,\delta) \cap E \ne \emptyset$.
不妨考虑$U(a,\frac{1}{n})$,很显然这个开集里面有E无穷多项.
取$x_{n1} \in U(a,1)\cap \{x_1,x_2,...,x_n,...\}$
$x_{n2} \in U(a,1/2)\cap \{x_{n1+1},x_{n1 +2},......\}$

如此类推,可以构造一个子列$\{x_{nk}\}$,并且满足$|x_{nk} - a | \le \frac{1}{k},k=1,2,...$
从而有$\lim\limits_{k \to \infty}x_{nk}=a$.

$\blacksquare$


proof:
假设数列$\{x_n\}$是有界列,必然有$\{x_n\} \subset [a,b]$.

那么$[a,b]$分拆为两个闭子区间,必然有一个子区间内有数列$\{x_n\}$的无穷多项,那么从$[a_1,b_1]$中挑选$x_{n1}$,设其为$[a_1,b_1]$,将$[a_1,b_1]$分成两个闭子区间,必然在其一个闭子区间里面必然有数列$\{x_n\}$的无穷多项,记其为$[a_2,b_2]$,那么从$[a_2,b_2]$中挑选$x_{n2}$继续下去,可知
1.$[a_{k+1},b_{k+1}] \subset [a_k,b_k]$
2.$|a_{k}-b_{k}| = \frac{b-a}{2^k} \to 0$ 
3.$[a_k,b_k]$里面都含有数列$\{x_n\}$的无穷多项,并且从$[a_k,b_k]$中挑选$x_{nk}$.
那么便可以组成一个子列$\{x_{nk}\}$.
因为是无穷项,可做到$\{nk\}$是严格单调递增列.
根据闭区间套定理,知道$\xi \in [a,b],\lim\limits_{n \to \infty}a_n = \xi = \lim\limits_{n \to \infty}b_n $

$\forall k \in \N,a_k \le \xi \le b_k$

根据子列的构造可以知道$a_k \le x_{nk} \le b_k$.
那当然有$|x_{nk} -\xi| \le |b_k-a_k| \to 0$

从而有$\lim\limits_{k \to \infty}x_{nk} = \xi$
从而可知,有界无穷列,必然存在收敛的子列.

$\blacksquare$


## Cauchy收敛原理




$R$上的,海涅博雷尔定理的证明是在给定的有界闭区间上证明的.
有界闭区间和有界闭区间还是有区别的,当时有界闭区间当然是有界闭集.

[**列紧集合**]
如果A中的任何序列都存在收敛于A中元素的收敛子列,则称A为列紧集合.

[**推论**]
$E \subset R$,E是列紧集合的充分必要条件是E是一个有界闭集.
proof:




$\blacksquare$



[**紧致集合**]
如果A的任何开覆盖都存在有限子覆盖,则称A为紧致集合.




[**推论**]
$E \subset R$,E是紧致集合的充分必要条件是E是一个有界闭集.







