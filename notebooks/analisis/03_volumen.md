## 3. Volumen del sistema
Se establece la igualdad entre la derivada del volumen del sistema con respecto al tiempo $t$, y la integral de flujo del campo vectorial $\vec{F}$ sobre la superficie $S(t)$
$$
\frac{dV(t)}{dt} = \oint_{S(t)} \vec{F} \cdot d\vec{S}
$$

Y haciendo uso del teorema de divergencia de Gauss, dicha integral de flujo es igual a la integral de la divergencia del campo vectorial a lo largo del volumen $V(t)$:

$$
\oint_{S(t)} \vec{F} \cdot dS = \oint_{V(t)} \Big(\,\nabla \cdot \vec{F} \,\Big) dV
$$

Por lo que se puede afirmar:
$$
\frac{dV(t)}{dt} = \oint_{V(t)} \Big(\,\nabla \cdot \vec{F} \,\Big) dV
$$

Adicionalmente se estableció en la sección anterior, que la divergencia del campo vectorial $\vec{F}$ es una constante negativa dada por:

$$
\nabla \cdot \vec{F} = -\sigma -1 -\beta
$$

Al resolver la integral de volumen con esta constante se tiene:

$$
\frac{dV}{dt} = (-\sigma -1 -\beta)\, V
$$

Finalmente, al resolver esta ecuación diferencial se obtiene una expressión para el volumen del sistema:

$$
\frac{dV}{(-\sigma -1 -\beta)\, V} = dt
$$
$$
\int\frac{dV}{(-\sigma -1 -\beta)\, V} = \int dt
$$
$$
\frac{1}{(-\sigma -1 -\beta)} \ln{V} = t+C
$$
$$
\ln{V} = (-\sigma -1 -\beta)(t+C)
$$
$$
V(t) = C \,e^{(-\sigma -1 -\beta)\, t}
$$

Para $t=0$ y un volumen inicial $V_0$ se tiene se tiene que 

$$
C = V_0
$$

Por lo que el volumen del sistema viene dado por:
$$
V(t) = V_0 \,e^{(-\sigma -1 -\beta)\, t}
$$


De esta expresión se puede observar que el volumen disminuye exponencialmente hacia cero en el tiempo. En consecuencia el sistema se encuentra delimitado a un espacio cada vez menor. Es por esto que el sistema de Lorenz se clasifica como **atractor** para cualquier grupo de parametros $\sigma$, $\rho$ y $\beta$