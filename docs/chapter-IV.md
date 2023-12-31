# Capítulo IV: Product Design

## 4.1. StyleGuidelines

### 4.1.1. General Style Guidelines.

En este apartado, se mostrará de manera organizada los estilos y herramientas que se usarán para diseñar nuestra solución.

**Brand Overview**

La necesidad de contar con un celular en buen funcionamiento se hace más notoria cada día en el Perú, ya sea por estudios, trabajos, etc. El servicio que se le brinda a la persona que desea reparar su celular, muchas veces no es el adecuado. Es verdad que no todos los técnicos dan un pésimo servicio, pero los que realmente son buenos, no son conocidos o muy poca gente conoce de ellos, lo que demuestra una desconexión entre un cliente y un buen técnico por ende ambos segmentos son afectados.

Nuestra solución Techelp, surge a partir de esa desconexión que hay entre los dos segmentos. Nuestro equipo ha diseñado un producto el cual conectará ambos segmentos para que de esta manera ambos consigan sus objetivos.

**Brand name**

El nombre de nuestra solución es Techelp. Esto debido al notar la necesidad de las personas por un buen servicio de un técnico de celulares. Del mismo modo, los técnicos son los que brindan ese servicio “Tecnológico”. Por ello, la “tecnología” en este caso los celulares y el brindar “ayuda” son las piezas claves de este software. Asimismo, ambas se juntan ya que queremos dejar claro al usuario que ambas palabras van de la mano. Además, se escogió el inglés por ser una lengua universal, lo que lo hace más comercial al usuario.

A continuación, se presenta el Logo:

![logo.png](../assets/img/chapter-IV/CompletoLogo.png)

**Typography**

La tipografía nos ayuda a seccionar por niveles los distintos contenidos de las páginas. Además, atrapa visualmente al usuario si estas son amigables y a su vez lo guía por toda nuestra interfaz.

El tipo de letra que nuestro equipo eligió fue Montserrat debido a su legibilidad al momento de leerlo y escribirlo. La tipografía de Techelp se organiza en 4 niveles headings, body, button y link.

![](../assets/img/chapter-IV/Montsrrat.png)

**Colors**

La elección de colores es una parte importante del diseño. Una buena elección de colores transmite al usuario lo que nosotros realmente ofrecemos. Por eso tenemos como color primario el azul y el color secundario el verde azulado. Además, se muestran los colores estado los cuales usaremos para que el usuario sepa qué sucede mientras interactúa con nuestra aplicación.

**Color Primario Azul:**

El color azul siempre hace alusión a dos cosas la tecnología y el bienestar. Con ese enfoque, damos entender al usuario de que será nuestra   aplicación web. Además se sabe que el azul genera serenidad y calma a las personas,   lo cual queremos lograr con el usuario.

![](../assets/img/chapter-IV/PrimaryColor.png)

**Color secundario azul-verdoso:**

Se eligió por su impacto, su tranquilidad y paz que transmite a los usuarios, pero sobre todo la confianza. Lo cual es primordial que desea   mostrar nuestra aplicación.

![](../assets/img/chapter-IV/SecndaryColor.png)

**Color estado: Rojo - (Acción inconclusa o incorrecta)**

Se usa el rojo para este estado debido a que el usuario identificará la acción que comete de manera errónea rápidamente.

![](../assets/img/chapter-IV/RedState.png)

**Color estado: Verde (Acción exitosa)**

Se consideró el verde como color de este estado debido a que el usuario     ya se siente familiarizado con este       color y sabrá que la acción fue exitosa   de manera inmediata.

![](../assets/img/chapter-IV/GreenState.png)

**Color estado: Amarillo (Advertencia de    una acción) **

Se eligió el color amarillo para este estado debido a que siempre se ha   usado para advertir al usuario si está cometiendo una acción que afectara a futuro las actividades que realice.

![](../assets/img/chapter-IV/YellosState.png)

**Color Estado: Gris (Botón o Acción deshabilitada)**

Sé usa este color gris para mostrar al usuario que la acción o botón está deshabilitada, ya que deberá completar otras posteriormente para poder así habilitarlas.

![](../assets/img/chapter-IV/GrayState.png)

**Spacing**

El espacio que usaremos para cada componente serán múltiplos de 8 pixeles.

![](../assets/img/chapter-IV/Spacing.png)

**Tono de lenguaje de comunicación y lenguaje aplicado**

El lenguaje que implementaremos será formal, serio, calma, confiabilidad y entusiasmo. Ya que se desea potenciar la paz, calma y confianza del usuario y darle a entender que la aplicación es serie y podrán solucionar sus problemas con esa aplicación.

### 4.1.2. Web Style Guidelines

Implementaremos un sitio web responsive, ose que se pueda adaptar a cualquier dispositivo sin arruinar la experiencia del usuario, siendo siempre comprensible y visualmente agradable. Teniendo en cuenta lo mencionado se tendrá que adaptar nuestra aplicación web a las resoluciones que hoy en día se usan en los diversos dispositivos.

![](../assets/img/chapter-IV/Responsive.png)

