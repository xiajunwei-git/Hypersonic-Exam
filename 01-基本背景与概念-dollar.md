# 高超声速流动基础理论

屈崑、李文丰

2022年秋

w.li@nwpu.edu.cn

微信: ichbinwenfeng

## 先修课程

- 计算方法, 计算流体力学基础

- 空气动力学

- 可压缩气体动力学

- 粘性流体力学

- 化学

- 物理

- 实验流体力学

基本内容

## 高超声速理论

- 马赫数无关性、高超声速相似率、高超声速小扰动理论

- 无粘流动的气动力工程快速算法

- 可压缩流动边界层理论

- 摩阻与表面热流的工程快速算法

- 化学反应流动简介与计算方法

- 热非平衡流动简介与计算方法

参考书目

Hypersonic and High TEMPERATURE GAS DYNAMICS Second Edition

John D. Anderson Jr.

![bo_d4puqmbef24c73bcjmlg_4_585_725_956_1025_0.jpg](bo_d4puqmbef24c73bcjmlg_4_585_725_956_1025_0.jpg)

## 基本背景

1. 什么是高超声速流动? 定义?

2. 高超声速飞行的重要性？

3. 同样Ma>1为什么和超声速流动区别开来?

4. 超声速飞行器VS高超声速飞行器

## 基本背景

空气动力学、气体动力学和复杂流动机理是空天飞机、航空及火箭发动机等大型装备的关键理论基础

![bo_d4puqmbef24c73bcjmlg_6_708_564_881_621_0.jpg](bo_d4puqmbef24c73bcjmlg_6_708_564_881_621_0.jpg)

1. 极端环境下, 飞行器气动力、气动热, 快速精确预测难 2. 气动力、热载荷引起结构的非线性动力学行为, 系统和响应分析难 3. 气动与结构相互作用及流动机制复杂

## 基本背景

![bo_d4puqmbef24c73bcjmlg_7_165_327_2069_1380_0.jpg](bo_d4puqmbef24c73bcjmlg_7_165_327_2069_1380_0.jpg)

## 基本背景

## 历史典故

Minimizing of aerodynamic heating of ICBMs

(洲际弹道导弹气动热降低问题)

> ICBMs reentry the atmosphere at the speeds of from 6 to 6.7km/s.(Ma>17)

> The aerodynamic heating of the reentry vehicles becomes severe, the cover of the war head will be heated up to 10,000K.

Dulut reentry body design can minimize the aerodynamic heating problem.

基本背景 Aerodynamic heating of the reentry vehicle

![bo_d4puqmbef24c73bcjmlg_9_237_406_1558_1284_0.jpg](bo_d4puqmbef24c73bcjmlg_9_237_406_1558_1284_0.jpg)

基本背景

![bo_d4puqmbef24c73bcjmlg_10_15_357_2075_948_0.jpg](bo_d4puqmbef24c73bcjmlg_10_15_357_2075_948_0.jpg)

尖头体和钝头体的气动加热情况比较

## 高超声速流动特点

- Thin Shock Layers (激波层变薄、湍流相互作用)

- Entropy Layer(等熵假设失效)

- Viscous Interaction

- High-Temperature Flows

- Low-Density Flow (高空、分子自由程)

## Thin Shock Layers

- 马赫数增加，激波角度变小，越来越接近壁面，导致激波层变薄

- 激波层可能与边界层发生相互作用

- 薄激波层为近似计算提供了理论基础

![bo_d4puqmbef24c73bcjmlg_12_651_1077_1279_462_0.jpg](bo_d4puqmbef24c73bcjmlg_12_651_1077_1279_462_0.jpg)

Fig. 1.13 Thin hypersonic shock layer.

## Entropy Layer

- 弓形激波区，出现强烈的熵增，导致等熵假设失效

- 导致边界层外边界条件变得复杂

![bo_d4puqmbef24c73bcjmlg_13_587_843_1142_758_0.jpg](bo_d4puqmbef24c73bcjmlg_13_587_843_1142_758_0.jpg)

