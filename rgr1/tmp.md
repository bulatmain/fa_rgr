 Задано:

$$
k = 3, \quad L = 15
$$

Функция $x(t)$:

$$
x(t) =
\begin{cases}
    x(3t) + \sin(5t), & 0 \leq t \leq \frac{1}{3} \\
    x(3t-2), & \frac{1}{3} \leq t \leq \frac{2}{3} \\
    x(3t-2) + \sin(3t - 6), & \frac{2}{3} \leq t \leq 1
\end{cases}
$$

Разность $T(x) - T(y)$:

$$
\max \left( x(3t) + \sin(5t) - y(3t) - \sin(5t) \right)
$$

 Максимум:

$$
\max \left( x(t) - y(t), 0 \leq t \leq 1 \right) = \frac{1}{4}
$$

Функция $x_n(t)$:

$$
x_n(t) = 
\begin{cases}
    t, & 0 \leq t \leq \frac{1}{3} \\
    2 - 3t, & \frac{1}{3} \leq t \leq \frac{2}{3} \\
    3t - 2 + \sin(3\pi t), & \frac{2}{3} \leq t \leq 1
\end{cases}
$$

Оценка нормы разности:

$$
\| x_n - x_0 \| \leq \frac{1}{n}
$$

Выражение с косинусом:

$$
\left| t^2 - 2t + \cos(8\pi t) \right|
$$

Приближение через логарифм:

$$
\lambda - 1 = \log_u \frac{20}{27}
$$

Рассчитанные значения:

$$
\lambda - 1 = -0.216, \quad \lambda = 1
$$
