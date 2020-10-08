

# 第一章：
1.分子间相互作用势：`$\varphi(r) = \displaystyle\frac{\sigma} {r^s} - \frac{\mu} {r^t}$`<br> 
- 林纳德·琼斯势(s = 12, t = 6):`$\varphi(r) = \displaystyle \frac{\sigma} {r^{12}} - \frac{\mu} {r^6}$`

2.分子平均动能:`$\bar{\varepsilon}_k = \frac{1}{2}m\bar{v^2}$`<br><br>
3.理想气体温标：<br>
- `T_V(p) = 273.16 \lim\limits_{p_0\rightarrow0} \displaystyle\frac{p}{p_0}`
- `$T_p(V) = 273.16 \lim \limits_{p_0 \rightarrow 0} \displaystyle\frac{V}{V_0} $`

4.描述物质状态变化的物理量:<br>
- 体膨胀系数：`$\alpha = \lim \limits_{\Delta T \rightarrow 0} \displaystyle\frac{1}{V}(\displaystyle\frac{\Delta V}{\Delta T})_p = \frac{1}{V} \big(\displaystyle\frac{\partial V}{\partial T} \big)_p$`
- 等温压缩系数：`$\kappa = \lim \limits_{\Delta p \rightarrow 0} -\displaystyle\frac{1}{V} (\displaystyle\frac{\Delta V}{\Delta p})_p  = - \frac{1}{V} \big(\displaystyle\frac{\partial V}{\partial p}\big)_T$`
- 等体压强系数：`$\beta = \lim\limits_{\Delta T \rightarrow 0} \displaystyle\frac{1}{V} \big(\displaystyle\frac{\Delta p}{\Delta T}\big)_V = \frac{1}{V} \big(\displaystyle\frac{\partial p}{\partial T}\big)_V$`
- 三者有如下关系：`$p\beta\kappa = \alpha$`

5.由上条可得：
- `$\mathrm{d}V = \big( \displaystyle\frac{\partial V}{\partial T}\big)_p \mathrm{d}T + \big( \frac{\partial V}{\partial p}\big)_T \mathrm{d}p$`
- `$\mathrm{d}p = \big( \displaystyle\frac{\partial p}{\partial T} \big)_V \mathrm{d}T + \big( \frac {\partial p}{\partial V} \big)_T \mathrm{d}V$`

6.理想气体状态方程：<br>
- `$pV = \displaystyle\frac{M}{\mu} RT = \nu RT \\ R = 8.314510$` J/(mol·K)
- 理想气体的`$\beta = \displaystyle\frac{1}{T},\alpha = \frac{1}{T},\kappa = \frac{1}{T}$`

7.分子动理论：
- `$\displaystyle p = \frac{2}{3}n \bar{\varepsilon_k} \\ $` 对于极端相对论粒子 `$p = \frac{1}{3}n \bar{\varepsilon_k}$`
- `$p = n k_B T \\ k_B = 1.380658 \times 10^{-23}$`   J/K

8.实际气体状态方程：
`$\displaystyle\bigg(p+\frac{a}{V_m^2}\bigg)\big( V_m - b\big) = RT$`<br>
- `$b \approx 4N_A v_0$`
- `$a = 4N_A^2E_Bv_0$`
***
# 第二章：
1.速度分布概率密度及速度分布概率 <br>
- 微观粒子速度分布函数：`$f(\vec{v}) = \displaystyle\frac{1}{N} \frac{\mathrm{d} V}{\mathrm{d}\vec{v}} \\ f(\vec{v})\mathrm{d}\vec{v}$`
表示速度处于`$\vec{v} \sim \vec{v} + \mathrm{d}\vec{v}$`区间内的粒子占所有粒子的概率
- 微观粒子能量分布函数： `$f(\varepsilon) = \displaystyle\frac{1}{N} \frac{\mathrm{d} N}{\mathrm{d}\varepsilon} \\ f(\varepsilon) \mathrm{d}\varepsilon$`
表示能量介于`$\varepsilon \sim \varepsilon + \mathrm{d}\varepsilon$`区间内的粒子占所有粒子的概率

2.粒子按各方向分速度的分布函数，以`$x$`方向为例：<br>`$f(v_x) = \displaystyle \frac{\mathrm{d} N (v_x)}{N \mathrm{d} v_x} \\ f(v_x, v_y, v_z) = f(v_x) f(v_y) f(v_z)$` <br>
3.麦克斯韦**速度**分布率：<br>`$f_M(\vec{v}) = \bigg(\displaystyle\frac{m}{2 \pi k_B T}\bigg)^{\frac{3}{2}} e^{- \frac{m \vec{v}^2 }{2 k_B T}} $` <br>
4.麦克斯韦**速率**分布率：<br>`$F_M(v) = 4\pi v^2 f_M (\vec{v})$`<br>
5.泻流数率：<br>`$\mathrm{d}N_c = \mathrm{d}\Gamma \mathrm{d}t \mathrm{d}S \\ \Gamma_{effu} = \frac{1}{4} n \bar{v}$` <br>
6.麦克斯韦分布率的应用：
- 最概然速率：`$\displaystyle\frac{\mathrm{d}}{\mathrm{d}v} F_M (v) = 0 \  \rArr \  v_p = \sqrt{\frac{2 k_B T}{m}}.$`
- 平均速率：`$\displaystyle\bar{v} = \sqrt{\frac{8 k_B T}{\pi m}}$`
- 方均根速率：`$\displaystyle \bar{v^2} = \int^{\infty}_{0} v^2 F_M(v) \mathrm{d} v = \frac{3 k_B T}{m} \ \Rarr \  \sqrt{\bar{v^2}} = \sqrt{\frac{3 k_B T}{m}}$` 

7.重力场中微粒密度随高度的等温分布：
- `$\displaystyle n= n_0 e^{-\frac{mgz}{k_B T}}$`
- `$\displaystyle p = p_0 e=^{-\frac{mgz}{k_B T}}$`
- 微粒随高度的等温分布率：`$\displaystyle f(z) = \frac {\mathrm{d} N (z)}{N \mathrm{d}z} = \frac{mg}{k_B T}e^{-\frac{mgz}{k_B T}} $`

8.麦克斯韦-玻尔兹曼分布率：<br> `$\displaystyle f(\vec{v},r) = f_M (\vec{v}) f_B (r) = f_0\bigg(\frac{m}{2\pi k_B T} \bigg)^{\frac{3}{2}} e^{-\frac{\varepsilon _k + \varepsilon _p}{k_B T}}$`<br>
9.平均热运动能量：<br>`$\displaystyle \bar{\varepsilon} = \frac{1}{2} (t+r+2s) k_B T$` <br>
10.理想气体的内能：<br>`$\displaystyle U = \frac{1}{2} \frac{M}{\mu} (t+r+2s) R T$` <br>
11.理想气体的定体热容：<br> `$\displaystyle C_{V,M} = \bigg(\frac{\partial{U_m}}{\partial{T}}\bigg)_V = \frac{1}{2}(t+r+2s)R$` <br>
***
# 第三章：
1.气体分子的碰撞：


