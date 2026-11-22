# Задача 3.11

Дано: $R,q$, $\lambda$
Найти: $F$ = ?
**Решение:**

1. Найдем напряженность электрического поля, создаваемого заряженным кольцом на его оси на расстоянии $z$ от центра. По принципу суперпозиции поле направлено вдоль оси кольца и равно:
$$
E(z) = \frac{1}{4\pi\varepsilon_0} \frac{q z}{(R^2 + z^2)^{3/2}}
$$

2. Рассмотрим бесконечно малый элемент нити длиной $dz$, находящийся на расстоянии $z$ от центра кольца. Заряд этого элемента равен:
$$
dq = \lambda dz
$$
3. Сила, действующая на этот элемент нити со стороны электрического поля кольца, равна:
$$
dF = E(z) \cdot dq = \frac{1}{4\pi\varepsilon_0} \frac{q \lambda z}{(R^2 + z^2)^{3/2}} dz
$$

4. Чтобы найти полную силу взаимодействия, проинтегрируем это выражение по всей длине нити от $$z = 0$$ (центр кольца) до $$z \to \infty$$ (нить очень длинная):
$$
F = \int_{0}^{\infty} \frac{1}{4\pi\varepsilon_0} \frac{q \lambda z}{(R^2 + z^2)^{3/2}} dz = \frac{q \lambda}{4\pi\varepsilon_0} \int_{0}^{\infty} z (R^2 + z^2)^{-3/2} dz
$$

5. Вычислим интеграл. Сделаем замену переменной: $$u = R^2 + z^2$$, тогда $$du = 2z dz$$, откуда $$z dz = \frac{du}{2}$$.
$$
\int z (R^2 + z^2)^{-3/2} dz = \frac{1}{2} \int u^{-3/2} du = \frac{1}{2} \left( \frac{u^{-1/2}}{-1/2} \right) = -\frac{1}{\sqrt{u}} = -\frac{1}{\sqrt{R^2 + z^2}}
$$

Подставим пределы интегрирования:
$$
\int_{0}^{\infty} z (R^2 + z^2)^{-3/2} dz = \left[ -\frac{1}{\sqrt{R^2 + z^2}} \right]_{0}^{\infty} = 0 - \left( -\frac{1}{\sqrt{R^2}} \right) = \frac{1}{R}
$$

6. Подставим значение интеграла в выражение для силы:
$$
F = \frac{q \lambda}{4\pi\varepsilon_0} \cdot \frac{1}{R} = \frac{q \lambda}{4\pi\varepsilon_0 R}
$$

**Ответ:**
$$
F = \frac{q \lambda}{4\pi\varepsilon_0 R}
$$
# 3.13
![[p11hw 13.png]]
$$\begin{aligned} &q, \quad 2a \\ &E(r) = ? \end{aligned}$$
## 1)
$$\begin{aligned} &R = \sqrt{l^2 + r^2} \\ &d\vec{E} = \frac{1}{4\pi\varepsilon_0} \cdot \frac{dq}{R^3} \vec{R} \\ &\frac{dq}{q} = \frac{dl}{2a} \Rightarrow dq = \frac{q\,dl}{2a} \\ &dE_y = dE \cos\alpha = \frac{1}{4\pi\varepsilon_0} \frac{q\,dl}{2a} \cdot \frac{1}{R^2} \cdot \frac{r}{R} = \frac{q\,dl \cdot r}{8\pi\varepsilon_0 a (l^2 + r^2)^{3/2}} \\ &E = \int\limits_{-a}^{a} \frac{qr}{8\pi\varepsilon_0 a (l^2 + r^2)^{3/2}} dl = \frac{qr}{8\pi\varepsilon_0 a} \cdot \frac{2a}{r^2 \sqrt{r^2 + a^2}} = \frac{q}{4\pi\varepsilon_0 r \sqrt{r^2 + a^2}} \end{aligned}$$
Вычисление интеграла:
$$\begin{aligned} \int\limits_{-a}^{a} \frac{dl}{(l^2 + r^2)^{3/2}} &= \left\vert{} \begin{aligned} &l = r\operatorname{tg}\varphi \\ &dl = \frac{r\,d\varphi}{\cos^2\varphi} \\ &\varphi \in \left[-\operatorname{arctg}\frac{a}{r}, \operatorname{arctg}\frac{a}{r}\right], \quad \varphi_0 = \operatorname{arctg}\frac{a}{r} \end{aligned} \right\vert{} = \\ &= \int\limits_{-\varphi_0}^{\varphi_0} \frac{\frac{r\,d\varphi}{\cos^2\varphi}}{r^3 (1 + \operatorname{tg}^2\varphi)^{3/2}} = \frac{1}{r^2} \int\limits_{-\varphi_0}^{\varphi_0} \cos\varphi\,d\varphi = \frac{2\sin\varphi_0}{r^2} = \frac{2a}{r^2 \sqrt{r^2 + a^2}} \end{aligned}$$
## 2)
$$\begin{aligned} &dq = \frac{q\,dl}{2a} \\ &dE = \frac{1}{4\pi\varepsilon_0} \cdot \frac{q\,dl}{2a} \frac{1}{(r - l)^2} \\ &E = \frac{q}{4\pi\varepsilon_0 \cdot 2a} \int\limits_{-a}^{a} \frac{dl}{(r - l)^2} = \frac{q}{8\pi\varepsilon_0 a} \int\limits_{-a}^{a} \frac{dl}{(l - r)^2} = \frac{q}{8\pi\varepsilon_0 a} \left.\left(-\frac{1}{l - r}\right)\right\vert{}_{-a}^{a} = \\ &= \frac{q}{8\pi\varepsilon_0 a} \left(-\frac{1}{a - r} + \frac{1}{-a - r}\right) = \frac{q}{8\pi\varepsilon_0 a} \left(\frac{1}{r - a} - \frac{1}{r + a}\right) = \\ &= \frac{q}{8\pi\varepsilon_0 a} \cdot \frac{r + a - (r - a)}{r^2 - a^2} = \frac{q}{4\pi\varepsilon_0 (r^2 - a^2)} \end{aligned}$$