Se usará el patrón Z, ya que queremos que el usuario comience la navegación de nuestro landing page y aplicación web visualizando el logo para que luego se ubique a la derecha donde verá las distintas opciones que le brindaremos.  Seguidamente de manera vertical hacia abajo el usuario verá el contenido general de nuestra landing page y aplicación web, Para que al final visualice de manera horizontal a la derecha la información de nuestra startup y cómo se puede contactar con nosotros.

![](../assets/img/chapter-IV/Zmethod.png)

Cabe mencionar que el diseño presenta colores que atraigan al usuario, para que le generen paz, confianza y ganas de usar nuestra aplicación. Además, los espacios y efectos que se incluirán facilitarán al usuario saber de qué se trata nuestro landing page y aplicación web.

## 4.2. Information Architecture

### 4.2.1. Organization Systems

A Continuación, se indican los tipos de estructura visual que tendrá cada grupo de información con respecto al segmento objetivo y al tipo de categorización que se usará.

**Segmento 1: Personas que deseen el servicio de un buen técnico**

**Jerarquía:**

Lista de Técnicos: Los técnicos se mostrarán de manera vertical y ordenada, se podrán usar filtros  para variar el orden, esto depende del usuario. De esta manera el usuario podrá elegir el técnico de su preferencia.

Perfil de Técnico: El usuario podrá acceder y visualizar el perfil del técnico para tener más información de este.

Lista de Favoritos: Los técnicos se mostrarán de manera vertical y ordenada, se podrán usar filtros para variar el orden, esto depende del usuario. De esta manera el usuario podrá elegir al técnico que le brindó un mejor servicio de manera más rápida.

Bandeja de entrada: Esta bandeja se dividirá en dos, por una parte las solicitudes de servicios a técnicos se mostrarán de manera ordenada y vertical . De igual manera las solicitudes aceptadas se mostrarán en una segunda pestaña dentro de la misma bandeja de entrada.

**Secuencial:**

Solicitud de servicio técnico: Este es un proceso en el cual el cliente debe realizar su solicitud detallada para que le puedan brindar un servicio técnico. Debe brindar nombre completo, fecha y hora, fallo del equipo y método de pago.

Calificar y comentar al técnico: Este es un proceso a la hora de finalizar el servicio con el técnico la persona puede calificar el servicio y comentar su experiencia a la hora de acudir a ese técnico.

**Matricial:**

Visualizar el progreso de la reparación:  En esta sección el usuario puede verificar en qué estado de reparación se encuentra su celular ya sea inicio, en proceso o finalizado.

**Segmento 2: Técnico de Celulares**

**Jerarquía:**

Lista de peticiones de reparación:  Se mostrarán de manera organizada y vertical las peticiones de los clientes que deseen reservar una cita con el técnico. El técnico en cuestión puede filtrar a su gusto para aceptar las reservas con las que él se sienta más cómodo.

Lista de tareas: Se mostrarán de manera organizada todas las tareas asignadas por el técnico las cuales estarán detalladas y podrán ser filtradas a gusto del técnico.

**Secuencial:**

Designar una tarea: Para designar una tarea el técnico ya debió realizar la cita con el cliente para que luego al designar esa tarea pueda detallar todos los términos en los cuales el cliente y él acordaron como también otros detalles técnicos.

Compra de membresía: Para poder realizar la compra de la membresía el técnico debe registrar datos de una tarjeta en la cual pueda realizar el pago y así obtener su membresía

Visualizar el Inventario: Para poder visualizar el inventario el técnico tendrá que dirigirse a su dashboard y seleccionar el apartado de su inventario.

Cancelar membresía: Para cancelar su membresía el técnico debe dirigirse a su perfil y describirse detallando por qué ya no desea la membresía y aceptando que se le quitaran los beneficios de esta.

**Matricial:**

Visualizar las tareas en progreso: Técnico podrá visualizar las tareas que se ha designado, visualizando los detalles y el tiempo que le queda para realizar la tarea.

De igual manera hay algunas funciones la cual va dirigida a ambos segmentos:

**Jerarquía:**

Landing Page: El sitio web estático es la sección en la cual nuevos usuarios observarán toda la información y beneficios que brinda nuestra aplicación web, además de nuestra información como equipo entre otros.  Toda la información será categorizada y organizada para que los nuevos usuarios se sientan cómodos.

Lista de comentarios: Los comentarios de los clientes sobre los servicios de los técnicos se muestran de manera ordenada para ambos en el perfil del técnico en el cual se le comentó su servicio.

**Matricial :**

Menú: Usuario y técnico podrán visualizar un menú de opciones que varía dependiendo de si es usuario o técnico en el cual se le brindará un acceso rápido a los apartados de la aplicación web.

### 4.2.2. Labeling Systems

En este apartado el equipo de trabajo mostrará el etiquetado que tendrá nuestra página de aterrizaje.

**Inicio/Home:** Sección preseleccionada que mostrará un banner con una frase representativa, de igual manera brindará una idea principal y a su vez un botón con el cual el usuario podrá entrar a la aplicación.

**Servicios/Service:** Sección dividida por cada segmento en donde se le mostrarán los beneficios que tendrá cada uno a la hora de usar la aplicación.

