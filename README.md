# Practica02-MiSitioWeb-CSS
**PRÁCTICA DE LABORATORIO**

**CARRERA** : Computación

**ASIGNATURA** : Programación Hipermedial

**TÍTULO PRÁCTICA** : Resolución de problemas sobre CSS3

**OBJETIVO ALCANZADO:**
-	Entender y organizar de una mejor manera los sitios web en internet.
-	Diseñar adecuadamente elementos gráficos en sitios web en internet.
-	Crear sitios web aplicando estándares actuales.

**ACTIVIDADES DESARROLLADAS**

1.	**Crear un repositorio en GitHub con el nombre “Practica02-Mi Sitio Web (CSS)”**

**Usuario de GitHub:** bryansb

**Repositorio de la presente práctica:** https://github.com/bryansb/Practica02-MiSitioWeb-CSS-

2. **Realizar un commit y push por cada requerimiento.**

Se fueron realizando commits de acuerdo se fue avanzando en el desarrollo de la práctica.

3. **Validar todas las páginas HTML y hojas de estilos CSS creadas, usando el W3C Validator.**

**Para HTML:** [https://validator.w3.org/](https://validator.w3.org/)

**Para CSS:** [http://jigsaw.w3.org/css-validator/](http://jigsaw.w3.org/css-validator/)

El sitio web cuenta con 9 páginas, que se crearon anteriormente: index.html, eduacion.html, cultura.html, fiestas.html, parques.html, historia.html, geografía.html, gastronomía.html y turismo.html; además de otra que se creó para esta práctica: formulario.html, lo cual da un total de 10 páginas HTML

Todas las páginas web se adaptaron a la nueva configuración, por lo que se sometieron a un rediseño; sobre todo en la estructura de _header_ y _footer_.

Además, se crearon 9 hojas de estilos CSS: home.css, contenidoHome.css, dosColumnas.css, contenidoDC.css, tresColumnas.css, contenidoTC.css, formulario.css, contenidoFormulario.css y común.css.

![imagen](/recursos/v1.png)

![imagen](/recursos/v2.png)

![imagen](/recursos/v3.png)

![imagen](/recursos/v4.png)

![imagen](/recursos/v5.png)

![imagen](/recursos/v6.png)

![imagen](/recursos/v7.png)

![imagen](/recursos/v8.png)

![imagen](/recursos/v9.png)

![imagen](/recursos/v10.png)

![imagen](/recursos/v11.png)

![imagen](/recursos/v12.png)

![imagen](/recursos/v13.png)

![imagen](/recursos/v14.png)

![imagen](/recursos/v15.png)

![imagen](/recursos/v16.png)

![imagen](/recursos/v17.png)

![imagen](/recursos/v18.png)

![imagen](/recursos/v19.png)

4. **Generar el archivo README del repositorio de GitHub.**

El archivo README se creó junto con el repositorio, el mismo tendrá la información presente en este informe.

5. **Generar el informe detallando los pasos y requerimientos de la guía de práctica.**

Para esta practica se requiere tomar como base el sitio web que se desarrolló en la Practica 01, y aplicarle las hojas de estilo CSS; para ello se requiere adaptar un diseño de dos columnas, y de tres columnas, además de modificar la página index.html para que se ajuste al diseño que se presenta en la Figura 1. De la guía de práctica.

Adicionalmente, se pide crear una página web la cual contenga un formulario de contacto, o de crear cuenta; tal como se lo muestra en la Figura 4. De la guía de práctica.

Para cumplir lo anterior expuesto, se requiere utilizar por lo menos cuatro archivos \*.css en donde se podrá la estructura, y reglas relacionadas al contenido, utilizando diferentes tipos de selectores, donde además se recomienda utilizar fuentes y gamas de colores, los cuales se pueden obtener de los siguientes links:

**Fuentes:** [**https://fonts.google.com/**](https://fonts.google.com/)

**Colores:** [**https://color.adobe.com/es/create**](https://color.adobe.com/es/create)

**A. Selectores**

**Descendentes:** Selectores que se caracterizan por tener cierta jerarquía determinada; como en el siguiente ejemplo, en el que se aplica la regla solo para los &quot;li&quot; que cumplan esa jerarquía.

![imagen](/recursos/1.png)

**Por Clase:** Cuando a un elemento se le ha asignado un nombre para una clase, puede haber varios con el mismo identificador de clase; como por ejemplo, una clase para definir tablas.

![imagen](/recursos/2.png)

**Por ID:** Son identificadores únicos, definen a un elemento en específico; por ejemplo, a continuación se hace referencia a tres elementos que tienen un identificador único.

![imagen](/recursos/3.png)

**B. Fuentes**

**Fuentes descargadas:** Para la práctica, se seleccionaron 3 fuentes diferentes y se las almacenaron de manera local en un directorio.
Para poderlas utilizar en las páginas web, se las tiene que agregar desde el archivo \*.css, de la siguiente manera:

![imagen](/recursos/4.png)

![imagen](/recursos/5.png)

**Visualización:** Según la regla anterior, al elemento &quot;h2&quot;, se le asigna la fuente que se ha descargado y agregado a la hoja de estilos. Además, se puede modificar el tamaño, color, espaciado y alineación del mismo. A continuación se presentará la visualización en la página web.

![imagen](/recursos/6.png)

**C. Colores**

**Gamas utilizadas:** Se visitó una página que recomienda colores en base a ciertos criterios, para seleccionar una gama de colores basado en el contenido de la página web, en este caso, la página web se basa en dos gamas:

![imagen](/recursos/7.jpg)

![imagen](/recursos/8.jpg)

Un ejemplo, se pudo visualizar en la sección anterior en cuanto a los títulos con h2, en el siguiente punto también se verá el uso de los colores antes mostrados.

**D. Hipervínculos**

**Pseudoclases usadas:** Las pseudo clases se utilizan para dar un poco de flexibilidad a la hora de visualizar el comportamiento de los hipervínculos, a continuación se muestra un ejemplo de aquello aplicado a la práctica; _hover_, es cuando se &quot;pasa&quot; con el cursor por el hipervínculo, en cambio, _focus_ hace referencia a cuando se le selecciona.

![imagen](/recursos/9.png)

![imagen](/recursos/10.png)

![imagen](/recursos/11.png)

**E. Cabecera y Pie de Página**

Todas las páginas tendrán estas dos &quot;partes&quot; de manera exactamente igual.

**Cabecera, estructura:** El _header_ de esta página está conformada por un logo (img), una barra de búsqueda (form), y tres elementos de una clase &quot;icono&quot; (iconos\_texto). Además de una barra de navegación. El objetivo, es presentar todo este _header_ de manera compacta; teniendo una barra de navegación horizontal (nav).

![imagen](/recursos/12.png)

![imagen](/recursos/13.png)

![imagen](/recursos/14.png)

**Cabecera visualización:**

![imagen](/recursos/15.png)

**Pie de página, estructura:** La estructura del pie de página es de tres divisores, uno que contendrá logos y la información de contacto, y otros dos que tendrán enlaces para navegar en el sitio web. Para ello se emplearán clases para editar las configuraciones de los tres.

![imagen](/recursos/16.png)

![imagen](/recursos/17.png)

**Pie de página visualización:**

![imagen](/recursos/18.png)

**F. Página Home**

**Estructura:** La página home, o index, es la más compleja. Se basa en una serie de divisiones que tienen una determinada función. Tiene una primera sección en donde se presenta una pequeña introducción a la página web, después una galería, una serie de artículos pequeños, y un directorio del equipo de trabajo. Para lograr esto, se utilizó un identificador para cada etiqueta div, las cuales posteriormente, fueron estilizadas de acuerdo con su id.

![imagen](/recursos/19.png)

![imagen](/recursos/20.png)

**Visualización:**

![imagen](/recursos/21.png)

![imagen](/recursos/22.png)

![imagen](/recursos/23.png)

![imagen](/recursos/24.png)

**G. Página a Dos Columnas**

**Estructura:** La estructura de una página de dos columnas es simple, además de contar con un _header_ y _footer,_ cuenta con una división que se encargará de contener una zona de navegación interna y otra que será en donde se vaya almacenando el contenido de la página web.

Para ello, tenemos una etiqueta \&lt;div id=&quot;menu&quot;\&gt; que se encontrará a la izquierda y tendrá un ancho menor al del contenido, y otra etiqueta \&lt;div class=&quot;contenido&quot;\&gt; que tendrá un ancho más predominante ya que contendrá a las etiquetas \&lt;article\&gt; que proveerá la información de la página.

![imagen](/recursos/25.png)

**Visualización:**

![imagen](/recursos/26.png)

**H. Página a Tres Columas**

**Estructura:** La estructura de tres columnas es muy similar a la de dos columnas. La única diferencia es que dentro del divisor &quot;contenido&quot;, habrá dos divisiones más; cada una será otra columna, una que contendrá la información principal del tema tratado, y la otra columna tendrá información secundaria relacionada con el tema central.

Entonces, en este caso, tendré dos clases de divisores más \&lt;div class=&quot;principal&quot;\&gt; y \&lt;div class=&quot;secundario&quot;\&gt;, en donde se le dará mayor preferencia al contenido del divisor principal, tal como se muestra a continuación:

![imagen](/recursos/27.png)

**Visualización:**

![imagen](/recursos/28.png)

**I. Formulario**

**Estructura:** La estructura de la página del formulario es la más sencilla de todas, ya que solo contará con una sección en donde se incluirá la imagen, y el formulario.

El punto de esta plantilla solo será la de estilizar cada componente del contenedor.

![imagen](/recursos/29.png)

**Visualización:**

![imagen](/recursos/30.png)

Entonces, para resumir, cada página tiene enlazado 3 hojas de estilos CSS.

1. Una que contiene reglas que son comunes para todas las páginas, como las de encabezado y pie de página.
2. Una que tiene reglas de estructura, de acuerdo al contenido que tiene. (home, dos columnas o tres columnas)
3. Una que tiene reglas de colores, fuentes, imágenes, videos, entre otros de acuerdo a la estructura que tiene.

Anteriormente se mostró principalmente las reglas que definían la estructura, las que definen el formato son similares, tomando cada elemento, y sub elemento de la estructura para formatearlo de acuerdo a la necesidad

**RESULTADO(S) OBTENIDO(S)**:

- Se logró entender, organizar y desarrollar de una mejor manera los sitios web.
- Se logró diseñar, de manera adecuada elementos gráficos en sitios web.
- Se logró aplicar hojas de estilos CSS a páginas web, logrando así una mejor presentación del mismo.


**CONCLUSIONES** :

- A fin de buscar una mejor experiencia de usuario, aplicar hojas de estilos a las páginas web, permite que estas se presenten de una manera más amigable y ordenada para el usuario.
- Atender a las necesidades de la experiencia de usuario es una de las prioridades cuando se realiza un diseño para una página web, ya que de esa manera toda la información contenida en la misma será mejor asimilada para el usuario final.


**RECOMENDACIONES** :

- Probar el sitio web en al menos tres navegadores web: Google Chrome, Firefox y Safari.
- En caso de dudas, preguntar al docente encargado.
- Revisar la documentación de apoyo, para así tener mejor entendimiento del tema.
- Haber asistido a las clases de la asignatura.

![imagen](/recursos/31.png)
