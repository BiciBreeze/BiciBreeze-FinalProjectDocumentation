# Capítulo IV: Product Design

## 4.1. Style Guidelines

En esta seccion definiremos los estilos de diseño frontend que  serán la base para dar forma a nuestro producto, utilizando patrones que consideren los aspectos de arquitectura de la información y accesibilidad necesarios para la implementación exitosa de UrProvider tanto en una Landing Page como en una Aplicación Web.

## 4.1.1. General Style Guidelines

- __Branding__: El branding del logo de nuestra plataforma “BiciBreeze” es una combinación de elementos que transmiten una imagen sólida y confiable. Nos enfocamos en la confianza de nuestro clientes al momento de tomar un servicio prestado , lo que mas resalta es la rueda que nos indica que es un startup relacionada al transporte para empezar con bicicletas para un posible expansion de marca . El nombre “BiciBreeze” se presenta en una tipografía elegante y profesional, mientras que la paleta de colores crea un contraste visual claro y transmite una sensación de miminalismo  y profesionalismo. En resumen, este logo tiene un enfoque clásico y profesional, y podría ser un elemento distintivo en nuestro sitio web.

<div style="text-align: center;">
 <img src="https://i.postimg.cc/hGLJ0Kmb/Untitled-logo-1-free-file-1.jpg" alt="Logo" style="width: 50%; height: auto;">
</div>

- __Typography__: Al seleccionar la tipografía para nuestro proyecto, hemos optado por utilizar Open Sans siguiendo las pautas de estilo general. Ya que ofrece una combinación única de legibilidad, versatilidad y modernidad que se alinea perfectamente con la identidad visual y los objetivos de MedicDefense. Su diseño limpio y contemporáneo proporciona una excelente lectura en una amplia gama de dispositivos, lo que garantiza una experiencia de usuario óptima para nuestros clientes, que incluyen tanto a profesionales médicos como a estudiantes de medicina. Además, la variedad de pesos y estilos disponibles nos permite crear una jerarquía visual clara y coherente en nuestro contenido, facilitando la navegación y la comprensión de la información.

<div style="text-align: center;">
 <img src="https://i.postimg.cc/90MrVTnJ/Fonts.png" alt="topography" style="width: 100%; height: auto;">
</div>

- __Colors__: Hemos escogido una paleta basada en colores suaves y elegantes, algo frios para dar sensacion de premiun . De tal modo, estos generan un ambiente profesional y acogedor para el usuario final.

Los tonos más claros pueden ser utilizados para fondos o elementos de diseño amplios, mientras que los colores más oscuros serán para textos o detalles más específicos asegurando legibilidad y contraste entre ellos.

De tal modo, se presentan nuestros 4 colores principales:


