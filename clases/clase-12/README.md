# clase-12

jueves 07 noviembre 2024

unidad 8: electricidad

## colores y computadores

un pixel RGB es capaz de brillar y con eso generar color.

si tenemos B bits de resolución por canal de color, entonces un pixel tiene 3B bits para representar su color.

entonces la cantidad de colores posibles en 1 pixel es:

$$colores_{pixel}= 2^{3 \cdot B}$$

si tenemos una pantalla de resolución 1080p, con 1920 por 1080 pixeles, entonces tenemos un total de.

$$pixeles = 1920 \cdot 1080 = 2,073,600$$

y cada uno de esos pixeles, puede ser de un color distinto, y necesitamos 3\*B bits de información para cada uno, y así definir su color.

si tenemos una tasa de refresco de 60 Hz, significa que tenemos 60 cuadros por segundo.

## electricidad

la palabra electricidad viene del latín elektrum, y a su vez, del griego elektron, que significa ámbar, ya que los primeros experimentos donde se observaron características eléctricas fueron hechos al frotar ámbar con otros objetos.

la electricidad describe flujo de energía y materia. con simpleza, tenemos la materia, hecha con átomos, en cuyo núcleo hay masa compuesta de protones y neutrones, que aportan carga positiva, y fuera del núcleo, orbitando, hay partículas de menor masa pero igual carga, llamadas electrones, con carga negativa.

un átomo o una molécula sin carga, es aquella que tiene igual número de protones y electrones, con lo que su carga total se anula y es 0. pero los electrones, en ciertas condiciones, pueden fluir, a lo que le llamamos corriente eléctrica.

## fuerza eléctrica

la ecuación de fuerza eléctrica entre 2 cargas viene dada por:

$$F_{electrica} = K \cdot \frac{q_1 \cdot q_2}{r^2}$$

donde:

- K es la constante de Coulomb
- q_1 y q_2 son cargas eléctricas, que tienen signo
- r es la distancia entre las cargas

la constante K de Coulomb tiene el siguiente valor y unidades:

$$K \approx 9 \cdot 10^9 \cdot \frac{N \cdot m^2}{C^2}$$

## corriente eléctrica

la corriente eléctrica la denotamos por I, de intensidad, y se mide en Amperes (A), que es una representación de carga eléctrica por unidad de tiempo. la unidad de carga eléctrica es Coulomb, con lo que 1 Ampere es igual a 1 Coulomb por segundo.

$$1 \cdot A = 1 \cdot \frac{C}{s}$$

1 Ampere es mucha carga por segundo, ya que 1 electrón posee una pequeña carga de aproximadamente

$$1 \cdot electron \approx 1.6 \cdot 10^{-19} \cdot  C$$

## voltaje eléctrico

el voltaje eléctrico es una medida de potencial eléctrico, y se mide en volts, donde 1 volt (V) es equivalente a 1 Joule dividido por Coulomb.

$$1 \cdot V = 1 \frac{J}{C}$$

las fuentes de poder que usamos en la vida cotidiana, como el enchufe, una batería, un puerto USB, tienen una medida de voltaje y una medida de corriente, donde ocurre lo siguiente:

- el voltaje entregado es IGUAL al de la especificación. ejemplos: enchufe 220 V en Chile, puerto USB 5 V, batería 1.5 V o 9V o algún otro estándar.
- la corriente entregada está LIMITADA por el valor de la especificación. si una fuente de poder es de 10 A, significa que lo máximo que provee es 10 A.

## potencia eléctrica

la potencia eléctrica se mide en watts (W), y un Watt es la cantidad de energía por segundo.

$$1 \cdot W = 1 \cdot \frac{J}{s}$$

la relación entre potencia, voltaje y corriente viene dada por la ecuación:

$$P = V \cdot I$$

y si analizamos las unidades, podemos comprobar:

$$1 \cdot W = 1 \cdot V \cdot 1 \cdot A = 1 \cdot \frac{J}{C} \cdot \frac{C}{s} = 1 \cdot {J}{s}$$

## magnetismo

los imanes tienen 2 polos: norte y sur.

la tierra está polarizada, por eso tenemos brújulas que son capaces de detectar estos polos magnéticos para orientar.

no se han observado en la naturaleza, polos aislados, que no se presenten de a pares.

## electromagnetismo

la electricidad produce magnetismo, y a su vez, el magnetismo produce electricidad, son fenómenos interrelacionados.

el resumen entre cómo electricidad y magnetismo interactúan fue resumido en 4 ecuaciones por James Clerk Maxwell (1831-1879).

la tríada de físicos considerados más relevantes son Newton, Maxwell y Einstein, en ese orden cronológico.

## aplicaciones industriales de electromagnetismo

los micrófonos son imanes, que al ser movidos, producen un voltaje inducido. ese voltaje puede ser amplificado, y usado para alimentar un motor, conectado a un parlante, para volver a transducir de energía eléctrica a energía mecánica.

la guitarra eléctrica tiene cuerdas de metal, que al ser tocadas, vibran sobre las cápsulas, que son imanes. estos imanes tienen un campo magnético, y cuando las cuerdas vibran,se induce un pequeño voltaje en las cápsulas, que luego puede ser amplificado y hacer mover un parlante.

las turbinas hidroeléctricas son imanes, que con la energía mecánica del agua, se mueven e inducen voltaje, que luego alimenta al sistema eléctrico.

## Leo Fender

Leo Fender fue un inventor estadounidense que revolucionó la música popular del siglo XX, al crear la primera guitarra eléctrica sólida de producción industrial (Fender Esquire/Telecaster, 1950), y luego inventar el bajo eléctrico (Precision Bass, 1951), a pesar de nunca haber aprendido a tocar estos instrumentos.

## referencias

- <https://en.wikipedia.org/wiki/James_Clerk_Maxwell>
- <https://en.wikipedia.org/wiki/Leo_Fender>
- <https://www.twitterandteargas.org/>
- <https://github.com/montoyamoraga/audiv020-2022-2/tree/main/clases/clase-06>
