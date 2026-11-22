## 3.356
![[p10hw 356.png]]
$$\begin{aligned} &L_1 = L_2 = L \\ &L_{\text{посл}} = ?, \quad L_{\text{пар}} = ? \end{aligned}$$

**а) Последовательное соединение**
При последовательном соединении ток через обе катушки одинаков ($I_1 = I_2 = I$), а общие магнитный поток, ЭДС самоиндукции и энергия магнитного поля складываются (взаимной индуктивностью пренебрегаем):
$$\begin{aligned} &\Phi_{\text{общ}} = \Phi_1 + \Phi_2 \\ &L_{\text{посл}} I = L I + L I = 2LI \\ &L_{\text{посл}} = 2L \end{aligned}$$
_(Через энергию: $W_M = W_1 + W_2 \Rightarrow \frac{L_{\text{посл}}I^2}{2} = \frac{LI^2}{2} + \frac{LI^2}{2} \Rightarrow L_{\text{посл}} = 2L$)
**б) Параллельное соединение**
При параллельном соединении на катушках одинаковая разность потенциалов (ЭДС самоиндукции $\mathcal{E}_{si1} = \mathcal{E}_{si2} = \mathcal{E}_{si}$), а общий ток делится ($I = I_1 + I_2$):
$$\begin{aligned} &\mathcal{E}_{si} = -L_{\text{пар}}\frac{dI}{dt} = -L\frac{dI_1}{dt} = -L\frac{dI_2}{dt} \\ &\frac{dI}{dt} = \frac{dI_1}{dt} + \frac{dI_2}{dt} \\ &\frac{\mathcal{E}_{si}}{L_{\text{пар}}} = \frac{\mathcal{E}_{si}}{L} + \frac{\mathcal{E}_{si}}{L} = \frac{2\mathcal{E}_{si}}{L} \\ &\frac{1}{L_{\text{пар}}} = \frac{2}{L} \Rightarrow L_{\text{пар}} = \frac{L}{2} \end{aligned}$$
_(Через энергию: при одинаковых катушках $I_1 = I_2 = \frac{I}{2}$, тогда $W_M = W_1 + W_2 \Rightarrow \frac{L_{\text{пар}}I^2}{2} = 2 \cdot \frac{L(I/2)^2}{2} = \frac{LI^2}{4} \Rightarrow L_{\text{пар}} = \frac{L}{2}$)_
**Ответ:** а) $2L$; б) $\frac{L}{2}$.