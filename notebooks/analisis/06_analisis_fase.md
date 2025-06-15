## 6. Análisis de fase del sistema

#### a. Jacobiano del sistema
Se calcula el Jacobiano del campo vectorial:

$$
A(x,y,z) =
\begin{bmatrix}
-\sigma & \sigma & 0 \
\rho - z & -1 & -x \
y & x & -\beta
\end{bmatrix}
$$

#### b. Análisis global
Análisis local en el origen $( p = (0,0,0) )$

Los autovalores en ese punto son:

$$
[
\lambda1 = -\beta, \quad
\lambda{\pm} = \frac{-1 - \sigma \pm \sqrt{4\rho\sigma + (\sigma - 1)^2}}{2}
]
$$

Dependiendo de $( \rho )$, el origen cambia de tipo:

Si $( 0 < \rho < 1 )$: el origen es un sumidero (estable).

Si $( \rho = 1 )$: ocurre una bifurcación de horquilla.

Si $( \rho > 1 )$: el origen es un punto silla (inestable).

#### c. Simetría
El sistema es simétrico respecto al origen en los planos $( x, y )$: si $( (x(t), y(t), z(t)) )$ es una solución, entonces también lo es $( (-x(t), -y(t), z(t)) )$. Esto explica la existencia de pares de puntos fijos ( $q_\pm$ ).
