# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management.

En esta sección se detallan las decisiones y normas que posibilitarán que el equipo garantice la coherencia a lo largo de todo el ciclo de vida de desarrollo de nuestra solución.

#### 5.1.1. Software Development Environment Configuration

En este apartado se proporcionan los enlaces a las aplicaciones y productos de software creados durante el ciclo del proyecto utilizando los programas correspondientes.

Con ese fin, se organizará en las siguientes secciones:

* Project Management
* Requirements Management
* Product UX/UI Design
* Software Development
* Software Testing
* Software Documentation

Asimismo, se clasificarán los elementos de estas secciones como rutas de referencia (para software basado en modelos Saas) o rutas de descarga (para productos que se ejecuten en las computadoras de los miembros del equipo) para cada uno de los productos de software.

**Project Management**

Esta disciplina se fundamenta en la administración de proyectos y busca principalmente la mejora de procesos y su entorno con el propósito de lograr los resultados esperados.

* Durante el ciclo digital del proyecto, se llevará a cabo la implementación de un producto de software basado en el modelo SaaS, el cual funcionará a través de un navegador web; no obstante, no se desarrollará una versión de la aplicación móvil correspondiente.

**Requirements Management:**

Este proceso se enfoca en asegurar que una organización documente, verifique y satisfaga las necesidades y expectativas de sus clientes, así como las de las partes interesadas internas o externas.

* **Pivotal Tracker:** Esta herramienta se describe como una plataforma que facilita la gestión de las historias de usuario, organizándolas en epopeyas y evaluando su importancia en el programa según su puntuación. Se utilizó debido a su capacidad para permitir que cada miembro del equipo comparta una vista en tiempo real de los avances en cada proyecto, contribuyendo con diferentes secciones o ajustando el flujo del proyecto.

**Product UX/UI Design**

Esta herramienta facilita la creación digital de modelos que se integran en la vida del consumidor. En este caso, estamos desarrollando un modelo de sitio web compatible tanto con computadoras como con dispositivos móviles.

Para lograrlo, utilizamos varias herramientas de diseño y colaboración, que incluyen:

