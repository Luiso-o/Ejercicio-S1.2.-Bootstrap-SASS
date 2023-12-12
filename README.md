## Ejercicio-S1.2.-Bootstrap-SASS

* Tu reto es construir una landing page.

## Instrucciones para Bootstrap:

* Utiliza siempre que sea posible los componentes de Bootstrap, como los botones, cards, navs, tooltips... esto te ahorrará tiempo y tu web ganará consistencia. Aquí tienes los componentes de Bootstrap -> <a href = "https://getbootstrap.com/docs/5.0/components/accordion/"> components accordion </a>

* ¡Nunca modifiques las clases de los archivos originales de Bootstrap!

* Posiciona los elementos con las clases de márgenes y rellenos de Bootstrap. Para proyectos grandes, esta práctica simplifica mucho los archivos CSS. Para obtener más información sobre -> <a href = "https://getbootstrap.com/docs/5.0/utilities/spacing/"> utilities spacing de Bootstrap</a>

* Personaliza el tema de Bootstrap por defecto para adaptarlo a los estilos de la web que estás creando mediante SASS. No es necesario crear nuevas clases, puedes ajustar Bootstrap para adaptarlo a tus necesidades: rellenos por defecto, colores del tema, márgenes...

# NIvel 1

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

### Requisitos mínimos:
- Responsivo.
- Botones de Bootstrap con el color primario definido en el ejercicio 1.

## fase 4
* ¡ENHORABUENA! ¡Ya casi tienes completado el nivel 1! Ahora toca desarrollar la sección de Preguntas Frecuentes (FAQS):

### Requisitos mínimos:
- Utilizar el componente "Accordion" y personalizar las clases para adaptarlo al diseño.

- Ser responsive.

- Utilizar un botón de Bootstrap.

# Nivel 2

* ¡OJO! Antes de pasar al nivel 2, verifica que has entendido bien todos los ejercicios del nivel 1.

* Los niveles 2 y 3 son opcionales; lo importante es comprender los conceptos de cada sprint. Si los has copiado rápidamente de internet, carece de valor. Si avanzas de esta manera en todos los sprints, habrás trabajado mucho pero aprendido poco.

* En una entrevista técnica en una empresa o en las pruebas de nivel del itinerario (después de los sprints 5 y 9), se detectan rápidamente estos casos. No retrases tu aprendizaje; es mejor hacer pocos ejercicios bien que muchos rápidos.

## fase 5

* Solamente falta un bloque para completar la web: el pie de página.

### Requisitos mínimos:
- Utilizar los formularios de Bootstrap.

- Mostrar un mensaje de error cuando se envía el formulario del boletín de noticias y el campo de entrada está vacío o la dirección de correo electrónico no está formateada correctamente. Debe realizarse con Bootstrap.

* Para obtener más información

* Sobre formularios de Bootstrap -> <a href = "https://getbootstrap.com/docs/5.0/forms/overview/"> Descripción general de formularios </a>

* Más información sobre cómo validar formularios con Bootstrap -> <a href = "https://www.youtube.com/results?search_query=bootstrap+5+form+validation"> Videos de validación de formularios en Bootstrap 5 </a>
