# Anonymous Proxy

Proyecto para la creación de una página web utilizando las herramientas vistas durante el módulo uno del curso. A continuación pasamos a detallar cada parte de la misma y comentar el proceso de construcción.

#### Acceso al proyecto y visualización

Se podrá acceder al proyecto desde la siguiente dirección:
http://beta.adalab.es/modulo-1-evaluacion-final-VirginiaMSordo/

Para una correcta visualización del mismo recomiendo acceder desde el inspector en Firefox:

- móvil: 319 x 800 53%
- tablet: 768 x 800 50%
- desktop: 1200 x 800 53%

(Dependiendo del alto y el % la posición de los elementos puede verse afecta. Se corregiría recolocando los tamaños de las cajas)

 *** cambiado a minwith 768

## HEADER

El header está maquetado con flexbox. Ocupa todo el ancho de la venta, para lo cual, la imagen la se ha puesto como backgroud img, lo que permite una gran flexibilidad y adaptación de la misma. (<a href=""><img title="Adalab"class="img" src="" alt="BG" /></a>)
En este caso, el hero está incluído dentro del header, ya que al mostrarse en la misma página que el título tiene más sentido semánticamente.
El botón menú de arriba a la izq permanece fijo al scroll y enlaza con una url externa, la página de Adalab.
La flecha inferior de la pantalla redirecciona a la sección dos de la misma web.

## SECCIÓN 1

La sección uno está maquetada con flexbox.
Insomnia Tips estuve también pensando en hacerlo como título 3 o 4.
El botón GO incluye hoover y enlaza con la web de Adalab. Podía haber dado un incluído ahora :
&:hover {
transform: scale(1.1, 1.1);
transition: transform 2s;

## SECCIÓN 2

La sección dos está maquetada con Grid.
El link More reasons tiene hover como se pedía y enlaza a la web de Adalab.
Añadido transform en More reasons
&:hover {
transform: scale(1.1, 1.1);
transition: transform 2s;

## FOOTER

El footer está maquetado con flexbox. Todos sus elementos son enlaces a la web de Adalab.
La flecha enlaza con el header tal como se pedía.

## LINKS

En el fichero de links se ha incluído en Sass los hover de toda la página.
Al posicionar el cursor sobre los links (salvo los del footer) sale un tiptool con el nombre de la página a la que te va a redireccionar.

### Tecnologías utilizadas

Página web básica utilizando HTML y para la creación de estilos CSS y SASS.
Para la nomenclatura de las clases se ha utilizado el marco de trabajo BEM.

### APRENDIZAJE DURANTE EL PROYECTO

### CONCLUSIONES

La página web está funcionando correctamente, a pesar de los detalles que se pueden incorporar para mejorar su uso. Me hubiera gustado incluir Sass en todas las ocasiones pero en muchos casos no ha funcionado como espera y al haber fecha de entrega estipulada no he querido arriesgar el tiempo en demasiadas pruebas.
Por otro lado, y enlazando con lo anterior, la realización de este proyecto me ha supuesto un reto muy interesante y me ha permitido comprobar en que partes necesito profundizar más.
Conceptos para seguir practicando (apenas hubo tiempo durante el módulo 1):

- Sass
- Grid
- Trabajar con %, dónde y cómo aplicarlos mejor para que sea más responsive.
