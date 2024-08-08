# clase-03

jueves 22 agosto 2024

## repaso clase anterior y programa hoy

la clase anterior repasamos conceptos básicos de matemática, incluyendo:

- escalares
- vectores
- fuerzas
- Leyes de Newton
- ley de gravitación universal

la clase de hoy es la unidad 1: cinemática en 1 y 2 dimensiones

- definición de cinemática
- ecuación de velocidad en 1D
- ecuación de velocidad en 2D
- ecuación de posición en 1D
- ecuación de posición en 2D

## definición de cinemática

en cinemática, describiremos y modelaremos los vectores de posición x, velocidad v y de aceleración a de cuerpos, sin importar las fuerzas ni las causas de estos movimientos.

## notación en cinemática

en 1D:

- posición: x(t), medida en m
- velocidad: v(t), medida en m/s
- aceleración: a(t), medida en m/s^2

en 2D:

- posición: vector x(t), descomponemos en x(t), y(t).
- velocidad: vector v(t), descomponemos en vx(t), vy(t).
- aceleración: vector a(t), descomponemos en ax(t), ay(t).

adicionales:

$$\Delta = Delta = final - inicial$$

## supuestos y simplificaciones de cinemática

- un cuerpo se puede describir con una posición en un punto
- en ese punto, está toda la masa del cuerpo

## relaciones entre posición, velocidad y aceleración

aceleración es cambio de velocidad en el tiempo, entonces por definición:

$$a(\Delta t) = \frac{\Delta v}{\Delta t} = \frac{v_2 - v_1}{t_2 - t_1}$$

donde Delta significa diferencia, y la ecuación anterior se lee como la aceleración en una ventana de tiempo, es igual a la variación de velocidad en esa ventana de tiempo, dividida por la ventana de tiempo.

velocidad es cambio de posición el tiempo, entonces por definición:

$$v(\Delta t) = \frac{\Delta x}{\Delta t} = \frac{x_2 - x_1}{t_2 - t_1}$$

## ecuación de aceleración en una dimensión (1D)

en este curso simplificaremos nuestros cálculos, usando una aceleración promedio, que notaremos como a y es una constante, entonces:

$$
a(t) = a
$$

nuestra aceleración será un número constante, y no dependerá del tiempo, o en otras palabras, tendrá el mismo valor para todo instante de tiempo.

## ecuación de velocidad en una dimensión (1D)

si conocemos la aceleración promedio a en un instante, podemos usar como ventana de tiempo el tiempo entre origen t=0s y ese instante, y así escribir la aceleración en ese instante de tiempo entre ellos como:

$$a =  \frac{v(t) - v(t_0)}{t - t_0}$$

podemos simplificar ya que sabemos que el instante inicial es 0s:

$$a = \frac{v(t) - v(t_0)}{t}$$

y sabemos que la velocidad inicial en el instante t=0, es una constante, que podemos llamar v sub 0, entonces:

$$
a = \frac{v(t) - v_0}{t}
$$

y despejando la velocidad v(t), tenemos la ecuación de velocidad:

$$v(t) =  v_0 + a \cdot t$$

nota: velocidad se mide en metros / segundo.

## ecuación de posición en una dimensión (1D)

la posición x(t) en el instante de tiempo t, es igual a la posición inicial $x_0$ más el producto entre la velocidad promedio v y el tiempo t.

$$
x(t) = x_0 + v_{promedio} \cdot t
$$

a su vez, la velocidad promedio la podemos plantear como:

$$
v_{promedio} =  \frac{v(t) + v_0}{2}
$$

y a su vez, podemos escribir $v(t)$ en función de de la velocidad inicial y la aceleración:

$$
v_promedio =  \frac{(v_0 + a \cdot t) + v_0}{2} = v_0 + \frac{a \cdot t}{2}
$$

y reemplazando en la ecuación de posición x(t) resulta en:

$$
x(t) = x_0 + (v_0 + \frac{a \cdot t}{2}) \cdot t
$$

y desarrollando:

$$
x(t) = x_0 + v_0 \cdot t + \frac{1}{2} a \cdot t^2
$$

## resumen cinemática en 1D

con aceleración promedio a, podemos escribir las ecuaciones de posición y aceleración asi:

