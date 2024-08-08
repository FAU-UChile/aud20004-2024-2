# clase-01

jueves 08 agosto 2024

en el curso anterior de matemáticas aprendimos a describir coordenadas, superficies, figuras, etc.

preguntas para estudiantes:

- qué aprendieron nuevo el semestre pasado?
- qué fue lo más emocionante?
- qué fue lo más difícil?
- qué quieren aprender este semestre?

hoy haremos una breve introducción a artistas, diseñadoras y proyectos como inspiración para este curso de física.

## fundamentos de matemática

- sistemas de ecuaciones
- ecuaciones cuadráticas
- sistemas de coordenadas
- unidades de medida
- sistema métrico e imperial
- wolfram alpha <https://www.wolframalpha.com/>

## aplicaciones de la física en el diseño

este semestre aprenderemos los fundamentos de física necesarios para su práctica de diseñadores, incluyendo temas como:

- modelamiento matemático del mundo físico
- cinemática y dinámica
- electricidad y magnetismo
- percepción humana de sonido, luz y calor

## presentación equipo docente

- aarón montoya-moraga <https://montoyamoraga.io/> <https://github.com/montoyamoraga/>
- NYU ITP <https://tisch.nyu.edu/itp>
- Processing <https://processing.org/>
- p5.js <https://p5js.org/>
- School of machines <https://www.schoolofma.org/>
- Opera of the future <https://www.media.mit.edu/groups/opera-of-the-future/>
- Future sketches <https://www.media.mit.edu/groups/future-sketches/>
- Sinestesia <https://www.sinestesia.cc/>
- Diseño UDP <https://diseno.udp.cl/>

- andrés martin
- Diseño UChile

## inspiraciones varias

- Ada Lovelace <https://es.wikipedia.org/wiki/Ada_Lovelace>
- Andreas Refsgaard <https://andreasrefsgaard.dk/>
- Ciat-Lonbarde <https://www.ciat-lonbarde.net/>
- Constanza Piña <https://es.wikipedia.org/wiki/Constanza_Pi%C3%B1a>
- Crank Sturgeon <https://cranksturgeon.com/>
- CW&T <https://cwandt.com/>
- Delight Lab <https://www.instagram.com/delight_lab_oficial/>
- Electro Faustus <https://www.electrofaustus.com/>
- Gaurav Patekar <https://www.gauravpatekar.in/>
- Katya Rozanova <https://www.katyarozanova.com/>
- Koma Elektronik <https://koma-elektronik.com/>
- Leo Fender <https://es.wikipedia.org/wiki/Leo_Fender>
- Limor Fried <https://es.wikipedia.org/wiki/Limor_Fried>
- Lisa Jamhoury <https://lisajamhoury.com/>
- Manifold Works <https://manifold.tv/>
- Manoloide <https://www.instagram.com/manoloide/>
- Matt Romein <https://matt-romein.com/>
- Nicole He <https://nicole.pizza/>
- Nicole L'Huillier <https://nicolelhuillier.com/>
- Nikola Tesla <https://es.wikipedia.org/wiki/Nikola_Tesla>
- Perry R. Cook <https://www.cs.princeton.edu/~prc/>
- Rafael Benguria <https://es.wikipedia.org/wiki/Rafael_Benguria>
- Rhizomatiks Research <https://research.rhizomatiks.com/>
- Robert Moog <https://es.wikipedia.org/wiki/Robert_Moog>
- Schorr Guitars <http://schorrguitars.de/>

la clase de hoy es la unidad 0: vectores y fuerzas

- escalares
- vectores
- fuerzas
- 3 leyes de Newton

## escalares

un escalar posee:

- una magnitud, medida en cierta unidad

ejemplos de escalares en fīsica:

- masa, medida en gramos
- distancia, medida en metros
- área, medida en metros cuadrados
- volumen, medido en metros cúbicos
- tiempo, medido en segundos
- temperatura, medida en grados Celsius
- carga eléctrica, medida en Coulomb

## aritmética de escalares

para hacer aritmética (suma, resta, multiplicación y división) entre vectores, basta con trabajar estas cantidades como si fueran números, y respetar las unidades, teniendo mucho cuidado con las equivalencias entre unidades.

## vectores

un vector posee:

- una magnitud, medida en cierta unidad
- una dirección (y un sentido), medida en cierto sistema de referencia

ejemplos de vectores en física:

- posición o desplazamiento, medido en $m$
- velocidad, medida en $\frac{m}{s}$
- aceleración, medida en $\frac{m}{s^2}$

## sistemas de referencia de vectores

si queremos representar cualquier punto en el plano XY, debemos hacer los siguientes pasos:

- definir un origen (0, 0)
- definir dirección y sentido del eje x, llamado vector unitario en x.
- definir dirección y sentido del eje y, llamado vector unitario en y.

$$\hat{x} = vector unitario en x$$

$$\hat{x} = vector unitario en y$$

se llaman vectores unitarios porque su magnitud es 1.

