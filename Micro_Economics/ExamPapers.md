# <center><b>2003年卷</b></center>
一、某垄断企业由两个工厂构成，工厂 ${\mathrm I}$ 的生产函数为 $y_1=x_1^\alpha x_2^{1-\alpha}$，工厂 ${\mathrm {II}}$ 的生产函数为 $y_2 = x_1^\beta x_2^{1-\beta}$，其中 $x_1$ 和 $x_2$ 为两种要素的投入数量， $\alpha$ 与 $\beta$ 为常数。如果要素市场为完全竞争市 场，$r_1$ 和 $r_2$ 为两种要素的价格，则该企业的成本函数如何？

解析：效用最大化、成本最小化问题首先要确定目标函数、约束条件。本题是成本最小化问题，约束条件为保证产量。

工厂 ${\mathrm I}$ 的成本最小化：
$$\min_{x_1,x_2}\quad {r_1x_1+r_2x_2}$$

$$s.t.\quad x_1^\alpha x_2^{1-\alpha}\ge  y_1$$

构造拉氏函数：
$$L(x_1,x_2,\lambda)=r_1x_1+r_2x_2-\lambda(x_1^\alpha x_2^{1-\alpha}-y_1)$$

对函数求变量的偏微分：
$$\frac{\partial \, L}{\partial \,x_1}=r_1-\lambda\alpha x_1^{\alpha -1 }x_2^{1-\alpha} = 0 \tag 1$$
$$\frac{\partial \, L}{\partial \,x_2}=r_2-\lambda(1-\alpha )x_1^{\alpha }x_2^{\neg\,\alpha} = 0 \tag 2$$
$$\frac{\partial \, L}{\partial \,\lambda}=x_1^\alpha x_2^{1-\alpha}-y_1 = 0 \tag 3$$

由 $(1),(2)$ 得：

$$\frac{r_1}{r_2}=\frac{\alpha\,x_2}{(1-\alpha) \,x_1}\tag 4$$
将 $(4)$ 带入 $(3)$ 中得：

$$\begin{cases}
x_1=y_1 \left[\frac{r_2 \, \alpha}{r_1(1-\alpha)}\right]^{1-\alpha} \\[2ex]
x_2=y_2 \left[\frac{r_1(1-\alpha)}{r_2 \, \alpha}\right]^{\alpha}
\end{cases} \tag 5
$$

将 $(5)$ 带入目标函数，得到工厂 ${\mathrm I}$ 的成本：
$$\begin {align}C_1(y_1)&=r_1 x_1+r_2 x_2\\[2ex]
&=r_1y_1 \left[\frac{r_2 \, \alpha}{r_1(1-\alpha)}\right]^{1-\alpha}+r_2y_1 \left[\frac{r_1(1-\alpha)}{r_2 \, \alpha}\right]^{\alpha}\\[2ex]
&= r_1^\alpha r_2^{1-\alpha}\left[{\left(\frac{\alpha}{1-\alpha}\right)}^{1-\alpha} + \left(\frac{1-\alpha}{\alpha}\right)^\alpha \right]y_1
\end{align}$$

令 $A=r_1^\alpha r_2^{1-\alpha}\left[{\left(\frac{\alpha}{1-\alpha}\right)}^{1-\alpha} + \left(\frac{1-\alpha}{\alpha}\right)^\alpha \right]$ ,则 $C_1(y_1)=A y_1$


同理，工厂 ${\mathrm {II}}$ 的成本最小化：
$$\min_{x_1,x_2}\quad {r_1x_1+r_2x_2}$$

$$s.t.\quad x_1^\alpha x_2^{1-\alpha}\ge  y_2$$

解得 $C_2(y_2)=r_1^\beta r_2^{1-\beta}\left[{\left(\frac{\beta}{1-\beta}\right)}^{1-\beta} + \left(\frac{1-\beta}{\beta}\right)^\beta \right]y_2$

令 $B=r_1^\beta r_2^{1-\beta}\left[{\left(\frac{\beta}{1-\beta}\right)}^{1-\beta} + \left(\frac{1-\beta}{\beta}\right)^\beta \right]$ ,则 $C_2(y_2)=B y_2$



则企业成本最小化问题为：

$$\min_{y_1,y_2}\quad{Ay_1+By_2}$$
$$\begin{aligned}s.t.\quad y_1+y_2=y\\
y_i\ge0,\;i=1,2\end{aligned} $$

构造拉氏函数：
$$L(y_1,y_2,\lambda,\mu_{i})=Ay_1+By_2-\lambda(y_1+y_2-y)-\sum_{i=1}^{2}{\mu_i y_i}$$

不等式约束条件下的**库克——塔恩条件**为：



二、已知某企业的生产函数为 $f(x_1,x_2) = [\;min{x1, x2}\;]^{\frac{1}{\alpha}}$，$x_1$ 和 $x_2$ 为两种投入要素的数量，$\alpha > 0$ 为常数。已知产品价格为 $p$ ，要素价格分别为$w_1,w_2$。请求出利润最大化的要素需求函数、供给函 数和利润函数。再讨论利润最大化时必须满足什么样的约束条件。

三、某垄断厂商生产的边际成本 ${\mathrm {MC}} = 5$，该厂商面临的市场需求函数为
$$Q_d = 53 􀀀- P$$

1. 计算该厂商的利润最大化的价格、产量、利润以及垄断所带来的净福利损失。

现假定第二个厂商加入到此市场中。该厂商具有和第一个厂商相同的成本函数。假定两个厂商进行Cournot 竞争。

2. 写出每个厂商最优的反应函数。
3. 找出Cournot 均衡的产量水平。
4. 市场的均衡价格是多少？计算每个厂商的利润。
5. 如果两个厂商进行Bertrand 竞争，那么市场的均衡价格是多少？

a | $A,\alpha$
- | ---------------------------------
b | ${\mathrm A},{\mathrm a}$
c | ${\mathit A},{\mathit a}$
d | ${\mathbb A},{\mathbb a}$
e | ${\mathfrak A},{\mathfrak a}$
f | $A,\alpha$
g | ${\mathscr A},{\mathscr a}$
h | ${\mathcal A},{\mathcal a}$
i | ${\mathbf A},{\mathbf a}$
j | ${\boldsymbol A},{\boldsymbol a}$
k | ${\mathsf A},{\mathsf a}$
l | ${\mathtt A},{\mathtt a}$
