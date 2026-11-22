## 3.226 (a, б)
а)
Дано:
a, b, $\phi$, O, $I$
Найти: 
$B_0$=?
Решение:
$$dB_1 = |\frac{\mu_0 I [d \vec{l} \vec{r}]}{4\pi \vec{r}^3}| = \frac{\mu_0Iadl}{4\pi a^3} = \frac{\mu_0 I dl}{4 \pi a^2}$$
$$B_1 = \int_0^{(2\pi-\phi)a} \frac{\mu_0 I dl}{4\pi a^2} = \frac{\mu_0 I}{4\pi a}(2\pi = \phi)$$
$$dB_2 = dB_3 = |\frac{\mu_0 I [d\vec{l}, \vec{r}]}{4 \pi \vec{r}^3}| = \frac{\mu_0 I dl  \sin{180}}{4\pi r^2} = 0 => B_2 = B_3 = 0$$
$$dB_4 =  |\frac{\mu_0 I [d\vec{l}, \vec{r}]}{4 \pi \vec{r}^3}| = \frac{\mu_0Iadl}{4\pi b^3} = \frac{\mu_0 I dl}{4 \pi b^2}$$
$$B_4 = \int^{4b}_0 \frac{\mu_0 I dl}{4 \pi b^2} = \frac{\mu_0 I \phi}{4 \pi b}$$
$$B_0 = B_1 + B_4 = \frac{\mu_0 I}{4\pi}(\frac{2\pi - \phi}{a} + \frac{\phi}{b})$$

б)
Дано:
a, b, $\phi$, O, $I$
Найти: 
$B_0$=?
Решение:
Из пункта а 
$$B_1 = \frac{\mu_0 I}{4\pi a}(\frac{3\pi}{2})$$
$$B_2 = B_3 = 0$$
$$r = \frac{b}{\sin{\alpha}} => \frac{r}{\sin{\alpha}} = \frac{dl}{d\alpha} => dl = \frac{d \alpha r}{\sin{\alpha}}$$

$$dB_4 = dB_5 = \frac{\mu_0}{4\pi}\frac{I dl \sin{\alpha}}{r^2} = \frac{\mu_0}{4\pi}\frac{I dl \sin{\alpha}}{b} => B_4 = B_5 = \int_{\frac{\pi}{2}}^{\frac{3\pi}{4}} \frac {\mu_0 d\alpha \sin{\alpha}}{4\pi b} = \frac{\mu_0 I}{4 \pi b}(\cos \frac{\pi}{2} - \cos \frac{3\pi}{4}) = \frac{\mu_0 I}{4 \sqrt{2} \pi b}$$

$$B_0 = 2B_4 + B_1 = \frac{\mu_0 I}{4 \pi} (\frac{3\pi}{2a}+\frac{\sqrt{2}}{b})$$