con el sistema cartesiano que hemos usado hasta ahora, en honor a René Descartes, usamos los vectores unitarios x e y, que son perpendiculares entre sí. con ellos podemos describir cualquier posición en el plano, como la siguiente suma:

$$\vec{P} = x \cdot \hat{x} + y \cdot \hat{y}$$

por ejemplo, el punto C en (-11, 3) puede ser descrito así:

$$\vec{C} = (-11, 3) = -11 \cdot \hat{x} + 3 \cdot \hat{y}$$

notar que podemos describir cualquier punto en el plano XY como la suma ponderada de los vectores unitarios x e y porque estos vectores son perpendiculares, y permiten movernos a lo largo de todo el plano.

otra manera de representar el plano es de forma polar, con un vector unitario de radio $\hat{r}$, y un ángulo $\theta$.

para convertir entre coordenadas cartesianas y polares, consideremos el vector P:

$$\vec{P} = (x, y) = x \hat{x} + y \hat{y}$$

si dibujamos la distancia entre el origen y el punto P y le llamamos r, podemos notar que r es la hipotenusa, y los valores de x e y los catetos de un triángulo rectángulo. si llamamos theta al ángulo entre eje X y r, podemos usar las identidades de seno y coseno del triángulo rectángulo.

$$sin(\theta) = \frac{cateto opuesto}{hipotenusa} = \frac{y}{r}$$

$$cos(\theta) = \frac{cateto adyacente}{hipotenusa} = \frac{x}{r}$$

y si despejamos x e y de estas ecucaciones obtenemos las siguientes expresiones para convertir de coordenadas polares a cartesianas:

$$x = r \cdot cos(\theta)$$

$$y = r \cdot sin(\theta)$$

y si queremos hacer lo inverso, convertir de coordenadas a cartesianas, tenemos las ecuaciones:

$$r = \sqrt{x^2 + y^2}$$

$$\theta = atan2(x, y)$$

donde atan2 es una versión especial de la arcotangente

para más info revisar acá: <https://es.wikipedia.org/wiki/Coordenadas_polares>

## aritmética de vectores

### suma y resta de vectores

para sumar y restar vectores, podemos descomponer en distintas coordenadas y tratarlas por separado.

por ejemplo:

$$\vec{A} = 5 \hat{x} + 3 \hat{y} \brack \vec{B} = 7 \hat{x} - 1 \hat{y}$$

si sumamos los vectores A y B obtenemos:

$$\vec{A} + \vec{B} =  (5 \hat{x} + 3 \hat{y}) + (7 \hat{x} - 1 \hat{y}) = (5 + 7) \hat{x} + (3 - 1) \hat{y} = 12 \hat{x} + 2 \hat{y}$$

y si restamos los vectores A y B obtenemos:

$$\vec{A} - \vec{B} = (5 \hat{x} + 3 \hat{y}) - (7 \hat{x} - 1 \hat{y}) = (5 - 7) \hat{x} + (3 - (-1)) \hat{y} = -2 \hat{x} + 4 \hat{y}$$

### multiplicación y división de vectores por escalares

multiplicar y dividir vectores por un escalar, permite escalar cada una de las componentes del vector.

por ejemplo si multiplicamos el vector A por el escalar 5:

$$5 \cdot \vec{A} = 5 \cdot (5 \hat{x} + 3 \hat{y}) = (5 \cdot 5) \hat{x} + (3 \cdot 5) \hat{y} = 25 \hat{x} + 15 {y}$$

y dividir funciona igual, afectando cada componente, por ejemplo si dividimos el vector B por 2:

$$\frac{1}{2} \cdot \vec{B} = \frac{1}{2} (7 \hat{x} - 1 \hat{y}) = \frac{7}{2} \hat{x} - \frac{1}{2} \hat{y} = 3.5 \hat{x} - 0.5 \hat{y}$$

## fuerzas

una fuerza en física es una influencia que puede hacer cambiar el movimiento de un cuerpo.

una fuerza es un vector: tiene una magnitud y una dirección.

las fuerzas se miden en Newton (N), que equivale a:

$$1N = 1\frac{kg \cdot m}{s^2}$$

en la naturaleza conocemos 4 fuerzas fundamentales:

estas 2 tienen un alcance infinito:

- fuerza gravitatoria: atracción entre entre cuerpos con masa.
- fuerza electromagnética: atracción o repulsión entre cuerpos con carga.

estas 2 actúan a corta distancia:

- fuerza nuclear fuerte: mantiene unidos los núcleos atómicos.
- fuerza nuclear débil: escapa de los contenidos de este curso :)

## antes de Newton

Aristóteles (~300 a.C.), postulaba que el estado natural de los cuerpos es el reposo. que para sacarlos del reposo, se le aplica una fuerza, y con esto los cuerpos adquieren velocidad. y que esta relación es directamente proporcional a la masa, resultado en la ecuación ahora desechada por la física:

$$\vec{F} = m \cdot \vec{v}$$

