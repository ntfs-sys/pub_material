# 3.53
![[p04hw 53.png]]
Дано: $q = 100 мКл, l = 1,5см$ Найти: А-?
Решение:
![[p04hw 53 fig1.png]]
$$
F = \frac{q^2}{4\pi\epsilon_04x^2} \\
A = \int\limits^\infty_l \frac{q^2}{4\pi\epsilon_04x^2}dx = \frac{q^2}{16\pi \epsilon_0} \int\limits^\infty_l \frac{dx}{x^2} = \frac{q^2}{16\pi\epsilon_0} (-\frac{1}{x})|^\infty_l = \frac{q^2}{16\pi\epsilon_0l} = \frac{10^{-4*2}}{16*3,14*1,5*10^{-2} * 8,85 * 10^{-12}} = 1500 Дж
$$

Ответ 1500 Джоулей

## 3.61
![[p03hw 61.png]]
Дано: R, Q, l
Найти: $\sigma$ = ?
Решение:
$$E_+ = \frac{1ql}{4 \pi \epsilon_0 (R^2+l^2)^{\frac{3}{2}}}$$
$$E = 2E_+ = \frac{1ql}{2 \pi \epsilon_0 (R^2+l^2)^{\frac{3}{2}}}$$
$$E = \frac{\sigma}{\epsilon_0} => \sigma = E\epsilon_0 = E = 2E_+ = \frac{1ql}{2 \pi (R^2+l^2)^{\frac{3}{2}}}$$

## 3.85
![[p03hw 85.png]]
Дано: $$E_0, \epsilon$$
Найти:
E - ?
D - ?

Решение:
а)
$$U = \int \vec{E} d \vec{l} = E_1\frac{d}{2} + E_2\frac{d}{2} = \{E_1 = E_2\} => U = E_0d => E_0 = E_1 = E_2$$
$$D_1 = \epsilon_0 E_1 = \epsilon_0 E_0, D_2 = \epsilon E_0$$
б)
$$D = \sigma, D_0 = \epsilon_0 E_0, D_1 = D_2 = \epsilon_0 E_0$$
$$D_1 = \epsilon_0 E_1 => \epsilon_0 E_1 = \epsilon_0 E_0 => E_1 = E_0$$
$$D_2 = \epsilon E_2 = \epsilon_0 E_0$$
$$E_2 = \frac{\epsilon_0 E_0}{\epsilon}$$
# 3.103
![[p03hw 103.png]]
**Дано:** $\varepsilon_1$, $\varepsilon_2$, $d_1$, $d_2$, $S$.  
**Найти:** $C - ?$

**Решение:**

![[p03hw 103(a) fig1.png]]
Данный конденсатор со слоистым диэлектриком эквивалентен двум последовательно соединённым плоским конденсаторам с ёмкостями $C_1$ и $C_2$:

$$C_1 = \frac{\varepsilon_0 \varepsilon_1 S}{d_1}, \qquad C_2 = \frac{\varepsilon_0 \varepsilon_2 S}{d_2}$$

Общая ёмкость при последовательном соединении:

$$C = \left(\frac{1}{C_1} + \frac{1}{C_2}\right)^{-1} = \left(\frac{d_1}{\varepsilon_0 \varepsilon_1 S} + \frac{d_2}{\varepsilon_0 \varepsilon_2 S}\right)^{-1} = \varepsilon_0 S \left(\frac{d_1 \varepsilon_2 + d_2 \varepsilon_1}{\varepsilon_1 \varepsilon_2}\right)^{-1} = \frac{\varepsilon_0 \varepsilon_1 \varepsilon_2 S}{d_1 \varepsilon_2 + d_2 \varepsilon_1}$$

**Ответ:** $C = \frac{\varepsilon_0 \varepsilon_1 \varepsilon_2 S}{d_1 \varepsilon_2 + d_2 \varepsilon_1}$