Fig. 1.14 Entropy layer.

## -Viscous Interaction

- 高马赫数下，边界层温度很高，密度变小，导致边界层更厚

- 变厚的粘性边界层明显改变了壁面的“形状”, 影响了压力分布

![bo_d4puqmbef24c73bcjmlg_14_22_1020_2248_727_0.jpg](bo_d4puqmbef24c73bcjmlg_14_22_1020_2248_727_0.jpg)

## . Viscous Interaction

- 当多种机制相互不干扰或者干扰较弱可忽略时，在分析时可以分开独立处理，实施起来更为简单；

- 当多种机制发生干扰时，必须在分析中考虑多种机制的耦合，在数学上更为复杂困难;

- 在 60 ~ 70 年代，计算机性能不足，依赖解析或者半解析分析， 干扰与耦合问题的处理尤其困难

- 当谈到 “等······假设”，必然是引入了简化条件，如不可压缩流动的“等密度假设”、“等温假设”、“无旋假设”，可压缩流动“等熵假设”，都使得方程大为简化

○ 反之则使得分析变得复杂困难

- 在高性能计算发展起来后，依靠大规模数值求解，解决这些困难的问题就变得简单粗暴许多了。

## -High-Temperature Flows

![bo_d4puqmbef24c73bcjmlg_16_1388_435_910_1118_0.jpg](bo_d4puqmbef24c73bcjmlg_16_1388_435_910_1118_0.jpg)

Fig. 1.17 High-temperature shock layer.

- 高温导致振动能与电子能被激发, 气体不再是理想气体

- 高温导致化学反应, 气体组分变化

。气体热力学性质变化, 导致气动力和传热都与理想气体不同

- 高温气体的传热, 辐射变得非常重要

## High-Temperature Flows

- 常温下的分子碰撞中，能量交换水平较低，仅有平动动能和转动动能参与能量交换。

> 化学键因为刚性足够大, 振动能不受碰撞影响, 不参与能量交换

> 电子也不会被激发导致能级跃迁，因此也不参与能量交换

- 在温度足够高时, 碰撞导致的能量交换水平足够高, 振动和电子能级会受到影响, 参与能量交换

○电子在高温时也会因为分子碰撞，脱离原子形成自由电子，具有宏观运动动能

## -High-Temperature Flows

![bo_d4puqmbef24c73bcjmlg_18_494_465_1141_1187_0.jpg](bo_d4puqmbef24c73bcjmlg_18_494_465_1141_1187_0.jpg)

## .Low-Density Flow

- 低密度下，NS方程不再有效，需要采用 Boltzmann方程

- 低密度气体的计算，常采用DSMC，或者求解 Boltzmann方程

![bo_d4puqmbef24c73bcjmlg_19_363_913_1449_775_0.jpg](bo_d4puqmbef24c73bcjmlg_19_363_913_1449_775_0.jpg)

![bo_d4puqmbef24c73bcjmlg_20_390_92_1433_1605_0.jpg](bo_d4puqmbef24c73bcjmlg_20_390_92_1433_1605_0.jpg)

## 再入飞行路线

- 考虑气动力与重力对再入飞行器的动量影响

$$
- \frac{1}{g}\frac{\mathrm{d}V}{\mathrm{\;d}t} = {\left( \frac{W}{{C}_{D}S}\right) }^{-1}\frac{\rho {V}^{2}}{2}
$$

- 升力主导，升力体

- 阻力主导，弹头形状、胶囊形状

$$
1 - \frac{1}{g}\frac{{V}^{2}}{R} = {\left( \frac{W}{{C}_{L}S}\right) }^{-1}\frac{\rho {V}^{2}}{2}
$$

![bo_d4puqmbef24c73bcjmlg_21_99_931_1010_801_0.jpg](bo_d4puqmbef24c73bcjmlg_21_99_931_1010_801_0.jpg)