**Membresía/Membership:** Se mostraran los precios que tendrá las membresías a los técnicos y los beneficios que tendrá a la hora de pagar por esta.

**Contactanos/Contact Us:** Se mostrarán nuestros canales de comunicación, a la vez que un formulario en donde pueda enviar sus comentarios.

**Nosotros/ About Us:** Esta sección el cliente podrá visualizar la información del equipo la cual trabaja en la aplicación.

A continuación el equipo de trabajo mostrará el etiquetado que tendrá nuestra aplicación web para ambos segmentos.

**Segmento 1: Personas que deseen el servicio de un buen técnico**

**Inicio/Home:** Sección preseleccionada que mostrará el progreso de reparación  de su equipo, lista de técnicos y la bandeja de entrada. Todas sin detallar para que el mismo usuario vaya a las demás secciones para ver los detalles.

**Progreso de Reparación/ Progress:** La sección le detalla al usuario que tanto le falta a su equipo para que él pueda ir a recogerlo.

**Técnicos / Technical:** Esta sección le brinda al usuario una lista de técnicos organizada de tal manera que se visualizará los técnicos con mejor calificación primero. Del mismo modo habrá un apartado en donde pueda filtrar los técnicos ya sea por su experiencia, calificación, costo. Además de contar con una barra de búsqueda.

**Favoritos/ Favorite:** Esta sección el usuario podrá visualizar a los técnicos que tiene como favoritos de esta manera se le facilitará  la búsqueda si desea contactar de nuevo con ellos.

**Bandeja de entrada/Inbox:** En esta sección el usuario puede visualizar todas las peticiones aceptadas por algún técnico con el que solicitó su servicio.

**Segmento 2: Tecnico de Celulares**

**Inicio/Home:** Sección preseleccionada que mostrará las tareas que están en progreso , el dashboard y los pedidos.  Todas sin detallar para que el mismo usuario vaya a las demás secciones para ver los detalles.

**Perfil/ Profile:** Sección el cual el técnico puede visualizar su perfil y comentarios que le han dedicado, además de poder editar su información.

**Tareas/ Task:** Sección la cual el técnico podrá  generar una tarea la cual usará como  método de recordatorio de a quién le está brindando su servicio que día debe ser culminado el servicio y el fallo que debe solucionar.

**Pedidos/Request:** Es una bandeja en la cual el técnico puede aceptar o no las citas de los clientes.

**Panel de control /Dashboard:** En este apartado se mostrará al técnico dos herramientas que le ofreceremos para que gestione su negocio. Se le brindará un inventario de componentes y las estadísticas de ingresos mensuales y semanales.

### 4.2.3. SEO Tags and Meta Tags

<a href="https://imgbb.com/"><img src="https://i.ibb.co/ZcF0Twz/image.png" alt="image" border="0"></a>

Esta etiqueta se utiliza para especificar la codificación de caracteres del documento HTML. Ayuda a los motores de búsqueda y navegadores a interpretar correctamente los caracteres especiales y asegura la correcta representación de texto en diferentes idiomas.

<a href="https://imgbb.com/"><img src="https://i.ibb.co/w4Qd1q5/image.png" alt="image" border="0"></a>

Esta etiqueta indica al navegador que utilice la última versión de Internet Explorer (o el modo de emulación Edge) para representar la página. Ayuda a garantizar la compatibilidad y la representación adecuada en navegadores antiguos de Internet Explorer.

<a href="https://imgbb.com/"><img src="https://i.ibb.co/zh0z7bV/image.png" alt="image" border="0"></a>

Esta etiqueta es esencial para el diseño web receptivo (responsive design). Específicamente, indica que el ancho del viewport debe ser igual al ancho del dispositivo y que la escala inicial debe ser 1.0, lo que ayuda a optimizar la visualización en dispositivos móviles.

<a href="https://imgbb.com/"><img src="https://i.ibb.co/KjctZyg/image.png" alt="image" border="0"></a>

Esta etiqueta meta se utiliza para especificar palabras clave relacionadas con el contenido del sitio web.

<a href="https://ibb.co/Pms8pMc"><img src="https://i.ibb.co/Gxfjw9W/image.png" alt="image" border="0"></a>

Esta etiqueta meta proporciona una breve descripción del contenido de la página. La descripción meta se muestra en los resultados de búsqueda de Google y otros motores de búsqueda.

<a href="https://imgbb.com/"><img src="https://i.ibb.co/QQtK8kz/image.png" alt="image" border="0"></a>

La etiqueta title se utiliza para definir el título de la página, que es crucial para el SEO. El título aparece en la barra de título del navegador y es uno de los factores más importantes para el posicionamiento en motores de búsqueda.

En resumen, estas etiquetas y meta tags se utilizan para mejorar la optimización de motores de búsqueda y la experiencia del usuario en el sitio web TecHelp al definir la codificación, la compatibilidad del navegador, el diseño receptivo, el título de la página, las palabras clave y la descripción del contenido.  