$$x(t) = x_0 + v_0 \cdot t + \frac{1}{2} \cdot a \cdot t^2$$

$$v(t) = v_0 + a \cdot t$$

## ecuación de velocidad en 2D

en 2D basta con tomar la ecuación de 1D y reemplazar por vectores:

$$\vec{v}(t) = \vec{v_0} + \vec{a} \cdot t$$

y descomponiendo en componentes x e y, tenemos el sistema:

$$v_{x}(t) = v_{x0} + a_{x} \cdot t$$

$$v_{y}(t) = v_{y0} + a_{y} \cdot t$$

## ecuación de posición en 1D

en 2D basta con tomar la ecuación de 1D y reemplazar por vectores:

$$\vec{x}(t) = \vec{x_0} + \vec{v_0} \cdot t + \frac{1}{2} \vec{a} \cdot t^2$$

y descomponiendo en los ejes x e y:

$$x(t) = x_0 + v_{x0} \cdot t + \frac{1}{2} a_{x} \cdot t^2$$

$$y(t) = y_0 + v_{y0} \cdot t + \frac{1}{2} a_{y} \cdot t^2$$

## resumen cinemática en 2D

podemos escribir las ecuaciones de posición y aceleración asi:

$$x(t) = x_0 + v_{x0} \cdot t + \frac{1}{2} a_{x} \cdot t^2$$

$$y(t) = y_0 + v_{y0} \cdot t + \frac{1}{2} a_{y} \cdot t^2$$

$$v_{x}(t) = v_{x0} + a_{x} \cdot t$$

$$v_{y}(t) = v_{y0} + a_{y} \cdot t$$

## comentarios matemáticos sobre estas ecuaciones físicas

las ecuaciones de velocidad en 1D y 2D del estilo:

$$v(t) = v_{0} + a \cdot t$$

las podemos pensar como ecuaciones con variable independiente $t$, donde v es la variable dependiente de t, y donde:

- la aceleración es la pendiente de la ecuación, por lo tanto su signo nos dice si la velocidad aumenta, disminuye o es constante con el paso del tiempo
- la velocidad inicial: intercepto de la recta v(t) con el eje vertical, donde t=0, nos dice la velocidad inicial.

a su vez, si analizamos las ecuaciones de posición en 1D y 2D del estilo:

$$x(t) = x_0 + v_0 \cdot t + \frac{1}{2} a \cdot t^2$$

podemos ver que

- la posición inicial $x_0$ es el intercepto de la recta x(t) con el eje vertical, donde t=0, nos dice la posición inicial.
- la velocidad inicial $v_0$ es la pendiente de la recta x(t) en el instante t=0, nos dice la velocidad inicial.

y si nos concentramos en la variable t de tiempo, recordemos que:

- t está multiplicando a la velocidad inicial, y que t al cuadrado está multiplicando a la aceleración
- por lo tanto, si analizamos cuando t es muy muy grande (positivo o negativo), el término aceleración por tiempo al cuadrado será el dominante.

## movimiento circular

consideración:

- consideramos una superficie en forma de disco
- se mueve con velocidad angular constante
- nos centramos en un radio del disco, todo ese radio avanza y pasa por el origen con regularidad (periodo T).
- pero un cuerpo a $\frac{R}{2}$ del centro, se más lento que un cuerpo en $R$.

la ecuación es:

$$
v = \omega \cdot r
$$

donde

- $v$ es velocidad, se mide en $\frac{m}{s}$
- $\omega$ es velocidad angular, se mide en $\frac{radianes}{s}$
- $r$ es radio, se mide en $m$

si tenemos una velocidad angular constante, podemos plantear esta ecuación como:

$$
\omega = \frac{v}{r}
$$

donde $v$ es directamente proporcional a $r$, entonces con velocidad angular constante, a mayor radio, mayor velocidad.

por lo tanto, un cuerpo muy cerca del centro va más lento que uno a mayor distancia.

eso aplica a las canchas para correr, donde a la personas que corren más fuera del centro se les da una ventaja, y después durante la carrera se les permite a todes ir al centro, para que corran la misma distancia.

## referencias

- <https://openstax.org/details/books/university-physics-volume-1>
- <https://www.cliffsnotes.com/study-guides/physics/classical-mechanics/kinematics-in-one-dimension>
