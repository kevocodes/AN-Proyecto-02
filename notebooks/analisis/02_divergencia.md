## 2. Divergencia del campo vectorial

La divergencia indica la *densidad* de un campo vectorial. Es decir, en que medida el campo se "dispersa" o "concentra" alrededor de un punto.


Para un campo vectorial $\vec{F}(x,y,z)$, esta operacion se define de la siguiente manera:

$$
\nabla \cdot \vec{F} = \frac{\delta F_x}{\delta x} + \frac{\delta F_y}{\delta y} + \frac{\delta F_z}{\delta z}
$$
Donde:
* $\vec{F}$ es el campo vectorial
* $F_x$, $F_y$ y $F_z$ son las componente de $\vec{F}$

Dependiendo del valor de divergencia se esperan 3 casos para un punto $p=(x_0, y_0, z_0)$:
| $\nabla \cdot \vec{F}(x_0,y_0,z_0)$ | Interpretación                     |
|------------------------|-------------------------------------------------|
| < 0                    | El campo aumenta su densidad alrededor de $p$   | 
| = 0                    | El campo mantiene su densidad alrededor de $p$  |
| > 0                    | El campo disminuye su densidad alrededor de $p$ |


Para el **atractor de Lorenz**  la divergencia viene dada por:

$$
\vec{F} = 
\begin{bmatrix}
\sigma (y - x) \\
x(\rho - z) - y \\
xy - \beta z
\end{bmatrix}
\qquad
\sigma, \rho, \beta > 0
$$

$$
\frac{\delta F_x}{\delta x} = \frac{\delta}{\delta x} \bigg[ \sigma (y - x) \bigg] = -\sigma
$$
$$
\frac{\delta F_y}{\delta y} = \frac{\delta}{\delta y} \bigg[ x(\rho - z) - y \bigg] = -1
$$
$$
\frac{\delta F_z}{\delta z} = \frac{\delta}{\delta z} \bigg[ xy - \beta z \bigg] = -\beta
$$

$$
\nabla \cdot \vec{F} = -\sigma -1 -\beta
$$

El valor de divergencia del sistema es dependiente únicamente de los parametros $\sigma$ y $\beta$. Y al estar estos parametros restringidos a valores positivos, la divergencia para será **negativa para cualquier punto** $(x,y,z)$. 

Esto indica un campo vectorial $\vec{F}$ *denso* para todo el sistema. Esto se traduce en que a pesar de la naturaleza caótica del sistema, sus trayectorias estarán restringidas a un espacio reducido.