**1\. Uxpressia:** Uxpressia es una plataforma en línea especializada en el mapeo de la trayectoria del cliente. Nos ayuda a crear mapas de impacto y perfiles de usuario, como User Personas, Empathy Maps y Journey Maps. Puedes encontrar más información sobre Uxpressia en [este enlace](https://uxpressia.com/).
**2\. MIRO:** MIRO es una pizarra digital colaborativa en línea que se adapta a diversas actividades colaborativas, como investigación, ideación, creación de lluvias de ideas y mapas mentales. Es una herramienta versátil que facilita el trabajo en equipo. Descubre más sobre MIRO en [su sitio web](https://miro.com/app/dashboard/).
**3\. Figma:** Figma es una herramienta de prototipado web y un editor de gráficos vectoriales. A diferencia de otras herramientas, Figma se ejecuta en línea, lo que permite crear modelos que funcionan tanto en navegadores web como en navegadores móviles. Puedes explorar Figma en [este enlace](https://www.figma.com/design/).
**4\. Lucid Chart:** Esta es una aplicación de diagramación en línea que permite a los usuarios colaborar y trabajar juntos en tiempo real para crear una variedad de diseños, incluidos diagramas UML, mapas mentales, prototipos de software y otros tipos de diagramas. Puedes conocer más acerca de Lucid Chart en [este enlace](https://lucid.app/lucidchart/).
**5\. Overflow:** Overflow es una herramienta de diagramación que ofrece la posibilidad de colaborar en tiempo real. Utilizamos esta herramienta para crear diagramas de Userflows. Si deseas obtener más información sobre Overflow, visita [su sitio web](https://userflow.com/app/).

Estas herramientas nos ayudan a dar vida a nuestros diseños digitales y a garantizar que nuestros productos sean accesibles y atractivos en diferentes plataformas.

**Software Development:**

El desarrollo de software es una metodología aplicada en la creación de productos de software. Esta metodología se utiliza para establecer un proceso que guía el desarrollo del software, y cada uno de sus pasos describe un enfoque específico para las distintas actividades que ocurren durante el proceso.

Aquí te presentamos algunas herramientas y tecnologías clave que utilizaremos en el proyecto:

**1\. GitHub:** GitHub es una plataforma de repositorio comunitario que se utiliza para almacenar y gestionar los avances de proyectos realizados por grupos de personas. Puedes acceder al repositorio del proyecto en [este enlace](https://github.com/LogicVersee).
**2\. Webstorm:** Webstorm es un entorno de desarrollo de JetBrains, una empresa especializada en software, orientado al desarrollo web en JavaScript. Esta herramienta proporciona facilidades para probar sitios web en navegadores como Google Chrome. En nuestro proyecto, utilizaremos webstorm para trabajar con lenguajes como HTML, CSS y JavaScript. Obtén más información sobre WebStorm [aquí](https://www.jetbrains.com/webstorm/).
**3\. HTML:** HTML es un lenguaje de marcado que se utiliza en el desarrollo de sitios web para crear hipertextos y enlazar a otros documentos. Este lenguaje proporciona herramientas para diseñar sitios web y se puede combinar eficazmente con CSS y JavaScript. En nuestro proyecto, utilizaremos HTML para implementar la documentación de la página web. Obtén más información sobre la edición de archivos HTML en WebStorm [aquí](https://www.jetbrains.com/help/idea/editing-html-files.html).
**4\. CSS:** CSS es un lenguaje de diseño destinado al entorno web, que posibilita la mejora de la interfaz de usuario previamente diseñada al añadir elementos como colores y tamaños, entre otros. Además, es posible crear un estilo en CSS y compartirlo en el sitio web creado en HTML. Este lenguaje será empleado en la implementación del diseño de nuestra plataforma web. Puedes obtener más información sobre CSS en [enlace](https://www.jetbrains.com/help/idea/style-sheets.html).
**5\. JavaScript:** Es un lenguaje de programación que es interpretado por otros programas. Funciona bajo el paradigma de programación orientada a objetos (POO), utilizando prototipos en lugar de clases para la implementación. Este lenguaje permite crear dinámicas para los usuarios a través de la lógica de programación y será utilizado en la creación de las interacciones dinámicas en la plataforma web. Puedes encontrar más detalles sobre JavaScript en [enlace](https://www.jetbrains.com/help/idea/javascript-specific-guidelines.html).

Estas herramientas y tecnologías desempeñarán un papel fundamental en la creación exitosa de nuestro producto de software.

**Software Testing:**

Se trata de la acción de evaluar los elementos y el funcionamiento del software sometido a prueba mediante procesos de validación y verificación.

**Lenguaje Gherkin:** Este lenguaje, conocido como DSL (Lenguaje Específico de Dominio), está diseñado específicamente para abordar problemas particulares. Además de poder ser interpretado en código, permite agregar historias de usuario del programa junto con sus componentes correspondientes, como Característica, Escenario, Ejemplo, Esquema de Escenario, Dado, Cuando, Entonces y Y.

**Software Documentation**

Se refiere a textos escritos o ilustraciones que acompañan al software de computadora o están integrados en su código fuente. Esta documentación tiene como objetivo explicar cómo funciona el software o cómo utilizarlo.

### 5.1.2. Source Code Management.

A continuación, se describe la gestión del código fuente, también conocida por sus siglas en inglés como SCM (Source Code Management). Su función principal consiste en rastrear las modificaciones que el equipo llevará a cabo durante el desarrollo de sus proyectos en los repositorios de código fuente. Se utilizará como un sistema de control de versiones que permite seguir los cambios realizados por cada miembro o desarrollador en el proyecto. Además, es importante destacar que utilizaremos **GitHub** como nuestro sistema de control de versiones.

* URL de la organización: [LogicVersee](https://github.com/LogicVersee) - *https://github.com/LogicVersee*
* URL del repositorio de la Landing Page: [LandingPageTecHelp](https://github.com/LogicVersee/LandingPageTecHelp) - *https://github.com/LogicVersee/LandingPageTecHelp*
* URL del repositorio del Front-End: [Front-End TecHelp](https://github.com/LogicVersee/TecHelp-FronEnd) - *https://github.com/LogicVersee/TecHelp-FronEnd*
* URL del repositorio del Back-End: [Back-End TecHelp](https://github.com/LogicVersee/TecHelp-Backend) - *https://github.com/LogicVersee/TecHelp-Backend*

**GitFlow**

GitFlow es un modelo alternativo para la creación de ramas en Git que se ha convertido en una herramienta esencial para muchos desarrolladores en los últimos años. Este flujo de trabajo de control de versiones, desarrollado y popularizado por Vicent Driessen, desempeña un papel crucial en la gestión de las versiones de un código, facilitando la creación ordenada de nuevas características (Features) y correcciones de problemas urgentes (Hotfixes).

![ GitFlow.png](../assets/img/chapter-v/GitFlow.png)

Como se mencionó previamente, GitFlow opera con ramas o "branches". A continuación, se detallan las ramas que se utilizarán en el flujo de trabajo de nuestro proyecto.

* **Main Branches:**
    * **Master:** Esta es la rama principal desde la cual se ramifican todas las demás. Contendrá la versión más reciente junto con las versiones anteriores creadas por los desarrolladores. Aquí se mantendrá el historial oficial de las versiones publicadas.
    * **Develop:** Esta rama puede ser creada a partir de la rama principal (Master) y contendrá todas las características (Features) estables. A través de esta rama, el equipo podrá integrar las funcionalidades de manera efectiva.
* **Support Branches**
A diferencia de las ramas principales, estas ramas secundarias tienen una vida útil limitada, ya que se eliminan al fusionarse con sus ramas primarias.
    * **Feature:**
        * Se ramifica de: develop
        * Debe fusionarse de nuevo en: develop
        * Se utilizan para desarrollar las nuevas funciones que se integrarán en la próxima versión. Es importante destacar que esta rama existe únicamente mientras está en proceso de desarrollo. Sin embargo, una vez que el desarrollador haya completado esa función, se fusionará nuevamente con la rama "develop".
* **Convenciones para nombrar los Features:**
    * **Feture Branch:** feature/name
    **Example:**
        1. feature/welcome
        2. feature/about
        3. feture/myfeture
    * **Conventional Commits**
    El commit debe seguir la siguiente estructura:
    **\<type> [optional scope]: \<description>**
    **[optional body]**
    **[optional footer(s)]**
        * **Type:**
        **1\. feat:** Cuando se agrega un nuevo feature.
        **2\. fix:** cuando corriges un error.
        **3\. build:** cuando afectan los componentes de compilación como la herramienta de compilación, las dependencias o la version del proyecto.
        **4\. chore:** modificaciones privadas del código.
        **5\. docs:** commits que afectan solo a la documentación.
        **6\. refractor:** commits que reescriben o reestructura el código, pero no cambia el comportamiento.
        **7\. perf:** commits especiales que mejoran el rendimiento.
        **8\. style:** commits que no afectan el programa. (espacios en blanco, formato, puntos o comas faltantes).
        **9\. test:** commits que agregan pruebas.
        * **Scope**
        Ofrece información contextual adicional. Aunque es opcional, es beneficioso incluirlo para proporcionar a los desarrolladores una descripción más detallada del commit.
        **\<description>**
        Es una parte obligatoria del formato de los commits. Siempre debemos usar lenguaje en modo imperativo y evitar escribir en mayúsculas
        **[optional body]**
        El cuerpo es opcional y, cuando se utiliza, debe explicar la motivación detrás del cambio y contrastarlo con el comportamiento anterior. Es ideal para mencionar identificadores de problemas y sus relaciones.
        **[optional footer(s)]**
        Esta sección es opcional y puede incluir información sobre cambios significativos. Puede hacer referencia al problema por su identificación y, en esta sección, se incluyen los cambios importantes precedidos por "BREAKING CHANGES:" seguido de uno o dos saltos de línea.
        **Ejemplos:**
            1. feat(welcome): add welcome section
            2. build(release): bump version to 1.0.0
            3. style: remove empty line
            4. feat(sign up): add the button to sign up
            5. feat!: send an email to the costumer when product is shipped
            6. feat: remove ticket list endpoint
            refers to JIRA-1337
            BREAKING CHANGES: ticket enpoints no longer supports list all entites.

Como se mencionó previamente, la gestión de nuestro código fuente se llevará a cabo mediante GitHub. El IDE utilizado en este caso, WebStorm, debe estar vinculado directamente con el repositorio creado por nuestra empresa, MIRAI. De esta manera, cada commit realizado por un miembro del equipo se subirá automáticamente y se cargará en el GitHub de la organización. A continuación, se detallarán las pautas para llevar a cabo este proceso de vinculación de manera correcta:

* **Activar el controlador de versiones del IDE**
Dado que utilizaremos GitHub para gestionar nuestro código, la opción que debe estar habilitada o seleccionada es aquella que indique que el sistema de control se realizará mediante Git. Para hacer esto, siga los siguientes pasos:
    1. Diríjase a la pestaña "VCS" en WebStorm.
    2. Luego, seleccione la opción "Enable Version Control Integration".

![Controlador-Versiones.png](../assets/img/chapter-v/Controlador-Versiones.png)

Ahora se debe seleccionar el sistema de control a través de Git y, por último aceptar los cambios.

![sistema-control-git.png](../assets/img/chapter-v/sistema-control-git.png)

* **Agregar una cuenta de GitHub, siga estos pasos:**
    1. Diríjase a la sección de configuración en su aplicación.
    2. Dentro de la pestaña 'File', busque y seleccione la opción 'Settings'.
    3. En la configuración, busque la sección de cuentas o integraciones.
    4. Agregue su cuenta de GitHub para obtener acceso a los repositorios.

![agregar-cuenta-github.png](../assets/img/chapter-v/agregar-cuenta-github.png)

* **Configurar el nombre de usuario de Git**
Una vez que hayas establecido el sistema de control de versiones que se vinculará con tu IDE, deberás ingresar la cuenta que utilizarás. Para hacerlo, sigue estos pasos:
    1. Realiza un commit en tu proyecto. Durante este proceso, se te solicitará que ingreses tu nombre de usuario de Git.
    2. Después de haberlo añadido, todos los cambios se guardarán en el repositorio especificado en esa plataforma, siempre y cuando des la orden correspondiente.
    3. Para configurar tu nombre de usuario de Git, primero selecciona la opción 'commit' que se encuentra dentro de la pestaña 'Git'.

![primer-commit.png](../assets/img/chapter-v/primer-commit.png)

* **Guardar el progreso en GitHub**
Con todo configurado en WebStorm, ahora puedes subir tu código a GitHub sin problemas. Simplemente dirígete a la opción 'GitHub' que se encuentra en la pestaña 'Git' y comparte el proyecto.

![compartir-GitHub.png](../assets/img/chapter-v/compartir-GitHub.png)

A continuación, debes ingresar el nombre del repositorio y, si lo deseas, proporcionar una breve descripción. Una vez realizado esto, podrás transferir o copiar el código a un repositorio en GitHub.

![ingresar-nombre-repositorio.png](../assets/img/chapter-v/ingresar-nombre-repositorio.png)

* **Configurar la propiedad del repositorio en GitHub**
Ahora, solo necesitas configurar la ubicación del repositorio. El código ya debería estar guardado en GitHub, pero solo estará presente en tu propia cuenta. Para cambiar la propiedad y transferirla a la organización deseada, sigue estos pasos:
    1. Ingresa al repositorio creado en GitHub.
    2. Selecciona la pestaña 'settings'
    3. Dirigite al apartado de 'DangerZone'
    4. Luego da click en 'transfer'
    5. Finalmente elegimos el nuevo lugar para guardar el repositorio.

![Imagen ingresar-repositorio-creado.png](../assets/img/chapter-v/ingresar-repositorio-creado.png)

![pestaña-settings.png](../assets/img/chapter-v/pesta%C3%B1a-settings.png)

![apartado-danger-zone.png](../assets/img/chapter-v/apartado-danger-zone.png)

![click-transfer.png](../assets/img/chapter-v/click-transfer.png)

![nuevo-repo.png](../assets/img/chapter-v/nuevo-repo.png)

* **Configurar control remoto en Git**
Por último, dado que el repositorio ahora está bajo la propiedad de la empresa y depende de ella, es necesario acceder al control remoto del código. Para hacerlo, simplemente ingresa al repositorio creado y copia la URL del repositorio.

![link-clonar-repo.png](../assets/img/chapter-v/link-clonar-repo.png)

Ahora, en el IDE, dirígete a la pestaña 'Git' y elige la opción 'Manage Remotes'.

![manage-remotes.png](../assets/img/chapter-v/manage-remotes.png)

Finalmente, como último paso, debes pegar el enlace copiado en el campo de dirección que solicita el IDE para el control remoto en Git.

![link-control-remoto-repo.png](../assets/img/chapter-v/link-control-remoto-repo.png)

Si has seguido correctamente todos los pasos y directrices mencionados, entonces has completado la configuración con éxito. Ahora, solo necesitas realizar un commit y los cambios que hayas efectuado se guardarán en el repositorio de GitHub, ya sea que hayas realizado modificaciones en el código, creado nuevas ramas u otras acciones.

### 5.1.3. Source Code Style Guide & Conventions.

En esta sección, se presentarán las pautas, convenciones, estilos y principios que se aplicarán a cada uno de los lenguajes utilizados en la creación de nuestra aplicación. La observancia de este conjunto de directrices reviste una importancia fundamental, ya que tiene el propósito de mantener la calidad estructural del software, mejorar la legibilidad del código fuente y simplificar el mantenimiento del mismo.

Dado que en este proyecto se emplearán varios lenguajes, como HTML, CSS, JavaScript, Java y TypeScript para el desarrollo de la plataforma web, así como Gherkin para el proceso de pruebas del programa, a continuación, se detallarán y describirán las reglas y recomendaciones generales que se tendrán en cuenta al utilizarlos.

**Nomenclatura General**

Para los nombres de variables, objetos, elementos y funciones que se utilicen en el proyecto, se emplearán términos en inglés que estén relacionados con lo que representan. No se utilizarán mayúsculas en estos nombres, ya que, de acuerdo con W3Schools (sin fecha), la combinación de mayúsculas y minúsculas puede dificultar la legibilidad del código. En su lugar, se optará por utilizar exclusivamente letras minúsculas, lo que contribuirá a una mayor claridad en el código.

Ejemplos de nomenclatura estándar, siguiendo las recomendaciones de Google (s.f.):

```
.gallery {}
.video {}
.login {}
```

Estas pautas de nomenclatura ayudarán a mantener una coherencia en el código y facilitarán su comprensión.

**Sangría**

Cuando se trabaje con HTML, CSS y/o JavaScript, se aplicará un espaciado de dos espacios antes de cada línea que se encuentre dentro de un bloque. Según W3Schools (sin fecha), no se recomienda el uso de la tecla "Tabulación". A continuación, se muestra un ejemplo de la sangría estándar en HTML siguiendo las directrices de W3Schools (s.f.):

``` html
<!DOCTYPE html>
<html>
  <head>
    <title>Título del Documento</title>
  </head>
  <body>
    <h1>Encabezado Principal</h1>
    <p>Este es un párrafo dentro del cuerpo del documento.</p>
  </body>
</html>
```

Este estilo de sangría proporciona una estructura clara y organizada al código, lo que facilita su lectura y mantenimiento.

Ejemplo de formato estándar de sangría en CSS, conforme a las recomendaciones de W3Schools (s.f):

``` CSS
html {
  background: #fff; /* Fondo blanco */
  color: #404;     /* Color de texto gris */
}
```

Ejemplo de nomenclatura estándar de la sangría en JavaScript según W3School (s.f.):

``` JavaScript
function toCelsius(fahrenheit) {
  return (5 / 9) * (fahrenheit - 32);
}
```

**Especificaciones generales**

A continuación, detallaremos las reglas específicas necesarias para comprender el código de nuestra aplicación en cada lenguaje.

**HTML:**

HTML, acrónimo de HyperText Markup Language en inglés, es un lenguaje de marcado que se utiliza para definir la estructura de una página web. También incluye funcionalidades que permiten controlar el comportamiento de diferentes elementos del contenido de la página, como cambiar el tamaño del texto o aplicar formato cursiva, entre otros. En nuestro proyecto, emplearemos HTML5, y a continuación, se presentan las características y directrices que debemos seguir para utilizar este lenguaje de la siguiente manera:

* **Declare Document Type**
La declaración del tipo de documento debe realizarse en la primera línea del código. Según las recomendaciones de Google (s.f.), se prefiere la sintaxis de HTML5 para todos los documentos HTML. Para declararla, simplemente copia lo siguiente:

``` html
<!DOCTYPE html>
```

* **Blank Lines**
Cada vez que comiences un nuevo bloque, lista o tabla de gran longitud, es recomendable dejar una línea en blanco después del elemento anterior para mejorar la legibilidad y la presentación del código, de acuerdo con las pautas de W3Schools (s.f.):

``` html
<!DOCTYPE html>
<html>
<head>
<title>Animales Exóticos</title>
</head>
<body>
<h1>Lemur de Madagascar</h1>
<p>El lémur de Madagascar es un primate endémico de la isla de Madagascar en el Océano Índico.</p>

<h1>Pangolín</h1>
<p>El pangolín es un mamífero cubierto de escamas que se encuentra en regiones de África y Asia.</p>

<h1>Ocelote</h1>
<p>El ocelote es un felino salvaje que habita en América del Sur y Central, conocido por su pelaje moteado.</p>
</body>
</html>
```

Esta práctica de dejar una línea en blanco mejora la estructura y legibilidad del código HTML.

* **Quote attribute Values**
Para los valores de los atributos, es común utilizar comillas dobles alrededor de ellos, aunque esta característica no sea obligatoria. Según W3Schools (sin fecha), esto mejora la legibilidad del código y es una práctica común entre los desarrolladores. Aquí tienes un ejemplo:

``` html
<table class="striped">
```

Este enfoque de usar comillas dobles alrededor de los valores de los atributos es ampliamente aceptado y recomendado en la comunidad de desarrollo web.

* **Never Skip the \<title> Element**
El elemento `<title>` permite que las páginas aparezcan en la lista de resultados al realizar búsquedas en un navegador web. Además, este elemento es responsable de proporcionar el nombre de la página cuando se agrega a marcadores o favoritos. A continuación, se muestra un ejemplo de su uso:

``` html
<title>Guía de Estilo HTML y Convenciones de Codificación</title>
```

Este elemento es esencial para mejorar la identificación y accesibilidad de una página web.

* **HTML Line-Wrapping**
A pesar de que en un documento HTML no exista un límite estricto en la cantidad de palabras por línea, no se recomienda generar líneas de código excesivamente largas. De hecho, hacerlo dificulta la legibilidad del código. Para continuar en la siguiente línea, se deben utilizar al menos cuatro espacios para distinguir elementos secundarios. Aquí tienes un ejemplo basado en las recomendaciones de Google (sin fecha):

``` html
<button mat-icon-button color='primary' class="menu-button"
(click)="openMenu()">
<mat-icon>menu</mat-icon>
</button>
```

Este estilo de formateo ayuda a mantener un código más legible y facilita la identificación de los elementos y su jerarquía en la estructura del documento HTML.

**CSS:**

CSS, conocido por sus siglas en inglés, Cascading Style Sheets (Hojas de Estilo en Cascada), es un lenguaje que se enfoca en definir y mejorar la presentación de un documento basado en HTML. A continuación, se presentan las directrices que debemos seguir al utilizar CSS:

* **Shorthand Properties**
Se recomienda utilizar abreviaturas de propiedades y declarar los campos de los elementos en la menor cantidad de líneas posible, según las pautas de Google (sin fecha). Esto aumenta la eficiencia del código y lo hace más legible. Además, se debe evitar agregar unidades después del valor cero. Aquí tienes un ejemplo:

``` css
border-top: 0;
font: 100%/1.6 palatino, georgia, serif;
padding: 0 1em 0;
```

Siguiendo estas recomendaciones, se puede lograr un código CSS más conciso y fácil de entender.

* **Declaration Stops**
Es importante incluir un punto y coma al final de cada declaración en CSS, al igual que en la mayoría de los lenguajes de programación. Siguiendo las pautas de Google (sin fecha), esta práctica contribuye a mantener la coherencia en el código. A continuación, se muestra un ejemplo:

``` css
html {
  background: #fff;
  color: #404;
}
```

El uso consistente de puntos y comas al final de las declaraciones CSS ayuda a prevenir errores y mejora la claridad del código.

* **Property Name Stops**
Es necesario incluir un espacio entre los dos puntos que siguen al nombre de una propiedad y el valor correspondiente. Siempre se debe colocar un solo espacio después de los dos puntos, pero no antes. A continuación, se muestra un ejemplo siguiendo esta convención estándar de Google (s.f):

``` css
html {
  background: #fff;
  color: #404;
}
```

Mantener esta consistencia en la colocación de espacios ayuda a que el código CSS sea más legible y fácil de entender.

* **Declaration Block Separation**
Es esencial utilizar un espacio separador después del nombre de un selector de elemento y antes de la llave que inicia un bloque de declaración CSS. Además, la llave de apertura del bloque debe estar en la misma línea que el selector. Aquí tienes un ejemplo siguiendo esta convención estándar de Google (sin fecha):

``` css
html {
  background: #fff;
  color: #404;
}
```

El cumplimiento de estas directrices ayuda a mantener la consistencia y la legibilidad en el código CSS.

* **CSS quotation Marks**
No se deben utilizar comillas dobles (`"`) en el código CSS; en su lugar, se permiten y deben emplearse comillas simples (`'`) únicamente para selectores de atributos y valores de propiedades.
Ejemplo conforme a las pautas estándar de Google (sin fecha):

``` css
html {
  font-family: 'open sans', arial, sans-serif;
}
```

Este ejemplo demuestra el uso de comillas simples para encerrar el valor del atributo `font-family` en CSS, lo cual es una práctica común y aceptada.

**JavaScript**

JavaScript es un lenguaje de programación que permite especificar de manera precisa las acciones que debe realizar el navegador web, incluyendo el orden de ejecución de tareas y la frecuencia con la que se deben llevar a cabo. A continuación, se presentan las pautas para el uso de JavaScript en nuestro proyecto:

* **Spaces around operators**
Es importante añadir espacios alrededor de cada operador matemático y comas que se utilicen en el código JavaScript. A continuación, se muestra un ejemplo siguiendo la convención estándar de W3Schools (sin fecha):

``` javascript
let x = y + z;
const myArray = ['Volvo', 'Saab', 'Fiat'];
```

El uso consistente de espacios alrededor de operadores y comas mejora la legibilidad del código JavaScript.

* **Simple Statement's End**
Es fundamental que una instrucción simple finalice con un punto y coma, tal como es el caso en muchos otros lenguajes de programación. A continuación, se muestra un ejemplo que cumple con la convención estándar de W3Schools (sin fecha):

``` javascript
let x = v + 7;
const myArray = ['Volvo', 'Saab', 'Fiat'];
```

El uso de punto y coma al final de cada instrucción ayuda a garantizar la estructura correcta del código JavaScript y a evitar posibles errores.

* **Beginning and End of Function**
Un bloque de función debe incluir una llave al final de la primera línea, de modo que el cierre de la función esté en la última línea, sin necesidad de un punto y coma. Este mismo principio se aplica a las estructuras condicionales y los bucles. A continuación, se muestra un ejemplo que cumple con la convención estándar de W3Schools (sin fecha):

``` javascript
function toCelsius(fahrenheit) {
  return (5 / 9) * (fahrenheit - 32);
}
```

En este ejemplo, la función `toCelsius` está formateada de acuerdo con estas pautas, con la llave de apertura en la misma línea que la declaración de la función y la llave de cierre en la última línea. Esto ayuda a mantener la estructura y la legibilidad del código JavaScript.

* **Object Rules**
Para la creación de un objeto, al igual que en una función, se comienza con una llave al final de la primera línea. Sin embargo, en este caso, la llave de cierre debe ir seguida de un punto y coma. Para definir las propiedades del objeto, se utilizan dos puntos y un espacio para separar el nombre de la propiedad de su valor. Si el valor es un string, se debe encerrar entre comillas dobles. A continuación, se muestra un ejemplo siguiendo la convención estándar de W3Schools (sin fecha):

``` javascript
const person = {
  firstName: "John",
  lastName: "Doe",
  age: 50,
  eyeColor: "blue"
};
```

En este ejemplo, el objeto `person` está formateado de acuerdo con estas pautas, lo que mejora la legibilidad y la estructura del código JavaScript.

**Gherking:**

Gherkin es un Lenguaje Específico de Dominio (DSL por sus siglas en inglés) que se utiliza para resolver problemas específicos mediante la generación de casos de prueba que validan una característica en diversos escenarios. Gherkin incluye varios elementos, entre los cuales los más conocidos y utilizados son Feature, Scenario, Example, Given, When y Then. A continuación, se presentan las pautas que debemos seguir al utilizar Gherkin en nuestro código:

* **Discernible Given-When-Then Blocks**
Es importante aplicar sangría a los elementos que representan los pasos a seguir en un escenario. En el caso de "And", se debe aplicar una sangría adicional. Siguiendo la recomendación de Keiblinger (2021), este enfoque ayuda a identificar rápidamente las partes que componen un escenario. A continuación, se muestra un ejemplo:

``` gherkin
Scenario: Ingreso de requisitos con claridad
  Given que en el formulario de ingreso de oferta laboral
  When escribo claramente los requisitos
  Then se mostrará el mensaje
  And mi oferta solo aparecerá a quienes cumplan con estos
  And se habilita la opción
```

En este ejemplo, se ha aplicado la sangría de manera adecuada para resaltar los pasos del escenario, y se ha utilizado una sangría adicional para los pasos que comienzan con "And". Esto mejora la legibilidad y la comprensión de los escenarios escritos en Gherkin.

* **Step with Tables**
Conforme a la recomendación de Keiblinger (2021), cuando sea necesario introducir valores en partes del escenario, se debe emplear una tabla o crear un formulario que refleje esa parte del escenario. Antes de esta representación, se deben colocar dos puntos. Aquí tienes un ejemplo:

``` gherkin
Then se mostrará el mensaje:
  | Mensaje |
  | Se completaron los requisitos adecuadamente |
```

Este enfoque permite una representación clara y estructurada de los valores relacionados con una parte específica del escenario.

* **Reducing Noise**
Para evitar la acumulación de demasiadas líneas de código en un escenario, es recomendable incluir valores por defecto dentro de los pasos para campos que no sean muy relevantes para ese escenario en particular. Los valores "estándar" que se coloquen deben estar entre comillas simples. Siguiendo el consejo de Keiblinger (2021), esta práctica contribuye significativamente a la reducción del tamaño del código. A continuación, se muestra un ejemplo:

``` gherkin
When escribo claramente los requisitos 'dominio en C'
```

En este ejemplo, se ha incluido un valor por defecto ('dominio en C') entre comillas simples dentro del paso para representar un campo que no es esencial en ese escenario. Esto ayuda a mantener el escenario más conciso y legible.

* **Scenarios Separator**
Para separar dos escenarios, se debe insertar un salto de línea y, según la sugerencia de Keiblinger (2021), si es posible, agregar una línea de comentario para facilitar la visualización de estos. De esta manera, se identifica rápidamente el inicio y el fin de un escenario. A continuación, se presenta un ejemplo:

``` gherkin
Scenario: Ingreso de requisitos con claridad
Given que en el formulario de ingreso de oferta laboral
When escribo claramente los requisitos
Then se mostrará el mensaje
And mi oferta solo aparecerá a quienes cumplan con estos
And se habilita la opción

# --------------------------

Scenario: Otro escenario
Given que en otro contexto
When ocurre algo diferente
Then se muestra otro resultado
```

En este ejemplo, se ha agregado un salto de línea entre los dos escenarios y se ha incluido una línea de comentario como separador para mejorar la visualización y la identificación de cada escenario.

**Java:**

Java es una plataforma informática de lenguaje de programación que fue desarrollada por Sun Microsystems en 1995. A lo largo de los años, ha experimentado una evolución significativa y ha desempeñado un papel fundamental en la creación de numerosos servicios y aplicaciones que conforman gran parte del mundo digital actual. A continuación, se presentan las pautas para utilizar Java en nuestro proyecto:

* **Clases e interfaces en Java**
Los nombres de las clases deben ser sustantivos y seguir una convención de mayúsculas y minúsculas, con la primera letra de cada palabra interna en mayúscula. Del mismo modo, los nombres de las interfaces deben comenzar con una letra mayúscula, al igual que los nombres de las clases. Se debe utilizar palabras completas y evitar el uso de acrónimos y abreviaturas. Aquí tienes un ejemplo:

``` java
interface Bicycle
class MountainBike implements Bicycle
interface Sport
class Football implements Sport
```

En este ejemplo, se han seguido las pautas para nombrar clases e interfaces de manera clara y legible.

* **Métodos en Java**
Los métodos deben seguir una convención de nombres que utilice verbos y mantenga la combinación de mayúsculas y minúsculas, con la primera letra de cada palabra interna (a partir de la segunda) en mayúscula. A continuación, se presenta un ejemplo:

``` java
void changeGear(int newValue);
void speedUp(int increment);
void applyBrakes(int decrement);
```

En este ejemplo, los nombres de los métodos siguen la convención recomendada, lo que los hace descriptivos y legibles.

* **Variables en Java**
Los nombres de las variables deben ser concisos pero significativos, evitando comenzar con un guión bajo (\_) o caracteres especiales como el signo de dólar ($). Deben ser mnemotécnicos, es decir, diseñados de manera que indiquen claramente su propósito a un observador casual. Generalmente, se deben evitar los nombres de una sola letra para las variables, a menos que se utilicen como variables temporales. Los nombres comunes para variables temporales son: i, j, k, m y n para enteros, y c, d y e para caracteres. A continuación, se muestra un ejemplo:

``` java
// Variables para la clase MountainBike
int speed = 0;
int gear = 1;
```

En este ejemplo, se han utilizado nombres de variables significativos y legibles, lo que facilita la comprensión de su propósito en el contexto de la clase MountainBike.

* **Excepciones**
A menos que se justifique en un comentario, es extremadamente raro que sea apropiado no realizar ninguna acción en respuesta a una excepción detectada. En el caso en que no sea necesario realizar ninguna acción en un bloque catch, la razón debe explicarse de manera clara en un comentario. A continuación, se presenta un ejemplo:

``` java
try {
    int i = Integer.parseInt(response);
    return handleNumericResponse(i);
} catch (NumberFormatException ok) {
    // No es un valor numérico; eso está bien, simplemente continúa
    return handleTextResponse(response);
}
```

En este ejemplo, se ha incluido un comentario para explicar por qué no se realiza ninguna acción en el bloque catch cuando se detecta una excepción de formato numérico. Esto ayuda a comprender el motivo detrás de esta decisión en el código.
En el contexto de las pruebas, es aceptable ignorar una excepción detectada sin comentarios si su nombre es o comienza con "expected". Esto es un patrón común para verificar que el código bajo prueba arroje una excepción del tipo esperado, por lo que no se requiere un comentario adicional en este caso. A continuación, se muestra un ejemplo:

``` java
try {
    emptyStack.pop();
    fail();
} catch (NoSuchElementException expected) {
    // No es necesario comentar aquí, ya que esperábamos esta excepción
}
```

En este ejemplo, la excepción "expected" no requiere un comentario adicional, ya que el nombre mismo indica que es esperada como parte de la prueba.
La anotación `@Override` se utiliza para marcar un método cuando es legal hacerlo. Esto incluye un método de clase que anula un método de una superclase, un método de clase que implementa un método de una interfaz y un método de interfaz que vuelve a especificar un método de una superinterfaz.
Excepción: Se puede omitir la anotación `@Override` cuando el método principal está marcado como `@Deprecated`.

**Typescript**

JavaScript es uno de los lenguajes más populares y ha experimentado un rápido avance y mejora en los últimos años. A continuación, se presentan las pautas para utilizar JavaScript en nuestro proyecto:

En TypeScript, se recomienda que las variables se declaren en minúsculas y se especifique el tipo de dato utilizando dos puntos después del nombre de la variable. Aquí tienes ejemplos de cómo declarar y asignar valores a variables en TypeScript:

``` typescript
// Definición e inicialización separadas
let edad: number;
edad = 20;

// Definición e inicialización en la misma línea.
let edadAitor: number = 18;
```

Además, en TypeScript, se siguen las mismas convenciones que se utilizan en JavaScript.

### 5.1.4. Software Deployment Configuration.

Dado que hemos mencionado anteriormente, la administración de nuestro código fuente se llevará a cabo mediante GitHub. Además, utilizaremos GitHub Pages para la publicación y despliegue de la página.

En cuanto al desarrollo de la página de inicio de TecHelp, hemos empleado las siguientes herramientas:

* **HTML:** Es el lenguaje de marcado que hemos utilizado para estructurar nuestro Landing Page

![vista-html.png](../assets/img/chapter-v/vista-html.png)

* **CSS:** Nos ayudó con la parte de diseño de interface para que esta sea interactubale con los visitantes de la Langding Page

![vista-css](../assets/img/chapter-v/vista-css.png)

* **git:**

Git es un sistema de control de versiones diseñado para optimizar la eficiencia y la compatibilidad de versiones. Esta herramienta desempeñó un papel fundamental en nuestra colaboración en equipo durante el desarrollo de la Landing Page.

![logo-git.png](../assets/img/chapter-v/logo-git.png)

**GitHub**

GitHub: Plataforma de desarrollo colaborativo.

![logo-GitHub.png](../assets/img/chapter-v//logo-GitHub.png)

**Git Flow**

Git Flow: Nos permitió controlar el avance de cada uno de nuestros
integrantes con respecto al desarrollo del Landing Page.

![GitFlow.png](../assets/img/chapter-v//GitFlow.png)

**Git Hub Pages**

Git Hub Pages: Servicio de Github que nos permitió alojar nuestra
lading page.

![github-pages.png](../assets/img/chapter-v/github-pages.png)

## 5.2. Landing Page, Services & Applications Implementation.

### 5.2.1. Sprint 1

En la fase inicial de nuestro proyecto, nos propusimos llevar a cabo la implementación del diseño de nuestra Landing Page utilizando WebStorm como entorno de desarrollo. Esto implica que al concluir el Sprint, todas las secciones, ya sea Home, Services, Pricing, Testimonials o About Us, deben estar completadas. A continuación, adjuntamos imágenes que ilustran cómo gestionamos las tareas en Pivotal Tracker.

**Repositorio:** [LandingPageTecHelp](https://github.com/LogicVersee/LandingPageTecHelp) - https://github.com/LogicVersee/LandingPageTecHelp

**LandingPageDeployed:** [TecHelp](https://logicversee.github.io/LandingPageTecHelp/) - https://logicversee.github.io/LandingPageTecHelp/

#### 5.2.1.1. Sprint Planning 1.

Para el desarrollo de este sprint el equipo ha considerado en total 29 horas :

![sprint1.png](../assets/img/chapter-v/sprint1.jpg)


<table>
    <thead>
        <tr>
            <th>Sprint #</th>
            <th>Sprint 1</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td colspan="2"><b>Sprint Planning Background</b></td>
        </tr>
        <tr>
            <td>Date</td>
            <td>yy/mm/dd</td>
        </tr>
        <tr>
            <td>Time</td>
            <td>11:00 PM</td>
        </tr>
        <tr>
            <td>Location</td>
            <td>Discord meeting</td>
        </tr>
        <tr>
            <td>Prepared by</td>
            <td>Brayan Morales</td>
        </tr>
        <tr>
            <td>Atendees (to planning meeting)</td>
            <td>
                Gonzalo Saldaña, Giovanni Ramos, Luis Lagos, Sebastián Ramirez 
            </td>
        </tr>
        <tr>
            <td>Sprint 1 Review Summary</td>
            <td>
                La opinion del product owner y las partes interesadas con respecto al avance realizado al concluir el sprint 3  fue el esperado.
            </td>
        </tr>
        <tr>
            <td>Sprint 1 Retrospective Summary</td>
            <td>
                Implementación de la primera version delanding page con algunas deficiencias en cuanto a diseño y usuablidad 
            </td>
        </tr>
        <tr>
            <td colspan="2"><b>Sprint Goal & User Stories</b></td>
        </tr>
        <tr>
            <td>Sprint 1 Goal</td>
            <td>
                Concluir y mejorar las intefaces y secciones de la landing page
            </td>
        </tr>
        <tr>
            <td>Sprint 1 Velocity</td>
            <td>
                30
            </td>
        </tr>
        <tr>
            <td>Sum of story points</td>
            <td>
                29
            </td>
        </tr>
    </tbody>
</table>


#### 5.2.1.2. Sprint Backlog 1.

A continuación, compartimos imágenes que demuestran cómo gestionamos las tareas en Pivotal Tracker. Posteriormente, presentamos la tabla de control de estado del Sprint.

<table>
  <tr>
    <td> <strong>Sprint #</strong></td>
    <td align="center" colspan="7"> <strong>Sprint 1</strong> </td>
  </tr>

   <tr>
    <td align="center" colspan="2"> <strong>User Story</strong></td>
    <td align="center" colspan="6"> <strong>Work-item/Task</strong></td>
  </tr>
  <tr>
    <td align="center"> <strong>ID</strong> </td>
    <td align="center"> <strong>Title<strong></td>
    <td align="center"> <strong>ID</strong> </td>
    <td align="center"> <strong>Title<strong></td>
    <td align="center"> <strong>Description<strong></td>
    <td align="center"> <strong>Estimation (Hours)<strong></td>
    <td align="center"> <strong>Assigned To<strong></td>
    <td align="center"> <strong> Status (To-do/In-Process/To-Review/Done)  <strong></td>
  </tr>
  <!---------------------------------------------------------------------- -->
  <tr>
    <td rowspan="4" align="center"> ID </td>
    <td rowspan="4" align="center"> US14: Navegar libremente por la Landing Page </td>
    <td align="center"> TA01 </td>
    <td align="center"> Añadir lista de etiquetas</td>
    <td align="justify"> Se añadirán las etiquetas de home, services, membreship, contac-us, about-us.</td>
    <td align="center"> 1 </td>
    <td align="center"> Luis Lagos</td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Vincular las secciones </td>
    <td align="center"> se determina la esturctura e IDs de las secciones y se vincula las etiquetas a estas para luego comenzar a codificar estas</td>
    <td align="center"> 1</td>
    <td align="center"> Luis Lagos</td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td align="center"> TA03 </td>
    <td align="center"> Añadir Logo y estilos del nav</td>
    <td align="center"> Se añede el logo de la solución planteada y se implementa los estilos del toolbar </td>
    <td align="center"> 3</td>
    <td align="center"> Luis Lagos</td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td align="center"> TA04 </td>
    <td align="center"> Añadir botones de modo oscuro e idioma.</td>
    <td align="center"> Se añeden los botones de cambio de idioma y boton de modo oscuro para hacerlo mas agaradable al posible usuario</td>
    <td align="center"> 2</td>
    <td align="center"> Luis Lagos</td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td rowspan="3" align="center"> ID </td>
    <td rowspan="3" align="center"> US 15: Apartado de contacto con el Startup</td>
    <td align="center"> TA01 </td>
    <td align="center"> Añadir título y descripción</td>
    <td align="justify"> Se añadirá el tiítulo correspodniente a la sección a realizar y redactar una oración inivitando a las personas a escribirnos</td>
    <td align="center"> 2</td>
    <td align="center"> Gonzalo Saldaña</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Añadir formulario</td>
    <td align="justify"> Se añadirá un formulario donde los usuarios objetivos deben ingresas sus nombres, medio de contacto y una descripción sobre la duda que tienen</td>
    <td align="center"> 1</td>
    <td align="center"> Gonzalo Saldaña</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA03 </td>
    <td align="center"> Añadir botón de enviar, imagen y estilos</td>
    <td align="justify"> Se añadirá una imagen llamativa sobre lo que ofrece nuestro software, se implementará un botón para enviar el contenido del formulario y se agregarán los estilos correspondientes. </td>
    <td align="center"> 3 </td>
    <td align="center"> Gonzalo Saldaña</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td rowspan="2" align="center"> ID </td>
    <td rowspan="2" align="center"> US 16: Beneficios de la aplicación</td>
    <td align="center"> TA01 </td>
    <td align="center"> Se añadirá el titulo y descripción de la sección</td>
    <td align="center"> Se añadirá una pregunta a modo de título (¿Por qué TecHelp?), descripciónes incitando a que usen nuestra solucón y lo que ofrece para cada tipo de posible usuario</td>
    <td align="center"> 1</td>
    <td align="center"> Sebastián Ramirez</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Organizar las beneficios en dos card</td>
    <td align="center"> Se organizará el contenido de la seccion de beneficios mediante cards para cada segmento objetivo</td>
    <td align="center"> 2</td>
    <td align="center"> Sebastián Ramirez</td>
    <td align="center"> Done</td>
  </tr>

   <tr>
    <td rowspan="3" align="center"> ID </td>
    <td rowspan="3" align="center"> US 19: Mostrar los planes disponibles</td>
    <td align="center"> TA01 </td>
    <td align="center"> Añadir título y decripción</td>
    <td align="center"> Se añade el título a manera de pregunta para captar la atención de nuestros posibles usuarios e invitamos a suscribirce a a nuestros planes </td>
    <td align="center"> 3</td>
    <td align="center"> Brayan Morales</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Cards para organizar las membresias</td>
    <td align="center"> Se agregarán cards para organizar la información de las membreisas e invitar a que sean parte de nostros con botones para suscribirse</td>
    <td align="center"> 2</td>
    <td align="center"> Brayan Morales</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA03 </td>
    <td align="center"> Botones de suscripciones y estilos de seccion</td>
    <td align="center"> Se añadirán las botones correspondientes a cada tipo de membresia y además se ñadirán los estilos correspondientes para que la sección sea más consistente</td>
    <td align="center"> 2</td>
    <td align="center"> Brayan Morales</td>
    <td align="center"> Done</td>
  </tr>

   <tr>
    <td rowspan="3" align="center"> ID </td>
    <td rowspan="3" align="center">  US 18: Información del startup</td>
    <td align="center"> TA01 </td>
    <td align="center"> Titulo y descripción</td>
    <td align="center"> Se agregará un título para diferenciar la sección y los estilos corresponidentes para distinguir una sección de la otra.</td>
    <td align="center"> 1</td>
    <td align="center"> Giovanni Ramos</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Descripción de integrantes</td>
    <td align="center"> Se agregará una descripción breve de los integrante del equipo que se está dedicando al proceso de desarrollo de la solución </td>
    <td align="center"> 2</td>
    <td align="center"> Giovanni Ramos</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA03 </td>
    <td align="center"> Organizar el contenido en cards</td>
    <td align="center"> Se agregarán los estilos correspondientes para separar cada integrante en cards para tener una mejor organización y cisualización de las mismas</td>
    <td align="center"> 3</td>
    <td align="center"> Giovanni Ramos</td>
    <td align="center"> Done</td>
  </tr>
</table>

##### 5.2.1.3. Development Evidence for Sprint Review.

<table>
  <tr>
    <td align ="center" > <strong>Repository</strong></td>
    <td  align ="center" > <strong>Branch</strong></td>
    <td  align ="center" > <strong>Commit ID</strong></td>
    <td  align ="center" > <strong>Commit message</strong></td>
    <td  align ="center" > <strong>Commit Masagge body</strong></td>
    <td  align ="center" > <strong>Commit on (date)</strong></td>
  </tr>

  <tr>
    <td rowspan="16" align="center"> https://github.com/LogicVersee/LandingPageTecHelp </td>
    <td align="center"> main</td>
    <td align="center"> 8bd0d4f30e77a3be35b7af58773bc12944e073dc</td>
    <td align="center"> chore: initial commit</td>
    <td align="center"> ---</td>
    <td align="center"> 18/09/2023</td>
  </tr>

  <tr>
    <td align="center"> main</td>
    <td align="center" > ca8a2540c8796fc2b32f8718539448faa82c3ae9</td>
    <td align="center"> chore: added multimedia material, style documents and scripts</td>
    <td align="center"> ---</td>
    <td align="center"> 18/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/header</td>
    <td align="center"> f69c7dbc27c7a4f515a9b5a23b1472cb084c96b5</td>
    <td align="center"> chore(Directory): Added the assests folder and its components</td>
    <td align="center"> ---</td>
    <td align="center"> 18/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/header</td>
    <td align="center"> 2ec418f0a5fbda0e26c7aa2d650bd306ae7f4541</td>
    <td align="center"> feat(Header): Added section Header</td>
    <td align="center"> ---</td>
    <td align="center"> 18/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/header</td>
    <td align="center"> 0e688ffbef8d6b73ffad101e1a6d5dab191575d1</td>
    <td align="center"> feat(Style): Added Header´s styles</td>
    <td align="center"> ---</td>
    <td align="center"> 18/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/header</td>
    <td align="center"> 2210435613199de5ec9d66a689ae7decae31a1f7</td>
    <td align="center"> feat(Header): Added english header</td>
    <td align="center"> ---</td>
    <td align="center"> 19/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/hero</td>
    <td align="center"> 1537977c0bc20e4712ec12aa07aee20aac52d2a6</td>
    <td align="center"> Merge remote-tracking branch 'origin/feature/header' into developer</td>
    <td align="center"> ---</td>
    <td align="center"> 18/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/hero</td>
    <td align="center"> 91cbbc1c6c47845a46293492ec728657a6eedf06</td>
    <td align="center"> feat(hero): add hero section</td>
    <td align="center"> ---</td>
    <td align="center"> 18/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/hero</td>
    <td align="center"> 20f00eaec38c4eb4b3b7feede2c73c5025e5a44c</td>
    <td align="center"> feat(hero): add styles</td>
    <td align="center"> ---</td>
    <td align="center"> 19/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/benefits</td>
    <td align="center"> d4be1d819cccada6d2d8f4773fc1f12db82af7ab</td>
    <td align="center"> feat(benefits): Added and fixed benefits and hero sections.</td>
    <td align="center"> ---</td>
    <td align="center"> 22/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/membreship</td>
    <td align="center"> 8047ff4ebd05ac2ab5bb65db1f762baa589929a0</td>
    <td align="center"> feat(membreship): Added section membreship.</td>
    <td align="center"> ---</td>
    <td align="center"> 22/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/contact </td>
    <td align="center"> d71ef61879d966483fbbf4ebaf69d2a2f457e47b</td>
    <td align="center"> feat(contact-us): added section contact-us.</td>
    <td align="center"> ---</td>
    <td align="center"> 22/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/about-us-footer</td>
    <td align="center"> 7cf0543b50c76a55325d9d3049d95dc3746f4e73</td>
    <td align="center"> feat(about us): added about us section</td>
    <td align="center"> ---</td>
    <td align="center"> 23/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/about-us-footer</td>
    <td align="center"> ffb6ebeb40c7e98b9cd410c1f51471979306c1f5</td>
    <td align="center"> feat(footer): added footer section</td>
    <td align="center"> ---</td>
    <td align="center"> 23/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/release-1.0</td>
    <td align="center"> b1dd6d99a64e19f441f89cb542e2123ccf06ce2d</td>
    <td align="center"> feat: merge developer into release-1.0</td>
    <td align="center"> ---</td>
    <td align="center"> 23/09/2023</td>
  </tr>

</table>


##### 5.2.1.4. Testing Suite Evidence for Sprint Review.

En el Sprint 1, se completaron únicamente las características relacionadas con el sitio web estático, sin que se llevara a cabo la implementación de los Web Services.

##### 5.2.1.5. Execution Evidence for Sprint Review.

Después de completar el Sprint 1, logramos implementar todas las secciones de nuestro Landing Page para garantizar una visualización perfecta. Además, le dimos un formato atractivo que captura la atención del usuario hacia sus diferentes componentes. También agregamos métodos de navegación en la página, como botones ubicados al principio y al final, que te permiten moverte fácilmente de una sección a otra. A continuación, te mostraremos los avances a través de imágenes del resultado obtenido.

Es importante destacar que el objetivo principal del Landing Page es convertir a los visitantes en futuros clientes o usuarios habituales de nuestro servicio. Para lograrlo, utilizamos llamados a la acción (Call To Action) que los guían hacia la aplicación web.

A continuación, te presentamos capturas de pantalla del desarrollo del Landing Page:

En la parte superior, se encuentra el encabezado (Header) que incluye botones de inicio (Home), servicios (Service), membresias (membership), cantacto (Contact-Us), información sobre nosotros (About Us), un botón para cambiar el idioma entre inglés y español y un botón para cambiar el entorno a modo oscuro. Estos elementos permiten a los visitantes desplazarse fácilmente a la sección que deseen visualizar.

![header.png](../assets/img/chapter-v/header.png)
**Imagen 1:** Encabezado y botones de desplazamiento.

Se presenta la sección "Hero", que incluye una breve descripción y una frase representativa de TecHelp. Además, permite iniciar el uso del servicio web y proporciona una imagen relacionada con el mismo.

![hero.png](../assets/img/chapter-v/hero.png)
**Imagen 2:** Sección Hero.

Se presenta la sección de beneficios del servicio para cada segmento objetivo identificado por el equipo.

![servis.png](../assets/img/chapter-v/servis.png)
**Imagen 3:** Sección benefits ó service.

Se presenta la sección membership de la landing page, en esta sección nuestros posibles usuarios podrán ver los tipos de membresias y sus costos.

![membership.png](../assets/img/chapter-v/membership.png)
**Imagen 4:** Sección membership.

A continuación se presenta la sección de contacto, aquí nuestros posibles usuarios pueden realizarnos preguntas personalizadas acerca de la aplicación que se está presentando.

![contac-us.png](../assets/img/chapter-v/contac-us.png)
**Imagen 5:** Sección contact-us.


Seguidamente, se presenta la sección sobre nosotros (about-us). En este apartado se muestra información a menra de resumen sobre las personas que están desarrollando la salución de software.
![about-us.png](../assets/img/chapter-v/about-us.png)
**Imagen 5:** Sección abot-us.

Por último, se exhibe la sección del pie de página, donde encontrará nuestros enlaces a redes sociales y botones que le facilitarán regresar a las secciones que desee el usuario.

![footer.png](../assets/img/chapter-v/footer.png)
**Imagen 5:** Sección footer.

##### 5.2.1.6. Services Documentation Evidence for Sprint Review.

En el primer sprint, hemos diseñado, programado y puesto en funcionamiento la página de inicio para presentar la aplicación web "Techelp". En esta página de inicio, encontrarás varias secciones creadas por el equipo LogicVerse, cada una a cargo de un miembro del grupo.

<table> 
  <tr>
    <td> <strong>End Point </strong></td>
    <td align="center"> <strong>Funciones</strong> </td>
  </tr>

  <tr>
    <td> https://logicversee.github.io/LandingPageTecHelp/</td>
    <td> Desplegar Landing Page de TecHelp</td>
  </tr>
</table>

##### 5.2.1.7. Software Deployment Evidence for Sprint Review.

Para la implementación de nuestra página, optamos por utilizar GitHub Pages. En este proceso, creamos un repositorio en GitHub donde gestionamos el control de versiones. En la sección de Configuración, publicamos el proyecto almacenado en la rama "main" que previamente se encontrba en la rama release-1.0.

**Link de la Landing Page desplegada:** [TecHelp](https://logicversee.github.io/LandingPageTecHelp/) **-** https://logicversee.github.io/LandingPageTecHelp/

##### 5.2.1.8. Team Collaboration Insights during Sprint.

En esta entrega, nuestra meta principal fue la implementación de la Landing Page. Para llevar a cabo este objetivo, hicimos uso de diversas herramientas como GitHub, Visual Studio Code, WebStorm, HTML, CSS y JavaScript. A continuación, vamos a presentar los diagramas de flujo que representan los commits realizados por cada miembro del equipo LogicVerse:

![commits-colaboration.png](../assets/img/chapter-v/commits-colaboration.png)

En la imagen se evidencia el gráfico de barras de la cantidad de commits realizadas por cada uno de los integrantes del equipo. 

![commits.png](../assets/img/chapter-v/commits.png)

En esta imagen, se ofrece una representación visual de las fechas en las que se llevaron a cabo cambios en el repositorio de nuestra Landing Page, junto con la cantidad de modificaciones realizadas en cada uno de los commits. Esta representación gráfica es una herramienta valiosa para comprender la evolución temporal del proyecto y la intensidad del desarrollo a lo largo del tiempo.

![git-clones.png](../assets/img/chapter-v/git-clones.png)

Estos gráficos ofrecen una representación visual de las clonaciones registradas en nuestro repositorio, junto con la fecha en que cada una de estas acciones se llevó a cabo. Además, se presenta información sobre la cantidad de visitantes que ha tenido el repositorio de nuestro equipo a lo largo del tiempo.

![network.png](../assets/img/chapter-v/network.png)







### 5.2.2. Sprint 2

En el segundo sprint, comenzamos a desarrollar nuestra aplicación web avanzando a través de las historias de usuario, siguiendo la secuencia definida en el backlog del producto. El total de puntos de historia de estas historias de usuario es de 21 puntos.

**Repositorio:** [TecHelp-FronEnd](https://github.com/LogicVersee/TecHelp-FronEnd) - https://github.com/LogicVersee/TecHelp-FronEnd

**FrontEnd Deployed:** [TecHelp-FronEnd-Deployment](https://techhelp-webapp-v1.web.app/) - https://techhelp-webapp-v1.web.app/

#### 5.2.2.1. Sprint Planning 2.

Para el desarrollo de este sprint el equipo ha considerado en total 29 horas:

![sprint1.png](../assets/img/chapter-v/sprint2.jpg)



<table>
    <thead>
        <tr>
            <th>Sprint #</th>
            <th>Sprint 2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td colspan="2"><b>Sprint Planning Background</b></td>
        </tr>
        <tr>
            <td>Date</td>
            <td>2023/11/11</td>
        </tr>
        <tr>
            <td>Time</td>
            <td>11:00 PM</td>
        </tr>
        <tr>
            <td>Location</td>
            <td>Discord meeting</td>
        </tr>
        <tr>
            <td>Prepared by</td>
            <td>Brayan Morales</td>
        </tr>
        <tr>
            <td>Atendees (to planning meeting)</td>
            <td>
                Gonzalo Saldaña, Giovanni Ramos, Luis Lagos, Sebastián Ramirez 
            </td>
        </tr>
        <tr>
            <td>Sprint 2 Review Summary</td>
            <td>
                La opinion del product owner y las partes interesadas con respecto al avance realizado al concluir el sprint 3  fue el esperado.
            </td>
        </tr>
        <tr>
            <td>Sprint 4 Retrospective Summary</td>
            <td>
                En el sprint 2 se pudo mejorar aspectos de eficiencia en algunos componentes y la organización de la arquitectura del front-end de la aplicación web 
            </td>
        </tr>
        <tr>
            <td colspan="2"><b>Sprint Goal & User Stories</b></td>
        </tr>
        <tr>
            <td>Sprint 2 Goal</td>
            <td>
                Concluir y mejorar las intefaces de la aplicación web, levantado las observaciones del sprint 3. Implementar las tablas para membreship y la capa de seguridad. 
            </td>
        </tr>
        <tr>
            <td>Sprint 2 Velocity</td>
            <td>
                30
            </td>
        </tr>
        <tr>
            <td>Sum of story points</td>
            <td>
                29
            </td>
        </tr>
    </tbody>
</table>



#### 5.2.2.2. Sprint Backlog 2.

A continuación, compartimos imágenes que demuestran cómo gestionamos las tareas y presentamos la tabla de control de estado del Sprint.

<table>
  <tr>
    <td> <strong>Sprint #</strong></td>
    <td align="center" colspan="7"> <strong>Sprint 2</strong> </td>
  </tr>

   <tr>
    <td align="center" colspan="2"> <strong>User Story</strong></td>
    <td align="center" colspan="6"> <strong>Work-item/Task</strong></td>
  </tr>
  <tr>
    <td align="center"> <strong>ID</strong> </td>
    <td align="center"> <strong>Title<strong></td>
    <td align="center"> <strong>ID</strong> </td>
    <td align="center"> <strong>Title<strong></td>
    <td align="center"> <strong>Description<strong></td>
    <td align="center"> <strong>Estimation (Hours)<strong></td>
    <td align="center"> <strong>Assigned To<strong></td>
    <td align="center"> <strong> Status (To-do/In-Process/To-Review/Done)  <strong></td>
  </tr>
  <!---------------------------------------------------------------------- -->
  <tr>
    <td rowspan="4" align="center"> ID </td>
    <td rowspan="4" align="center"> US12	Visualiza  perfil </td>
    <td align="center"> TA01 </td>
    <td align="center"> Realizar componente del perfil del técnico</td>
    <td align="justify"> Se define la estructura o template del componente y los estilos para tener similitud con el prototipo.</td>
    <td align="center"> 3 </td>
    <td align="center"> Luis Lagos</td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Obtener técnico por id </td>
    <td align="center"> Se desarrollará una funcionalidad para obtener el objeto que coincida con el id del técnico seleccionado por el usuario.</td>
    <td align="center"> 1</td>
    <td align="center"> Giovanni Ramos</td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td align="center"> TA03 </td>
    <td align="center"> Rutas de acceso</td>
    <td align="center"> Se definen las rutas de acceso desde el componente Búsqueda de técnicos </td>
    <td align="center"> 1</td>
    <td align="center"> Sebastian Ramirez</td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td align="center"> TA04 </td>
    <td align="center"> Rutas de salida.</td>
    <td align="center"> Se define las rutas de salida hacia el request de los datos del cliente y agendar una solicitud de reparación.</td>
    <td align="center"> 1</td>
    <td align="center"> Brayan Morales</td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td rowspan="3" align="center"> ID </td>
    <td rowspan="3" align="center"> US10	Buqueda de tecnicos</td>
    <td align="center"> TA01 </td>
    <td align="center"> Definir componente para la búsqueda de técnicos</td>
    <td align="justify"> Se definirá el template del componente y los estilos que requiera para tener similitud con el mock up</td>
    <td align="center"> 4</td>
    <td align="center"> Gonzalo Saldaña</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Implementar servicio para datos de los técnicos</td>
    <td align="justify"> Se desarrolla un servicio que implementa un Fake Api para mostrar la información de los técnicos, tal como nombre, calificación, y la foto del mismo.</td>
    <td align="center"> 2</td>
    <td align="center"> Giovanni Ramos</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA03 </td>
    <td align="center"> Definir rutas para acceder al componente Búsqueda de técnicos</td>
    <td align="justify"> Se define una ruta para el componente búsque de técnicos desde el componente principal Home. Así mismo se defina un link de ruta para el componente del perfil del técnico.</td>
    <td align="center"> 1 </td>
    <td align="center"> Giovanni Ramos</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td rowspan="4" align="center"> ID </td>
    <td rowspan="4" align="center"> US02	Solicitar reparación de celular</td>
    <td align="center"> TA01 </td>
    <td align="center">Implementar Label </td>
    <td align="center"> Se implementa en angular CLI el codigo en htlm para cada label definido con anterioridad.</td>
    <td align="center"> 1</td>
    <td align="center"> Luis Lagos</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Validacion de Label</td>
    <td align="center"> Se valida cada label en el apartado de components.ts</td>
    <td align="center"> 1</td>
    <td align="center"> Sebastián Ramirez</td>
    <td align="center"> Done</td>
  </tr>
 
  <tr>
    <td align="center"> TA03 </td>
    <td align="center"> Implementacion de Css</td>
    <td align="center"> En el apartado css del componente request se implementa el diseño de los labels</td>
    <td align="center"> 1</td>
    <td align="center"> Gonzalo Saldaña</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA04 </td>
    <td align="center"> Implementacion de ruta a home</td>
    <td align="center">En el apartado routing realizo las rutas necesarias para conectar las paginas  </td>
    <td align="center"> 2</td>
    <td align="center"> Bryan Morales</td>
    <td align="center"> Done</td>
  </tr>
</table>

##### 5.2.2.3. Development Evidence for Sprint Review.

<table>
  <tr>
    <td align ="center" > <strong>Repository</strong></td>
    <td  align ="center" > <strong>Branch</strong></td>
    <td  align ="center" > <strong>Commit ID</strong></td>
    <td  align ="center" > <strong>Commit message</strong></td>
    <td  align ="center" > <strong>Commit Masagge body</strong></td>
    <td  align ="center" > <strong>Commit on (date)</strong></td>
  </tr>

  <tr>
    <td rowspan="27" align="center"> https://github.com/LogicVersee/LandingPageTecHelp </td>
    <td align="center"> main</td>
    <td align="center"> id commit</td>
    <td align="center"> chore: initial commit</td>
    <td align="center"> ---</td>
    <td align="center"> 18/09/2023</td>
  </tr>

  <tr>
    <td align="center"> main</td>
    <td align="center" > id commit</td>
    <td align="center"> chore: added multimedia material, style documents and scripts</td>
    <td align="center"> ---</td>
    <td align="center"> 18/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/home</td>
    <td align="center"> 64b097668eff10e74c80b19e9a5fdf0bb0859eb7</td>
    <td align="center"> feat (home): added components of home</td>
    <td align="center"> ---</td>
    <td align="center"> 24/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/home</td>
    <td align="center"> ce8a91b547cf00ec32f5bfa81ba77bc0eb502c1f</td>
    <td align="center"> chore(database): added fake data for technicals</td>
    <td align="center"> ---</td>
    <td align="center"> 24/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/requestservice</td>
    <td align="center"> ce8a91b547cf00ec32f5bfa81ba77bc0eb502c1f</td>
    <td align="center"> chore(database): added fake data for technicals</td>
    <td align="center"> ---</td>
    <td align="center"> 24/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/requestservice</td>
    <td align="center"> d390fec1b3f05a459d9ed9ff48ae5f1807a5b8f0</td>
    <td align="center"> feat (request): added form</td>
    <td align="center"> ---</td>
    <td align="center"> 26/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/requestservice</td>
    <td align="center"> 87b24fa5aeb8c82c9583707a9f00b80f92acc440</td>
    <td align="center"> feat (request): added form</td>
    <td align="center"> ---</td>
    <td align="center"> 26/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/requestservice</td>
    <td align="center"> fa6113dfc746047b636fbf78809fde29e3988208</td>
    <td align="center"> ffeat (request): added formrequest</td>
    <td align="center"> ---</td>
    <td align="center"> 26/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/requestservice</td>
    <td align="center"> e7d71246a32e5f0275751e06740ebed6b3cfc2a0</td>
    <td align="center"> feat (form): added css of form</td>
    <td align="center"> ---</td>
    <td align="center"> 27/09/2023</td>
  </tr>
  <tr>
    <td align="center"> feature/searchTechnicals</td>
    <td align="center"> 7215b7cd555910dc6f93007801205749b3073a98</td>
    <td align="center"> chore: added needed dependecies.</td>
    <td align="center"> ---</td>
    <td align="center"> 21/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/searchTechnicals</td>
    <td align="center"> ce8a91b547cf00ec32f5bfa81ba77bc0eb502c1f</td>
    <td align="center"> chore(database): added fake data for technicals</td>
    <td align="center"> ---</td>
    <td align="center"> 24/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/searchTechnicals</td>
    <td align="center"> 1f6a70df2d07ae96d40b5b0335a61951350427c4</td>
    <td align="center"> feat(searchTechnical): added dependencies for component</td>
    <td align="center"> ---</td>
    <td align="center"> 24/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/searchTechnicals</td>
    <td align="center"> 6903d342a9abdcf1304dfe904199ceb151f82f2a</td>
    <td align="center"> feat(searchTechnical): fixed dependencies modules on sidenav</td>
    <td align="center"> ---</td>
    <td align="center"> 24/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/searchTechnicals</td>
    <td align="center"> 6a074c4f620a5135f99947028e7a29e69201ec8b</td>
    <td align="center"> feat(searchTechnical): view to search technicals added</td>
    <td align="center"> ---</td>
    <td align="center"> 25/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/techProfile</td>
    <td align="center"> ce8a91b547cf00ec32f5bfa81ba77bc0eb502c1f</td>
    <td align="center"> chore(database): added fake data for technicals</td>
    <td align="center"> ---</td>
    <td align="center"> 24/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/techProfile</td>
    <td align="center"> 1f6a70df2d07ae96d40b5b0335a61951350427c4</td>
    <td align="center"> feat(searchTechnical): added dependencies for component</td>
    <td align="center"> ---</td>
    <td align="center"> 24/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/techProfile</td>
    <td align="center"> 6903d342a9abdcf1304dfe904199ceb151f82f2a</td>
    <td align="center"> feat(searchTechnical): fixed dependencies modules on sidenav</td>
    <td align="center"> ---</td>
    <td align="center"> 24/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/techProfile</td>
    <td align="center"> 6a074c4f620a5135f99947028e7a29e69201ec8b</td>
    <td align="center"> feat(searchTechnical): view to search technicals added</td>
    <td align="center"> ---</td>
    <td align="center"> 25/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/techProfile</td>
    <td align="center"> 1d40787636006704d9070552f097a50c9dd54ddf</td>
    <td align="center"> feat(searchTechnical): implemented facade service for technicals list</td>
    <td align="center"> ---</td>
    <td align="center"> 27/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/techProfile</td>
    <td align="center"> b1e9b9eb62f3252608724f4c2fba7132dcf5c008</td>
    <td align="center"> feat(searchTechnical): implemented material icon resources</td>
    <td align="center"> ---</td>
    <td align="center"> 27/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/techProfile</td>
    <td align="center"> 50a02291eb792950c227eb8979fce6ad9450555f</td>
    <td align="center"> feat(sidenav-toolbar): added sidenav-toolbar component</td>
    <td align="center"> ---</td>
    <td align="center"> 27/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/techProfile</td>
    <td align="center"> 529093aa07e2dacb8f7bf6993269590c36116e11</td>
    <td align="center"> feat(searchTechnical): merge searchTechnical branch into developer</td>
    <td align="center"> ---</td>
    <td align="center"> 27/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/techProfile</td>
    <td align="center"> 6754abaf5993b6bec139f2717b1ca52992ea16e6</td>
    <td align="center"> feat(techProfile): added tech profile component dependencies</td>
    <td align="center"> ---</td>
    <td align="center"> 27/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/techProfile</td>
    <td align="center"> 90785382aff9e4335ea5c81ae3875c1503d4f954</td>
    <td align="center"> feat(techProfile): added tech profile component functionalities.</td>
    <td align="center"> ---</td>
    <td align="center"> 27/09/2023</td>
  </tr>


  <tr>
    <td align="center"> developers </td>
    <td align="center"> 21ca339152d3370a90d5e6aff112667e7578d707</td>
    <td align="center"> Merge remote-tracking branch 'origin/feature/requestservice' into developers</td>
    <td align="center"> ---</td>
    <td align="center"> 27/09/2023</td>
  </tr>

  <tr>
    <td align="center"> developers </td>
    <td align="center"> b7f79e23138866327ee1984e313e77f2db63c563</td>
    <td align="center"> fMerge remote-tracking branch 'origin/developers' into developers</td>
    <td align="center"> ---</td>
    <td align="center"> 27/09/2023</td>
  </tr>

  <tr>
    <td align="center"> developers</td>
    <td align="center"> 399f2827591b236879279c60ecdc59882052bb4e</td>
    <td align="center"> Merge remote-tracking branch 'origin/feature/home' into developers</td>
    <td align="center"> ---</td>
    <td align="center"> 27/09/2023</td>
  </tr>

</table>

##### 5.2.2.4. Execution Evidence for Sprint Review.

Después de completar el Sprint 2, logramos implementar y desplegar la sección de de búsqueda de servicios técnicos, visualizar el perfil de un centro técnico y solicitar el servicio de reparación de un teléfono móvil.

**Evidencia:**
* **NOMBRE DE LA SECCIÓN:** 
  
![home.png](../assets/img/chapter-v/HomeAngular.png)

**Imagen 1:** Home

Se presenta la sección "Home", que incluye el navbar con el cual el usuario puede navegar por la pagina.

![tecnicos.png](../assets/img/chapter-v/VISUALIZARTECNICOS.png)
**Imagen 2:** Busqueda de Tecnico.

Se presenta la sección donde se visualizaran todos los tecnicos de la pagina web.

![perfiles.png](../assets/img/chapter-v/JOSEPEREZANGULAR.png)
**Imagen 3:** Visualizar perfil.

Se presenta la sección donde el usuario puede visualizar el perfil del tecnico con una reseña y su ubicación.

![request.png](../assets/img/chapter-v/REQUESTSERVICEANGULAR.png)
**Imagen 4:** Solicitar servicio.

Se presanta la opcion  la cual el cliente puede solicitar el servicio a un tecnico y rellenar la información pedida de la peticion.


##### 5.2.2.6. Services Documentation Evidence for Sprint Review.

En el segundo sprint, hemos diseñado, programado y puesto en funcionamiento la página de inicio para presentar la aplicación web "Techelp". En esta página de inicio, encontrarás varias secciones creadas por el equipo LogicVerse, cada una a cargo de un miembro del grupo.

<table> 
  <tr>
    <td> <strong>End Point </strong></td>
    <td align="center"> <strong>Funciones</strong> </td>
  </tr>
  <tr>
    <td> https://www.npmjs.com/package/json-server</td>
    <td> Fake API  del Frontend de TecHelp</td>
  </tr>
  <tr>
    <td> https://techhelp-webapp-v1.web.app/</td>
    <td> Desplegar  Frontend de TecHelp</td>
  </tr>
</table>

##### 5.2.2.7. Software Deployment Evidence for Sprint Review.

Para la implementación de nuestra página, optamos por utilizar Firebase. En este proceso, se creo un proyecto en Firebase y se vinculo atravez de Angular Firebase, para acceder a los datos se necesita el json de manera local.

**Link de la aplicacion web desplegada:** [TecHelp](https://techhelp-webapp-v1.web.app/) **-** https://techhelp-webapp-v1.web.app/

##### 5.2.2.8. Team Collaboration Insights during Sprint.

En esta entrega, nuestra meta principal fue la implementación de las funciones de request y visualizacion de tecnicos. Para llevar a cabo este objetivo, hicimos uso de diversas herramientas como GitHub, Visual Studio Code, WebStorm, HTML, CSS y JavaScript. A continuación, vamos a presentar los diagramas de flujo que representan los commits realizados por cada miembro del equipo LogicVerse:

![commits-colaborationsprint2.png](../assets/img/chapter-v/commits-colaborationsprint2.PNG)

En la imagen se evidencia el gráfico de barras de la cantidad de commits realizadas por cada uno de los integrantes del equipo. 

![commits.png](../assets/img/chapter-v/commitssprint.PNG)

En esta imagen, se ofrece una representación visual de las fechas en las que se llevaron a cabo cambios en el repositorio de nuestra segundo sprint, junto con la cantidad de modificaciones realizadas en cada uno de los commits. Esta representación gráfica es una herramienta valiosa para comprender la evolución temporal del proyecto y la intensidad del desarrollo a lo largo del tiempo.

![git-clones.png](../assets/img/chapter-v/git-clonessprint2.PNG)

Estos gráficos ofrecen una representación visual de las clonaciones registradas en nuestro repositorio, junto con la fecha en que cada una de estas acciones se llevó a cabo. Además, se presenta información sobre la cantidad de visitantes que ha tenido el repositorio de nuestro equipo a lo largo del tiempo.

![network.png](../assets/img/chapter-v/networksprint2.PNG)

### 5.2.3. Sprint 3

#### 5.2.3.1. Sprint Planning 3.

En este punto el equipo tiene como objetivo levantar observaciones proporcionadas por el product owner y las partes interesadas. Tambien se plantea un avance del 40% del backend de la palicación web. 

<table>
  <tr>
    <td><strong>Sprint #</strong></td>
    <td>Sprint 3</td>
  </tr>

  <tr>
    <td colspan="2"><strong>Sprint Planning Background</strong></td>
  </tr>

  <tr>
    <td><strong>Date</strong></td>
    <td>2023-11-01</td>
  </tr>

  <tr>
    <td><strong>Time</strong></td>
    <td>11:15 AM</td>
  </tr>

  <tr>
    <td><strong>Location</strong></td>
    <td>Reunion realizada en el grupo de discord del equipo de trabajo</td>
  </tr>
  
  <tr>
    <td><strong>Prepared By</strong></td>
    <td>Brayan Smith Morales Quispe <b>(Lider de grupo)</b></td>
  </tr>

  <tr>
    <td><strong>Attendees (to planning meeting)</strong></td>
    <td>
      <ol type="A">
        <li>Ramirez Mendez Sebastián André</li>
        <li>Lagos Aguilar Luis Eduardo</li>
        <li>Ramos Calderon Giovanni Andres</li>
        <li>Saldaña Vela, Janover Gonzalo</li>
      </ol>
    </td>
  </tr>

  <tr>
    <td><strong>Sprint 2 Review Summary</strong></td>
    <td>El anterior sprint desarrollado de 12 al 19 de setiembre que tuvo como meta el  desarrollo del frontend al 40%.Se obtuvo como resultado el completo completo desarrollo y su despliege en su totalidad con las caracteristicas planteadas por el equipo de trabajo.La opinion de los miembros del equipo fue que tuvimos una mala coordinacion al momento de realizar la documentacion y falta de comunicacion. El feeback dado al sprint anterior fue la falta del spring planning 2,call_to_action con la appweb y mala evidencia de comunicacion oral entre los miembros del grupo  </td>
  </tr>

  <tr>
    <td><strong>Sprint 2 Retrospective Summary</strong></td>
    <td>Las opiniones del equipo de trabajo son las siguientes:
      <ol type="A">
        <li>Se debe mejorar nuestra coordinacion como equipo de trabajo en el desarrollo de los sprints</li>
        <li>Debemos se mas responsables cumpliendo las fechas establecidas para la entrega de cada parte desarrollado por un mienbro.</li>
        <li>Debemos ser mas minuciosos al momento de revisar las fallas de nuestro trabajo</li>
      </ol>
    </td>
  </tr>

  <tr>
    <td colspan="2"><strong>Sprint Goal & User Stories</strong></td>
  </tr>

  <tr>
    <td><strong>Sprint 3 Goal</strong></td>
    <td>El objetivo del sprint es el desarrollo de la backend superior al 40%</td>
  </tr>

  <tr>
    <td><strong>Sprint 3 Velocity</strong></td>
    <td>30</td>
    
    
  </tr>

  <tr>
    <td><strong>Sum of Story Points</strong></td>
    <td>29</td>
  </tr>
</table>


#### 5.2.3.2. Sprint Backlog 3.
<table>
  <tr>
    <td> <strong>Sprint #</strong></td>
    <td align="center" colspan="7"> <strong>Sprint 2</strong> </td>
  </tr>

   <tr>
    <td align="center" colspan="2"> <strong>User Story</strong></td>
    <td align="center" colspan="6"> <strong>Work-item/Task</strong></td>
  </tr>
  <tr>
    <td align="center"> <strong>ID</strong> </td>
    <td align="center"> <strong>Title<strong></td>
    <td align="center"> <strong>ID</strong> </td>
    <td align="center"> <strong>Title<strong></td>
    <td align="center"> <strong>Description<strong></td>
    <td align="center"> <strong>Estimation (Hours)<strong></td>
    <td align="center"> <strong>Assigned To<strong></td>
    <td align="center"> <strong> Status (To-do/In-Process/To-Review/Done)  <strong></td>
  </tr>
  <!---------------------------------------------------------------------- -->
  <tr>
    <td rowspan="4" align="center"> ID </td>
    <td rowspan="4" align="center"> US10 Busqueda de Tecnicos </td>
    <td align="center"> TA01 </td>
    <td align="center"> Desarrollar las entidades,agregados y objetos de valor que usara el servicio en nuestra backend</td>
    <td align="justify">Se define los atributos de las entidades,agregados y objetos de valor</td>
    <td align="center"> 2 </td>
    <td align="center"> Luis Lagos</td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Desarrollo del controlador </td>
    <td align="center"> Se desarrollará el controlador para adminitrar los pedidos GET a nuestra API con ciertas caracteristicas de la entidad tecnico</td>
    <td align="center"> 2</td>
    <td align="center"> Giovanni Ramos</td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td align="center"> TA03 </td>
    <td align="center"> Implementacion de Queries</td>
    <td align="center"> Se desarrolla los queries para la implementacion con el servicio </td>
    <td align="center"> 1</td>
    <td align="center"> Sebastian Ramirez</td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td align="center"> TA04 </td>
    <td align="center"> Revision de la aquitectura </td>
    <td align="center"> Se revisa la arquitectura de las carpetas siguiendo Domain Driven Design</td>
    <td align="center"> 1</td>
    <td align="center"> Brayan Morales</td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td rowspan="3" align="center"> ID </td>
    <td rowspan="3" align="center"> US12 Visualizar Tecnico</td>
    <td align="center"> TA01 </td>
    <td align="center"> Implementacion de Queries</td>
    <td align="center"> Se desarrolla los queries para la implementacion con el servicio </td>
    <td align="center"> 1</td>
    <td align="center"> Sebastian Ramirez</td>
    <td align="center">Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Desarrollo del controlador </td>
    <td align="center"> Se desarrollará el controlador para adminitrar los pedidos GET a nuestra API </td>
    <td align="center"> 2</td>
    <td align="center"> Giovanni Ramos</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA03 </td>
    <td align="center"> Revision de la aquitectura </td>
    <td align="center"> Se revisa la arquitectura de las carpetas siguiendo Domain Driven Design</td>
    <td align="center"> 1</td>
    <td align="center"> Giovanni Ramos</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td rowspan="4" align="center"> ID </td>
    <td rowspan="4" align="center"> US11 Progreso del dispositivo</td>
    <td align="center"> TA01 </td>
    <td align="center"> Implementacion de Queries y commands</td>
    <td align="center"> Se desarrolla los queries y commands para la implementacion con el servicio </td>
    <td align="center"> 1</td>
    <td align="center"> Luis Lagos</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Desarrollo del controlador </td>
    <td align="center"> Se desarrollará el controlador para adminitrar los pedidos PUT y POST a nuestra API </td>
    <td align="center"> 2</td>
    <td align="center"> Sebastián Ramirez</td>
    <td align="center"> Done</td>
  </tr>
 
  <tr>
    <td align="center"> TA03 </td>
    <td align="center"> Implementacion de los queries y commands con el servicio del boundex context</td>
    <td align="center"> Se implementara los commands y queries al servicio para su uso</td>
    <td align="center"> 1</td>
    <td align="center"> Gonzalo Saldaña</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA04 </td>
    <td align="center"> Revision de la aquitectura </td>
    <td align="center"> Se revisa la arquitectura de las carpetas siguiendo Domain Driven Design</td>
    <td align="center"> 1</td>
    <td align="center"> Bryan Morales</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td rowspan="4" align="center"> ID </td>
    <td rowspan="4" align="center"> US05 Administrar Tareas</td>
      <td align="center"> TA01 </td>
    <td align="center"> Implementacion de Queries y commands</td>
    <td align="center"> Se desarrolla los queries y commands para la implementacion con el servicio </td>
    <td align="center"> 1</td>
    <td align="center"> Luis Lagos</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA02 </td>
    <td align="center"> Desarrollo del controlador </td>
    <td align="center"> Se desarrollará el controlador para adminitrar los pedidos PUT y POST a nuestra API </td>
    <td align="center"> 2</td>
    <td align="center"> Sebastián Ramirez</td>
    <td align="center"> Done</td>
  </tr>
 
  <tr>
    <td align="center"> TA03 </td>
    <td align="center"> Implementacion de los queries y commands con el servicio del boundex context</td>
    <td align="center"> Se implementara los commands y queries al servicio para su uso</td>
    <td align="center"> 1</td>
    <td align="center"> Gonzalo Saldaña</td>
    <td align="center"> Done</td>
  </tr>

  <tr>
    <td align="center"> TA04 </td>
    <td align="center"> Revision de la aquitectura </td>
    <td align="center"> Se revisa la arquitectura de las carpetas siguiendo Domain Driven Design</td>
    <td align="center"> 1</td>
    <td align="center"> Bryan Morales</td>
    <td align="center"> Done</td>
  </tr>

</table>


#### 5.2.3.3. Development Evidence for Sprint Review.

Para este tercer sprint logramos desplegar y desarrollar las siguientes secciones de nuestra aplicación web:Login, Register, Home(Cliente,Tecnico),Progress, Technical, ViewProgress,Memberchip,Task,CreateTask,UpdateTask,ViewTask,TechnicalProfile,EditTechnicalProfile.
* Evidencias del FrontEnd:
<br>
<table>
  <tr>
    <td align ="center" > <strong>Repository</strong></td>
    <td  align ="center" > <strong>Branch</strong></td>
    <td  align ="center" > <strong>Commit ID</strong></td>
    <td  align ="center" > <strong>Commit message</strong></td>
    <td  align ="center" > <strong>Commit Masagge body</strong></td>
    <td  align ="center" > <strong>Commit on (date)</strong></td>
  </tr>

  <tr>
    <td rowspan="41" align="center"> https://github.com/LogicVersee/TecHelp-FronEnd </td>
    <td align="center"> main</td>
    <td align="center"> 7215b7cd555910dc6f93007801205749b3073a98</td>
    <td align="center"> chore: initial commit</td>
    <td align="center"> ---</td>
    <td align="center"> 21/09/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/dashboard</td>
    <td align="center" > 5cbd9f91ceaf7fdfb847fef9216c87672a48846d</td>
    <td align="center"> feat(dashboard): added dashboard dependencies</td>
    <td align="center"> ---</td>
    <td align="center"> 14/10/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/dashboard</td>
    <td align="center"> b514667f3df22507cd762f93b08e92085b502044</td>
    <td align="center"> feat(analytics): analytics chart implemented</td>
    <td align="center"> ---</td>
    <td align="center"> 14/10/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/dashboard</td>
    <td align="center"> 6a62d1f28c1bd9f92dce2fbbb2d11a120000a6cf</td>
    <td align="center"> feat(inventory): inventory component implemented</td>
    <td align="center"> ---</td>
    <td align="center"> 18/10/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/dashboard </td>
    <td align="center"> cb8b6bbe7efb3ad3eda1c10f180983962194ebdb</td>
    <td align="center"> feat(dashboard): dashboard style updated</td>
    <td align="center"> ---</td>
    <td align="center"> 19/10/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/dashboard </td>
    <td align="center"> 990ed4abec92ab6f81c1032f45d72c5bd22a7ae3</td>
    <td align="center"> feat(analytics): analytics style updated </td>
    <td align="center"> ---</td>
    <td align="center"> 20/10/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/membership </td>
    <td align="center"> cb8979d9d217670f35caead88ecc4a4951d20cae</td>
    <td align="center"> feat (request): added form</td>
    <td align="center"> ---</td>
    <td align="center"> 25/10/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/membership </td>
    <td align="center"> 53ec9cc3ec9d13356f5dfe3a6acd675bc6aee410 </td>
    <td align="center"> fet(Membership): Add Membership Component</td>
    <td align="center"> ---</td>
    <td align="center"> 25/10/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/membership </td>
    <td align="center"> 6eeb77706c1deafb02f4e0f75b92a2d227a5934e </td>
    <td align="center"> Change(membership): Update name of membership component </td>
    <td align="center"> ---</td>
    <td align="center"> 31/10/2023</td>
  </tr>
  <tr>
    <td align="center"> feature/membership </td>
    <td align="center"> 723a784974ff336d55a5f6ed802e52c755534521 </td>
    <td align="center"> feat(membership): added service api implementation </td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/monitoring </td>
    <td align="center"> 47c2b915a6383caeb0f85aad8b81f9109d37ee98 </td>
    <td align="center"> feat(monitoring): added list task. </td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/monitoring </td>
    <td align="center"> 01696b9f5e1c2735e9105dd89a220a2bc974a1c3</td>
    <td align="center"> feat(monitoring): added model progress task. </td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/monitoring </td>
    <td align="center"> eef8478c16ac43bba6b421cee7a87f3083077152</td>
    <td align="center"> feat(monitoring): added service monitor task. </td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/monitoring </td>
    <td align="center"> 19121cac2baa7effe9f8606479aee31bedf819e0</td>
    <td align="center"> feat(monitoring): added page of view unique progress task. </td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/monitoring </td>
    <td align="center"> da4b65da269ea5dc793fc9144a352fb029c269a9</td>
    <td align="center"> chore(app): updated app module and routing. </td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/myProfile</td>
    <td align="center"> 09272b4b5a5d338aabbc18923c37ddf2aecbd774</td>
    <td align="center"> chore(myProfile): Added API services.</td>
    <td align="center"> ---</td>
    <td align="center"> 20/10/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/myProfile</td>
    <td align="center"> e073af6a39aff8f22715f9450578cce289289167</td>
    <td align="center"> chore(myProfile): implemented edit component and interface</td>
    <td align="center"> ---</td>
    <td align="center"> 20/10/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/myProfile</td>
    <td align="center"> 38d00a2d96db98eb9dac69237ffe513f572171b4</td>
    <td align="center"> chore(myProfile): Add myProfile component</td>
    <td align="center"> ---</td>
    <td align="center"> 20/10/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/myProfile</td>
    <td align="center"> 0a99942e1bf64679c12ca047bfbd93dc37fa1ef7</td>
    <td align="center"> chore(myProfile): Add routing</td>
    <td align="center"> ---</td>
    <td align="center"> 20/10/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/myProfile</td>
    <td align="center"> c70a504a4e207c48ad68543560db4f4fda60058d</td>
    <td align="center"> chore(myProfile): Json server added.</td>
    <td align="center"> ---</td>
    <td align="center"> 25/10/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/myProfile</td>
    <td align="center"> c9e35b082d000ff62b364271fefc5e5643fb4a0d</td>
    <td align="center"> feat(tech-profile): button to edit profile routed </td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/security</td>
    <td align="center"> cb66d4dbd08adff094922ba2fa3d49509d7f1c65</td>
    <td align="center"> feat(security): Added and implemented customer, technician and user classes</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/security</td>
    <td align="center"> c05fd2d8bc26db75e1b23c95d0c89ce7135fdd77</td>
    <td align="center"> feat(security): added login and registration components.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/security</td>
    <td align="center"> f76bb0a27bc61ab6205194015904d79a92527d41</td>
    <td align="center"> feat(security): Added page not found component and base service.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>


  <tr>
    <td align="center"> feature/security </td>
    <td align="center"> b26af8802d0f54d9ee8e35b66fb8daf13269251c</td>
    <td align="center"> feat(security): The base service was implemented.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/security </td>
    <td align="center"> 94a372f797de4fad43bd917ba99adaee11d58ded</td>
    <td align="center"> feat(security): Implemented page not found.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/security</td>
    <td align="center"> 123da2873c447be0d0f51376612794ff45012e64</td>
    <td align="center"> feat(security): Implemented service technical and user.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>

 <tr>
    <td align="center"> feature/security</td>
    <td align="center"> ed4e6c8c0085328bf0ab4b6835fe43e541d7f78a</td>
    <td align="center"> feat(security): login view added.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>
 <tr>
    <td align="center"> feature/security</td>
    <td align="center"> 91867032ae4c544bc20007ba61792a315bd11f05</td>
    <td align="center"> feat(security): sign up view added.</td>
    <td align="center"> ---</td>
    <td align="center"> 4/11/2023</td>
  </tr>
 <tr>
    <td align="center"> feature/task</td>
    <td align="center"> fe38bf7082fdd47f33c3964ca29bd5caa8cd3d80</td>
    <td align="center"> chore(service): added base class for service facade.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>
 <tr>
    <td align="center"> feature/task</td>
    <td align="center"> ddadc6fbc00c96ff584dd4bca8deda6ec2867fce</td>
    <td align="center"> feat(tasks): added service facade for students endpoint.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>
 <tr>
    <td align="center"> feature/task</td>
    <td align="center"> 59cd2c3c81b79341a1aac7644027ef1abb3c8813</td>
    <td align="center"> feat(tasks): added student form with behavior.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>
 <tr>
    <td align="center"> feature/task</td>
    <td align="center"> d1ad8fb2693bb245237de9a9c3b9f33de18b73e4</td>
    <td align="center"> feat(tasks): implemented task form layout and visualization characteristics.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>
 <tr>
    <td align="center"> feature/task</td>
    <td align="center"> 0ff9773b67564336e5a23d75f7e6aa93528c259f</td>
    <td align="center"> feat(tasks): implemented task catalogue behavior.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>
 <tr>
    <td align="center"> feature/task</td>
    <td align="center"> 3fc6c89eaa8541d4d3281058605509f84285d9e1</td>
    <td align="center"> feat(tasks): implemented task.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>
 <tr>
    <td align="center"> feature/task</td>
    <td align="center"> 8c004d44ef3cb0f6db2d644d937f3928fed28665</td>
    <td align="center"> fix(task): fixed some errors.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>
 <tr>
    <td align="center"> feature/task</td>
    <td align="center"> 22cede04eed8b9e43625d2f9393564e8ba106733</td>
    <td align="center"> fix(task): fixed some errors.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>
 <tr>
    <td align="center"> main/developers </td>
    <td align="center"> c9e35b082d000ff62b364271fefc5e5643fb4a0d </td>
    <td align="center"> feat(tech-profile): button to edit profile routed.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>
 <tr>
    <td align="center"> main/developers</td>
    <td align="center"> 5f3e20865cec16688f39f3ee4afbfc108e27c9d6</td>
    <td align="center"> feat(develop): routed.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>
 <tr>
    <td align="center"> main/developers</td>
    <td align="center"> 723a784974ff336d55a5f6ed802e52c755534521 </td>
    <td align="center"> feat(membership): added service api implementation. </td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>
 <tr>
    <td align="center"> main/developers</td>
    <td align="center"> ca2b5d9bdd22e1144d9a88f3893d69faff3ecdce</td>
    <td align="center"> feat(router): :routed components. </td>
    <td align="center"> ---</td>
    <td align="center"> 4/11/2023</td>
  </tr>

</table>

* Evidencias del BackEnd:
<br>
<table>
  <tr>
    <td align ="center" > <strong>Repository</strong></td>
    <td  align ="center" > <strong>Branch</strong></td>
    <td  align ="center" > <strong>Commit ID</strong></td>
    <td  align ="center" > <strong>Commit message</strong></td>
    <td  align ="center" > <strong>Commit Masagge body</strong></td>
    <td  align ="center" > <strong>Commit on (date)</strong></td>
  </tr>

  <tr>
    <td rowspan="33" align="center"> https://github.com/LogicVersee/techelp-center-platform-backend </td>
    <td align="center"> master</td>
    <td align="center"> bc3df0401d1b07fc4d74d41eaa4e000e388a0c9e</td>
    <td align="center"> chore: initial commit</td>
    <td align="center"> ---</td>
    <td align="center"> 23/10/2023</td>
  </tr>

  <tr>
    <td align="center"> master</td>
    <td align="center" > 4b801f00a6a332cdbeefc124158228036b76be27</td>
    <td align="center"> chore: added dependencies.</td>
    <td align="center"> ---</td>
    <td align="center"> 23/10/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/technical</td>
    <td align="center"> 56fca751ebf0aa88beb50a8ad3875d5ea876465c</td>
    <td align="center"> feat(technical): technical, dashboard, component and incomes entities implemented</td>
    <td align="center"> ---</td>
    <td align="center"> 23/10/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/technical</td>
    <td align="center"> 6db06a22c15ec56e7ede07d353eda1c153b3cad7</td>
    <td align="center"> feat(technical): technical controller created </td>
    <td align="center"> ---</td>
    <td align="center"> 29/10/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/technical </td>
    <td align="center"> cb5e517aa6505a77f03221872d78e12b11ff73d0</td>
    <td align="center"> feat(inventory): inventory controller created</td>
    <td align="center"> ---</td>
    <td align="center"> 29/10/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/technical </td>
    <td align="center"> 9338e88d83169e4d7b9eb70befef63dd74e509a5</td>
    <td align="center"> feat(dash-board): implemented dashboard context facade </td>
    <td align="center"> ---</td>
    <td align="center"> 29/10/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> e63bc3022f2253d762509f0ceb5e811abb46c049</td>
    <td align="center"> feat(task): task command created</td>
    <td align="center"> ---</td>
    <td align="center"> 1/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> 3080bfc3d56b0c1262f30cd16b88719e72435ea1 </td>
    <td align="center"> feat(task): client name's value object created</td>
    <td align="center"> ---</td>
    <td align="center"> 1/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> af28c9ab9cb54f0223160c0e83a0ca42df46eae2 </td>
    <td align="center"> feat(task): client phone name's value object created </td>
    <td align="center"> ---</td>
    <td align="center"> 1/11/2023</td>
  </tr>
  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> 2469e86a7045e480af1d04ac0b0eca2e68f1f72f </td>
    <td align="center"> feat(task): client problem's value object created </td>
    <td align="center"> ---</td>
    <td align="center"> 1/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> 6cc2bd4ab00ce32798ee41c6578f71bb15dfebd0 </td>
    <td align="center"> feat(task): client delivery day's value object created. </td>
    <td align="center"> ---</td>
    <td align="center"> 1/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> 749fb2af8589fa694db41b6fac1680cd3f16de0d</td>
    <td align="center"> fix(task): task command created fixed. </td>
    <td align="center"> ---</td>
    <td align="center"> 1/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> c3bfc367367eb794b8193f1919d0ea8ebd4d3369</td>
    <td align="center"> feat(task): task entity created. </td>
    <td align="center"> ---</td>
    <td align="center"> 1/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> 73f2f9d39bcb5e3e602f618516c04fa0696156e2</td>
    <td align="center"> feat(task): get task by technicalid created. </td>
    <td align="center"> ---</td>
    <td align="center"> 1/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> 4ea62f50c5d8c40ac137c9f2a03e14aa28447a53</td>
    <td align="center"> feat(task): task services created </td>
    <td align="center"> ---</td>
    <td align="center"> 1/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> a210a72d51d4c7e39c8994c08a6fe467ac2e0344</td>
    <td align="center"> feat(task): task repository created</td>
    <td align="center"> ---</td>
    <td align="center"> 1/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> d929347a7840b6db553b156ddf7992c1edc87122</td>
    <td align="center"> feat(task): task context facade created </td>
    <td align="center"> ---</td>
    <td align="center"> 1/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task</td>
    <td align="center"> a1f19abb6490ac11049e1aea8a7415b09c9acad2</td>
    <td align="center"> feat(task): task service implementation created </td>
    <td align="center"> ---</td>
    <td align="center"> 2/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task</td>
    <td align="center"> 4a8dd81a699f53beb81fe2b1c9eb25e8a067e921</td>
    <td align="center"> feat(task): task controller created</td>
    <td align="center"> ---</td>
    <td align="center"> 2/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task</td>
    <td align="center"> 18298a9831ff3d3362fdd56875735e2d7c653ece</td>
    <td align="center"> feat(task): task by id query created.</td>
    <td align="center"> ---</td>
    <td align="center"> 2/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task</td>
    <td align="center"> 81d67e09fa54490a72e06f9a2538fffbfe0789cb</td>
    <td align="center"> fix(DeliveryDay): public string getdeliveryday fixed </td>
    <td align="center"> ---</td>
    <td align="center"> 2/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task</td>
    <td align="center"> 430655d64b4c6866a2d9f23328253101a0c61cf6</td>
    <td align="center"> feat(task): task resource added</td>
    <td align="center"> ---</td>
    <td align="center"> 2/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task</td>
    <td align="center"> a6d59a4b95dec69455a1e1632aeef4ebba989942</td>
    <td align="center"> feat(task): create task resource added.</td>
    <td align="center"> ---</td>
    <td align="center"> 2/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task</td>
    <td align="center"> 4550c3c4dfe0aa68fb1c09673fcd1b56cce73e31</td>
    <td align="center"> feat(task): create task from resource assembler transform added.</td>
    <td align="center"> ---</td>
    <td align="center"> 2/11/2023</td>
  </tr>


  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> a036a754794f4062aba1837cef37f1685e231b21</td>
    <td align="center"> feat(task): task from entity assembler transform added.</td>
    <td align="center"> ---</td>
    <td align="center"> 2/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> c21233ed8bf057a3512d1e0d82b359e9c30ff61c</td>
    <td align="center"> feat(task): task command service implementation created.</td>
    <td align="center"> ---</td>
    <td align="center"> 2/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task</td>
    <td align="center"> b2c45b715a653a7886320fa050109ed7409784f6</td>
    <td align="center"> feat(task): task query service implementation created.</td>
    <td align="center"> ---</td>
    <td align="center"> 2/11/2023</td>
  </tr>

 <tr>
    <td align="center"> feature/task</td>
    <td align="center"> d2b279205081e497cee79221d9458d37ebe0c60d</td>
    <td align="center"> feat(task): task controller added.</td>
    <td align="center"> ---</td>
    <td align="center"> 2/11/2023</td>
  </tr>
 <tr>
    <td align="center"> feature/task</td>
    <td align="center"> 1412700dabd3377c8bc7f2cc391abe18725eb229</td>
    <td align="center"> feat(task): edited dependencies.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>
 <tr>
    <td align="center"> feature/task</td>
    <td align="center"> ad269d55c2d5f8cada22e412767aebdcb349b26a</td>
    <td align="center"> feat(task): added query to get tasks by technical id.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>
 <tr>
    <td align="center"> test</td>
    <td align="center"> ca2b5d9bdd22e1144d9a88f3893d69faff3ecdce</td>
    <td align="center"> feat(test): technicals feature added.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>
 <tr>
    <td align="center"> test</td>
    <td align="center"> 8734d23116b1e7d9502e82e82eb0eaa2cf3a75bb</td>
    <td align="center"> feat(test): item feature added.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>
 <tr>
    <td align="center">test </td>
    <td align="center"> 38ee3231dcbfed24f7d2797973ddb5aba612e16f</td>
    <td align="center"> feat(test): tasks feature added.</td>
    <td align="center"> ---</td>
    <td align="center"> 3/11/2023</td>
  </tr>


</table>

#### 5.2.3.4. Testing Suite Evidence for Sprint Review.

En esta sección representamos el conjunto de Acceptance Test relacionadas con las User Stories para el desarrollo del tercer sprint. Se uso el lenguaje Gherkin para los criteros de aceptación.

<table>
  <tr>
    <td align ="center" > <strong>Repository</strong></td>
    <td  align ="center" > <strong>Branch</strong></td>
    <td  align ="center" > <strong>Commit ID</strong></td>
    <td  align ="center" > <strong>Commit message</strong></td>
    <td  align ="center" > <strong>Commit Masagge body</strong></td>
    <td  align ="center" > <strong>Commit on (date)</strong></td>
  </tr>

  <tr>
    <td rowspan="3" align="center"> https://github.com/LogicVersee/techelp-center-platform-backend/commits/test </td>
    <td align="center"> test</td>
    <td align="center"> ca2b5d9bdd22e1144d9a88f3893d69faff3ecdce</td>
    <td align="center"> feat(test): technicals feature added.</td>
    <td align="center"> ---</td>
    <td align="center"> 4/11/2023</td>
  </tr>

  <tr>
    <td align="center"> test</td>
    <td align="center" > 8734d23116b1e7d9502e82e82eb0eaa2cf3a75bb</td>
    <td align="center"> feat(test): item feature added.</td>
    <td align="center"> ---</td>
    <td align="center"> 4/11/2023</td>
  </tr>

  <tr>
    <td align="center"> test</td>
    <td align="center"> 38ee3231dcbfed24f7d2797973ddb5aba612e16f</td>
    <td align="center"> feat(test): tasks feature added.</td>
    <td align="center"> ---</td>
    <td align="center"> 4/11/2023</td>
  </tr>

</table>

#### 5.2.3.5. Execution Evidence for Sprint Review.
Para este tercer sprint se ha desplegado las siguientes secciones en nuestra aplicacion web.

Login: Muestra a usuario el inicio de la apliación web en donde podra usar su correo y contraseña para entrar como tecnico o usuario.

![network.png](../assets/img/chapter-v/frontlogin.PNG)

Registro: Muestra a usuario un formulario con el cual podra registrarse.

![network.png](../assets/img/chapter-v/frontregister.PNG)

Progress: Muestra una lista de las tareas que creo el tecnico.

![network.png](../assets/img/chapter-v/frontProgress.PNG)

ViewProgress: Muestra a usuario el inicio de la apliación web.

![network.png](../assets/img/chapter-v/frontviewprogress.PNG)

Profile: Muestra al tecnico su perfil.

![network.png](../assets/img/chapter-v/frontProfile.PNG)

Membership: Muesta al tecnico la memebresia la cual puede adquirir.

![network.png](../assets/img/chapter-v/frontMembership.PNG)

EditProfile: Muesta al tecnico un formalario en donde puede editar su informacion.

![network.png](../assets/img/chapter-v/fronteditProfile.PNG)

Dashboard: Muestra al tecnico el dashboard.

![network.png](../assets/img/chapter-v/frontDashboard.PNG)

Inventario: Muestras al tecnio el inventario que tiene.

![network.png](../assets/img/chapter-v/frontInventory.PNG)

Analytics: Se le muestra una vista mas amplia de las estadisticas.

![network.png](../assets/img/chapter-v/frontAnalytic.PNG)


#### 5.2.3.6. Services Documentation Evidence for Sprint Review.

En el tercer sprint se pudo desarrollar el 50% del BackEnd; sin embargo, aún no se ha implementado, pero si se ha logrado desplegado.

![network.png](../assets/img/chapter-v/BackEndTablas.png)
![network.png](../assets/img/chapter-v/BackEnd.png)

Por esta razon aún se está usando una Fake-Api.A continuacion se mostraran los endpoints desarrollados en este sprint.

<table>
  <tr>
    <td align ="center" > <strong>EndPoint</strong></td>
    <td  align ="center" > <strong>HttpVerb</strong></td>
    <td  align ="center" > <strong>Action</strong></td>

  </tr>

  <tr>
    <td  align="center"> https://my-json-server.typicode.com/Mirroy25/TechHelpTaskDb/task </td>
    <td align="center"> GET POST PUT DELETE</td>
    <td align="center"> - Se obtiene todos los datos.
    <br> -Se obtiene los datos por Id. 
    <br> - Se crea una nueva tarea
    <br> -Se actualiza una tarea mediante la id. </td>
  </tr>


  <tr>
    <td align="center"> https://my-json-server.typicode.com/GioRC0/TechHelpDB/technicals</td>
    <td align="center"> GET POST</td>
    <td align="center"> -Se obtiene todos los datos<br>
    -Registra los datos</td>

  </tr>

  <tr>
    <td align="center"> https://my-json-server.typicode.com/GioRC0/TechHelpDB/inventories</td>
    <td align="center"> GET POST </td>
    <td align="center"> -Se obtiene todos los datos del inventario.<br>
    -Se crea un inventario para un dashboard</td>

  </tr>

</table>


#### 5.2.3.7. Software Deployment Evidence for Sprint Review.

En esta sección se resume los procesos realizados en relación con Deployment durante este Sprint. 
Llevamos a cabo la implementación en un dos plataformas de confianza. Empleamos Railway para la implementación de la base de datos MySQL. Utilizamso la plataforma Zeabur para configurar el Service API aprovechando su facilidad en el uso. 

La plataforma Railway nos ofrece una serie de alternativas para integrar nuestro proyecto a su base de datos MySQL.  
![RailwayMySQL](https://i.ibb.co/2vgwnzC/Screenshot-1.jpg)  

Ingresamos con nuestra cuenta de GitHub y nos ofrece la opción de crear nuestro contenedor por MySQL.  
![MySQL](https://i.ibb.co/K7J0DKb/Screenshot-2.jpg)  


Creamos nuestra base de datos en el apartado que visualizamos en la derecha que dice "New".  
![MySQL](https://i.ibb.co/pvKnfgp/Screenshot-3.jpg)  


Seleccionamos la opción de "Add MySQL" para agregar un contenedor para nuestra solución.    
![MySQL](https://i.ibb.co/g6qK5c4/Screenshot-4.jpg)     

Una vez seleccionada la opción, automaticamente nos mostrará el contenedor creado con nuestra base de datos en MySQL.   
![MySQL](https://i.ibb.co/6vHwBH5/Screenshot-5.jpg)      
  
Dentro de las opciones, en la pestaña "Variables" tendremos toda la información para realizar la cadena de conexión entre la API y la base de datos.  
![MySQL](https://i.ibb.co/xFD8N5F/Screenshot-6.jpg)    

Para realizar el despliegue de nuestra API, integramos el uso de Zeabur, ya que es una solución que nos brinda HTTPS y es muchísimo más fácil deplegarla por esta plataforma que otras. 
![DeployAPI](https://i.ibb.co/r7wc4cV/Screenshot-7.jpg)   

Nuevamente ingresamos a la plataforma por nuestra cuenta de GitHub, en esta plataforma sí es importante, ya que lograremos usar el repositorio por esta forma y será más fácil para su implementación. Le damos a la opción de "Create Project".    
![DeployAPI](https://i.ibb.co/pj97yTK/Screenshot-8.jpg)     


Elegimos el servidor que más cerca se encuentra de nosotros, en este caso "California, United States".  
![DeployAPI](https://i.ibb.co/XWPgjfP/Screenshot-9.jpg)  


En la opción de implementar servicios, escogemos la forma de subir el proyecto por medio de nuestro Git.  
![DeployAPI](https://i.ibb.co/z8DNfjX/Screenshot-10.jpg)    
  
Seleccionamos el repositorio donde estamos realizando toda la solución de nuestra API.   
![DeployAPI](https://i.ibb.co/SdjRSQH/Screenshot-11.jpg)  

Una vez seleccionado el repositorio, automaticamente comenzará a desplegarse y nos mostrará el detalle de la implementación.  
![DeployAPI](https://i.ibb.co/mtLQNdR/Screenshot-12.jpg)    


Generamos el dominio para nuestra solución adecuado al nombre de nuestro proyecto, en nuestro caso, Techelp-api, que luego emplearemos el Swagger UI para mostrarlo.      
![DeployAPI](https://i.ibb.co/S3yF1MD/Screenshot-13.jpg)       


Una vez asignado el dominio, podremos visualizar nuestra API y la asignación que le hemos brindado a los Endpoints de la solución.      
![DeployAPI](https://i.ibb.co/nmGbGZT/Screenshot-14.jpg)  

Link del Api desplegada: [https://techelp-center-platform.zeabur.app/swagger-ui/index.html#/](https://techelp-center-platform.zeabur.app/swagger-ui/index.html#/)


#### 5.2.3.8. Team Collaboration Insights during Sprint.
__Backend__
En esta entrega, nuestra meta principal fue la implementación parcial del backend. Para llevar a cabo este objetivo, hicimos uso de diversas herramientas como GitHub, intellij y java. A continuación, vamos a presentar los diagramas de flujo que representan los commits realizados por cada miembro del equipo LogicVerse:

![commits-colaboration.png](../assets/img/chapter-v/barras.png)

En la imagen se evidencia el gráfico de barras de la cantidad de commits realizadas por cada uno de los integrantes del equipo. 

![commits.png](../assets/img/chapter-v/contribuciones.png)

En esta imagen, se ofrece una representación visual de las fechas en las que se llevaron a cabo cambios en el repositorio de nuestra Landing Page, junto con la cantidad de modificaciones realizadas en cada uno de los commits. Esta representación gráfica es una herramienta valiosa para comprender la evolución temporal del proyecto y la intensidad del desarrollo a lo largo del tiempo.


![network.png](../assets/img/chapter-v/Networkgraph.png)
En esta imagen se muestra las ramas realizadas para el desarrollo del backend de nuestra app web.Siendo una muestra del desarrollo de esta.

__Frontend__

En esta entrega, nuestra segunda meta fue la implementación total del fontend. Para llevar a cabo este objetivo, hicimos uso de diversas herramientas como GitHub y Webstrom. A continuación, vamos a presentar los diagramas de flujo que representan los commits realizados por cada miembro del equipo LogicVerse:

![commits-colaboration.png](../assets/img/chapter-v/barras_front.png)

En la imagen se evidencia el gráfico de barras de la cantidad de commits realizadas por cada uno de los integrantes del equipo. 

![commits.png](../assets/img/chapter-v/contribuidores_frontend.png)

En esta imagen, se ofrece una representación visual de las fechas en las que se llevaron a cabo cambios en el repositorio de nuestra Landing Page, junto con la cantidad de modificaciones realizadas en cada uno de los commits. Esta representación gráfica es una herramienta valiosa para comprender la evolución temporal del proyecto y la intensidad del desarrollo a lo largo del tiempo.


![network.png](../assets/img/chapter-v/network_frontend.png)
En esta imagen se muestra las ramas realizadas para el desarrollo del frontend de nuestra app web.Siendo una muestra del desarrollo de esta.




## 5.3. Validation Interviews.

### 5.3.1. Diseño de Entrevistas.

El propósito de las entrevistas es analizar el rendimiento del prototipo del Landing Page y la Web Application entre los usuarios y técnicos que utilizarán TecHelp. A partir de sus opiniones, evaluaremos posibles mejoras en nuestra aplicación y página de inicio, con el objetivo de adaptarlas a las necesidades de nuestros clientes.

Los userflow que presentaremos a los usuarios son los siguientes:  

__Landing Page - Usuario__  

* Ingresa a la sección "Home".  
* Ingresa a la sección "Service".  
* Ingresa a la sección "Membership".  
* Ingresa a la sección "Contact us".  
* Ingresa a la sección "About us".  
* Ingresa a la sección "Spanish".  
* Ingresa a la sección "English".  
* Ingresa a la sección "Dark Mode".  


__Web Application - Usuario__  

* Ingresa a la sección "Home".
* Ingresa a la sección "Technical".
* Ingresa a la sección "Progress".

Los userflow que presentaremos a los técnicos son los siguientes:  

__Landing Page - Técnico__  

* Ingresa a la sección "Home".  
* Ingresa a la sección "Service".  
* Ingresa a la sección "Membership".  
* Ingresa a la sección "Contact us".  
* Ingresa a la sección "About us".  
* Ingresa a la sección "Spanish".  
* Ingresa a la sección "English".  
* Ingresa a la sección "Dark Mode".  


__Web Application - Técnico__  

* Ingresa a la sección "Home".
* Ingresa a la sección "Profile".
* Ingresa a la sección "Task".
* Ingresa a la sección "Dashboard".
* Ingresa a la sección "Petition".


### 5.3.2. Registro de Entrevistas.

<center>
Entrevista Usuario 1
</center>

[![Ver entrevista](https://i.ibb.co/qdkNSZK/Screenshot-15.jpg)](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20191e575_upc_edu_pe/ERYKiNZU5cBGuz00fmGFYFYB9m8lpKKb2KAxUmPgYScrFg?e=R89AoR&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19)

* Nombre: Sandro Alarcon Rondón  
* Edad: 20  
* Distrito: San Juan de Lurigancho  
* Ocupación: Estudiante


Duración: [00:00:00 - 00:05:35]  
Descripción:  Sandro es un estudiante de 20 años que reside en el distrito de San Juan de Lurigancho. Él es uno de los entrevistados que aceptó a participar en esta validación, ya que también le interesa saber sobre un proyecto que solucione muchos de sus problemas en la vida cotidiana, tal como lo es la reparación de su celular. En la entrevista Sandro nos menciona que las funcionalidades implementadas dentro del proyecto, son muy completas ya que satisfacen las necesidades que pueda necesitar al momento de requerir un técnico especializado. También nos menciona, que el diseño de las vistas puede mejorar, ya que no resulta tan atractivo a la vista del usuario, y más aún si la aplicación depende de la interacción del usuario que del mismo técnico.  

<br>
--------------------------------------  

<center>
Entrevista Técnico 1  
</center>  

* Nombre: Gino Aro  
* Edad: 22  
* Distrito: La Victoria  
* Ocupación: Técnico en reparación de celulares.  


[![Ver entrevista](https://i.ibb.co/QpQhs85/Screenshot-16.jpg)](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20191e575_upc_edu_pe/ERYKiNZU5cBGuz00fmGFYFYB9m8lpKKb2KAxUmPgYScrFg?e=gcczGy&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19)

Duración:  [00:05:35 - 00:10:26]  
Descripción:  Gino es un técnico de 22 que reside en el distrito de La Victoria, es un especialista en reparación de celulares y él le interesa la plataforma ya que es parte de su trabajo del día a día. A él le motiva que existan este tipo de plataformas para promover la forma de promocionar su trabajo. Nos comenta que las funcionalidades le parece muy buenas para la vista del usuario, ya que todas cumplen en base a lo que sus clientes piden. Nos comenta también que le gustaría que mejoren la experiencia del usuario con el diseño de la aplicación. 

--------------------------------------  





### 5.3.3. Evaluaciones según heurísticas.

<Table>
  <tr>
    <td><b>#</b></td>
    <td><b>Problema</b></td>
    <td><b>Escala de Severidad</b></td>
    <td><b>Heurística/Principio violada(o)</b></td>
  </tr>

  <tr>
    <td>1</td>
    <td>Se repite constantemente algunas opciones</td>
    <td>2</td>
    <td>Usability: Consistencia y estandares</td>
  </tr>

  <tr>
    <td>2</td>
    <td>No hay mensajes que confirmen al eliminar un Componente</td>
    <td>3</td>
    <td>Usability:Libertad y Control</td>
  </tr>
    
  <tr>
    <td>3</td>
    <td>El Dashboard no muestra informacion concreata</td>
    <td>2</td>
    <td>Information Architecture: Is it usable?</td>
  </tr>

  <tr>
    <td>4</td>
    <td>Se repite constantemente algunas paginas</td>
    <td>1</td>
    <td>Usability:Consistencia y estandares</td>
  </tr>

   <tr>
    <td>5</td>
    <td>No hay peronalizacion mas propia del usuario respecto a los colores</td>
    <td>1</td>
    <td>Usability:Libertad y Control</td>
  </tr>

 
</Table>

## 5.4. Video About-the-Product.
En el siguiente se presentara el video de nuestra aplicacion web se presentara a nuestros publicos objetivos 
![video](../assets/img/chapter-v/videoaboutproduct.png)

link: [https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211f984_upc_edu_pe/Efgyenk14YJJhHOpUMNUqbsB64hw12GZ_dwjKxZoLHb1zw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19&e=f2AcMS](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20211f984_upc_edu_pe/Efgyenk14YJJhHOpUMNUqbsB64hw12GZ_dwjKxZoLHb1zw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZyIsInJlZmVycmFsQXBwUGxhdGZvcm0iOiJXZWIiLCJyZWZlcnJhbE1vZGUiOiJ2aWV3In19&e=f2AcMS)

## 5.2.4. Sprint 4

### 5.2.4.1. Sprint Planning 4

En este punto se busca perfeccionar la arquitectura del back-end, corrigiendo y optimizando aspectos identificados durante el Sprint 3. Este sprint no solo se centra en la rectificación de fallos y la mejora de la eficiencia, sino que también se propone implementar una capa adicional de seguridad vital para el funcionamiento robusto de nuestro sistema y ademas se implementa la capa de membresias.

<table>
    <thead>
        <tr>
            <th>Sprint #</th>
            <th>Sprint 4</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td colspan="2"><b>Sprint Planning Background</b></td>
        </tr>
        <tr>
            <td>Date</td>
            <td>2023/11/11</td>
        </tr>
        <tr>
            <td>Time</td>
            <td>11:00 PM</td>
        </tr>
        <tr>
            <td>Location</td>
            <td>Discord meeting</td>
        </tr>
        <tr>
            <td>Prepared by</td>
            <td>Brayan Morales</td>
        </tr>
        <tr>
            <td>Atendees (to planning meeting)</td>
            <td>
                Gonzalo Saldaña, Giovanni Ramos, Luis Lagos, Sebastián Ramirez 
            </td>
        </tr>
        <tr>
            <td>Sprint 4 Review Summary</td>
            <td>
                La opinion del product owner y las partes interesadas con respecto al avance realizado al concluir el sprint 3  fue el esperado.
            </td>
        </tr>
        <tr>
            <td>Sprint 4 Retrospective Summary</td>
            <td>
                En el sprint 3 se pudo mejorar aspectos de eficiencia en algunos componentes y la organización de la arquitectura del Back-End. Para el sprint 4 se plantee levantar estas observaciones para el correcto funcionamiento de la aplicación. 
            </td>
        </tr>
        <tr>
            <td colspan="2"><b>Sprint Goal & User Stories</b></td>
        </tr>
        <tr>
            <td>Sprint 4 Goal</td>
            <td>
                Concluir y mejorar las intefaces de la aplicación web, levantado las observaciones del sprint 3. Implementar las tablas para membreship y la capa de seguridad. 
            </td>
        </tr>
        <tr>
            <td>Sprint 4 Velocity</td>
            <td>
                30
            </td>
        </tr>
        <tr>
            <td>Sum of story points</td>
            <td>
                30
            </td>
        </tr>
    </tbody>
</table>


### 5.2.4.2. Sprint Backlog 4

En el tercer sprint backlog, el equipo completó en un 80% el front end y un 70% del back end de la aplicación web. La herramienta utilizada para organizar y gestionar a los miembros del equipo fue Trello. Esta herramienta permitio al equipo de desarrollo dividir las user stories que corresponden al sprint 4 en tareas y asignar al responsables.

![Trello Sprint 4]()


Link de Trello:

<table>
    <thead>
  <>
    <tr>
        <th>Sprint #</th>
        <th colspan="7">Sprint 4</th>
    </tr>
    <tr>
      <th colspan="2">Technical User Story</th>
      <th colspan="6">WorkItem / Task</th>
    </tr>
    <tr>
      <th>Id</th>
      <th>Title</th>
      <th>Id</th>
      <th>Title</th>
      <th>Description</th>
      <th>Estimation (Hours)</th>
      <th>Assigned To</th>
      <th>Status(To-do/In-Process/To-Review/Done)</th>
    </tr>
    <tr>
            <td rowspan="3">UH01</td>
            <td rowspan="3">Administrar inventario</td>
            <td>TA01</td>
            <td>Implementación del backend</td>
            <td>Se implementara en el backend el bounded context Inventory </td>
            <td> 5</td>
            <td> Giovanni Ramos </td>
            <td>Done</td>
        </tr>
        <tr>
            <td>TA02</td>
            <td>Implementcion del Frontend</td>
            <td>Se implementara en el frontend el bounded context inventory</td>
            <td> 5h</td>
            <td> Luis Lagos </td>
            <td>Done</td>
        </tr>
        <tr>
            <td>TA03</td>
            <td>Uso de Api externar</td>
            <td>Integraciaon de la backend con el frontend</td>
            <td>2h</td>
            <td> Sebastian </td>
            <td>Done</td>
        </tr>
        <tr>
            <td rowspan="2">UH03</td>
            <td rowspan="2">Registro de la aplicación</td>
            <td>TA04</td>
            <td>Implementación del backend</td>
            <td>Se implementara en el backend el bounded context Inventory</td>
            <td> 5h</td>
            <td> Brayan Morales </td>
            <td>Done</td>
        </tr>
        <tr>
            <td>TA05</td>
           <td>Implementacion del Frotnend</td>
            <td>Se implementara el bounded context en el backend</td>
            <td> 4h</td>
            <td> Gonzalo Janover </td>
            <td>Done</td>
        </tr>

### 5.2.4.3. Development Evidence for Sprint Review.

Para este cuarto sprint logramos desplegar y desarrollar las siguientes secciones de nuestra aplicación web:Login, Register,Progress, Technical, ViewProgress,Memberchip,Task,CreateTask,UpdateTask,ViewTask,TechnicalProfile,EditTechnicalProfile.

Evidencias del BackEnd:

<br>
<table>
  <tr>
    <td align ="center" > <strong>Repository</strong></td>
    <td  align ="center" > <strong>Branch</strong></td>
    <td  align ="center" > <strong>Commit ID</strong></td>
    <td  align ="center" > <strong>Commit message</strong></td>
    <td  align ="center" > <strong>Commit Masagge body</strong></td>
    <td  align ="center" > <strong>Commit on (date)</strong></td>
  </tr>

  <tr>
    <td rowspan="33" align="center"> https://github.com/LogicVersee/techelp-center-platform-backend </td>
    <td align="center"> master</td>
    <td align="center"> bc3df0401d1b07fc4d74d41eaa4e000e388a0c9e</td>
    <td align="center"> chore: initial commit</td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> master</td>
    <td align="center" > 4b801f00a6a332cdbeefc124158228036b76be27</td>
    <td align="center"> chore: added dependencies.</td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/register</td>
    <td align="center"> 56fca751ebf0aa88beb50a8ad3875d5ea876465c</td>
    <td align="center"> feat(technical): technical, dashboard, component and incomes entities implemented</td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/register</td>
    <td align="center"> 6db06a22c15ec56e7ede07d353eda1c153b3cad7</td>
    <td align="center"> feat(technical): technical controller created </td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/register</td>
    <td align="center"> cb5e517aa6505a77f03221872d78e12b11ff73d0</td>
    <td align="center"> feat(inventory): inventory controller created</td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/register </td>
    <td align="center"> 9338e88d83169e4d7b9eb70befef63dd74e509a5</td>
    <td align="center"> feat(dash-board): implemented dashboard context facade </td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/register </td>
    <td align="center"> e63bc3022f2253d762509f0ceb5e811abb46c049</td>
    <td align="center"> feat(task): task command created</td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/register </td>
    <td align="center"> 3080bfc3d56b0c1262f30cd16b88719e72435ea1 </td>
    <td align="center"> feat(task): client name's value object created</td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/register </td>
    <td align="center"> af28c9ab9cb54f0223160c0e83a0ca42df46eae2 </td>
    <td align="center"> feat(task): client phone name's value object created </td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>
  <tr>
    <td align="center"> feature/register </td>
    <td align="center"> 2469e86a7045e480af1d04ac0b0eca2e68f1f72f </td>
    <td align="center"> feat(task): client problem's value object created </td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/register </td>
    <td align="center"> 6cc2bd4ab00ce32798ee41c6578f71bb15dfebd0 </td>
    <td align="center"> feat(task): client delivery day's value object created. </td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> 749fb2af8589fa694db41b6fac1680cd3f16de0d</td>
    <td align="center"> fix(task): task command created fixed. </td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> c3bfc367367eb794b8193f1919d0ea8ebd4d3369</td>
    <td align="center"> feat(task): task entity created. </td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> 73f2f9d39bcb5e3e602f618516c04fa0696156e2</td>
    <td align="center"> feat(task): get task by technicalid created. </td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> 4ea62f50c5d8c40ac137c9f2a03e14aa28447a53</td>
    <td align="center"> feat(task): task services created </td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> a210a72d51d4c7e39c8994c08a6fe467ac2e0344</td>
    <td align="center"> feat(task): task repository created</td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> d929347a7840b6db553b156ddf7992c1edc87122</td>
    <td align="center"> feat(task): task context facade created </td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task</td>
    <td align="center"> a1f19abb6490ac11049e1aea8a7415b09c9acad2</td>
    <td align="center"> feat(task): task service implementation created </td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task</td>
    <td align="center"> 4a8dd81a699f53beb81fe2b1c9eb25e8a067e921</td>
    <td align="center"> feat(task): task controller created</td>
    <td align="center"> ---</td>
    <td align="center">23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task</td>
    <td align="center"> 18298a9831ff3d3362fdd56875735e2d7c653ece</td>
    <td align="center"> feat(task): task by id query created.</td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task</td>
    <td align="center"> 81d67e09fa54490a72e06f9a2538fffbfe0789cb</td>
    <td align="center"> fix(DeliveryDay): public string getdeliveryday fixed </td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task</td>
    <td align="center"> 430655d64b4c6866a2d9f23328253101a0c61cf6</td>
    <td align="center"> feat(task): task resource added</td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task</td>
    <td align="center"> a6d59a4b95dec69455a1e1632aeef4ebba989942</td>
    <td align="center"> feat(task): create task resource added.</td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task</td>
    <td align="center"> 4550c3c4dfe0aa68fb1c09673fcd1b56cce73e31</td>
    <td align="center"> feat(task): create task from resource assembler transform added.</td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>


  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> a036a754794f4062aba1837cef37f1685e231b21</td>
    <td align="center"> feat(task): task from entity assembler transform added.</td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task </td>
    <td align="center"> c21233ed8bf057a3512d1e0d82b359e9c30ff61c</td>
    <td align="center"> feat(task): task command service implementation created.</td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

  <tr>
    <td align="center"> feature/task</td>
    <td align="center"> b2c45b715a653a7886320fa050109ed7409784f6</td>
    <td align="center"> feat(task): task query service implementation created.</td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>

 <tr>
    <td align="center"> feature/task</td>
    <td align="center"> d2b279205081e497cee79221d9458d37ebe0c60d</td>
    <td align="center"> feat(task): task controller added.</td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>
 <tr>
    <td align="center"> feature/task</td>
    <td align="center"> 1412700dabd3377c8bc7f2cc391abe18725eb229</td>
    <td align="center"> feat(task): edited dependencies.</td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>
 <tr>
    <td align="center"> feature/task</td>
    <td align="center"> ad269d55c2d5f8cada22e412767aebdcb349b26a</td>
    <td align="center"> feat(task): added query to get tasks by technical id.</td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>
 <tr>
    <td align="center"> test</td>
    <td align="center"> ca2b5d9bdd22e1144d9a88f3893d69faff3ecdce</td>
    <td align="center"> feat(test): technicals feature added.</td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>
 <tr>
    <td align="center"> test</td>
    <td align="center"> 8734d23116b1e7d9502e82e82eb0eaa2cf3a75bb</td>
    <td align="center"> feat(test): item feature added.</td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>
 <tr>
    <td align="center">test </td>
    <td align="center"> 38ee3231dcbfed24f7d2797973ddb5aba612e16f</td>
    <td align="center"> feat(test): tasks feature added.</td>
    <td align="center"> ---</td>
    <td align="center"> 23/11/2023</td>
  </tr>


</table>

### 5.2.4.4. Testing Suite Evidence for Sprint Review.

### 5.2.4.5. Execution Evidence for Sprint Review.
Para este cuarto  sprint se ha desplegado la siguientes secciones en nuestra aplicacion web.

La implementacion de ambas vistas tanto para el usuario como del tecnico.

![commits.png](../assets/img/chapter-v/dashboard.jpg)

![commits.png](../assets/img/chapter-v/dashboardTh.jpg)

### 5.2.4.6. Services Documentation Evidence for Sprint Review.
En este Sprint se tomó importancia la parte de la seguridad, es por ello que se implementaron los siguientes Endpoints para la lógica de autentificación.

![DeployAPI](https://images-ext-1.discordapp.net/external/xkyY_67lLFW-_MpNXHDKVZ6VpkEweCE-DQjRmPlP-gg/https/i.ibb.co/QcYN8jB/Screenshot-12.jpg?format=webp)


### 5.2.4.7.  Software Deployment Evidence for Sprint Review.

En esta sección se resume los procesos realizados en relación con Deployment durante este Sprint.
Llevamos a cabo la implementación en un dos plataformas de confianza. Empleamos Railway para la implementación de la base de datos MySQL. Utilizamso la plataforma Zeabur para configurar el Service API aprovechando su facilidad en el uso.

La plataforma Railway nos ofrece una serie de alternativas para integrar nuestro proyecto a su base de datos MySQL.  
![RailwayMySQL](https://i.ibb.co/2vgwnzC/Screenshot-1.jpg)

Ingresamos con nuestra cuenta de GitHub y nos ofrece la opción de crear nuestro contenedor por MySQL.  
![MySQL](https://i.ibb.co/K7J0DKb/Screenshot-2.jpg)


Creamos nuestra base de datos en el apartado que visualizamos en la derecha que dice "New".  
![MySQL](https://i.ibb.co/pvKnfgp/Screenshot-3.jpg)


Seleccionamos la opción de "Add MySQL" para agregar un contenedor para nuestra solución.    
![MySQL](https://i.ibb.co/g6qK5c4/Screenshot-4.jpg)

Una vez seleccionada la opción, automaticamente nos mostrará el contenedor creado con nuestra base de datos en MySQL.   
![MySQL](https://i.ibb.co/6vHwBH5/Screenshot-5.jpg)

Dentro de las opciones, en la pestaña "Variables" tendremos toda la información para realizar la cadena de conexión entre la API y la base de datos.  
![MySQL](https://i.ibb.co/xFD8N5F/Screenshot-6.jpg)

Para realizar el despliegue de nuestra API, integramos el uso de Zeabur, ya que es una solución que nos brinda HTTPS y es muchísimo más fácil deplegarla por esta plataforma que otras.
![DeployAPI](https://i.ibb.co/r7wc4cV/Screenshot-7.jpg)

Nuevamente ingresamos a la plataforma por nuestra cuenta de GitHub, en esta plataforma sí es importante, ya que lograremos usar el repositorio por esta forma y será más fácil para su implementación. Le damos a la opción de "Create Project".    
![DeployAPI](https://i.ibb.co/pj97yTK/Screenshot-8.jpg)


Elegimos el servidor que más cerca se encuentra de nosotros, en este caso "California, United States".  
![DeployAPI](https://i.ibb.co/XWPgjfP/Screenshot-9.jpg)


En la opción de implementar servicios, escogemos la forma de subir el proyecto por medio de nuestro Git.  
![DeployAPI](https://i.ibb.co/z8DNfjX/Screenshot-10.jpg)

Seleccionamos el repositorio donde estamos realizando toda la solución de nuestra API.   
![DeployAPI](https://i.ibb.co/SdjRSQH/Screenshot-11.jpg)

Una vez seleccionado el repositorio, automaticamente comenzará a desplegarse y nos mostrará el detalle de la implementación.  
![DeployAPI](https://i.ibb.co/mtLQNdR/Screenshot-12.jpg)


Generamos el dominio para nuestra solución adecuado al nombre de nuestro proyecto, en nuestro caso, Techelp-api, que luego emplearemos el Swagger UI para mostrarlo.      
![DeployAPI](https://i.ibb.co/S3yF1MD/Screenshot-13.jpg)


Una vez asignado el dominio, podremos visualizar nuestra API y la asignación que le hemos brindado a los Endpoints de la solución.      
![DeployAPI](https://images-ext-1.discordapp.net/external/xkyY_67lLFW-_MpNXHDKVZ6VpkEweCE-DQjRmPlP-gg/https/i.ibb.co/QcYN8jB/Screenshot-12.jpg?format=webp)

Link del Api desplegada: [https://techelp-center-platform.zeabur.app/swagger-ui/index.html#/](https://techelp-center-platform.zeabur.app/swagger-ui/index.html#/)

### 5.2.4.8. Team Collaboration Insights during Sprint.

__Backend__
En esta entrega, nuestra meta principal fue la implementación parcial del backend. Para llevar a cabo este objetivo, hicimos uso de diversas herramientas como GitHub, intellij y java. A continuación, vamos a presentar los diagramas de flujo que representan los commits realizados por cada miembro del equipo LogicVerse:

![commits-colaboration.png](../assets/img/chapter-v/barras.png)

En la imagen se evidencia el gráfico de barras de la cantidad de commits realizadas por cada uno de los integrantes del equipo.

![commits.png](../assets/img/chapter-v/contributors.png)

En esta imagen, se ofrece una representación visual de las fechas en las que se llevaron a cabo cambios en el repositorio de nuestra Landing Page, junto con la cantidad de modificaciones realizadas en cada uno de los commits. Esta representación gráfica es una herramienta valiosa para comprender la evolución temporal del proyecto y la intensidad del desarrollo a lo largo del tiempo.


![network.png](../assets/img/chapter-v/newtworkbd.PNG)
En esta imagen se muestra las ramas realizadas para el desarrollo del backend de nuestra app web.Siendo una muestra del desarrollo de esta.

__Frontend__

En esta entrega, nuestra segunda meta fue la implementación total del fontend. Para llevar a cabo este objetivo, hicimos uso de diversas herramientas como GitHub y Webstrom. A continuación, vamos a presentar los diagramas de flujo que representan los commits realizados por cada miembro del equipo LogicVerse:

![commits-colaboration.png](../assets/img/chapter-v/barras_ft.PNG)

En la imagen se evidencia el gráfico de barras de la cantidad de commits realizadas por cada uno de los integrantes del equipo.

![commits.png](../assets/img/chapter-v/contri_ft.PNG)

En esta imagen, se ofrece una representación visual de las fechas en las que se llevaron a cabo cambios en el repositorio de nuestra Landing Page, junto con la cantidad de modificaciones realizadas en cada uno de los commits. Esta representación gráfica es una herramienta valiosa para comprender la evolución temporal del proyecto y la intensidad del desarrollo a lo largo del tiempo.


![network.png](../assets/img/chapter-v/netft.PNG)
En esta imagen se muestra las ramas realizadas para el desarrollo del frontend de nuestra app web.Siendo una muestra del desarrollo de esta.