un elemento fundamental que no fue incluido en este modelo, fue la consideración de fuerzas como el roce o fricción. la física de Aristóteles también postulaba que cuando los cuerpos caen en caída libre, los objetos más pesados caen más rápido que los objetos más livianos.

esta observación viene de haber considerado solamente la experiencia de estar dentro de un fluido, en nuestro caso, el aire, la atmósfera. un fluido opone resistencia a la caída libre según la forma o área del cuerpo, y eso ocasiona roce, que se opone a la fuerza de gravedad y hace que distintos objetos caigan a velocidades distintas.

pero en el vacío, todos los cuerpos, independiente de su masa, son solamente afectados por la gravedad, y caen con la misma aceleración.

esta concepción del movimiento duró dos mil años, hasta Newton.

Newton, nacido en 1643, publicó en 1687 su libro "Principios matemáticos de filosofía natural", donde expone sus 3 leyes de movimiento y cambió esta percepción.

## primera ley de Newton: inercia

todos los cuerpos permanecen moviéndose en línea recta a velocidad constante, hasta que se le aplica una fuerza externa.

consecuencias:

- si observamos un objeto descansando en una mesa, está moviéndose en línea recta con velocidad constante, lo que pasa es que esta velocidad es cero.
- si hacemos esta afirmación mientras estamos sin movernos, notamos que estamos asumiendo el planeta como sin moverse, cuando en realidad se está moviendo en torno al sol!
- es relativo, no existe un standard absoluto de reposo, siempre hay que definir un origen y un sistema de coordenadas.

## segunda ley de newton: momentum

momentum (vector p) se define como la cantidad de movimiento, y es el producto entre masa m y velocidad de un cuerpo.

$$\vec{p} = m \cdot \vec{v}$$

el cambio de momentum de un objeto es proporcional a la fuerza aplicada y ocurre en la dirección de la fuerza aplicada. eso en matemáticas, implica que la derivada del momentum es la fuerza, esto es.

$$\vec{F} = \frac{d \vec{p}}{dt} = \frac{d (m \cdot \vec{v})}{dt}$$

si la masa m es constante, podemos simplificar así:

$$\vec{F} =  m \frac{d (\vec{v})}{dt} = m \cdot \vec{a}$$

lo que resulta en que la fuerza es igual al producto entre masa y aceleración.

## tercera ley de newton: acción y reacción

para cada acción siempre hay una opuesta de igual magnitud.

ojo: las fuerzas no se anulan, porque se aplican en cuerpos distintos. ejemplo:

si una pelota está reposando en la superficie de la tierra, la fuerza de gravedad que ejerce la tierra sobre la pelota, tiene su reacción en la fuerza opuesta: la atracción que ejerce la pelota por sobre la tierra.

si la pelota está en reposo, no es porque esas fuerzas se anulen, es porque la fuerza de atracción que ejerce la tierra sobre la pelota, es contrarrestada por la fuerza normal que ejerce la superficie de la tierra sobre la pelota. estas dos fuerzas actuando sobre la pelota se contrarrestan, haciendo que el vector F sea 0, y por lo tanto, aceleración cero, y con eso, velocidad constante.

## ley de gravitación universal de Newton

como ya vimos, existen 4 fuerzas fundamentales de la naturaleza, y en este curso estudiaremos 2: las gravitatoria y la electromagnética.

otro avance que hizo Newton, fue a través de experiencias empíricas, fue definir la ley de gravitación universal, con una ecuación que describe el vector F de fuerza entre dos cuerpos, donde:

- sus masas son m1 y m2
- sus posiciones son los vectores x1 y x2.
- la distancia entre los cuerpos es r, que en 2D es:

$$r = \sqrt{(x_1-x_2)^2 + (y_1-y_2)^2}$$

esta ley de gravitación universal postula que existe una fuerza gravitacional que hace cada cuerpo contra el otro que cumple con:

- ser directamente proporcional a cada masa m1 y m2
- ser inversamente proporcional a radio al cuadrado, la distancia entre los cuerpos al cuadrado
- ser una fuerza atractiva, con m1 atrayendo a m2, y a su vez, m2 atrayendo a m1
- tener una constante de gravitación universal llamada G

la ecuación entonces resulta:

$$F = G \frac{m_1 \cdot m_2}{r^2}$$

esa ecuación es útil para encontrar la magnitud de estas fuerzas ejercidas entre los cuerpos, y si queremos encontrar los vectores fuerza, basta con multiplicar ese escalar $F$ por una dirección.

si notamos el vector F(1,2) como la fuerza que hace el cuerpo m1 sobre m2, y el vector unitario r(1,2) como el vector unitario que va desde m2 a m1 podemos escribir así la ecuación:

$$\vec{F_{1,2}} = F \cdot \hat{r_{2,1}} = G \frac{m_1 \cdot m_2}{r^2} \cdot \hat{r_{2, 1}}$$

## videos de repaso

estos videos están disponibles con subtítulos en español

- <https://www.khanacademy.org/science/ap-college-physics-1/>
  - ver sección "Position, acceleration, and velocity"
