# Actividad 3 - Web Corporativa Responsiva

## Introducción

Este proyecto es una página web para una empresa fictícia llamada tramaSTUDIO. Ofrece informaciones básicas sobre la empresa y un formulario para contacto.

## Objetivos

Con la realización de esta actividad, se pretende asentar los conocimientos de HTML y CSS vistos en la materia de Lenguaje de Marcas y Sistemas de Gestión, con la realización de una página web corporativa.
También se pretende trabajar competencias tales como el trabajo en equipo, comunicación y organización por parte del alumnado, situaciones que se encontraran en el mundo laboral.

### Requerimiento 1
Realización página web corporativa según las pautas indicadas:
- Home: <br>Página principal del sitio
- Áreas de actuación (diseño libre):<br>En esta página se mostrarán los diferentes servicios de la empresa.
- Quiénes somos:<br>Página con un texto y una foto con la descripción de la empresa
- Formulario de contacto:<br>En este formulario debes de usar TODOS los elementos HTML5 asociados a los formularios las veces que sean necesarias, debe de ser un formulario bien diseñado a las necesidades de tu página web.

### Requerimiento 2
Vamos a realizar un menú desplegable basado en listas de HTML, donde por medio de CSS le daremos un aspecto visual atractivo y con solapas desplegables. Dichas solapas llevarán a las páginas operativas descritas anteriormente.

### Requerimiento 3
Realizar la adaptación de la página web completa para dispositivos móviles.
La página debe optimizarse para visualizarse en los siguientes dispositivos (debe verse claramente que los elementos son modificados en cada caso):
• Adaptación de ancho fijo de resoluciones de más de 1300px de ancho.
• Adaptación optimizada para verse en una tablet en posición vertical.
• Adaptación optimizada para verse en una tablet en posición horizontal.
• Adaptación optimizada para verse en un teléfono posición vertical.
• Adaptación optimizada para verse en un teléfono posición horizontal.

### Requerimiento 4
Se pide como labor de investigación que los alumnos suban la actividad a github.io o algún otro hosting gratuito para que se pueda ver en la web.

**Mira la aplicación online [aquí](https://tanimaraeliassantos.github.io/web-corporativa-daw/).**

![tramaSTUDIO Showcase](img/tramastudioshowcase.gif)

## Características

- Página principal con elemento interactivo que lleva usuarios a páginas secundarias
- Página secundaria con formulario para que el usuario pueda entrar en contacto con la empresa enviando sus datos
- Páginas secundariaas con informaciones relevantes al negocio de la empresa

**index.html (Home)**

  Página de inicio que presenta una introducción al estudio y su propuesta de valor.
  Estructura: Utiliza grid para el layout principal con áreas definidas para header, nav, main-aside, y footer. Dentro de main, se usa grid
  para organizar la sección de texto y el aside de la imagen en dos columnas en pantallas medianas y grandes.
  Se adapta a diferentes tamaños de pantalla utilizando Media Queries, apilando la sección y el aside en una sola columna en pantallas más pequeñas (móvil y tablet vertical).

**contacto.html (Contacto)**

  Página con un formulario de contacto para que los usuarios envíen mensajes y datos de contacto al estudio, además de mostrar información de contacto directa.
  Estructura: El contenido principal contiene varios elementos fieldset para organizar los campos del formulario. Se utilizan label para las etiquetas de los campos y varios          tipos de input (text, email, tel, url, number, date, time, range, radio, checkbox), select, textarea, y datalist. Los botones de enviar y limpiar están dentro de un div con la      clase inline. La información de contacto (email, teléfono, ubicación) también está dentro de un div con la clase inline.
  Se adapta a diferentes tamaños de pantalla utilizando Media Queries, haciendo que los elementos inline se apilen en pantallas pequeñas y ajustando el ancho de los fieldset.

**quienessomos.html (Quiénes Somos)**

  Página que presenta la historia, la filosofía y los valores del estudio.
  Estructura: El contenido principal utiliza grid para organizar el texto y la imagen en dos columnas en pantallas medianas y grandes. El texto se encuentra dentro de un div y la     imagen está fuera.
  Se adapta a diferentes tamaños de pantalla utilizando Media Queries, haciendo que la disposición del texto y la imagen pase a una sola columna (apilándose verticalmente) en         pantallas más pequeñas.

**servicios.html (Areas de Actuación)**

  Página que lista y describe las diferentes áreas de actuación o servicios que ofrece el estudio.
  Estructura: El contenido principal utiliza grid para organizar las secciones de servicios en dos columnas en pantallas medianas y grandes. Cada servicio tiene un encabezado         con un ID para el anclaje desde el menú y un párrafo con la descripción.
  Se adapta a diferentes tamaños de pantalla utilizando Media Queries, haciendo que las secciones de servicios se dispongan en una sola columna en pantallas más pequeñas.

**Menú de Navegación**

  Una lista desordenada con elementos de lista. Algunos elementos de lista tienen la clase dropdown y contienen un enlace y otra lista desordenada para el submenú.
  En pantallas pequeñas (móvil vertical), el menú se transforma a una disposición vertical y el submenú se oculta por defecto, requiriendo interacción. En pantallas de móvil          horizontal, el menú vuelve a ser horizontal.

**Footer**

  Estructura: Contiene un párrafo con información de copyright y otro párrafo con un enlace de correo electrónico.
  El estilo básico del footer se mantiene en todas las resoluciones, con ajustes mínimos de padding y tamaño de fuente en pantallas más pequeñas.

## Technologies

- CSS
- HTML

### Autora

[Tanimara Elias Santos](https://github.com/tanimaraeliassantos)

### Versión

1.0.0
