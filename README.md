# Documentación del Proyecto: Página Web Personal

## Descripción del trabajo
Este proyecto es una página web estática desarrollada para la asignatura de Fundamentos de Ingeniería Informática de la UFV. El objetivo es aplicar conocimientos de HTML5 y CSS3 para crear un conjunto de páginas sobre diferentes cosas, que permite el conocer la mayoria de las etiquetas más importantes de HTML5, asi como la forma de usar los estilos que ofrece CSS3. 

Está dividido en 7 páginas y un documento de estilo CSS, las páginas tiene un diseño basado en tarjetas estructurado en un contenedor principal, lo que permite un mejor enfoque de la información.

Descripción de lo implementado en las páginas:  

- Lo que hay en todas las páginas:

    - **Menú:** Es un menú horizontal ubicado en la parte superior de las páginas, permite el acceso a cualquier página desde el lugar en el que se encuentre el usuario, utiliza la opcion de flex que tiene CSS para poder ser horizontal, se utiliza la etiqueta nav que es lo que lo hace un menú y las ubicaciones de las páginas en la carpeta.

    - **Contenedor principal:** El contenedor principal es una división (etiqueta div) que permite que la pagina tenga: "diseño basado en tarjeta", que ocupa un ancho del 90 porciento de la pantalla (con un máximo de 900px) y se encuentra centrado.

    -**Body:** El body general (se encuentra en todas las páginas menos topic y degree) es de color negro para generar un mayor contraste con el contenido de la página que se encuentra en el contenedor general, se hizo cambiando el estilo de la etiqueta en el dicumento CSS.

- Estilos de CSS usados:

    - **.galeria:** Creada por buscar la forma de mostrar imágens de manera horizontal en una página de estilo vertical, se uso el: "display = flex", el cual permite que sea horizontal, ademas de esto se encuentra centrado y con un margen y gap que permite que se vea como una galería, fue implementado por primera vez en la página de F1 y su estructura fue copiada y utilizada en las de Net y Sobre mi.

    - **.sidebar:** Creado por la necesidad de tener un segundo menú que no tapara el inicial y que se mantuviera en toda la página, tiene las secciones de la parte de grado, dividiendo la página en cada curso (usando la etiqueta de section).

    - **section:** Creado por la necesidad de que cada sección de degree se viera bien.

    - **main:** Creado para que el contenido de la página degree no estuviera encima del menú vertical.

    - **html:** Para que al bajar de página (en degree) se vea más bonito. 

## Metodología implementada

Inicialmente no seguí ninguna metodología específica, pero si se puede explicar:

En general fue parecido a una metodología de Desarrollo Incremental e Iterativo, con técnicas de Refinamiento Progresivo para asegurar la calidad vidual. La forma en que desarrolle la página fue:

Empecé con lo básico, de ahí mejoré el aspecto visual general y despúes el aspecto visual más específico (prototipo evolutivo). Resolví tareas pequeñas y especificas (parecido a la metodología Scrum). También lo desarrollé por partes (lo que se puede considerar como módulos), cada parte de una página era probada antes de seguir, con cada página siendo desarrollada en difernetes momentos, solo se trataron varias cuando eran cambios o errores en los que era necesarios tartar con más de una.

## Problemas durante el desarrollo
- **Configuracion repositorio de GitHub** El error incial o el primero fue que según git el reposito a vinvular con GitHub no existia, despues de solucionar ese error, salió otro, pero referente a que no tenía el permiso para concetar con el repositorio en GitHub, ambos problemas fueron solucionados despúes de unas cuantas horas de buscar y probar lo encontrado en internet.

- **Configuración de GitHub Pages:** Inicialmente, hubo dificultades para que la página cargara el archivo `index.html` debido a su ubicación en el repositorio.

- **Rutas de archivos:** Se presentaron errores al enlazar el archivo CSS y las páginas entre sí despúes de tener que mover el index.html a laa carpeta anterior a los de public, se solucionaron ajustando las rutas relativas.

- **Enlace a las url de las páginas de los otros compañeros:** Cuando se coloca la ruta directa (la que ellos me enviaron) sin el index.html despúes del último / no llevaba a sus páginas salía error 404 Page not found, se solucionó añadiendo lo mencionado.

- **Errores de visualización (relacionados con CSS):** Como hacer que el menú vertical y horizontal se vieran bonitos, como hacer para que existieran imágenes de manera horizontal (con varias en una misma fila) sin que se vieran mal, división en una misma página. Todo esto se solucionó buscando información por internet y haciendo pruebas de ensayo y error.  

- **Que el formulario al darle enviar no saliera un error en la página**

## Conclusiones
El desarrollo de este sitio permitió entender la importancia de la estructura de carpetas en un proyecto web y el flujo de trabajo básico con Git y GitHub para el despliegue de sitios en vivo, así como aprender el como usar de manera básica el HTML5 y el CSS3.
El internet es la mejor fuente de información para el aprendizaje de estos dos lenguajes, solo con buscar salen las soluciones a lo que se plantea (lo errores, que algo se vea de alguna forma) 

