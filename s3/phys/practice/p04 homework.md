## 3.103(a) (дубль из 3 домашки)

Дано:
$$\epsilon_1, \epsilon_2, d_1, d_2, S$$
Найти: С-?
Решение:
$$С_1 = \frac{\epsilon_0 \epsilon_1 S}{d_1}$$
$$С_2 = \frac{\epsilon_0 \epsilon_2 S}{d_2}$$
$$С = (\frac{d_1}{\epsilon_0 \epsilon_1 S} + \frac{d_2}{\epsilon_0 \epsilon_2 S})^{-1} = \epsilon_0 S (\frac{d_1 \epsilon_2 + d_2 \epsilon_1}{\epsilon_1\epsilon_2})^{-1} = \frac{\epsilon_0\epsilon_1\epsilon_2 S}{d_1\epsilon_2 + d_2 \epsilon_1}$$

## 3.114(a)
![[p04hw 114.png]]
![[p04hw 114 fig1.png]]
$C = C_1 + C_2 + C_3$
## 3.116
![[p04hw 116.png]]
$C_1 = 1\text{ мкФ}, \quad U_1 = 6\text{ кВ}, \quad C_2 = 2\text{ мкФ}, \quad U_2 = 4\text{ кВ},$ $U - ?$
При последовательном соединении $Q_1 = Q_2 = Q,$ $Q_{1\max} = C_1 U_1 = 1 \cdot 6 = 6\text{ мкКл}.$ $Q_{2\max} = C_2 U_2 = 2 \cdot 4 = 8\text{ мкКл}.$ $Q_{\max} = 6\text{ мкКл}.$ $U_1 = 6\text{ кВ}, \quad U_2 = \frac{Q_{\max}}{C_2} = \frac{6}{2} = 3\text{ кВ}$ $U = U_1 + U_2 = 9\text{ кВ}$
## 3.119
![[p04hw 119.png]]
![[p04hw 119 fig1.png]]
$\mathcal{E} = 10\text{ В}, \quad C_1 = 1\text{ мкФ} = 10^{-6}\text{ Ф}, \quad C_2 = 2\text{ мкФ} = 2 \cdot 10^{-6}\text{ Ф}, \quad \varphi_A - \varphi_B = 5\text{ В}, \quad U_1 = ?, \quad U_2 = ?$
$U_1 + U_2 = 5\text{ В} + 10\text{ В} = 15\text{ В}$ $Q_1 = Q_2 = Q \Rightarrow C_1 U_1 = C_2 U_2 \Rightarrow$ $\Rightarrow U_1 = 2U_2$ $3U_2 = 15 \Rightarrow U_2 = 5\text{ В} \Rightarrow U_1 = 10\text{ В}$
## 3.138
![[p04hw 138.png]]
$q = 3 \cdot 10^{-6}\text{ Кл}, \quad \varepsilon = 3, \quad a = 0,25\text{ м}, \quad b = 0,5\text{ м}, \quad W - ?$
![[p04hw 138 fig1.png]]
$$\begin{aligned} &E(r) = \frac{q}{4\pi \varepsilon_0 \varepsilon r^2} \\ &w = \varepsilon \varepsilon_0 \frac{E^2}{2} = \frac{q^2}{32\pi^2 \varepsilon_0 \varepsilon r^4} \\ &dV = 4\pi r^2 dr \quad V = \frac{4}{3}\pi r^3 \\ &\int\limits_a^b w dV = \int\limits_a^b \frac{q^2 4\pi r^2 dr}{32\pi^2 \varepsilon_0 \varepsilon r^4} = \int\limits_a^b \frac{q^2 dr}{8\pi \varepsilon_0 \varepsilon r^2} = \\ &= \frac{q^2}{8\pi \varepsilon_0 \varepsilon} \int\limits_a^b \frac{dr}{r^2} = \frac{q^2}{8\pi \varepsilon_0 \varepsilon} \left.\left(-\frac{1}{r}\right)\right\vert{}_a^b = \\ &= \frac{q^2}{8\pi \varepsilon_0 \varepsilon} \left(\frac{1}{a} - \frac{1}{b}\right) = \\ &= \frac{9 \cdot 10^{-12}\text{ Кл}^2}{8\pi \varepsilon_0 \cdot 3} (4 - 2)\text{ м}^{-1} \approx 2,70 \cdot 10^{-2}\text{ Дж} \end{aligned}$$