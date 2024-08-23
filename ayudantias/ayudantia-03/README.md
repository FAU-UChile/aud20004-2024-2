# ayudantía-04

viernes 05 abril 2024

## resumen

### vectores

un vector es un objeto geométrico que representa una dirección y un sentido dentro de un sistema de coordenadas. En general se representa como una flecha.

el vector de dos dimensiones $\vec{V}$ de coordenadas $(V_x, V_y)$ se grafica de la siguiente manera:

![Alt text](./img/vec.JPG)

#### modulo, magnitud o amplitud de un vector $||\vec{V}||$

el módulo o amplitud de un vector nos dice su tamaño.

$$||\vec{V}|| = \sqrt{V_x^2 + V_y^2}$$

#### componentes de un vector

teniendo el ángulo de un vector y su magnitud es posible calcular las componentes del vector utilizando trigonometría.

$$\vec{F} = (F \cdot cos(\alpha), F \cdot sen(\alpha))$$

![Alt text](./img/vector_fuerza.jpg)

### movimiento uniformemente acelerado en 2D

#### vector aceleración constante en el tiempo

$$\vec{a}(t) = (a_x, a_y) \ [m/s^2]$$

#### vector velocidad en el tiempo

$$\vec{v}(t) = \vec{v_0} + \vec{a} \cdot t$$

#### vector pósición en el tiempo

$$\vec{x}(t) = \vec{x_0} + \vec{v_0} \cdot t + \frac{1}{2} \vec{a} \cdot t^2$$

### dinámica en 2D

#### segunda ley de Newton vectorial

$$\vec{F} = m \cdot \vec{a}$$

### diagrama de cuerpo libre

