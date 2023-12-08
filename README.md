## Ejercicio-S1.2.-Bootstrap-SASS

* Tu reto es construir una landing page.

## Instrucciones para Bootstrap:

* Utiliza siempre que sea posible los componentes de Bootstrap, como los botones, cards, navs, tooltips... esto te ahorrará tiempo y tu web ganará consistencia. Aquí tienes los componentes de Bootstrap -> <a href = "https://getbootstrap.com/docs/5.0/components/accordion/"> components accordion </a>

* ¡Nunca modifiques las clases de los archivos originales de Bootstrap!

* Posiciona los elementos con las clases de márgenes y rellenos de Bootstrap. Para proyectos grandes, esta práctica simplifica mucho los archivos CSS. Para obtener más información sobre -> <a href = "https://getbootstrap.com/docs/5.0/utilities/spacing/"> utilities spacing de Bootstrap</a>

* Personaliza el tema de Bootstrap por defecto para adaptarlo a los estilos de la web que estás creando mediante SASS. No es necesario crear nuevas clases, puedes ajustar Bootstrap para adaptarlo a tus necesidades: rellenos por defecto, colores del tema, márgenes...

## Fase 1

* En este ejercicio comenzaremos con la parte principal, que es el contenido que ven los usuarios al entrar en la web:

* Para lograr esto, deberás implementar:

* La barra de navegación superior fija, utilizando el componente "navBar" de Bootstrap.
-> <a href = "https://getbootstrap.com/docs/5.0/components/navbar/">Componentes navbar</a>

* El contenido principal, utilizando el "grid responsive" que proporciona Bootstrap para dividir la pantalla en dos columnas. A la izquierda, como se puede ver, se encuentra el eslogan, la descripción y los botones, y en la columna derecha, la imagen.
-> <a href = "https://getbootstrap.com/docs/5.0/layout/grid/">Sistema de cuadrícula (Grid system)</a>

### Requisitos mínimos:
* Instalar Bootstrap en el proyecto, no utilizar cdn (carga mediante enlace, por ejemplo "<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/...." rel="stylesheet" crossorigin="anonymous">").

* Utilizar el componente navBar de Bootstrap.

* Utilizar el Grid Responsive de Bootstrap, ya que debe visualizarse correctamente en tabletas y móviles.

* Modificar con SASS, a través del archivo creado por ti "main.scss", el color principal y secundario de Bootstrap. Utiliza estas variables para los colores de los botones:

* Color principal: #5265E1
* Color secundario: #FA5959.

## fase 2

* Ahora toca crear la parte de funcionalidades del producto que estamos vendiendo:

### Requisitos mínimos:

* La sección "Características", con el texto descriptivo, debe ir dentro del sistema de cuadrícula de Bootstrap.
* Debes utilizar el componente de pestañas (tabs) de Bootstrap, modificando sus estilos para adaptarlos a nuestra página web.

### Para obtener más información:

* En este tutorial se explica cómo hacerlo: <a href = "https://turbofuture.com/computers/Apply-custom-styles-to-bootastrap-tabs-step-by-step"> enlace al tutorial. </a>

* Diseño adaptable (responsive).

## fase 3
* Debes construir la tercera parte del sitio web: el área de descargas.

* Dado que las tarjetas de la imagen son muy diferentes a las tarjetas de Bootstrap, en este ejercicio te damos la opción de personalizar las tarjetas de Bootstrap o bien crear tus propias clases para maquetarlas.

Requisitos mínimos:
- Responsivo.
- Botones de Bootstrap con el color primario definido en el ejercicio 1.
