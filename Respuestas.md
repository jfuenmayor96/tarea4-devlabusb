# Tarea 4
### Admisión Ene-Mar 2018 del Devlab 

## HTML intermedio 

### Respuestas

**1. Qué es un diseño responsive? Por qué son importantes?**

Un diseño responsive es una tećnica del diseño web en la cual se esquematiza 
una página web de forma que esta se ajusta para verse bien en diferentes 
dispositivos que no comparten la misma resolución. Tales dispositivos suelen 
ser celulares, tabletas, computadoras y hasta televisores.

El diseño responsive es logrado con la combinación de HTML y CSS de manera que 
los elementos de la página se ordenan, se redimensionan, se encogen, o crecen 
dependiendo del tamaño del dispositivo en el que se está visualizando.

Esta técnica de diseño es importante ya que hoy en día los usuarios navegan por
los sitios web desde distintos dispositivos y se quiere que la experiencia que
tengan estos usuarios en cualquiera de estos sea la mejor buscando así ofrecer
un diseño correcto.

**2. Qué es un media query?**

Un media query es una técnica de CSS introducida en CSS3.

El media query utiliza la regla @media para incluir un bloque de propiedades
CSS sólo si cierta condición es cierta.

El ejemplo más común de un media query es cuando se quiere que cierta propiedad
de CSS sea válida para dispositivos que sean de un tamaño especifico por ejemplo:

@media only screen (min-width: 767px){
	reglas css
}

Lo que se indique en reglas css se aplicara únicamente cuando el tamaño de la 
pantalla del dispositivo sea mayor a 768 pixeles.

~~**3. Cuáles son las resoluciones estándares, o breakpoints, que se utilizan en el diseño responsive?**~~

~~Las resoluciones estándares que se han utilizado hasta ahora son~~


**4. Qué es Bootstrap?**

Bootstrap es un framework gratuito de desarollo sitios web tanto responsive 
como mobile-first.

Fue creado por Twitter para su uso interno y posteriormente fue liberado como
código abierto. Se convirtió en el proyecto de desarrollo más popular de Github.

Bootstrap contiene plantillas de diseño de formularios, botones, menús de
navegación, entre otras cosas.


**5. Mencione otras librerias para la personalización de front end**

* Materialize 
* Pure
* Jeet
* Susy

y más..

**6. Cómo funciona el grid system de Bootstrap?**

El grid system de bootstrap es un sistema que permite alinear una página web
a través de contenedores, filas y columnas. 

* Los contenedores sirven para centrar horizontalmente el contenido del sitio.

* Las filas son wrappers para columnas. Cada columna tiene un padding horizontal
para controlar el espacio entre ellos. El padding es contraarrestado en las filas
con un margen negativo. De esta forma todo el contenido de las columnas es 
alineado visualmente en el lado izquierdo.

* En un diseño basado en columnas el contenido debe ser colocado en columnas
y las columnas únicamente pueden ser hijos inmediatos de las filas.

* Para que los grids sean responsive, existen cinco breakpoints uno para cada 
breakpoint responsive: todos los breakpoints (extra pequeño), pequeños, 
medianos, grandes y extra grandes.

~~**7. En Bootstrap, que sígnifican o qué representan los siguientes conceptos? Cómo se utilizan?  container, container-fluid, row, row-fluid, col**~~

~~* container:~~
~~* container-fluid: cuando un container es fluid significa que ocupa el tamaño
completo de la pantalla~~
~~* row:~~
~~* row-fluid:~~
~~* col:~~

~~**8. En las columnas de Bootstrap, que es un offset y cómo se utiliza?**~~

~~**9. Cómo puedes ocultar y mostrar selectivamente secciones de código utilizando Bootstrap según la resolución del dispositivo?**~~

~~Con los media querys:  @media only screen (max-width:767px)~~

**10. Cómo se puede cambiar una propiedad de CSS para un breakpoint en específico?**

@media only screen (min-width: 767px){
	propiedad:valor;
}

**11. Qué es un modal?**

Un modal es una ventana de diálogo/popup que se muestra en el tope de la
página actual.

![alt text](https://s3.envato.com/files/216435063/screenshots/11.roundBorderModal.png "Modal")

**12. Qué es un carrusel?**

El carrusel es una presentación de láminas para "ciclar" a través de una serie
de contenido, construido con CSS 3D y un poco de JavaScript. Funciona con una 
serie de imágenes, texto o markup personalizado. Incluye soporte para controles 
e indicadores anteriores / siguientes.

**13. Qué es un tooltip?**

Es un pequeño cuadro emergente que aparece cuando el usuario mueve el puntero 
del ratón sobre un elemento:

**14. Qué es un navbar?**

Un navbar es un elemento de una página web que funciona como barra de navegación.

Un navbar puede estar presente en una página web de muchas maneras. Normalmente
se encuentra en el tope de ésta ya sea fijo en el tope de la página o fixed que 
es cuando el navbar "persigue" al usuario a lo largo del scrolling de la página.

**15. Qué es un footer?**

El footer es un elemento de una página web el cual se refiere al pie de la página.

Casi siempre es el último elemento presente en un sitio web el cual se encuentra
al final de este.

Normalmente en el footer se incluye la siguiente información

* Links de navegación de la página
* Redes sociales
* Información de contacto e información de derechos de autor
* Información sobre el desarrollador de la pagina

**16. Qué es un jumbotron?**

Un jumbotron es un elemento de boostrap el cual funciona una caja grande para 
obtener atención extra de algún contenido o información.

Para crear un jumbotron se crea un div con la clase jumbotron de la siguiente
manera:

```html
<div class="jumbotron>
  Aqui puede ir cualquier etiqueta html
</div>
```

**17. Qué es flex box?**

Flexbox es un módulo de diseño el cual facilita la estructura de diseño responsive
sin necesidad de usar float o posicionamiento. Permite crear diseños flexibles
olvidando los métodos tradicionales y antiguos de CSS los cuales en muchos casos
no cubren con las exigencias de los retos y suelen ser problemáticos.

Los elementos básicos de este nuevo esquema son los siguientes:

* Contenedor: es el elemento padre el cual contendrá cada uno de los elementos
flexibles y adaptables.

* Item: cada uno de los hijos flexibles	pertenecientes al contenedor.

* Eje principal: los contenedores flexibles tendrán una orientación principal.
El valor por defecto es horizontal (en forma de fila)

* Eje secundario: orientación secundaria la cual es perpendicular a la principal.
Si la principal es horizontal la secundaria es vertical y viceversa.

![alt text](https://lenguajecss.com/p/css/propiedades/flexbox-como-funciona.png "Flexbox")

~~**18. Cuáles son los distintos tipos de flex que existen y para qué sirve cada uno?**~~

~~**19. Para que sirven las propiedades flex-flow, justify-content y align-content?**~~