### 4.3.1. Landing Page Wireframe
En esta sección se mostrará el desarrollo final de los Wireframes del Landing Page. [Link del Wireframe](https://www.figma.com/file/qSyCbAqHOXsX1mVh4EX8yy/Open-Source?type=design&node-id=508%3A838&mode=design&t=c0yzJ4yiEgVpak2m-1)

![Wireframes](../assets/img/chapter-IV/Lading%20Page%20Wireframe.png)

En este capítulo se desarrolló lo wireframes que es una representación de bajo nivel a una escala de grises que permite tener una idea temprana de nuestro diseño del landing page.

### 4.3.2. Landing Page Mock-up
En esta sección se mostrará el desarrollo final de los Mockup del Landing Page. [Link del Mockup](https://www.figma.com/file/qSyCbAqHOXsX1mVh4EX8yy/Open-Source?type=design&node-id=508%3A838&mode=design&t=c0yzJ4yiEgVpak2m-1)

![Mockup](../assets/img/chapter-IV/LadingPageMockup.png)

En este capítulo se desarrolló el mockup, diseñado con tonalidades de azul, con el tipo de letra Montserrat e implementando las imagenes necesarias.

### 4.4.1. Web Application Wireframes
En esta sección se mostrará el desarrollo final de los Wireframes de la Web Application, que es una representacion de baja fidelidad en una escala de grises. 
<b>
[Link](https://www.figma.com/file/qSyCbAqHOXsX1mVh4EX8yy/Open-Source?type=design&node-id=508%3A838&mode=design&t=c0yzJ4yiEgVpak2m-1)

* __Interfaz para nuevos usuarios y antiguos usuarios__

  En estos wireframes se muestra el inicio de sesión y registro que fueron desarrollados con la Tipografía y tamaño establecido en la documentación.


![1](../assets/img/chapter-IV/LoginUsuarioWireframe.png)

![1](../assets/img/chapter-IV/RegistroUsuarioWireframe.png)

<br></br>

* __Interfaz de Personas__

  En esta sección se muestra las páginas de "Home" para el cliente donde se puede ver el progreso, técnicos y se verá algunas reparaciones que se están llevando a cabo o ya finalizaron. La siguiente página "técnicos "mostrara a los técnicos cercanos, donde además podemos filtrarlos y buscar por nombre. En la página "Progreso" se mostrará el estado de la reparación que será representada por un gráfico. La página "Favorita" mostrará los técnicos guardados como favoritos por el usuario y el "Inbox" se podrá ver notificaciones de aceptación de reparación de los técnicos además de brindar al usuario el contacto con el técnico.

![3](../assets/img/chapter-IV/InterfazHomeClienteWireframe.png)
![3](../assets/img/chapter-IV/InterfazTechnicalClienteWireframe.png)
![3](../assets/img/chapter-IV/InterfazProgressClienteWireframe.png)
![3](../assets/img/chapter-IV/InterfazFavoriteClienteWireframe.png)
![3](../assets/img/chapter-IV/InterfazInboxClienteWireframe.png)

<br></br>

* __Pedir una reparación al técnico__

  En esta sección se puede ver la forma que al momento de pedir una reparación a un técnico determinado escogido de la página "técnicos".
  
![3](../assets/img/chapter-IV/InterfazHomeClienteWireframe.png)
![5](../assets/img/chapter-IV/SeleccionTechnicalClienteWireframe.png)
![](../assets/img/chapter-IV/SeleccionarServicioTechnicalClienteWireframe.png)
![5](../assets/img/chapter-IV/CompletarServicioTechnicalClienteWireframe.png)
![](../assets/img/chapter-IV/RetornarHomeClienteWireframe.png)

<br></br>

* __Interfaz de Tecnico__

  En esta sección se muestra las páginas de "Home" que muestra un resumen de tareas, dashboard y peticiones recientes. El "DashBoard" que es exclusivo para los técnicos. La página "petición" que permite mostrar al técnico las peticiones de reparaciones "perfil" que permitirá administrar al técnico su propia información, comprar membresía o cancelarla y el "Task" que permite al técnico visualizar las tareas aceptadas y en proceso.

![2](../assets/img/chapter-IV/InterfazHomeTecnicoWireframe.png)
![2](../assets/img/chapter-IV/InterfazDashboardTecnicoWireframe.png)
![2](../assets/img/chapter-IV/InterfazPetitionTecnicoWireframe.png)
![2](../assets/img/chapter-IV/InterfazProfileTecnicoWireframe.png)
![2](../assets/img/chapter-IV/InterfazTaskTecnicoWireframe.png)

<br></br>

* __Conseguir Menbresia__

  En esta sección se muestra la compra de una membresía mostrando los beneficios de esta, para luego de aceptar mostrara el formulario para rellenar la tarjeta de crédito o débito. Además de mostrar una ventana emergente que muestre la finalización correcta y regrese al inicio.

![11](../assets/img/chapter-IV/SeleccionBeamemberTecnicoWireframe.png)
![11](../assets/img/chapter-IV/SeleccionPaqueteTecnicoWireframe.png)
![11](../assets/img/chapter-IV/RellenarFormulariodeTarjetaWireframe.png)
![11](../assets/img/chapter-IV/RetornarHomeBeamember.png)
![11](../assets/img/chapter-IV/VisualizacionInsigniaTecnicoWireframe.png)

* __Agregar una nueva tarea__

  En esta sección se mostrará la forma de agregar una nueva tarea al apartado "task", en el proceso podrá usar su inventario de componentes previamente establecidos por usted.

![12](../assets/img/chapter-IV/CrearNuevoTaskTecnicoWireframe.png)
![12](../assets/img/chapter-IV/SeleccionInventoyTecnicoWireframe.png)
![12](../assets/img/chapter-IV/IncluirComponentesTecnicoWireframe.png)
![12](../assets/img/chapter-IV/GuardarNuevoTaskTecnicoWireframe.png)
![12](../assets/img/chapter-IV/RetornarHomeTecnicoTask.png)

* __Inventario__

  En esta sección se muestra el menú del inventario donde se podrá agregar componentes para la reparación de los equipos además de poder mostrar los costos a los clientes de una forma más rápida.
  ![14](../assets/img/chapter-IV/CrearNuevoInventoryTecnicoWireFrame.png)
  ![14](../assets/img/chapter-IV/AgregarComponentesTecnicoWireframe.png)
  ![14](../assets/img/chapter-IV/VisualizarInventoryTecnicoWireframe.png)

### 4.4.2. Web Application Wireflow Diagrams
#### Usuarios

* __User Goal:__ Como usuario deseo registrarse dentro de la aplicación web.

![img](../assets/img/chapter-IV/DigramaRegistroUsurio.png)

El usuario comienza su interacción con la aplicación rellenando los siguientes datos para la creación de su cuenta: Nombre completo, email, contraseña, confirme su contraseña y fecha de nacimiento, seleccionando qué es un usuario que desea un servicio.

* __User Goal:__ Como usuario deseo iniciar mi sesión para acceder al contenido de la aplicación web

![img](../assets/img/chapter-IV/DiagramaInicioSesionUsuario.png)

El usuario rellena los datos que le pide el inicio de sesión los cuales son: correo electrónico y su contraseña. De esta manera podrá ingresar a su cuenta.

* __User Goal:__ Como usuario deseo solicitar una cita con el servicio de un técnico

![img](../assets/img/chapter-IV/DiagramaSolicitarServicioUsuario.png)

El usuario se dirige al apartado de "Technical", luego selecciona la opción para solicitar el servicio del técnico, luego rellena los datos que se pide la solicitud, después envía la solicitud y regresa al inicio.

* __User Goal:__  Como usuario deseo ver cuánto tiempo le falta a mi equipo para ser reparado.

![img](../assets/img/chapter-IV/DiagramaVisualizarProgresoUsuario.png)

El usuario se dirige al apartado de "Progress", luego selección el equipo el cual el técnico está reparando y visualiza los detalles y el tiempo que le queda al equipo en ser reparado.

* __User Goal:__  Como usuario deseo comentar y calificar el servicio que me proporcionaron
  ![img](../assets/img/chapter-IV/DiagramaComentarYCalificarUsuario.png)

El usuario se dirige a la opción progress, luego al visualizer que su servicio ha concluido selecciona "Finalizar y comentar", después califica y comenta el servicio, como último paso envía la reseña y retorna a la página de inicio.

* __User Goal:__ Como usuario deseo guardar a mis técnicos favoritos
  ![img](../assets/img/chapter-IV/DiagramaElegirFavoritoUsuario.png)

El usuario se dirige a la opción Technical y elige el técnico que desea enviar a favoritos, luego le da a la "estrella" para poder enviarlo.

* __User Goal:__ Como usuario deseo saber si el técnico acepto mi petición.
  ![img](../assets/img/chapter-IV/DiagramaVerPeticionesUsuario.png)

El usuario se dirige a la opción inbox y visualiza el comentario que le mando el técnico que acepto su cita. Ver los detalles del mismo.

* __User Goal:__ Como usuario deseo buscar a un técnico por su nombre

![img](../assets/img/chapter-IV/DiagramaBuscarTecnicoporNombreUsuario.png)

El usuario se dirige a la opción Technical, sucesivamente selecciona la barra de búsqueda y escribe el nombre de cualquier técnico.

* __User Goal:__ Como usuario deseo buscar a un técnico por un filtro.

![img](../assets/img/chapter-IV/DiagramaBuscarporFiltroUsuario.png)

El usuario se dirige a la opción Technical, sucesivamente selecciona la sección de filtro, filtra a un técnico ya sea por sus estrellas o experiencia.

#### Tecnicos
* __User Goal:__ Como técnico, deseo crear una cuenta para poder usar la aplicación.

![img](../assets/img/chapter-IV/DiagramaRegistroTecnico.png)

En técnico ingresa a rellenar el formulario con los siguientes datos "Nombre", "Ocupación", "Email”, Contraseña" y "Cumpleaños" para poder crear su cuenta y poder usar las herramientas que dispone la aplicación.

* __User Goal:__ Como técnico, deseo poder iniciar sesión en mi cuenta.

![img](../assets/img/chapter-IV/DiagramaInicioSesionTecnico.png)

El técnico está en la página de inicio de sesión donde procede a rellenar con sus datos "email" y "Contraseña" para luego ir a su página de inicio.

* __User Goal:__ Como técnico, deseo completar mi perfil para poder destacar sobre los demás técnicos.

![img](../assets/img/chapter-IV/DiagramaEditarPerfilTecnico.png)

El técnico está en su página de inicio, este quiere configurar su perfil, para eso va a la barra lateral y busca la opción "Perfil" donde procede a rellenar los datos para tener un perfil más relevante en la app.

* __User Goal:__ Como técnico, deseo comprar la membresía de la aplicación.
  ![img](../assets/img/chapter-IV/DiagramaComprarMembresiaTecnico.png)

El técnico está en su página de inicio, este quiere comprar la membresía para esto se va a la barra lateral donde selecciona la opción "Perfil", para luego comprar la membresía poniendo los datos de su tarjeta bancaria para luego esta confirmarse y redirigir al inicio.

* __User Goal:__ Como técnico, deseo generar una nueva tarea acoplándome a los datos y servicios que pide el cliente.
  ![img](../assets/img/chapter-IV/DiagramaGenerarNuevaTarea.png)

El técnico está en su página de inicio, este quiere ver sus tareas, para esto se va a la barra lateral donde selecciona la opción "Task" donde puede administrar las peticiones de reparación que le llegan pudiendo ver detalles.

* __User Goal:__ Como técnico, deseo poder ver los detalles de las tareas del celular que estoy reparando
  ![img](../assets/img/chapter-IV/DiagramaVisualizarTarea.png)

El técnico está en su página de inicio, este quiere ver sus tareas, para esto se va a la barra lateral donde selecciona la opción "Task" donde puedo ver los detalles del equipo que ayudaran en la reparación del equipo.

* __User Goal:__ Como técnico, deseo poder crear un nuevo inventario.
  ![img](../assets/img/chapter-IV/DiagramaCrearNuevoInventario.png)

El técnico está en su página de inicio, este quiere ver sus inventarios, para esto se va a la barra lateral donde selecciona la opción "Dashboard" donde este le dirige al dashboard y le da la opción de empezar agregar componentes en su inventario, para que luego estos se vean en el inicio del dashboard.

* __User Goal:__ Como técnico, deseo poder ver mis ingresos semanales.
  ![img](../assets/img/chapter-IV/DiagramaVisualizarIngresos.png)

El técnico está en su página de inicio, este quiere ver sus ventas semanales, para esto se va a la barra lateral donde selecciona la opción "Dashboard", donde se aprecia una gráfica semanal permitiéndole ver sus ventas
* __User Goal:__ Como técnico, deseo poder ingresar a ver los consejos.
  ![img](../assets/img/chapter-IV/DiagramaVisualizarConsejosTecnico.png)

El técnico está en su página de inicio, este quiere ver sus consejos, para esto se va a la barra lateral donde selecciona la opción "Dashboard", donde este selecciona los consejos para poder ver muchos consejos sobre la aplicación.

* __User Goal:__  Como técnico deseo poder mandar un mensaje comunicándole al cliente cualquier cambio en su equipo

![img](../assets/img/chapter-IV/DiagramaCrearMensajeTecnico.png)

El técnico está en su página de inicio, este quiere enviar un mensaje que ayuden a la comunicación entre el usuario y el, para esto se va a la barra lateral donde selecciona la opción "Inbox" que le permitirá enviar un mensaje automatizado al cliente proporcionándole comunicación entre ellos por otros medios como Whatsapp.

### 4.4.3. Web Application Mock-ups

En esta sección se mostrara el desarrollo final de los Mock-ups de la Web Application, que es una representación de mediana o alta fidelidad teniendo en cuenta los Style Guidelines . [Link](https://www.figma.com/file/qSyCbAqHOXsX1mVh4EX8yy/Open-Source?type=design&node-id=508%3A838&mode=design&t=c0yzJ4yiEgVpak2m-1)

* __Interfaz para nuevos usuarios y antiguos usuarios__

  En estos wireframes se muestra el inicio de sesión y registro que fueron desarrollados con la tipografía y tamaño establecido en la documentación.


![1](../assets/img/chapter-IV/LoginUsuarioMockup.png)

![1](../assets/img/chapter-IV/RegistroUsuarioMockup.png)

<br></br>

* __Interfaz de Personas__

  En esta sección se muestra las páginas de "Home" para el cliente donde se puede ver el progreso, técnicos y se verá algunas reparaciones que se están llevando a cabo o ya finalizaron. La siguiente página "técnicos "mostrara a los técnicos cercanos, donde además podemos filtrarlos y buscar por nombre. En la página "Progreso" se mostrará el estado de la reparación que será representada por un gráfico. La página "Favorita" mostrará los técnicos guardados como favoritos por el usuario y el "Inbox" se podrá ver notificaciones de aceptación de reparación de los técnicos además de brindar al usuario el contacto con el técnico.

![3](../assets/img/chapter-IV/InterfazHomeClienteMockup.png)
![3](../assets/img/chapter-IV/InterfazTechnicalClienteMockup.png)
![3](../assets/img/chapter-IV/InterfazProgressClienteMockup.png)
![3](../assets/img/chapter-IV/InterfazFavoriteClienteMockup.png)
![3](../assets/img/chapter-IV/InterfazInboxClienteMockup.png)

<br></br>

* __Pedir una reparación al técnico__

  En esta sección se puede ver la forma que al momento de pedir una reparación a un técnico determinado escogido de la página "técnicos".

![5](../assets/img/chapter-IV/BuscarTecnicoUsuarioMockup.png)
![5](../assets/img/chapter-IV/SeleccionarTecnicoUsuarioMockup.png)
![5](../assets/img/chapter-IV/SolicitarServicioUsuarioMockup.png)
![5](../assets/img/chapter-IV/CompletarSolicitudUsuarioMockup.png)
![5](../assets/img/chapter-IV/RetornarHomeMockup.png)

<br></br>

* __Interfaz de Tecnico__

  En esta sección se muestra las páginas de "Home" que muestra un resumen de tareas, dashboard y peticiones recientes. El "DashBoard" que es exclusivo para los técnicos. La página "petición" que permite mostrar al técnico las peticiones de reparaciones "perfil" que permite administrar al técnico su propia información, comprar membresía o cancelarla y el "Task" que permite al técnico visualizar las tareas aceptadas y en proceso.

![2](../assets/img/chapter-IV/InterfazHomeTecnicoMockup.png)
![2](../assets/img/chapter-IV/InterfazProfileTecnicoMockup.png)
![2](../assets/img/chapter-IV/InterfazTaskTecnicoMockup.png)
![2](../assets/img/chapter-IV/InterfazDashboardTecnicoMockup.png)
![2](../assets/img/chapter-IV/InterfazHomePetitionMockup.png)

<br></br>

* __Conseguir o Cancelar Menbresia__

  En esta sección se muestra la compra de una membresía mostrando los beneficios de esta, para luego de aceptar mostrara el formulario para rellenar la tarjeta de crédito o débito. Además de mostrar una ventana emergente que muestre la finalización correcta y regrese al inicio.
  ![11](../assets/img/chapter-IV/SeleccionBeamemberTecnicoMockup.png)
  ![11](../assets/img/chapter-IV/SeleccionPaqueteTecnicoMockup.png)
  ![11](../assets/img/chapter-IV/RellenarFormulariodeTarjetaMockup.png)
  ![11](../assets/img/chapter-IV/RetornarProfile.png)
  ![11](../assets/img/chapter-IV/VisualizacionInsigniaTecnicoMockup.png)

* __Agregar una nueva tarea__

  En esta sección se mostrará la forma de agregar una nueva tarea al apartado "task", en el proceso podrá usar su inventario de componentes previamente establecidos por usted.
  ![12](../assets/img/chapter-IV/CrearNuevoTaskTecnicoMockup.png)
  ![12](../assets/img/chapter-IV/RellenarDatosTaskTecnicoMockup.png)
  ![12](../assets/img/chapter-IV/IncluirComponentesTecnicoMockup.png)
  ![12](../assets/img/chapter-IV/GuardarNuevoTaskTecnicoMockup.png)
  ![12](../assets/img/chapter-IV/RetornarHomeTecnicoTaskMockup.png)

* __Inventario__

  En esta sección se muestra el menú del inventario donde se podrá agregar componentes para la reparación de los equipos además de poder mostrar los costos a los clientes de una forma más rápida.
  ![14](../assets/img/chapter-IV/CrearNuevoInventoryTecnicoMockup.png)
  ![14](../assets/img/chapter-IV/VisualizarInventoryTecnicoMockup.png)
  ![14](../assets/img/chapter-IV/AgregarComponentesTecnicoMockup.png)

### 4.4.3. Web Application User Flow Diagram

En este apartado se presenta los user flows diagrams de nuestro mockup, el usuario tendrá que realizar varios flujos.

#### Segmento Objetivo: Pacientes

*__USER GOAL__

Como usuario deseo registrarse dentro de la aplicación web.

![img](../assets/img/chapter-IV/DiagramaFlujoRegistro.png)

*__USER GOAL__

Como usuario deseo iniciar mi sesión para acceder al contenido de la aplicación web

![img](../assets/img/chapter-IV/DiagramaFlujoIniciarSesion.png)

*__USER GOAL__

Como usuario deseo buscar a un técnico por su nombre

![img](../assets/img/chapter-IV/DiagramaFlujoBusquedaNombre.png)

*__USER GOAL__

Como usuario deseo buscar a un técnico por un filtro

![img](../assets/img/chapter-IV/DiagramaFlujoBusquedaFiltro.png)

*__USER GOAL__

Como usuario deseo solicitar una cita con el servicio de un técnico

![img](../assets/img/chapter-IV/DiagramaFlujoSolicitarServicio.png)

*__USER GOAL__

Como usuario deseo ver cuánto tiempo le falta a mi equipo para ser reparado.

![img](../assets/img/chapter-IV/DiagramaFlujoVisualizarProgreso.png)

*__USER GOAL__

Como usuario deseo comentar y calificar el servicio que me proporcionaron

![img](../assets/img/chapter-IV/DiagramaFlujoCalificarYComentar.png)

*__USER GOAL__

Como usuario deseo ver el comentario del técnico

![img](../assets/img/chapter-IV/DiagramaFlujoVisualizarInbox.png)

## 4.5. Web Applications Prototyping
En esta sección se mostrará el prototipo de la aplicación web desarrollado en figma siguiendo los estilos establecidos en los anteriores puntos.
[Link: Visualizar Prototipo en Figma](https://www.figma.com/proto/9U0r61ZoDHjQf7Ck7zotUL/Prototype-TecHelp-APP?type=design&node-id=1-3234&t=HruT40GoBdMnazGq-1&scaling=min-zoom&page-id=0%3A1&starting-point-node-id=1%3A3234&show-proto-sidebar=1&mode=design )

![captura](../assets/img/chapter-IV/CapturaDelPrototipo.png)

## 4.6 Domain-Driven Software Architecture

Los diagramas de arquitectura de software nos ayudan a plantear el sistema de nuestro software, basándonos en el enfoque de desarrollo de Domain Driven Design.
### 4.6.1. Software Architecture Context Diagram.

A continuación, presentamos el diagrama de contexto de nuestra arquitectura, el cual muestra cómo encaja en el mundo con los usuarios que lo usa y con los sistemas de software externo que interactúa.

![imagen](../assets/img/chapter-IV/structurizr-85868-SystemContext-001.png)

### 4.6.2. Software Architecture Container Diagrams.

En esta sección indicamos los contenedores de nuestro diagrama de contexto. Donde se muestran los elementos tecnológicos de alto nivel.
![imagen](../assets/img/chapter-IV/structurizr-86231-Container-001.png)

### 4.6.3. Software Architecture Components Diagrams.

En este apartado se presenta el diagrama de componentes, donde se detallan los componentes que pertenecen a cada uno de nuestros contenedores relacionados a los bounded context de nuestro proyecto.

#### Reparación Component Diagram
![imagen](../assets/img/chapter-IV/structurizr-85868-Component-001.png)
#### Monitoreo Component Diagram
![imagen](../assets/img/chapter-IV/structurizr-85868-Component-002.png)
#### Seguridad Component Diagram
![imagen](../assets/img/chapter-IV/structurizr-85868-Component-003.png)
#### Calificación Component Diagram
![imagen](../assets/img/chapter-IV/structurizr-85868-Component-004.png)

## 4.7 Software Object-Oriented Design
### 4.7.1. Class Diagrams.
Para el desarrollo del diagrama de clases se usó diferentes patrones entre creacionales (Factory y Builder) y de comportamiento (State). Además del uso de lucip.app

![imagen](../assets/img/chapter-IV/DiagramadeClases.png)
<center>

[Link de lucid del diagrama de clases](https://lucid.app/lucidchart/667477fb-235b-4eb3-9565-e1784ea10efa/edit?viewport_loc=-1946%2C-1960%2C5713%2C2716%2C0_0&invitationId=inv_a6dd4c01-7a29-4da7-8688-209bb0e06f14)

</center>

### 4.7.2. Class Dictionary
En esta sección se mostrará el diccionario de las clases usado para el desarrollo de nuestra solución.

* __User:__ Clase padre de las clase Person y Technical. Contiene atributos básicos y métodos que heredan sus hijos.
* __Person:__ Clase hija de la clase User que puede buscar técnicos, realizar una reseña, pedir una reparación y añadir a favoritos a los técnicos
* __Technical:__ Clase hija de la clase User, que tiene de atributos a Dashboard y city propios de este mismo
* __Factory:__ Clase que permite la creación de un diferente tipo de usuario ya sea Person y Technical

* __CellPhone:__ Clase que es parte de Person, pues una Person tiene varios celulares

* __State:__ Clase que permite cambiar el estado de la reparación

* __Received:__ Clase hija de State que define el estado de Recibido.

* __SRepair:__ Clase hija de State que define el estado de reparación.

* __Delivered:__ Clase hija de State que define el estado de Entregado.

* __Finish:__ Clase hija de State que define el estado de finalizado.

* __BuilderRepair:__ Clase hija de Builder que especifica la construcción de una reparacion.

* __Builder:__ Clase padre de BuildeRepair que tiene métodos virtuales que permite cambiarlos en la clase hija. Esto es esencial para la construcción de diferentes tipos de reparaciones

* __DashBoar:__ Clase que pertenece al técnico, donde se puede realizar la petición de mostrar ingresos, visitas y mayor servicio realizado (por mes ,año y día). Además de permitirnos acceder al inventario de componentes asociado al técnico.

* __Inventory:__ Clase que permite almacenar objetos de la clase componente, modificarlos, añadirlos, eliminar, buscar por id o por nombre.

* __Component:__ Clase que es parte del inventario. Dado que un componente esta almacenado en un inventario.

* __ListRepair:__ Clase que guarda las reparaciones realizadas por el usuario para luego para luego el técnico lo pueda ver.

## 4.8. Database Design.
### 4.8.1. Database Diagram

En este punto se presentará nuestro Physical data modelo desarrollado en vertabelo, con sus respectivas relaciones y entidades.

![Diagrama Base de datos](../assets/img/chapter-IV/DataBaseTecHelp.png)

[Link para visualizar el diagrama de base de datos](https://my.vertabelo.com/doc/fO4P0j8AMrEflYiQRGERtsJAMCOcbVjB)


