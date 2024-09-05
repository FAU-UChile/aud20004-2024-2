# clase-06

jueves 12 septiembre 2024

unidad 4: dinámica y cinemática de cuerpo rígido

- supuestos para cuerpos puntuales
- supuestos para cuerpos rígidos
- movimiento angular
- torque
- torques nulos
- aplicaciones de torque: puerta y manilla
- aplicaciones de torque: palanca
- aplicaciones de torque: balancín

## supuestos para cuerpos puntuales

hasta ahora, en cinemática, dinámica, energía y trabajo, hemos utilizado los siguientes supuestos:

- los cuerpos no tienen volumen
- los cuerpos pueden ser resumidos como su posición en el espacio, y su masa.
- aceleración de gravedad es constante en la tierra e igual a 10 metros / segundos cuadrados.
- no hay atmósfera y por lo tanto, no hay roce.

## supuestos para cuerpos rígidos

primero definamos un cuerpo rígido: definición de cuerpo rígido: un cuerpo rígido tiene una masa constante y un volumen sólido e indeformable.

en la clase de hoy, veremos cuerpos rígidos por lo que los supuestos que usaremos son:

- los cuerpos tienen masa distribuida en un volumen
- aceleración de gravedad es constante en la tierra e igual a 10 metros / segundos cuadrados.
- no hay atmósfera y por lo tanto, no hay roce.

## movimiento angular

como nuestros cuerpos ahora no son puntos, sino que son volúmenes, pueden rotar.

en vez de medir su desplazamiento lineal como una distancia metros, vamos a medir su desplazamiento angular en radianes.

una vuelta completa es 360 grados, lo que equivale a 2 por Pi radianes.

$$360^{\circ} = 2 \cdot \pi \cdot radianes$$

$$ángulo = \theta(t)$$

similarmente a la velocidad lineal, que es la diferencia de posición en el tiempo, la velocidad angular es la diferencia de posición angular en el tiempo y la anotamos con la letra griega omega minúscula.

$$\omega(t) = \frac{\Delta \theta}{\Delta t}$$

comparemos las ecuaciones de velocidad lineal y velocidad angular:

$$v(t) = v_0 + a \cdot t$$

$$\omega(t) = \omega_0 + \alpha \cdot t$$

notar que aceleración angular la anotamos con la letra griega alpha.

## torque

el torque lo anotamos con la letra griega tau.

$$\tau = torque$$

el torque es el producto entre estos 3 términos:

- r = radio o distancia entre el punto y su centro de rotación, medida en metros.
- F = fuerza aplicada en el punto, medida en Newton.
- sin(ángulo) = ángulo entre r y F.

y la ecuación resulta:

$$\tau = r \cdot F \cdot sin(\theta)$$

la unidad en la que se mide torque es Newton por metro, lo que simboliza fuerza aplicada sobre un radio o brazo.

veamos los casos extremos cuando el torque es nulo (cero).

## torques nulos

a partir de la ecuación de torque

$$\tau = r \cdot F \cdot sin(\theta)$$

distinguimos que en estos casos el torque es nulo:

- r = 0: la distancia entre la aplicación de la fuerza y su centro de rotación es cero.
- F = 0: la fuerza aplicada es nula.
- sin(ángulo) = 0, esto ocurre cuando el ángulo es 0 o 180 grados (Pi radianes), o múltiplos.

## aplicaciones de torque: puerta y manilla

por qué la manilla de la puerta está en el extremo opuesto al centro de rotación?

- porque así maximizamos el torque, con el radio o distancia siendo máximo.
- si pusieramos la manilla al medio de la puerta, tendríamos que ejercer el doble de fuerza para lograr el mismo torque que en el extremo.
- si pusieramos la manilla en el eje de rotación, el brazo sería cero, y sin importar la fuerza, no habría torque y con eso no podríamos abrir la puerta.
- si hacemos la fuerza paralela a la distancia r, en vez de perpendicular, el ángulo entre ambos es 0 o 180 grados, y con eso sin(ángulo) es 0, y la puerta no gira en torno a su eje de rotación.

## aplicaciones de torque: palanca

si tenemos una barra que usamos como palanca, y la barra mide 75 cm, y aplicamos en su extremo una fuerza de 25 N, en un ángulo de 45 grados, cuánto es el torque que aplicamos?

de la ecuación de torque

$$\tau = r \cdot F \cdot sin(\theta)$$

podemos reemplazar

$$\tau = 0.75 \cdot m \cdot 25 \cdot N \cdot sin(45^{\circ})$$

y calcular

$$\tau = \frac{3}{4} \cdot 25 \cdot \frac{\sqrt(2)}{2} \cdot N \cdot m $$

y aproximando:

$$\tau \approx 13.26 \cdot N \cdot m $$

## aplicaciones de torque: balancín

en un balancín, tendremos una barra de un cierto largo L, que puede girar en torno a su punto medio, y podemos hacer fuerzas a ambos lados del punto medio, para hacerlo girar, y podemos revisar hacia dónde va a girar, o si va a estar equilibrado.

por ejemplo:

si tenemos un balancín de largo 10m, y hacemos a su lado izquierdo una fuerza perpendicular de 4N, a una distancia de 3m del centro de rotación, cuánto torque recibe el balancín?

de la ecuación de torque

$$\tau_1 = r \cdot F \cdot sin(\theta)$$

podemos reemplazar

$$\tau_1 = 3 \cdot m \cdot 4 \cdot N \cdot sin(90^{\circ})$$

y desarollando

$$\tau_1 = 12 \cdot N \cdot  m$$

como esta fuerza ejerce este torque sobre el balancín, va a girar. si queremos contrarrestar ese torque para que quede en equilibrio, podemos hacer una fuerza al otro lado de la barra, que la haga girar en dirección contraria.

podemos preguntarnos, qué fuerza F se necesita hacer en ángulo 90 grados y a 1m del centro de rotación del otro lado del balancín para contrarrestar el torque de 12 Nm?

de la ecuación de torque

$$\tau_2 = r \cdot F \cdot sin(\theta)$$

podemos reemplazar:

$$12 \cdot N \cdot m = 1 \cdot m \cdot X \cdot N \cdot sin(90^{\circ})$$

dividimos a ambos lados por Nm:

$$12 = X  \cdot sin(90^{\circ})$$

y como sin(90 grados) es igual a 1:

$$X = 12$$

con esto, necesitamos una fuerza de 12 N en 90 grados y a 1m del centro de rotación para contrarrestar el torque y que el sistema balancín quede en equilibrio y no gire.

notamos que esta fuerza de 12 N es mayor que la que está al otro lado del balancín que es de 4N, ya que el torque es directamente proporcional tanto a la distancia como a la fuerza.

$$\tau = r \cdot F \cdot sin(\theta)$$

entonces si distancia o fuerza aumentan, el torque también aumenta.

y si queremos mantener un torque constante, a mayor distancia menos fuerza, y viceversa, a menor distancia mayor fuerza.

## referencias

- <https://www.cliffsnotes.com/study-guides/physics/classical-mechanics/rotational-motion-of-a-rigid-body>
- <https://www.khanacademy.org/science/high-school-physics#torque-and-angular-momentum>
