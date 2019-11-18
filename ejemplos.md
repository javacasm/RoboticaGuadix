# Ejemplos

## Dibujos en los leds


![DibujosSencillos](./images/DibujosSencillos.png)

[Ejemplo](https://makecode.microbit.org/_2umDKgXr687x)

## Cálculos sencillos

![CalculosSencillos](./images/CalculosSencillos.png)

[Ejemplo](https://makecode.microbit.org/_L9iibr2646bF)


## Contando de 0 a 12

![Contador 0 a 12](./images/Contador0-12.png)

[Ejemplo](https://makecode.microbit.org/_avMERWV6DW3i)

## Contador de 12 a 0

![Contador 12 a 0](./images/Contador12-0.png)

[Ejemplo](https://makecode.microbit.org/_VaPMFeUmph3e)

## Interacción con botones: eventos

![botones](./images/botones.png)

[Ejemplo](https://makecode.microbit.org/_HiMTd56HvbXF)


## Quiz: preguntas y respuestas

![Quiz](./images/Quiz.png)

[Ejemplo](https://makecode.microbit.org/_5rFevrfKAVwJ)

## Cuenta personas

### Comprobando los pulsadores

![CuentaPersonasBucle](./images/CuentaPersonasBucle.png)

[Proyecto](https://makecode.microbit.org/_2tM31LEe6f93)

### Usando eventos

![CuentaPersonasEvento](./images/CuentaPersonasEvento.png)

[Proyecto](https://makecode.microbit.org/_aRMTbjKDb5AD)

## Dado 0-9 o letra aleatoria

Vamos a convertir nuestra micro:bit en un dado aleatorio
* Si la agitamos nos dará un número aleatorio entre 0 y 9
* Si pulsamos el botón A nos mostrará una letra (de entre unas determinadas) para cualquier juego de palabras. 

Para ello usamos el bloque de elegir un número aleatorio (que está en Matemáticas) y las herramientas de Texto (en avanzado) para seleccionar la letra escogida

![Dado-letraAleatoria](./images/Dado-letraAleatoria.png)

[Ejemplo](https://makecode.microbit.org/_1VsbxM97Cbi9)

## Dando color a la vida

Un led RGB (o neopixel si usamos la marca de @adafruit) está formado por 3 leds Rojo, verde y azul en el mismo encapsulado. 

Encendiendo o apagando unos y otros podemos producir el efecto de generar luces de distinto color

![Colores-MezclaRGB.jpeg](./images/Colores-MezclaRGB.jpeg)

A cada uno de ellos le podemos dar una intensidad entre 0 y 255. Si usamos un [selector de color](https://htmlcolorcodes.com/es/) podemos encontrar los valores adecuados para producir un color concreto.

Para utilizarla con micro:bit necesitamos incluir la extensión neopixel des la paleta **Extensiones** desplegando **Avanzado**.

os leds la forman. En nuestro caso la hemos conectado a P0 y son 4

![ExtensionNeopixel](./images/ExtensionNeopixel.png)



Vamos a hacer un programa que muestre distintos colores al pulsar los botones.

Antes de empezar a manejar los neopixeles debemos inicializar, en el contenedor **Al inciar**, la tira de leds indicando a qué pin está conectada y cuántos leds tenemos.

* Al pulsar el botón A ponemos color púrpura
* Al pulsar el botón B ponemos color naranja
* Al pulsar los dos a la vez un color formado por los valores RGB 123, 200 y 50


![ColoresBloques](./images/ColoresBloques.png)


### Ejercicio

Mostrar distintos colores al agitar de diferentes formas la micro:bit

## Termómetro con color

Incluímos la extensión **Neopixel**

Vemos cómo podemos "controlar" la temperatura desde el simulador

![TermometroColorSimulador](./images/TermometroColorSimulador.png)

Medimos la temperatura. Si es mayor que 25 ponemos los led en rojo, si es menor en azul

En caso de que se pulse el botón A mostramos la temperatura  actual

![TermometroColorBloques](./images/TermometroColorBloques.png)

[Ejemplo](https://makecode.microbit.org/_XcPcJEfhvd3v)