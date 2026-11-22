## №3.32

Дано:
R, $\sigma$
a) l $\to$ 0
б) l >> R
Найти:
E(l) - ?
$\phi$ - ?
Решение:
$$dq = \sigma dS = 2\pi r\sigma dr$$
$$d\phi = \frac{1}{4\pi \epsilon_0} \frac{dq}{\sqrt{r^2 + l^2}} = \frac{\sigma}{2\epsilon_0} \frac{r dr}{\sqrt{r^2 + l^2}}$$

$$\phi(l) = \int^{R}_{0} d\phi = \int^{R}_{0}\frac{\sigma}{2\epsilon_0} \frac{rdr}{\sqrt{r^2+l^2}} = \frac{\sigma}{2\epsilon_0}\int^{R}_{0} \frac{rdr}{\sqrt{r^2+l^2}} = \frac{\sigma}{2\epsilon_0}(\sqrt{R^2+l^2} - |l|) = \frac{\sigma}{2\epsilon_0}(\sqrt{R^2+l^2} - l), l>0$$

$$E(l) = -\frac{d}{dl}[\frac{\sigma}{2\epsilon_0}(\sqrt{R^2+l^2}-l)] = \frac{\sigma}{2\epsilon_0}(1-\frac{l}{\sqrt{R^2+l^2}})$$
a) $$\lim_{l\to 0} \phi(l) = \phi(0) = \frac{\sigma R}{2 \epsilon_0}$$

$$\lim_{l\to0} E(l) = E(0) = \frac{\sigma}{2 \epsilon_0}$$
б)
$$l>>R: \phi(l) = \frac{\sigma}{2\epsilon_0}(\sqrt{R^2+l^2} - l) = \frac{\sigma}{2\epsilon_0}(l \sqrt{\frac{R^2}{l^2}+1} - l) = \frac{\sigma}{2\epsilon_0}(l + \frac{R^2}{2l} - l) = \frac{\sigma R^2}{4\epsilon_0 l} = \frac{q}{4\pi \epsilon_0 l}$$

$$E(l) = \frac{\sigma}{2\epsilon_0}(1 - (1 + \frac{R^2}{l^2})^{-\frac{1}{2}}) = \frac{q}{4\pi\epsilon_0 l^2}$$

## №3.34

Дано:
$q, R, \epsilon = 1, \phi(r)$
Найти:
а) $\phi(0)$ = ?
б) $\phi(r)$ = ?
Решение:
$$\rho = \frac{3q}{4\pi R^3}, \phi(\infty) = 0$$
$$r \geq R: E(r) = \frac{q}{4\pi \epsilon_0 r^2}$$
$$r \leq R: E(r) = \frac{q_{внутреннее}}{4\pi \epsilon_0 r^2} = \frac{qr}{4\pi \epsilon_0 R^3}$$

$$r \geq R: \phi(r) = \int_r^\infty E(r`)dr` = \int_r^\infty \frac{q}{4\pi \epsilon_0 r^2} dr` = \frac{q}{4\pi \epsilon_0 r}$$

$$r = R: \phi(R) = \frac{q}{4\pi \epsilon_0 R}$$

б) 
$$E(r) = -\frac{d\phi}{dr} \to d\phi = -E(r)dr$$
$$\phi(r) - \phi(R) = \int_r^RE(r`)dr` = \int^R_r \frac{qr`}{4\pi \epsilon_0 R^3} dr`$$

$$\phi(r) - \phi(R) = \frac{q}{8\pi \epsilon_0 R^3}(R^2-r^2)$$

$$\phi(R) = \frac{q}{4\pi \epsilon_0 R}$$
$$\phi(r) = \frac{q}{8\pi \epsilon_0 R} (3 - \frac{r^2}{R^2})$$
a) $$\phi(0) = \frac{3q}{8\pi \epsilon_0 R}$$

## №3.51
Дано:
$\phi=ar^2+b$ 
$a,b=const$
Найти:
$\rho(r)=?$
Решение:
$$E(r) = -\frac{d\phi}{dr}$$
$$E(r) = -2ar$$
$$\Delta \phi = -\frac{\rho}{\epsilon_0}$$
$$divE=\frac{1}{r^2}\frac{d}{dr}(r^2Er)$$

$$\frac{\rho}{\epsilon_0}=\frac{1}{r^2}\frac{d}{dr}(r^2(-2ar))$$
$$\frac{\rho}{\epsilon_0} = -6a$$
$$\rho(r)=-6a\epsilon_0$$
