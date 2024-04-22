# Triple Espresso

## Descripción del proyecto y su funcionalidad.

Este es la etapa 4 y final del sprint 4 de mi curso de Tripleten.
La finalidad de este proyecto es hacer una página principal donde:

- Podamos tener una bienvenida al usuario, donde sea vistosa, tenga una barra de navegación funcional a las secciones correspondientes y a su vez tenga pequeños pies de pagina indicando un horario y una ubicación.
- Una sección de Recetas, donde podemos recomendar al usuario unas recetas de nuestra propia elección.
- Una sección donde simulemos un formulario para reservar una mesa (Esto incluye el diseño del mismo).
- Y por ultimo pero menos importante, un pie de pagina donde podamos mostrar de forma expresiva la información de la página web.

## Descripción de las tecnologías y técnicas utilizadas.

Iniciando por la metodología aprendia. Hemos utilizado BEM, tanto como para organizar nuestro codigo, clases, elementos, modificadores, etc.. También lo utilizamos para organizar nuestra gestión de archivos.

Increiblemente, hemos estado avanzano con un diseño mucho más avanzado sobre HTML y CSS donde hemos podido aprender:

- **Reforzamiento de etiquetas de estilo:** Fuentes, Fondos, Margenes, Posisionamiento, Dirección de Flujo (Flexbox), Pseudoclases y Peusoelementos, etc...
- **Reforzamiento de Mezclas:** Para el correcto uso de la metodología BEM.
- **Importacion de estilos de fuentes externas:** Utilizando Google Fonts.
- **Importación y uso del iframe: ** Donde lo utilizamos para exportar contenido de contenidos externos para el diseño de nuestro Recetario.
- **Creación y modificacion de estilos de Formularios:** Donde aprendimos como crear formularios, las diferentes formas de enlazarlo y como poner nuestro propio estilo.

Y por utlimo, aprendimos a tener un mejor uso de Git, ya que como lo hemos estado utilizando constantemente, ha hecho que sea una herramienta mucho más comun en nuestro hambito como desarrolladores.

## Imágenes, GIF o capturas de pantalla que detallan las funciones del proyecto.

Para este proyecto, he marcado las partes importantes de cada sección, que han un desafio y parte importante de mi aprendizaje. Veamos más a fondo cada Sección de la Página.

### Sección Header

![header](https://github.com/ChristianP-M/web_project_coffeeshop/assets/165349786/9228b1d7-5dd2-445b-8a85-ad858fabc236)

1.  **Logo de la Empresa:** Englosado a la barra de navegación, debe presentarse exactamente como se muestra en la imagen, para ello, se inserto la imagen dentro del bloque de `nav` y se agregó con una posicion: `position: relative;` con ello se logró posicionar como dictaba el Brief.

2.  **Menú de Navegación:** Cada menú esta englozado a su correspondiente sección a travéz de una etiqueta `a`, Correspondientemente, contribuye a las indicaciónes del brief donde, cada una al acercase el ratón del mouse, este debe tener un efecto `hover`.

3.  **Diseño y posicion de textos e imagenes:** Además de estar acostumbrado a trabajar con `flex-box`. Esta parte presento un gran reto, ya que además de que el título debe ser parte de una misma etiqueta, debe tener distinta topografia. La imagen debe estar a un costado y la descripción debe estar exactamente alineada al titulo, por lo tanto debia haber un perfecto flujo al usar `position`.

4.  **Pide de página de Footer:** Reforzando mis conocimientos con `flex-box` y `justify-content`, presentó un gran reto al tener que estar alineado perfectamente junto con sus horarios, ubicación y alineacion con los demás elementos.

### Sección Recipes

![recetas](https://github.com/ChristianP-M/web_project_coffeeshop/assets/165349786/8230a2bc-2aa6-4bb1-a9b6-1dbb9ae38e89)

1. **Roforzamiento de estilos y titulos de la pagina.**

2. **Aprender a usar iframe:** Además de aprender a usar `iframe`, se aprendio a un correcto uso de etiquetas al `iframe` junto con un buen manejo para dar estilos a ese `iframe`.

### Sección Reservation

![reservation](https://github.com/ChristianP-M/web_project_coffeeshop/assets/165349786/564fee45-be6d-4d60-a1e7-62e2b5ec8d27)

1. **Reforzamiento de estilos y titulos de la página.**

2. **Aprender prácticamente a hacer formularios:** Además de crear un formulario, reforce mis conocimientos para declarar casillas requeridas y dar estilos, crear etiquetado para `inputs` y buen uso de `labels` para la creación de este formulario.

3. **Creación y Estilos de un Boton**

4. **Elaboración de casilla de verificación.** Aquí aprendí a crear un `input` de tipo `type: checkbox`, además de reforzar mi entendimiento de creación de `label` ya que para este ejercicio, este debe estar centrado junto con toda su casilla de verificación.

### Sección Footer

![footer](https://github.com/ChristianP-M/web_project_coffeeshop/assets/165349786/19f27c14-5cfa-4cd7-a23b-2467f057d8f2)

1. **Posicionamiento del Logo:** De misma manera que el header, este debe estar dentro del bloque `footer__content` pero cuidando, que el circulo azul no este por delante de este logo.

2. **Creacion y Posicionamiento del elemento social**

3. **Creación de la lista de redes sociales:** Además de reforzar mi conocimieto con la creación de elementos `ul` y `li`. Estos elementos deben de tener como elemento un hipervinculo, y a su vez una trancisión `hover` al pasar por ellos.

4. **Creación de un elemento copyright.**

5. **Creacion de un Circulo para el diseño de la pagina.** Para mi, la parte más dificil puesto que aquí lo más importante es como reacciona junto con los demás elementos, un muy correcto uso de `position` y `z-index`.
