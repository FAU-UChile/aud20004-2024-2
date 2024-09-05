# clase-05

jueves 05 septiembre 2024

unidad 3: energía y cantidad de movimiento

- definición de trabajo
- cálculo de trabajo
- definición de energía
- definición de potencia
- conservación de energía

## relación entre fuerza, energía y trabajo

una FUERZA aplicada en un objeto puede generar un TRABAJO, y así causar un cambio en su ENERGÍA.

## definición de trabajo

se hace trabajo cuando una fuerza aplicada a un cuerpo lo desplaza una cierta distancia.

el trabajo es el resultado entre el producto entre fuerza y desplazamiento y el coseno del ángulo entre la fuerza y el desplazamiento.

$$trabajo = fuerza \cdot desplazamiento \cdot cos(\theta)$$

el trabajo es un escalar, no un vector, y se mide en Joules (J). como la fuerza se mide en Newton (N) y el desplazamiento en metros (m), podemos expresar Joule con estas equivalencia:

$$ 1 J = 1 N \cdot 1 m$$

en palabras, 1 Joule, es la cantidad de trabajo necesaria para ejercer una fuerza de 1N en un desplazamiento de 1 metro.

a su vez, podemos reemplazar la unidad de fuerza Newton por unidades de masa y aceleración, resultando en la equivalencia.

$$ 1J = 1 N \cdot 1 m = \frac{kg \cdot m}{s^2} \cdot m = \frac{kg \cdot m^2}{s^2} $$

## cálculo de trabajo

de la ecuación de trabajo, primero revisemos en qué casos el trabajo es cero:

- si no hay fuerza, no hay trabajo
- si no hay desplazamiento, no hay trabajo
- si el ángulo entre fuerza y desplazamiento es múltiplo de 90 grados (perpendicular), no hay trabajo.

por efecto del ángulo, tenemos que trabajo es máximo cuando el ángulo entre fuerza y desplazamiento es 0 grados, y con eso coseno de 0 grados es 1.

pensemos en la fuerza que ve todo cuerpo m en la tierra, su peso:

$$peso = m \cdot g$$

en este curso, evaluaremos la fuerza que haremos para empujar o levantar objetos en la tierra, su relación con la fuerza peso, y evaluaremos el desplazamiento que producimos y el ángulo entre fuerza y desplazamiento, para calcular el trabajo.

## definición de potencia

la potencia es la cantidad de trabajo realizada en una unidad de tiempo.

$$potencia = \frac{trabajo}{tiempo}$$

la potencia se mide en Watts (W).

$$1 W = \frac{J}{s} = \frac{kg \cdot m^2}{s^3}$$

entonces para un trabajo, mientras es realizado en menos tiempo su potencia es mayor, y viceversa.

## definición de energía

la palabra energía viene del griego enérgeia, que se traduce como actividad.

la energía es una propiedad que tiene un cuerpo o sistema físico, que se reconoce al efectuar trabajo o como luz o calor.

la energía en un sistema, siempre se conserva, no se puede crear ni destruir.

a veces nuestro sistema solamente analizará un cuerpo, por ejemplo un cuerpo en caída libre. a veces considerará un cuerpo, la tierra, y a nosotros que estamos ejerciendo una fuerza sobre ese objeto, por ejemplo cuando empujamos un cuerpo.

estudiaremos dos tipos de energía asociadas a la posición y movimiento de cuerpos puntuales de masa m:

- energía potencial: la energía en un cuerpo sólido por su posición, dependiente también de la masa y la gravedad.
- energía cinética: la energía de un cuerpo sólido por su velocidad, dependiente también de la masa.

## energía potencial

la energía potencial de un cuerpo depende de su masa, la gravedad a la que está expuesto, y la altura que se encuentra, con respecto a una referencia.

la energía potencial es energía, se mide en Joule (J).

la ecuación de energía potencial es:

$$E_p = m \cdot g \cdot h$$

donde:

- m = masa del cuerpo, en kg
- g = aceleración de gravedad, medida en metros / segundos cuadrados
- h = altura ("height" en inglés), con respecto a un sistema de referencia.

pensaremos la energía potencial como energía asociada a la posición de un cuerpo.

## energía cinética

la energía cinética de un cuerpo depende de su masa y la velocidad que tiene.

la energía potencial es energía, se mide en Joule (J).

la ecuación de energía cinética es:

$$E_c = \frac{1}{2} \cdot m \cdot v^2$$

donde:

- m = masa del cuerpo, en kg.
- v = velocidad del cuerpo, en metros / segundo