![bo_d4puqmbef24c73bcjmlg_21_1194_1022_1020_676_0.jpg](bo_d4puqmbef24c73bcjmlg_21_1194_1022_1020_676_0.jpg)

![bo_d4puqmbef24c73bcjmlg_22_220_287_1904_1231_0.jpg](bo_d4puqmbef24c73bcjmlg_22_220_287_1904_1231_0.jpg)

![bo_d4puqmbef24c73bcjmlg_23_321_36_1782_1651_0.jpg](bo_d4puqmbef24c73bcjmlg_23_321_36_1782_1651_0.jpg)

# 2斜激波关系式

Oblique Shock Wave Relations/斜激波关系式

![bo_d4puqmbef24c73bcjmlg_25_276_343_1587_1081_0.jpg](bo_d4puqmbef24c73bcjmlg_25_276_343_1587_1081_0.jpg)

回顾空气动力学基础

## Oblique Shock Wave Relations/斜激波关系式

![bo_d4puqmbef24c73bcjmlg_27_16_262_2314_1471_0.jpg](bo_d4puqmbef24c73bcjmlg_27_16_262_2314_1471_0.jpg)

![bo_d4puqmbef24c73bcjmlg_28_1228_88_1090_1418_0.jpg](bo_d4puqmbef24c73bcjmlg_28_1228_88_1090_1418_0.jpg)

## > 连续方程

下图虚线包围区域为控制体， 应用连续方程:

$$
{\oint }_{S}\rho \overrightarrow{V} \bullet  \overrightarrow{dS} = 0
$$

$$
- {\rho }_{1}{u}_{1}{A}_{1} + {\rho }_{2}{u}_{2}{A}_{2} = 0
$$

${u}_{1}$ : 波前法向速度

${u}_{2} :$ 波前法向速度 $\;{A}_{2} = d$

$$
{\rho }_{1}{u}_{1} = {\rho }_{2}{u}_{2}
$$

(9.2)

## > 动量方程 (切向)

积分形式动量方程的切向分量:

$$
{\iint }_{S}\left( {\rho \overrightarrow{V} \bullet  \overrightarrow{dS}}\right) w =  - {\iint }_{S}{\left( p\overrightarrow{dS}\right) }_{\text{ tangential }} \tag{9.3}
$$

$$
- \left( {{\rho }_{1}{u}_{1}{A}_{1}}\right) {w}_{1} + \left( {{\rho }_{2}{u}_{2}{A}_{2}}\right) {w}_{2} = 0
$$

(9.4)

$$
{w}_{1} = {w}_{2}
$$

(9.5)

![bo_d4puqmbef24c73bcjmlg_29_1226_545_1079_494_0.jpg](bo_d4puqmbef24c73bcjmlg_29_1226_545_1079_494_0.jpg)

The tangential component of the flow velocity is constant across an oblique shock.

通过斜激波流动的切向速度分量保持不变。

## > 动量方程(法向)

![bo_d4puqmbef24c73bcjmlg_30_1220_316_1078_477_0.jpg](bo_d4puqmbef24c73bcjmlg_30_1220_316_1078_477_0.jpg)

积分形式动量方程的法向分量:

$$
{\iint }_{s}\left( {\rho \overrightarrow{V} \bullet  \overrightarrow{dS}}\right) u =  - {\iint }_{s}{\left( pd\overrightarrow{S}\right) }_{\text{ normal }} \tag{9.6}
$$

$$
- \left( {{\rho }_{1}{u}_{1}{A}_{1}}\right) {u}_{1} + \left( {{\rho }_{2}{u}_{2}{A}_{2}}\right) {u}_{2} =  - \left( {-{p}_{1}{A}_{1} + {p}_{2}{A}_{2}}\right)
$$

$$
{p}_{1} + {\rho }_{1}{u}_{1}^{2} = {p}_{2} + {\rho }_{2}{u}_{2}^{2}
$$

(9.7)

(9.7) 式中只出现激波的法向分量。

> 能量方程

