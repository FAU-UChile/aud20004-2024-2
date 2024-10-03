# clase-08

jueves 03 octubre 2024

unidad 6: ondas y sonido

- definición de onda
- análisis de Fourier
- parámetros de las ondas sinusoidales
- definición de sonido
- relaciones entre mundo físico y perceptual
- velocidad del sonido
- efecto Doppler

## definición de onda

cuando grafiquemos ondas, vamos a tener 2 gráficos:

- gráfico de amplitud de la onda en el tiempo, lo que implica que el punto en el espacio está fijo, aquí el eje horizontal de la variable independiente es TIEMPO.

- gráfico de amplitud de la onda en el espacio, lo que implica que el tiempo está fijo o detenido, aquí el eje horizontal de la variable independiente es ESPACIO.

ojo con los ejes!!

## análisis de Fourier

Fourier postuló que toda onda se puede expresar como una suma de ondas sinusoidales.

esto es genial, porque las sinusoides se identifican con 3 datos:

1. amplitud, se mide en metros.
2. frecuencia, se mide en Hz.
3. fase, se mide en radianes.

entonces, si tenemos una máquina que es capaz de crear ondas sinusoidales y sumarlas, podemos crear cualquier onda, por ejemplo, cualquier sonido.

por eso, en ciencias tendemos a analizar las señales y ondas en función de las sinusoides que los conforman.

un nombre de esta técnica que encuentran en computación es FFT, que significa Fast Fourier Transform.

## parámetros de las ondas sinusoidales

una onda sinusoidal se puede definir por estas tres características:

- amplitud (A): distancia entre el punto de equilibrio y el desplazamiento máximo, se mide en metros.
- periodo (T): tiempo que demora la onda en repetirse, se mide en segundos.
- frecuencia (f): inverso del periodo, se mide en Hz.

## longitud de onda

otro parámetro importante para el estudio de ondas, que usaremos cuando medimos su velocidad es.

- longitud de onda (lambda): distancia entre repeticiones de la onda, se mide en metros.

$$lambda = \lambda$$

## definición de sonido

el sonido es una onda producida por un cuerpo en vibración.

la vibración comprime y descomprime el aire alrededor, lo que genera una onda longitudinal.

las moléculas de aire oscilan de forma paralela a la dirección del movimiento de la onda, recibiendo energía de moléculas adyacentes.

el otro tipo de onda es transversal, donde las moléculas se mueven de forma perpendicular al movimiento de la onda.

## relaciones entre mundo físico y perceptual

- la amplitud de una onda de sonido la percibimos como volumen.
- la frecuencia de una onda de sonido la percibimos como altura.
- la fase de una onda no produce un cambio perceptual.

nuestra percepción es logarítmica en cuanto a volumen, necesitamos aproximadamente 10 veces más amplitud física para percibir una duplicación de volumen.

si tomamos un sonido a cierta frecuencia, un sonido al doble de frecuencia lo percibimos como del mismo sabor, entonces a nivel cultural el problema es cuántos pasos hay entre medio.

nuestra percepción en frecuencia funciona como una escalera en espiral, podemos subir y descender, pero ese movimiento va en espiral y se van repitiendo las notas musicales, por ejemplo. en occidente, decidimos que entre dos repeticiones de una nota, hayan 12 notas en total.

## velocidad del sonido

a 20 Celsius, la velocidad del sonido es de 343 metros por segundo, y es la velocidad que usaremos en este curso.

$$v_{sonido} = 343 \cdot \frac{m}{s}$$

la ecuación que relaciona la velocidad, longitud y frecuencia de una onda es:

$$v_{sonido} = \lambda \cdot f_{sonido}$$

entonces podemos calcular la longitud de onda de cualquier onda si sabemos su frecuencia.

por ejemplo, la longitud de una onda con frecuencia 20 Hz:

$$\lambda_{20Hz} = \frac{v_{sonido}}{f_{sonido}} = \frac{343 \cdot \frac{m}{s}}{20 Hz} = 17.15 \cdot m$$

por ejemplo, la longitud de una onda de frecuencia 20 kHz

$$\lambda_{20kHz} = \frac{v_{sonido}}{f_{sonido}} = \frac{343 \cdot \frac{m}{s}}{20k Hz} = 17.15 \cdot mm$$

entonces otra forma de pensar en el rango humano de escucha, en vez de pensar en frecuencias, podemos también pensar en longitudes de onda mínima y máxima.

## efecto Doppler

$$f = f_{original} \cdot \frac{v_{sonido} \mp v_{receptor}}{v_{sonido} \mp v_{fuente}}$$

para efectos de este curso, asumiremos que la velocidad del receptor es 0, y solamente nos concentraremos en la velocidad de la fuente.

$$f = f_{original} \cdot \frac{v_{sonido}}{v_{sonido} \mp v_{fuente}}$$

sabemos que cuando una fuente se acerca a nosotros, la frecuencia percibida es mayor, y cuando se aleja, la frecuencia percibida es menor.

con eso, sabemos que cuando la fuente se acerca, el signo es negativo, y cuando se aleja, el signo es positivo.

## bibliografía

- <https://www.cliffsnotes.com/study-guides/physics/waves-and-sound/wave-motion>
- <https://www.cliffsnotes.com/study-guides/physics/waves-and-sound/sound>
- <https://en.wikipedia.org/wiki/Wavelength>