1.  Blanco (#FFFFFF)

__Descripción:__
El color blanco es el color más claro del espectro y está asociado con pureza, limpieza y simplicidad. A menudo se utiliza para representar la paz y la neutralidad, y es común en espacios que buscan una apariencia fresca y clara.

```css
<span style="color:#FFFFFF; background-color:#000000;">Este es un texto en color blanco.</span>
``` 

2.  Negro (#252523)

__Descripción:__
El color negro es un color oscuro que representa la elegancia, el misterio y la sofisticación. Es frecuentemente utilizado para dar un toque de seriedad y formalidad, y también para el contraste con colores más brillantes.

```css
<span style="color:#252523">Este es un texto en color negro.</span>
``` 



3.  Gris Claro (#B4C1C7)

__Descripción:__
El color gris claro es un tono suave y neutro que se asocia con la calma, la estabilidad y la sofisticación. A menudo se usa en diseño para crear un fondo elegante y discreto, o para complementar otros colores.

```css
<span style="color:#B4C1C7">Este es un texto en gris claro.</span>
``` 


4. Azul Claro (#72B9EA)

__Descripción:__
El color azul claro es un tono fresco y relajante asociado con la serenidad, la confianza y la creatividad. A menudo se utiliza en diseños que buscan transmitir una sensación de calma y apertura.

```css
<span style="color:#72B9EA">Este es un texto en azul claro.</span>
``` 

<div style="text-align: center;">
 <img src="https://i.postimg.cc/9fgfbzM9/Adobe-Color-colors.jpg" alt="colors" style="width: 80%; height: auto;">
</div>

## 4.1.2. Web Style Guidelines

En nuestra guía de estilo web, los colores seleccionados juegan un papel esencial en la creación de una experiencia de usuario coherente y efectiva. El blanco se utiliza predominantemente para los fondos y elementos de diseño, promoviendo una sensación de limpieza y claridad, y asegurando que el contenido sea visualmente accesible. El negro, con su elegancia y sofisticación, se emplea en textos principales y detalles clave, ofreciendo un fuerte contraste que facilita la lectura y resalta la información importante. El gris claro, con su tono neutro y suave, se usa para fondos y textos secundarios, aportando calma y estabilidad, y creando un equilibrio visual que mejora la fluidez de la experiencia de lectura. El azul claro, asociado con serenidad y creatividad, se aplica a elementos destacados y llamados a la acción, atrayendo la atención del usuario y guiando la interacción hacia acciones clave. Cada color ha sido elegido para contribuir a una interfaz visualmente atractiva y funcional, centrada en mejorar la navegación y la comunicación con el usuario.

# 4.2. Information Architecture

## 4.2.1. Organization Systems

La organización de BiciBreeze se presenta a través de un diagrama que detalla la estructura de navegación y funcionalidad de la aplicación. Comienza en la Página de Aterrizaje, desde la cual los usuarios pueden acceder a la opción de Iniciar Sesión o Registrarse, con una opción adicional para Recuperar Contraseña. Una vez que los usuarios inician sesión, son dirigidos a la página Inicio (Home), que actúa como el núcleo del sistema, desde donde se ramifican múltiples secciones principales: Perfil, Bicicletas, Barra de Navegación (Navbar), Configuración (Settings), Alquiler (Rent) y Pago (Payment). Cada una de estas secciones incluye subfuncionalidades; por ejemplo, dentro del perfil, el usuario puede editar su información, y dentro de la configuración, puede modificar sus preferencias o cerrar sesión. La sección de bicicletas permite ver el estado y los elementos disponibles, mientras que la sección de pago ofrece diferentes tipos de transacciones, como efectivo, tarjetas de crédito y billeteras virtuales. El sistema es intuitivo y está diseñado para guiar al usuario a través de diversas opciones relacionadas con el alquiler de bicicletas, configuración de perfil, y gestión de pagos de una manera organizada y accesible.

<div style="text-align: center;">
 <img src="https://i.postimg.cc/gjXL88Hr/Bici-Breeze-Organization-Systems-1.png" alt="O-S" style="width: 100%; height: auto;">
</div>

Link : https://www.figma.com/board/wkDJMnrYZRK1yRuETAcpAW/BiciBreeze---Organization-Systems?node-id=0-1&t=CZPkzLf8DCWgiMKp-1

## 4.2.2. Labeling Systems
__Landing Page__: Etiqueta para la página de inicio donde los usuarios pueden seleccionar entre iniciar sesión, registrarse o recuperar una contraseña.

__Login:__ Etiqueta para la función que permite a los usuarios ingresar a la aplicación.

__Home:__ Etiqueta para la página principal que actúa como el centro de navegación de la aplicación una vez que el usuario ha iniciado sesión.

__Profile:__ Incluye etiquetas adicionales como:

__Edit User:__ Para editar la información del usuario.
Config: Para configuraciones relacionadas con el perfil del usuario.
User: Para la información del usuario organizada por país y ciudad.
Bikes: Contiene las etiquetas:

__Items:__ Para los artículos disponibles.
State: Para el estado de las bicicletas.
Navbar: Etiqueta para la barra de navegación, que incluye opciones como:

__Rent:__ Para alquilar bicicletas.
Support: Para soporte al usuario.
Payment: Para opciones de pago.
Config: Para configuraciones generales.
Settings: Incluye etiquetas como:

__Edit Config:__ Para editar configuraciones.
Sign Out: Para cerrar sesión.
Rent: Etiqueta para la función de alquiler, que incluye:

__Time:__ Para gestionar el tiempo de alquiler, con opciones de fecha.
Expired: Para indicar cuando un alquiler ha expirado.
Payment: Etiqueta para la gestión de pagos, con opciones de:

__Type:__ Para seleccionar el tipo de pago, como efectivo, tarjetas de débito/crédito o billetera virtual.
Subscription: Para gestionar suscripciones.

### 4.2.3. SEO Tags and Meta

Las etiquetas son representativas del contenido de nuestro proyecto, incluyendo tanto el Landing Page como el Sitio Web. Están diseñadas para potenciar la visibilidad de nuestro proyecto en los motores de búsqueda más importantes, lo que facilitará que los usuarios encuentren fácilmente nuestra plataforma de BiciBreeze.

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <!-- Meta Tags -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="BiciBreeze, la mejor opción de alquiler de bicicletas para universitarios. Alquila tu bici de manera rápida y económica con nuestro servicio exclusivo para estudiantes.">
    <meta name="keywords" content="alquiler de bicicletas, bicicletas para universitarios, bicis para estudiantes, alquiler de bicis, transporte universitario, BiciBreeze, bicis económicas">
    <meta name="author" content="BiciBreeze">
    
    <!-- Open Graph Meta Tags -->
    <meta property="og:title" content="BiciBreeze | Alquiler de Bicicletas para Universitarios">
    <meta property="og:description" content="Descubre BiciBreeze, la plataforma ideal para alquilar bicicletas, diseñada especialmente para estudiantes universitarios. ¡Ahorra dinero y viaja de manera sostenible!">
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://www.bicibreeze.com">
    <meta property="og:image" content="https://www.bicibreeze.com/images/landing-page.jpg">
    
    <!-- Twitter Card Meta Tags -->
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="BiciBreeze | Alquiler de Bicicletas para Universitarios">
    <meta name="twitter:description" content="Alquila una bicicleta de manera rápida y económica con BiciBreeze, el servicio exclusivo para estudiantes universitarios.">
    <meta name="twitter:image" content="https://www.bicibreeze.com/images/landing-page.jpg">
    
    <!-- Title Tag -->
    <title>BiciBreeze | Alquiler de Bicicletas para Universitarios</title>

<body>
    <!-- Codigo de la landing...... -->

</body>
</html>
```

##  4.2.4. Searching Systems

__Ubicación:__ Se encuentra de manera prominente en la página principal para que los usuarios puedan buscar bicicletas, estaciones cercanas, o cualquier otra información relacionada con facilidad.

__Funcionalidad:__ Permite la búsqueda por palabras clave, como “bicicletas eléctricas en Campus 1” o “estaciones cerca de mí”.
Filtros de Búsqueda:

__Ubicación:__ Filtrar por ciudad, campus universitario, o áreas específicas.

__Disponibilidad:__ Muestra bicicletas disponibles en tiempo real.
Tipo de Bicicleta: Filtrar según el tipo de bicicleta, como estándar, eléctrica, etc.

__Rango de Precios:__ Permite al usuario seleccionar un rango de precios que se ajuste a su presupuesto.

__Duración del Alquiler:__ Permite seleccionar la duración del alquiler, ya sea por día, semana, o mes.

__Presentación:__ Los resultados se muestran en una lista o un mapa interactivo, proporcionando detalles como disponibilidad, ubicación exacta, y precios.

__Ordenamiento:__ Los resultados pueden ordenarse por cercanía, precio, o popularidad.
Sugerencias de Búsqueda:

## 4.2.5. Navigation Systems

En la plataforma de BiciBreeze, los usuarios pueden navegar de manera fluida a través de un menú de navegación principal ubicado en la parte superior de cada página.

<div style="text-align: center;">
 <img src="https://i.postimg.cc/x1RyPrzm/Captur1e21a.png" alt="N-S" style="width: 100%; height: auto;">
</div>

## 4.3. Landing Page UI Design
 En esta seccion Diseñaremos con los fundamentos obtenidos en el UX la landing Page y el Website que seria toda la parte visible por parte del cliente.

 ### 4.3.1. Landing Page Wireframe

<div style="text-align: center;">
 <img src="https://i.postimg.cc/vH4pjzzD/Bici-Breeze-Landing-Wireframe.png" alt="N-S" style="width: 100%; height: auto;">
</div>

Link para una mejor visualizacion: https://www.figma.com/board/XDFNTPooV7cVGfn8XCMCUi/BiciBreeze-Landing-Wireframe?node-id=0-1&t=eBl4gROdPEGX94Gr-1

 ### 4.3.2. Landing Page Mock-up

 <div style="text-align: center;">
 <img src="https://i.postimg.cc/gJ0Mhztr/l1.png" alt="N-S" style="width: 100%; height: auto;">
</div> 

<div style="text-align: center;">
 <img src="https://i.postimg.cc/pV3HP4yK/l2.png" alt="N-S" style="width: 100%; height: auto;">
</div> 

<div style="text-align: center;">
 <img src="https://i.postimg.cc/28vfyGBM/l3.png" alt="N-S" style="width: 100%; height: auto;">
</div> 

<div style="text-align: center;">
 <img src="https://i.postimg.cc/gcCfChBD/l4.png" alt="N-S" style="width: 100%; height: auto;">
</div> 


Link del Figma: https://www.figma.com/design/dgS00phyaRs0jgU5GPVZUx/Landing-Page?node-id=0-1&t=qjbIEII7v76RjMSe-1


## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.

<div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2FBiciBreeze%20(1)-1.png?alt=media&token=5644e9c2-9bd4-4427-bf79-c45344705d75" alt="w-w" style="width: 100%; height: auto;">
</div> 

<div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2FBiciBreeze%20(1)-2.png?alt=media&token=c2493ccf-1aff-4fc1-b201-368a574effdf" alt="w-w" style="width: 100%; height: auto;">
</div> 

<div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2FBiciBreeze%20(1)-3.png?alt=media&token=a1b3aa5e-c4ed-41fa-9070-41001c4f1e09" alt="w-w" style="width: 100%; height: auto;">
</div> 

<div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2FBiciBreeze%20(1)-4.png?alt=media&token=2b03826b-bfcb-47c3-9d4c-a443ff6922be" alt="w-w" style="width: 100%; height: auto;">
</div> 

<div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2FBiciBreeze%20(1)-6.png?alt=media&token=02144bbd-ab80-406f-8525-f5c1c0ca9dcb" alt="w-w" style="width: 100%; height: auto;">
</div> 

<div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2FBiciBreeze%20(1)-7.png?alt=media&token=3fc098b0-592e-4b60-bfbf-566c250c013b" alt="w-w" style="width: 100%; height: auto;">
</div> 


### 4.4.2. Web Applications Wireflow Diagrams.

<div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2FBicycle%20Rental%20Website%20Flow%20Diagram.png?alt=media&token=ab6a4cb1-0426-47ed-ac08-ca46247de8ee" alt="W-D" style="width: 100%; height: auto;">
</div> 

### 4.4.2. Web Applications Mock-ups.

<div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2FBiciBreeze_page-0001.jpg?alt=media&token=b32040e1-6820-4a4c-ad57-20fd64180858" alt="W-D" style="width: 100%; height: auto;">
</div> 

<div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2FBiciBreeze_page-0002.jpg?alt=media&token=41c41a7d-5d31-4929-8438-9a9169c8bfdb" alt="W-D" style="width: 100%; height: auto;">
</div> 

<div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2FBiciBreeze_page-0003.jpg?alt=media&token=62b32e44-ba65-4bff-b8a8-655910f02ca9" alt="W-D" style="width: 100%; height: auto;">
</div> 

<div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2FBiciBreeze_page-0004.jpg?alt=media&token=4ae7c393-4f2f-4035-a560-1786a9ba754b" alt="W-D" style="width: 100%; height: auto;">
</div> 

<div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2FBiciBreeze_page-0005.jpg?alt=media&token=a46043fa-ee3a-4a6c-a005-9618b17f5f5d" alt="W-D" style="width: 100%; height: auto;">
</div> 

<div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2FBiciBreeze_page-0006.jpg?alt=media&token=5c884a10-eaf8-47c2-ab08-56fc13229ad0" alt="W-D" style="width: 100%; height: auto;">
</div> 

link del figma: https://www.figma.com/design/JjHab3CxGK7SuZxPxuMcvf/BiciBreeze?node-id=0-1&t=wXsOiHwXeh4QXj6x-1 

### 4.4.3. Web Applications User Flow Diagrams.

<div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2Fuserflowbiccibreeze.png?alt=media&token=ec28cba3-8b47-4306-aa09-6b6fb79582ac" alt="pr" style="width: 100%; height: auto;">
</div> 


## 4.5. Web Applications Prototyping

<div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2F821-1x-shots-so.png?alt=media&token=2cbf53f4-cf80-4474-90dd-4b245b2368ce" alt="pr" style="width: 100%; height: auto;">
</div> 


<div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2F88_1x_shots_so.png?alt=media&token=a53e9234-5e0b-4b8b-b9b7-8e25df87b7a1" alt="pr" style="width: 100%; height: auto;">
</div> 

## 4.6 Domain Driven Software Architecture.

Los diagramas de arquitectura de software nos ayudan a plantear el sistema de nuestro software, basándonos en el enfoque de desarrollo de Domain Driven Design.

#### 4.6.1. Software Architecture Context Diagram
Este es el diagrama de Contexto de nuestro sistema:

 <div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2Fc4%20model%2Fstructurizr-SystemContext-001.png?alt=media&token=d71c4b9a-a4d0-4dcb-8962-a1ec6f5f24df" alt="pr" style="width: 100%; height: auto;">
</div> 

#### 4.6.1. Software Architecture Container Diagram
Este es el diagrama de Contenedores de nuestro sistema:

 <div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2Fc4%20model%2Fstructurizr-Container-001.png?alt=media&token=4425b3bf-880b-438b-84a1-15bb677fa35c" alt="pr" style="width: 100%; height: auto;">
</div> 

#### 4.6.1. Software Architecture Components Diagram
Esto son los diagramas de componentes de nuestro sistema:

 <div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2Fc4%20model%2Fstructurizr-ComponentsUserProfile.png?alt=media&token=86a560b1-40d3-4d1e-b63e-f051f411a2c2" alt="pr" style="width: 100%; height: auto;">
</div> 

 <div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2Fc4%20model%2Fstructurizr-ComponentsSubscription.png?alt=media&token=cc227841-4062-486a-ab08-268e255e5997" alt="pr" style="width: 100%; height: auto;">
</div> 

 <div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2Fc4%20model%2Fstructurizr-ComponentsRegistration.png?alt=media&token=a3f5de65-281d-4b16-af4f-7d965212973f" alt="pr" style="width: 100%; height: auto;">
</div> 

 <div style="text-align: center;">
 <img src="https://firebasestorage.googleapis.com/v0/b/bicibreeze.appspot.com/o/imagenes%20bicibreeze%2Fc4%20model%2Fstructurizr-ComponentsPayment.png?alt=media&token=8a08dcd5-9081-4d6c-b7be-c1f2d90cfdce" alt="pr" style="width: 100%; height: auto;">
</div> 
