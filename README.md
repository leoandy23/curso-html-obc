# Tareas del Curso de HTML y Bootstrap

## Tarea 1

Crea un nuevo documento HTML e implementa lo siguiente:

- Utiliza la etiqueta de título para poner en el título "Ejercicio de Introducción a HTML en OpenBootcamp"

- Dentro de la etiqueta body pon un comentario de dos líneas

  - Este es mi primer comentario de dos líneas

  - Aprendiendo a documentar mi código con OpenBootcamp

- Crea una lista desordenada de tus tres vídeos de Youtube favoritos, siguiendo las siguientes pautas:

  - Cada elemento de la lista tiene que ser un enlace

  - El texto del enlace debe ser el título del vídeo

## Tarea 2

### Tarea 2.1

Crea un nuevo documento HTML que cumpla los siguientes parámetros:

- El título debe ser "Ejercicio 02 - Formularios en HTML"

- El body debe contener un formulario que cumpla las siguientes características

  - El atributo action será "/"

  - Debe contener los siguientes campos:

    - Un campo de texto llamado "nombre"

    - Un campo numérico llamado "edad"

    - Un campo de área de texto llamado "frase-favorita"

    - Un botón de envío

    - Un botón de reset

### Tarea 2.2

Crea un nuevo documento HTML que cumpla los siguientes parámetros:

- El título debe ser "Ejercicio 02/2 - Tablas en HTML"

- El body debe contener una tabla que cumpla las siguientes características

  - Las columnas serán las siguientes: "Título", "Autor", "Año de publicación", "Enlace a Amazon"

  - Debe tener tres entradas, que corresponderán a tus tres libros favoritos

## Tarea 3

Crea un nuevo documento HTML que cumpla los siguientes parámetros:

- Debe estar dividido en tres secciones (etiqueta)

- Condiciones para la primera sección

  - Debe tener un título (h1) indicando "Aprendiendo a utilizar imágenes"

  - Debes incluir una imagen de tu videojuego favorito

- Condiciones para la segunda sección

  - Debe tener un título (h1) indicando "Aprendiendo a utilizar los vídeos"

  - Descárgate cualquier vídeo de youtube

  - Debes incluir una etiqueta de vídeo que reproduzca el vídeo que acabas de descargar

  - El vídeo debe mostrar los controles, reproducirse automáticamente y en bucle, PERO inicialmente debe estar sin sonido

- Condiciones para la tercera sección

  - Debe tener un título (h1) indicando "Aprendiendo a utilizar los audios"

  - Descárgate cualquier audio de una canción de youtube

  - Debes incluir una etiqueta de audio que reproduzca el audio que acabas de descargar

  - El audio debe mostrar los controles, reproducirse automáticamente y en bucle

## Tarea 4

Crea un nuevo documento HTML con el título "Ganando precisión con los selectores en CSS"

- Crea un nuevo fichero CSS e impórtalo en el documento HTML principal

- Dentro del body crea una sección con los siguientes elementos:

  - Encabezado que contenga el texto "Lista de la compra"

    - Añade en el encabezado un atributo id con el valor "titulo"

    - Añade también un atributo class con el valor "encabezado"

  - Una lista desordenada con cinco elementos que representen artículos de la compra

    - Cada uno de los elementos debe tener un id como sigue: primer elemento "elemento-1", segundo elemento "elemento-2", etc.

  - Una lista ordenada con cinco elementos que representan los supermercados más cercanos a tu casa

    - Al igual que en la lista anterior, cada uno de los elementos debe tener un id como sigue: primer elemento "elemento-1", segundo elemento "elemento-2", etc.

  - Modifica el CSS para que el primer elemento de cada lista se muestre de color rojo

  - A través del encadenamiento de selectores, haz que el primer elemento de la primera lista tenga un tamaño de letra de 2rem

## Tarea 5

Crea un nuevo documento HTML con el título "Disposición de elementos en CSS"

- Crea un nuevo fichero CSS e impórtalo en el documento HTML principal

- Utiliza la disposición flex-box para crear una galería de 6 imágenes con los siguientes parámetros

  - Las imágenes deben tener 300 píxeles de ancho

  - Deben reagruparse (wrap) cuando el ancho del viewport cambia

## Tarea 6

Crea un nuevo documento HTML con el título "Selectores, pseudo-clases y pseudo-elementos en CSS"

- Crea un nuevo fichero CSS e impórtalo en el documento HTML principal

- Crea un botón con el texto "Pasa por encima" (TIP: Este texto debes agregarlo a través de un pseudo-elemento)

- Utiliza las pseudo-clases para que cuando se pase el ratón por encima de este botón, el texto se vuelva blanco y el fondo de color verde

- Utiliza los pseudo-elementos para cambiar el texto del botón a "¡Hecho!"

## Tarea 7

Replica el ejercicio del vídeo 3 de esta sesión y realiza el siguiente cambio:

- Replícalo exactamente igual, pero realiza una nueva versión en modo oscuro

- Los colores serán los siguientes

  - El rosa se queda igual

  - El fondo blanco será sustituido por el color #161717

  - El fondo de los inputs tendrá un color #212121

  - El fondo de los inputs cuando se hace hover será del color #454045

  - Los textos tendrán un color blanco

## Tarea 8

Crea un nuevo documento HTML con el título "Introducción a Bootstrap"

- Utilizando la página oficial getbootstrap.com, añade la última versión de Bootstrap a este documento HTML

## Tarea 9

Crea un nuevo documento HTML con el título "Animaciones y transiciones en CSS"

- Crea un nuevo fichero CSS e impórtalo en el documento HTML principal

- En el body crea un botón con el atributo class "btn-modern"

- Implementa las líneas necesarias en el CSS para que cuando el ratón pase por encima del botón ocurra lo siguiente (hover):

  - El botón se traslade -5px en el eje de las Y

  - Se añada una sombra

  - El color de fondo del botón cambie

  - El color del texto cambie

  - Todo esto con una transición de 0.4s

## Tarea 10

Crea un nuevo documento HTML con el título "Diseño Responsive con CSS"

- Crea un nuevo fichero CSS e impórtalo en el documento HTML principal

- Crea las siguientes dos secciones:

  - Una barra lateral izquierda con tres elementos en vertical

  - Una sección principal a la derecha

  - (Tip: Utiliza la disposición flex donde la sección principal utilizará flex-grow)

- Utiliza las media queries para que cuando el ancho del viewport sea menor de 640px ocurra lo siguiente:

  - La barra lateral izquierda se muestre como una navegación en la parte inferior

  - La disposición de los elementos de la barra lateral se vuelva horizontal

  - (Tip: Trabaja con la propiedad flex-direction)

## Tarea 11

Crea un nuevo documento HTML con el título "Sistema grid de Bootstrap"

- Utilizando la página oficial getboostrap.com, añade la última versión de Bootstrap a este documento HTML

- Crea 6 div con un texto en su interior

- Utilizando únicamente el atributo class de cada uno de los div haz lo siguiente:

  - Por defecto, cada elemento ocupará el ancho máximo

  - Para viewports SM - cada fila contendrá 2 elementos

  - Para viewports MD - cada fila contendrá 3 elementos

  - Para viewports LG - cada fila contendrá 4 elementos

  - Para viewports XL - cada fila contendrá 6 elementos
