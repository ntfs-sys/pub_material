## №3.320
Дано:
$$R, \tau, Ф = at(\tau - t)$$
Найти:
Q - ?

Решение:
$$\epsilon = -\frac{dФ}{dt} = -\frac{d}{dt}(at\tau - at^2) = -a\tau+2at = a(2t-\tau)$$

$$I = \frac{\epsilon}{R} = \frac{a(2t - \tau)}{R}$$
$$dQ = I^2Rdt$$
$$\int^\tau_0 dQ = \frac{a^2(2t - \tau)^2}{R}dt$$

$$Q = \frac{a^2}{R}\int^\tau_0 (4t^2-4t\tau+\tau^2)dt=\frac{a^2}{R}[\frac{4t^3}{3}-2t^2\tau+\tau^2t]|_0^\tau = \frac{a^2\tau^3}{3R}$$