$$
{\iint }_{s}\rho \left( {e + \frac{{V}^{2}}{2}}\right) \overrightarrow{V} \bullet  \overrightarrow{dS} =  - {\oiint }_{s}p\overrightarrow{V} \bullet  \overrightarrow{dS}
$$

(9.8)

$$
- {\rho }_{1}\left( {{e}_{1} + \frac{{V}_{1}^{2}}{2}}\right) {u}_{1}{A}_{1} + {\rho }_{2}\left( {{e}_{2} + \frac{{V}_{2}^{2}}{2}}\right) {u}_{2}{A}_{2} =  - \left( {-{p}_{1}{u}_{1}{A}_{1} + {p}_{2}{u}_{2}{A}_{2}}\right)
$$

(9.9)

$$
- {\rho }_{1}{u}_{1}\left( {{e}_{1} + \frac{{p}_{1}}{{\rho }_{1}} + \frac{{V}_{1}^{2}}{2}}\right)  + {\rho }_{2}{u}_{2}\left( {{e}_{2} + \frac{{p}_{2}}{{\rho }_{2}} + \frac{{V}_{2}^{2}}{2}}\right)  = 0
$$

${u}_{1},{M}_{n,1}$

${u}_{2},{M}_{n,2}$

${w}_{1},{M}_{t,1}$

${W}_{2},{M}_{t,2} \; {V}_{2},{M}_{2}$

$\theta$

${V}_{1},{M}_{1} \; \beta$

## > 能量方程

$$
{\rho }_{1}{u}_{1}\left( {{h}_{1} + \frac{{V}_{1}^{2}}{2}}\right)  = {\rho }_{2}{u}_{2}\left( {{h}_{2} + \frac{{V}_{2}^{2}}{2}}\right)
$$

(9.10)

$$
{h}_{1} + \frac{{V}_{1}^{2}}{2} = {h}_{2} + \frac{{V}_{2}^{2}}{2} \tag{9.11}
$$

$$
{V}_{1}^{2} - {V}_{2}^{2} = \left( {{u}_{1}^{2} + {w}_{1}^{2}}\right)  - \left( {{u}_{2}^{2} + {w}_{2}^{2}}\right)  = {u}_{1}^{2} - {u}_{2}^{2}
$$

$$
{h}_{1} + \frac{{u}_{1}^{2}}{2} = {h}_{2} + \frac{{u}_{2}^{2}}{2}
$$

(9.12)

$$
{\rho }_{1}{u}_{1} = {\rho }_{2}{u}_{2} \tag{9.2}
$$

$$
{p}_{1} + {\rho }_{1}{u}_{1}^{2} = {p}_{2} + {\rho }_{2}{u}_{2}^{2} \tag{9.7}
$$

(9.12)

![bo_d4puqmbef24c73bcjmlg_32_1237_307_1077_491_0.jpg](bo_d4puqmbef24c73bcjmlg_32_1237_307_1077_491_0.jpg)

![bo_d4puqmbef24c73bcjmlg_33_1235_144_1080_708_0.jpg](bo_d4puqmbef24c73bcjmlg_33_1235_144_1080_708_0.jpg)

] 方程(9.2)、(9.7)、(9.12)分别是斜激波的连续、动量、能量方程。 它们只包含斜激波的法向速度分量 ${u}_{1}\text{ 、 }{u}_{2}$ ，而不包含斜激波的切向速度分量 ${w}_{1}\text{ 、 }{w}_{2}$ 。

I 换句话说:对于斜激波，可将波前速度和波后速度分解到斜激波法向和切向两个方向:1) 法向可等效为正激波进行处理；2) 切向速度不变。

斜激波控制方程归纳 / Summary of governing equations

$$
{\rho }_{1}{u}_{1} = {\rho }_{2}{u}_{2} \tag{9.2}
$$

$$
{w}_{1} = {w}_{2} \tag{9.5}
$$

$$
{p}_{1} + {\rho }_{1}{u}_{1}^{2} = {p}_{2} + {\rho }_{2}{u}_{2}^{2} \tag{9.7}
$$