pensaremos la energía cinética como energía asociada a la velocidad de un cuerpo.

## conservación de energía

la energía en un sistema no se crea ni se destruye, solamente se transforma.

por ejemplo, si tenemos un cuerpodefinimos al suelo como altura = 0, podemos decir que la energía total en un sistema que solamente observa a ese cuerpo es:

$$E_{cuerpo} = E_{potencial} + E_{cinética} = m \cdot g \cdot h + \frac{1}{2} \cdot m \cdot v^2$$

donde

- m = masa del cuerpo
- g = aceleración de gravedad
- h = altura posición del cuerpo (h del inglés height, altura)
- v = velocidad del cuerpo

## conservación de energía en un cuerpo en caída libre

si tomamos el sistema que solamente tiene este cuerpo, y asumimos que no hay fuerzas que estén sobre ese cuerpo, sabemos que la ecuación de energía de este cuerpo de masa m, altura h y velocidad v:

$$E = E_{p} + E_{c} = m \cdot g \cdot h + \frac{1}{2} \cdot m \cdot v^2$$

si definimos nuestra altura = 0 como el suelo de la tierra, y tenemos al inicio un cuerpo a una distancia h del suelo y con velocidad nula, entonces su energía inicial está dada por:

$$E_i = E_{pi} + E_{ci} = m \cdot g \cdot h + \frac{1}{2} \cdot m \cdot 0^2 =  m \cdot g \cdot h$$

si ese cuerpo parte desde esa posición y cae en caída libre, su energía en el instante cuando choca contra el suelo es:

$$E_f = E_{pi} + E_{ci} = m \cdot g \cdot 0 + \frac{1}{2} \cdot m \cdot v^2 = \frac{1}{2} \cdot m \cdot v^2$$

y como la energía se conserva, podemos igualar:

$$E_i = E_f$$

y reemplazando:

$$m \cdot g \cdot h = \frac{1}{2} \cdot m \cdot v^2$$

y podemos dividir por m a ambos lados:

$$g \cdot h = \frac{1}{2} \cdot v^2$$

y luego multiplicar por 2 a ambos lados:

$$2 \cdot g \cdot h = \cdot v^2$$

y aplicando raíz cuadrada a ambos lados para despejar la velocidad:

$$ v = \sqrt{2 \cdot g \cdot h}$$

y con esto podemos darnos cuenta que a mayor altura inicial o mayor gravedad, la velocidad final cuando se llega al suelo es mayor, y que no depende de la masa del cuerpo!

## caloría como medida de energía

en física calcularemos trabajo y energías potencial y cinética en Joule, que equivale a Newton multiplicado por metro.

una unidad de energía alternativa es una caloría (cal), que se define como la cantidad de energía necesaria para elevar en 1 grado Celsius (o Kelvin) la temperatura de un gramo de agua.

como esta cantidad es muy chica, en las tablas nutricionales de alimentos, se usa el múltiplo kilocaloría (kcal), que equivale a la energía necesaria para elevar en 1 grado Celsius (o Kelvin) la temperatura de un kilogramo de agua.

la equivalencia entre Joule y caloría está dada por:

$$1 \cdot cal = 4.184 \cdot J \approx 4 J$$

$$1 \cdot J = 0.239 \cdot cal \approx \frac{1}{4} cal$$

podemos medir la energía de cualquier fuente como un barril de petróleo, electricidad, alimentos, y usarlo para comparar entre distintos trabajos que podemos realizar, como mover cuerpos en distancias.

por ejemplo, si decimos que una manzana tiene 100 kcal, entonces su energía expresada en Joule es aproximadamante:

$$E_{manzana} = 100 kcal = 100 \cdot 1000 \cdot cal = 100,000 \cdot 4 \cdot J = 400,000 J$$

y en palabras, la energía de una manzana es de cuatrocientos mil Joules, lo que equivale cuatrocientos mil Newton \* metro, y podemos crear estas equivalencias.

$$400,000 \cdot J = 400,000 N \cdot m = (400 N) \cdot (1,000 m) = (1 N) \cdot (400,000 m) = (400,000 N) \cdot (1 m)$$

lo que en palabras significa que podemos tomar la cantidad de energía cuatrocientos mil Joule, y podemos expresarla como el trabajo realizado por una fuerza de X de Newton, desplazando a un cuerpo por Y metros, siempre y cuando X por Y sea igual a la constante cuatrocientos mil.

## referencias

- <https://www.cliffsnotes.com/study-guides/physics/classical-mechanics/work-and-energy>
