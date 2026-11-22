## 3.151 (б, в)
Дано: R
Найти: $R_{общее}$
Решение:
б)
$$R_1=\frac{R}{2}$$
$$R_2=R+R=2R$$
$$R_3=\frac{5}{7R}$$
$$R_4 = R+\frac{5}{7R}$$
$$R_{общее}=(\frac{4}{9R}+\frac{1}{R})^{-1}=\frac{7R}{12}$$
в) 
$$R_{общее}=\frac{3R}{4}$$
## 3.185
Дано:
Найти: $I$
Решение:
$$\begin{equation} \left\{ \begin{aligned} I_2-I_3-I &= 0 \\ I_1R_1 &= -\epsilon_0 \\ I_2R_2+I_3R_3 &= -\epsilon_0 \\ I_2R_2 + IR &= -\epsilon_0 - \epsilon \end{aligned} \right. \end{equation}$$
$$\Delta = \begin{vmatrix} 0 & 1 & -1 & -1 \\ R_1 & 0 & 0 & 0 \\ 0 & R_2 & R_3 & 0 \\ 0 & R_2 & 0 & R \end{vmatrix} = -R_1 \begin{vmatrix} 1 & -1 & -1 \\ R_2 & R_3 & 0 \\ R_2 & 0 & R \end{vmatrix} = -R_1(RR_3 + R_2R_3 + RR_2)$$

$$\Delta_I = \begin{vmatrix} 0 & 1 & -1 & 0 \\ R_1 & 0 & 0 & -\epsilon_0 \\ 0 & R_2 & R_3 & -\epsilon_0 \\ 0 & R_2 & 0 & -\epsilon_0+\epsilon \end{vmatrix} = -R_1(-(\epsilon_0 + \epsilon)R_3+\epsilon_0R_2 - (\epsilon_0 + \epsilon)R_2)$$

$$I = \frac{\Delta_I}{\Delta} = -\frac{(\epsilon_0 + \epsilon)R_3 + \epsilon R_2}{R_2R_3 + R(R_2+R_3)} = -\frac{\epsilon(R_2+R_3)+\epsilon_0R_3}{R(R_2+R_3) + R_2R_3}$$

## 3.191 (a)
Дано:
$$R=75Ом,q=100Кл,\Delta t = 50c$$
Найти: Q=?
Решение:
$$I=\alpha(\Delta t - t), \alpha = const$$
$$\int_0^{\Delta t} \alpha(\Delta t - t) dt = q => \int_0^{\Delta t} \alpha \Delta tdt - \int_0^{\Delta t} \alpha t dt = q => (\alpha \Delta t t - \frac{2t^2}{2}) |^{\Delta t}_0 = q => \alpha = \frac{2q}{\Delta t^2}$$

$$Q = \int_0^{\Delta t} (\frac{q^2(\Delta t - t)}{\Delta t^2})^2 R dt = \frac{4q^2R}{\Delta t^2} \int_0^{\Delta t} (\Delta t - t)^2dt = \frac{4q^2R}{3 \Delta t}$$