$$
{h}_{1} + \frac{{u}_{1}^{2}}{2} = {h}_{2} + \frac{{u}_{2}^{2}}{2} \tag{9.12}
$$

方程(9.2)、(9.7)、(9.12)与正激波控制方程(8.2)、(8.6)、(8.1 完全相同。

$>$ 只要将正激波关系式中所有的 ${M}_{1}$ 用 ${M}_{\mathrm{n},1}\left( {u}_{1}\right)$ 代替， ${M}_{2}$ 用 ${M}_{\mathrm{n},2}\left( {u}_{2}\right)$ 代替，就可以得到通过斜激波的流动特性变化量。

## 斜激波关系式

由斜激波控制方程，可以得到:

准确解

$$
\frac{{p}_{2}}{{p}_{1}} = 1 + \frac{2\gamma }{\gamma  + 1}\left( {M{a}_{1}^{2}{\sin }^{2}\beta  - 1}\right)
$$

$$
\frac{{\rho }_{2}}{{\rho }_{1}} = \frac{\left( {\gamma  + 1}\right) M{a}_{1}^{2}{\sin }^{2}\beta }{\left( {\gamma  - 1}\right) M{a}_{1}^{2}{\sin }^{2}\beta  + 2}
$$

$$
\frac{{T}_{2}}{{T}_{1}} = \frac{\left( {p}_{2}/{p}_{1}\right) }{\left( {\rho }_{2}/{\rho }_{1}\right) }
$$

$\frac{{u}_{2}}{{V}_{1}} = 1 - \frac{2\left( {M{a}_{1}^{2}{\sin }^{2}\beta  - 1}\right) }{\left( {\gamma  + 1}\right) M{a}_{1}^{2}}$

$$
\frac{{v}_{2}}{{V}_{1}} = \frac{2\left( {M{a}_{1}^{2}{\sin }^{2}\beta  - 1}\right) \cos \beta }{\left( {\gamma  + 1}\right) M{a}_{1}^{2}}
$$

$$
\frac{{p}_{2}}{{p}_{1}} = 1 + \frac{2\gamma }{\gamma  + 1}\left( {{M}_{n,1}^{2} - 1}\right) \tag{9.14}
$$

$$
\frac{{\rho }_{2}}{{\rho }_{1}} = \frac{\left( {\gamma  + 1}\right) {M}_{n,1}^{2}}{2 + \left( {\gamma  - 1}\right) {M}_{n,1}^{2}} \tag{9.15}
$$

$$
\frac{{T}_{2}}{{T}_{1}} = \frac{{p}_{2}}{{p}_{1}}\frac{{\rho }_{1}}{{\rho }_{2}} \tag{9.16}
$$

$$
{M}_{n,2}^{2} = \frac{1 + \left\lbrack  {\left( {\gamma  - 1}\right) /2}\right\rbrack  {M}_{n,1}^{2}}{\gamma {M}_{n,1}^{2} - \left( {\gamma  - 1}\right) /2} \tag{9.17}
$$

注意: ${M}_{n,1}$ 和 ${M}_{n,2}$ 分别是斜激波波前和波后的法向马赫数

确定斜激波关系式需要几个参数?

${M}_{n,1}$ 和 ${M}_{n,2}$ 分别是斜激波波前和波后的法向马赫数，所以有:

$$
{M}_{n,1} = {M}_{1}\sin \beta \tag{9.13}
$$

![bo_d4puqmbef24c73bcjmlg_36_84_475_1141_727_0.jpg](bo_d4puqmbef24c73bcjmlg_36_84_475_1141_727_0.jpg)

${M}_{n,1}$ 既依赖于 ${M}_{1}$ 又依赖于 $\beta$ ; 2个参数?

$$
{M}_{2} = \frac{{M}_{n,2}}{\sin \left( {\beta  - \theta }\right) } \tag{9.18}
$$

${M}_{2}$ 既依赖于 ${M}_{n,2}$ 又依赖于 $\beta$ 和 $\theta$ ；3个参数?

问题: $\theta$ 是不是一个独立的自变量即第三个参数?

$\theta$ 与 ${M}_{1}$ 和 $\beta$ 的函数关系

$$
\frac{\tan \left( {\beta  - \theta }\right) }{\tan \beta } = \frac{{u}_{2}}{{u}_{1}} = \frac{{\rho }_{1}}{{\rho }_{2}}
$$

(9.21)

![bo_d4puqmbef24c73bcjmlg_37_230_347_1810_775_0.jpg](bo_d4puqmbef24c73bcjmlg_37_230_347_1810_775_0.jpg)

(9.20)

θ – β – M 关系式 / θ – β – M relations

$$
\frac{\tan \left( {\beta  - \theta }\right) }{\tan \beta } = \frac{2 + \left( {\gamma  - 1}\right) {M}_{1}^{2}{\sin }^{2}\beta }{\left( {\gamma  + 1}\right) {M}_{1}^{2}{\sin }^{2}\beta } \tag{9.22}
$$

$$
\tan \theta  = 2\cot \beta \frac{{M}_{1}^{2}{\sin }^{2}\beta  - 1}{{M}_{1}^{2}\left( {\gamma  + \cos {2\beta }}\right)  + 2} \tag{9.23}
$$

方程(9.23) 被称为 $\theta  - \beta  - M$ 关系式，它限定了 $\theta$ 为 ${M}_{1}$ 和 $\beta$ 的唯一函数。这是分析斜激波特性的最重要的关系式，其结果在图9.9中给出 $\left( {\gamma  = {1.4}}\right)$ 。

![bo_d4puqmbef24c73bcjmlg_39_9_0_2286_1753_0.jpg](bo_d4puqmbef24c73bcjmlg_39_9_0_2286_1753_0.jpg)

- 压强比

$$
\frac{{p}_{2}}{{p}_{1}} = 1 + \frac{2\gamma }{\gamma  + 1}\left( {{M}_{1}^{2}{\sin }^{2}\beta  - 1}\right)
$$

$$
{M}_{1}^{2}{\sin }^{2}\beta  \gg  1
$$

$$
\frac{{p}_{2}}{{p}_{1}} = \frac{2\gamma }{\gamma  + 1}{M}_{1}^{2}{\sin }^{2}\beta
$$

- 密度比

$$
\frac{{\rho }_{2}}{{\rho }_{1}} = \frac{\left( {\gamma  + 1}\right) {M}_{1}^{2}{\sin }^{2}\beta }{\left( {\gamma  - 1}\right) {M}_{1}^{2}{\sin }^{2}\beta  + 2}
$$

$$
\frac{{\rho }_{2}}{{\rho }_{1}} = \frac{\gamma  + 1}{\gamma  - 1}
$$

- 温度比

$$
\frac{{T}_{2}}{{T}_{1}} = \frac{{2\gamma }\left( {\gamma  - 1}\right) }{{\left( \gamma  + 1\right) }^{2}}{M}_{1}^{2}{\sin }^{2}\beta
$$

$$
\frac{{u}_{2}}{{V}_{1}} = 1 - \frac{2\left( {{M}_{1}^{2}{\sin }^{2}\beta  - 1}\right) }{\left( {\gamma  + 1}\right) {M}_{1}^{2}}
$$

- 速度比

$$
\frac{{u}_{2}}{{V}_{1}} = 1 - \frac{2{\sin }^{2}\beta }{\gamma  + 1}
$$

$$
\frac{{v}_{2}}{{V}_{1}} = \frac{2\left( {{M}_{1}^{2}{\sin }^{2}\beta  - 1}\right) \cos \beta }{\left( {\gamma  + 1}\right) {M}_{1}^{2}}
$$

$$
\frac{{v}_{2}}{{V}_{1}} = \frac{2\left( {{M}_{1}^{2}{\sin }^{2}\beta }\right) \cot \beta }{\left( {\gamma  + 1}\right) {M}_{1}^{2}} = \frac{2\sin \beta \cos \beta }{\gamma  + 1}
$$

$$
{C}_{p} = \frac{{p}_{2} - {p}_{1}}{{q}_{1}}
$$

$$
{q}_{1} = \frac{1}{2}{\rho }_{1}{V}_{1}^{2} = \frac{1}{2}{\rho }_{1}{V}_{1}^{2}\frac{\gamma {p}_{1}}{\gamma {p}_{1}} = \frac{\gamma {p}_{1}}{2}\frac{{V}_{1}^{2}}{{a}_{1}^{2}} = \frac{\gamma }{2}{p}_{1}{M}_{1}^{2}
$$

$$
{C}_{p} = \frac{{p}_{2} - {p}_{1}}{{q}_{1}} = \frac{2}{\gamma {M}_{1}^{2}}\left( {\frac{{p}_{2}}{{p}_{1}} - 1}\right)
$$

$$
\frac{{p}_{2}}{{p}_{1}} = 1 + \frac{2\gamma }{\gamma  + 1}\left( {{M}_{1}^{2}{\sin }^{2}\beta  - 1}\right)
$$

$$
{C}_{p} = \frac{4}{\gamma  + 1}\left( {{\sin }^{2}\beta  - \frac{1}{{M}_{1}^{2}}}\right)  \rightarrow  {C}_{p} = \left( \frac{4}{\gamma  + 1}\right) {\sin }^{2}\beta
$$

$$
\sin \beta  \approx  \beta
$$

$$
\tan \theta  = 2\cot \beta \left\lbrack  \frac{{M}_{1}^{2}{\sin }^{2}\beta  - 1}{{M}_{1}^{2}\left( {\gamma  + \cos {2\beta }}\right)  + 2}\right\rbrack
$$

$$
\cos {2\beta } \approx  1
$$

$\tan \theta  \approx  \sin \theta  \approx  \theta$

$$
\theta  = \frac{2}{\beta }\left\lbrack  \frac{{M}_{1}^{2}{\beta }^{2} - 1}{{M}_{1}^{2}\left( {\gamma  + 1}\right)  + 2}\right\rbrack
$$

$$
\theta  = \frac{2}{\beta }\left\lbrack  \frac{{M}_{1}^{2}{\beta }^{2}}{{M}_{1}^{2}\left( {\gamma  + 1}\right) }\right\rbrack
$$

$\frac{\beta }{\theta } = \frac{\gamma  + 1}{2}$

In the hypersonic limit

$$
\frac{{p}_{2}}{{p}_{1}} \rightarrow  \frac{2\gamma }{\gamma  + 1}{M}_{1}^{2}{\sin }^{2}\beta
$$

$$
\frac{{\rho }_{2}}{{\rho }_{1}} \rightarrow  \frac{\gamma  + 1}{\gamma  - 1}
$$

$\frac{{T}_{2}}{{T}_{1}} \rightarrow  \frac{{2\gamma }\left( {\gamma  - 1}\right) }{{\left( \gamma  + 1\right) }^{2}}{M}_{1}^{2}{\sin }^{2}\beta$

$$
\frac{{u}_{2}}{{V}_{1}} \rightarrow  1 - \frac{2{\sin }^{2}\beta }{\gamma  + 1}
$$

$$
\frac{{v}_{2}}{{V}_{1}} \rightarrow  \frac{\sin \left( {2\beta }\right) }{\gamma  + 1}
$$

$$
{C}_{p} \rightarrow  \left( \frac{4}{\gamma  + 1}\right) {\sin }^{2}\beta
$$

In the hypersonic limit

and for small $\theta$

$$
\beta  \rightarrow  \frac{\gamma  + 1}{2}\theta
$$

- 比精确公式更加简单

- 在一些关系中, Mach数消失了

# 3高超声速相似参数 $K \equiv  {M}_{1}\theta  \equiv$ hypersonic similarity parameter

$$
\sin \beta  \approx  \beta
$$

$$
\tan \theta  = 2\cot \beta \left\lbrack  \frac{{M}_{1}^{2}{\sin }^{2}\beta  - 1}{{M}_{1}^{2}\left( {\gamma  + \cos {2\beta }}\right)  + 2}\right\rbrack
$$

$$
\cos {2\beta } \approx  1
$$

$\tan \theta  \approx  \sin \theta  \approx  \theta$

$$
\theta  = \frac{2}{\beta }\left\lbrack  \frac{{M}_{1}^{2}{\beta }^{2} - 1}{{M}_{1}^{2}\left( {\gamma  + 1}\right)  + 2}\right\rbrack
$$

$$
{M}_{1}^{2}{\beta }^{2} - 1 = \frac{\gamma  + 1}{2}{M}_{1}^{2}{\beta \theta }
$$

$$
{\left( \frac{\beta }{\theta }\right) }^{2} - \frac{\gamma  + 1}{2}\left( \frac{\beta }{\theta }\right)  - \frac{1}{{M}_{1}^{2}{\theta }^{2}} = 0
$$

$$
\frac{{p}_{2}}{{p}_{1}} = 1 + \frac{2\gamma }{\gamma  + 1}\left( {{M}_{1}^{2}{\beta }^{2} - 1}\right)
$$

$$
\frac{\beta }{\theta } = \frac{\gamma  + 1}{4} + \sqrt{{\left( \frac{\gamma  + 1}{4}\right) }^{2} + \frac{1}{{M}_{1}^{2}{\theta }^{2}}}
$$

$$
{\beta }^{2} = \left\lbrack  {\frac{\left( \gamma  + 1\right) }{2}\frac{\left( \gamma  + 1\right) }{4} + \frac{\gamma  + 1}{2}\sqrt{{\left( \frac{\gamma  + 1}{4}\right) }^{2} + \frac{1}{{M}_{1}^{2}{\theta }^{2}}}}\right\rbrack  {\theta }^{2} + \frac{1}{{M}_{1}^{2}}
$$

0.025

$$
\frac{{p}_{2}}{{p}_{1}} = 1 + \frac{\gamma \left( {\gamma  + 1}\right) }{4}{M}_{1}^{2}{\theta }^{2} + \gamma \sqrt{{\left( \frac{\gamma  + 1}{4}\right) }^{2} + \frac{1}{{M}_{1}^{2}{\theta }^{2}}}{M}_{1}^{2}{\theta }^{2}
$$

$$
\frac{{p}_{2}}{{p}_{1}} = 1 + \frac{\gamma \left( {\gamma  + 1}\right) }{4}{K}^{2} + \gamma {K}^{2}\sqrt{{\left( \frac{\gamma  + 1}{4}\right) }^{2} + \frac{1}{{K}^{2}}}
$$

## 斜激波

$$
\frac{{p}_{2}}{{p}_{1}} = 1 + \frac{\gamma \left( {\gamma  + 1}\right) }{4}{K}^{2} + \gamma {K}^{2}\sqrt{{\left( \frac{\gamma  + 1}{4}\right) }^{2} + \frac{1}{{K}^{2}}}
$$

$$
{C}_{p} = 2{\theta }^{2}\left\lbrack  {\frac{\gamma  + 1}{4} + \sqrt{{\left( \frac{\gamma  + 1}{4}\right) }^{2} + \frac{1}{{K}^{2}}}}\right\rbrack
$$

、膨胀波

$$
{C}_{p} = \frac{2{\theta }^{2}}{\gamma {K}^{2}}\left\lbrack  {{\left( 1 - \frac{\gamma  - 1}{2}K\right) }^{{2\gamma }/\left( {\gamma  - 1}\right) } - 1}\right\rbrack
$$

$$
\frac{{p}_{2}}{{p}_{1}} = {\left( 1 - \frac{\gamma  - 1}{2}K\right) }^{{2\gamma }/\left( {\gamma  - 1}\right) }
$$