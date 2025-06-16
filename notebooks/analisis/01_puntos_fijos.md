## 1. Puntos de equilibrio

Un punto de equilibro es aquel que provoca que el sistema no cambie. Lo que se traduce en puntos en donde el campo vectorial $\vec{F}$ del sistema es igual a 0

$$
\vec{F} = 
\begin{bmatrix}
\sigma (y - x) \\
x(\rho - z) - y \\
xy - \beta z
\end{bmatrix}
=\begin{bmatrix}
0 \\
0 \\
0
\end{bmatrix}
\qquad
\sigma, \rho, \beta > 0
$$

es decir:
$$
\begin{cases}
\sigma (y - x) = 0 \\
x(\rho - z) - y = 0 \\
xy - \beta z = 0
\end{cases}
\qquad
\sigma, \rho, \beta > 0
$$
De la primera equación se concluye que: $$1)\space y=x$$\
Al reemplazar este resultado en la segunda equación se obtiene $$2) \space z=\rho - 1$$\
Finalmente al utilizar ambos resultados  1 y 2 en la tercera ecuación y despejar para $x$ o $y$ se obtiene:
$$
y=x=\pm\sqrt{\beta(\rho - 1)}
$$





Por lo que es posible obtener los puntos de equilibrio del sistema a partir de los parametros  $\rho$ y $\beta$. En concreto, los puntos:
$$
\bigg(\sqrt{\beta(\rho - 1)}, \sqrt{\beta(\rho - 1)}, \rho - 1 \bigg)
$$
$$
\bigg(-\sqrt{\beta(\rho - 1)}, -\sqrt{\beta(\rho - 1)}, \rho - 1 \bigg)
$$

Debe notarse la influencia del parametro $\rho$ en los puntos de equilibro.\
* Para valores de $\rho < 1$ se obtendran soluciones complejas con parte real 0 para las coordenadas $x$ y $y$.
* Para $\rho = 1$ se obtiene el origen $(0,0,0)$ como único punto de equilibrio. Sin embargo debe notarse que el origen es siempre un punto de equilibro sin importar los valores de los parametros del sistema.
