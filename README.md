Activation Function:
$$
\sigma^{(i)}=e^{\theta^{\top} \bold x^{(i)}}-1
$$
Cost Function:
$$
J(\theta)= \prod_{i=1}^{m}(\frac{\sigma^{(i)}}{\bold y^{(i)}})^{\frac{1}{m}}
$$
When $\sigma=\bold y$, $J=1$
To find the derivative:
$$
ln(J_\theta) = {\frac 1m}\sum_{i=1}^{m}{ln({\sigma^{(i)})}-{\frac 1m}\sum_{i=1}^{m}ln({y^{(i)})}}
$$
$$
\frac{\partial J_\theta}{\partial\theta_i}={J(\theta)}{\frac 1m}\sum_{i=1}^{m}{\frac {x^{(i)}}{h_\theta(x^{(i)})}}
$$