recomiendo revisar los siguientes videos del canal de Youtube _["Susi Profe"](https://www.youtube.com/@SusiProfe):_

- [Fuerzas que actúan sobre un cuerpo](https://www.youtube.com/watch?v=L4KYnv2R2GU)

- [Fuerza peso](https://www.youtube.com/watch?v=J8pumn0d56A)

- [Calcular fuerza resultante](https://www.youtube.com/watch?v=m0_gQ9RBUZc)

- [Suma de fuerzas por componentes rectangulares](https://www.youtube.com/watch?v=WMy8Y72EDVs)

### fuerza normal

Es la fuerza que impide que los cuerpos se hundan en la superficie en que están sostenidos. Aparece por consecuencia de la tercera ley de newton (acción y reacción).

En una superficie plana, la fuerza normal es igual a la fuerza peso del cuerpo.

$$\vec{N} = \vec{W}$$

Si estamos en un plano inclinado, la normal es igual a la componente del "vector peso", perpendicular a la superficie de contacto.

$$\vec{N} = \vec{W_y}$$

### fuerza de roce estático y dinámico

la fuerza de roce $F_r$ es una fuerza que se opone al movimiento de los cuerpos. Es igual a un porcentaje de la fuerza normal. este porcentaje se le conoce como coeficiente de roce y suele escribirse con la letra $\mu$.

$$\vec{F_r} = \mu \cdot \vec{N}$$

la fuerza de roce cambia si el cuerpo está estático o ya está en movimiento. el coeficiente de roce estático $\mu_e$ suele ser mayor que el coeficiente de roce dinámico $\mu_d$.

## ejercicio-01

si una pelota de basketball se mueve a una velocidad constante de $\vec{v} = (2, 3) [m/s]$, responda:

- ¿cuál es su velocidad en el eje $\hat{x}$ de coordenadas?

- ¿cuál es su velocidad en el eje $\hat{y}$ de coordenadas?

- ¿en qué eje de coordenadas se desplazará más rápido?

- calcule la velocidad lineal de la pelota.

### solución-ejercicio-01

- su velocidad en el eje $\hat{x}$ es de $2 [m/s]$.

- su velocidad en el eje $\hat{y}$ es de $3 [m/s]$.

- se desplazará más rápido en el eje $\hat{y}$ (hacia arriba).

- para encontrar la velocidad lineal de la pelota, calculamos la magnitud del vector velocidad:

$$||\vec{v}|| = \sqrt{v_x^2 + v_y^2}$$

$$||\vec{v}|| = \sqrt{2^2 + 3^2}$$

$$||\vec{v}|| = \sqrt{4 + 9}$$

$$||\vec{v}|| = \sqrt{13}$$

$$||\vec{v}|| \approx 3.605 \ [m/s]$$

## ejercicio-02

si una pelota de tenis de $50[g]$ es golpeada con una fuerza de $20 N$ con un ángulo de incidencia $60°$.

- calcule el vector fuerza ejercido a la pelota al momento de ser golpeada.

- ¿en qué eje de coordenadas recibe mayor fuerza?

- calcule el vector aceleración ejercida en la pelota al momento de ser golpeada.

- calcule la aceleración lineal ejercida en la pelota al momento de ser golpeada.

### solución-ejercicio-02

- para calcular el vector fuerza utilizamos trigonometría:

$$\vec{F} = (F \cdot cos(\alpha), F \cdot sen(\alpha))$$

$$\vec{F} = (20 N \cdot cos(60°), 20 N \cdot sen(60°))$$

$$\vec{F} \approx (10, 17.32) N$$

- por lo tanto, recibe una fuerza mayor en el eje $\hat{y}$ (hacia arriba).

- para calcular la aceleración, aplicamos la versión vectorial de la segunda ley de newton:

$$\vec{F} = m \cdot \vec{a}$$

$$\vec{a} = \frac{\vec{F}}{m}$$

$$\vec{a} = \frac{(10, 17.32) N}{50[g]}$$

$$\vec{a} = \frac{(10, 17.32) N}{0.05[kg]}$$

$$\vec{a} = \left(\frac{10 N}{0.05 kg}, \frac{17.32 N}{0.05 kg }\right)$$

$$\vec{a} = (200[m/s^2], 346[m/s^2])$$

$$\vec{a} = (200, 346) \ [m/s^2]$$

- la aceleración lineal se calcula con el módulo del vector aceleración:

$$||\vec{a}|| = \sqrt{a_x^2 + a_y^2}$$

$$||\vec{a}|| = \sqrt{200^2 + 346^2}$$

$$||\vec{a}|| \approx 400 [m/s^2]$$

## ejercicio-03

una bola de billar de $150[g]$ experimenta una aceleración vectorial constante $\vec{a} = (1,2)\cdot \frac{m}{s^2}$.

- calcule el vector fuerza que experimenta.

- asumiendo que la bola de billar parte en la posición $x = (0,0) \cdot m$ y velocidad $\vec{v} = (0,0) \frac{m}{s}$, calcule el vector posición de la bola de billar en $t = 2 s$.

### solución-ejercicio-03

- el vector fuerza se calcula utilizando la versión vectorial de la segunda ley de newton:

$$\vec{F} = m \cdot \vec{a}$$

$$\vec{F} = 150 g \cdot (1,2)\cdot \frac{m}{s^2}$$

$$\vec{F} = 0.150 kg \cdot (1,2) \cdot \frac{m}{s^2}$$

$$\vec{F} = (0.150 \cdot kg, 2 \cdot 0.150 \cdot kg) \cdot \frac{m}{s^2}$$

$$\vec{F} = (0.150, 0.3) \cdot kg \cdot \frac{m}{s^2}$$

$$\vec{F} = (0.150, 0.3) \cdot N$$

- el vector posición en $t=2[s]$ utilizamos las fórmulas del movimiento uniformemente acelerado pero ahora de forma vectorial.

$$\vec{x}(t) = \begin{pmatrix}x*{1*{inicial}} + v*{1*{inicial}} \cdot t + \frac{1}{2} \cdot a*1 \cdot t^2 \\ x*{2*{inicial}} + v*{2\_{inicial}} \cdot t + \frac{1}{2} \cdot a_2 \cdot t^2 \end{pmatrix}$$

$$\vec{x}(2[s]) = \begin{pmatrix}0 + 0 \cdot 2[s] + \frac{1}{2} \cdot 1[m/s^2] \cdot (2[s])^2 \\ 0 + 0 \cdot 2[s] + \frac{1}{2} \cdot 2[m/s^2] \cdot (2[s])^2  \end{pmatrix}$$

$$\vec{x}(2[s]) = \begin{pmatrix}\frac{1}{2} \cdot 1[m/s^2] \cdot 4[s^2] \\ \frac{1}{2} \cdot 2[m/s^2] \cdot 4[s^2]  \end{pmatrix}$$

$$\vec{x}(2[s]) = \begin{pmatrix}2[m] \\ 4[m] \end{pmatrix}$$

## ejercicio-04

en un plano inclinado de $30°$ se abandona un cuerpo que empieza a caer lentamente. el coeficiente de rozamiento entre el plano y el objeto es de $\mu = 0.2$.

calcule la aceleración del cuerpo.

### solución-ejercicio-04

![Alt text](./img/ayud04-ej04.jpg)
