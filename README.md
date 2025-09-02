# **Propósito de Aprendizaje 1: Comprender los fundamentos del desarrollo de aplicaciones web.**
<img width="259" height="173" alt="image" src="https://github.com/user-attachments/assets/3700991d-4548-4065-8909-d5147df46e2e" />

# 1.-**Introducción al desarrollo web**
La historia del desarrollo web comienza con Tim Berners-Lee en 1989, quien creó la World Wide Web para compartir información científica, desarrollando HTML, HTTP y URL, y publicando el primer sitio web en 1991. La evolución de la web abarca desde la Web 1.0 (estática y basada en texto) hacia la Web 2.0 (interactiva y social), la Web 3.0 (con IA y personalización) y la futura Web 4.0 (integrada con la tecnología). Hitos clave incluyen el uso de tablas para diseño en 1992, la introducción de CSS y JavaScript a fines de los 90, y el auge del diseño web adaptable en la década de 2010.
Las aplicaciones web se clasifican en: **estáticas** (contenido fijo), **dinámicas** (contenido generado por el servidor y personalizable), **Aplicaciones Web de Página Única** (SPA) (carga un solo HTML y actualiza contenido sin recargar la página) y **Aplicaciones Web Progresivas** (PWA) (combinan lo mejor de las apps web y nativas, con funciones como acceso sin conexión y notificaciones push). 

# 2.-**Arquitectura de aplicaciones web**
- La arquitectura cliente-servidor es un modelo informático donde un programa cliente solicita servicios o recursos a un programa servidor, que los provee. El cliente interactúa con el usuario, mientras que el servidor gestiona y centraliza los recursos y el procesamiento de datos. Ejemplos comunes son el uso de un navegador web (cliente) para acceder a sitios web (servidor) o aplicaciones como Netflix.
- La arquitectura de tres capas es un patrón de diseño de software que organiza una aplicación en tres capas lógicas e independientes: **Presentación**, que es la interfaz de usuario y maneja la interacción con el usuario; **Lógica** (o de Negocio), que contiene las reglas de negocio y el procesamiento de datos; y **Datos** (o de Acceso a Datos), responsable de almacenar y recuperar información de las bases de datos. Esta separación mejora la mantenibilidad, escalabilidad y flexibilidad de la aplicación al distribuir las responsabilidades. 
- REST (Representational State Transfer) es un estilo arquitectónico para diseñar aplicaciones web y sus API, mientras que el diseño API-first es una estrategia de desarrollo que prioriza el diseño de la API antes de escribir código, buscando la reutilización y la creación de experiencias intuitivas para los usuarios de la API. El diseño API-first utiliza especificaciones como OpenAPI para definir y documentar la API, lo que permite la colaboración temprana y la creación de productos mejores y más eficientes. 

# 3.-**Lenguajes y tecnologías fundamentales**
- HTML, siglas de HyperText Markup Language (Lenguaje de Marcado de Hipertexto), es el lenguaje fundamental para crear páginas web. Su propósito es estructurar y dar formato al contenido de un sitio web, definiendo elementos como párrafos, imágenes, enlaces, videos y tablas, para que un navegador web pueda mostrarlos correctamente.
- CSS, que significa Cascading Style Sheets (Hojas de Estilo en Cascada), es un lenguaje de estilos que se utiliza para describir la presentación y el aspecto visual de documentos escritos en lenguajes de marcado como HTML.
- JavaScript (JS) es un lenguaje de programación versátil usado principalmente para dar interactividad y contenido dinámico a las páginas web, aunque también se utiliza en el lado del servidor con Node.js.
- PHP es un lenguaje de programación de código abierto para el desarrollo web del lado del servidor que permite crear sitios y aplicaciones web dinámicas e interactivas. Se ejecuta en el servidor, genera contenido dinámico, interactúa con bases de datos y puede integrarse fácilmente con HTML, CSS y JavaScript.
- MySQL es un sistema de gestión de bases de datos relacionales (RDBMS) de código abierto que almacena y gestiona datos en tablas organizadas en filas y columnas. Se utiliza ampliamente en aplicaciones web, como sitios de comercio electrónico y redes sociales, gracias a su popularidad, fiabilidad, rendimiento y facilidad de uso.

# **4.-Control de versiones**
- Git es un sistema de control de versiones, una herramienta que permite rastrear cambios y gestionar el historial de un proyecto, funcionando de manera local en tu computadora. Por otro lado, GitHub es una plataforma web que utiliza Git para ofrecer un servicio de alojamiento de repositorios en la nube, facilitando la colaboración en equipo, el trabajo remoto y proporcionando herramientas de gestión de proyectos, como la gestión de incidencias y la revisión de código. 
- Un flujo de trabajo con ramas en control de versiones como Git, como el que se usa en GitHub, permite el desarrollo colaborativo seguro al aislar nuevas funcionalidades en ramas (branches) separadas de la rama principal (main). Para integrar estos cambios, se crea una solicitud de fusión (pull request), que permite la revisión de código y la discusión antes de fusionar (merge) los cambios en la rama principal, manteniendo un historial limpio y organizado del proyecto. 

# **Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web**
<img width="271" height="179" alt="image" src="https://github.com/user-attachments/assets/381d0d8d-76a7-4cdc-abd6-a51075bec823" />

# **1.-Diseño e implementación del frontend**
- La maquetación se refiere al proceso de dar estructura y forma a un diseño, utilizando wireframes para el esqueleto funcional y mockups para la representación visual detallada del aspecto final. Los wireframes son bocetos de baja fidelidad que muestran la estructura y la distribución de elementos, priorizando el flujo de usuarios, mientras que los mockups son representaciones estáticas y detalladas del diseño visual, incluyendo colores y tipografías, que simulan el aspecto del producto final. 
- Una API (interfaz de programación de aplicaciones) es un conjunto de reglas y definiciones que permite que dos aplicaciones de software diferentes se comuniquen entre sí, actuando como un puente para el intercambio de datos y servicios.
# **2.-Diseño e implementación del backend**
- Un servidor es una computadora o sistema informático potente diseñado para proporcionar y administrar recursos, datos o servicios a otros dispositivos (clientes) dentro de una red, como Internet.
- El manejo de peticiones y respuestas HTTP se basa en un modelo cliente-servidor donde el cliente (por ejemplo, un navegador web) envía una petición a un servidor web solicitando un recurso o acción. El servidor procesa esta solicitud y responde con una respuesta HTTP, que incluye un código de estado para indicar el resultado (éxito, error o redirección), cabeceras para información adicional y, opcionalmente, un cuerpo con los datos solicitados o un mensaje de error. 
- Para conectarse a bases de datos (MySQL, PostgreSQL, MongoDB), se usan detalles de conexión como el host, puerto, nombre de la base de datos, usuario y contraseña, variando la sintaxis y los requisitos según el tipo de base de datos y la herramienta de gestión o el cliente de línea de comandos utilizado. 
# **3.-Bases de datos**
- El modelado de datos es el proceso de crear una representación visual de los datos y sus relaciones para estructurar, almacenar y acceder a la información de manera eficiente.
- Un ORM (Object-Relational Mapping o Mapeo Objeto-Relacional) es una herramienta de software que traduce los datos entre el modelo de objetos de un lenguaje de programación y las tablas de una base de datos relacional, permitiendo a los desarrolladores interactuar con la base de datos usando sus propios objetos en lugar de escribir directamente consultas SQL.
- El CRUD (Crear, Leer, Actualizar, Eliminar) es un conjunto de operaciones fundamentales en el backend de una aplicación para gestionar datos persistentes, usualmente a través de una API que interactúa con una base de datos.

# **4.-Seguridad básica en aplicaciones web**
- La validación de formularios es el proceso de verificar que los datos introducidos por un usuario en un formulario sean precisos, completos y tengan el formato correcto antes de ser enviados, utilizando reglas para asegurar la integridad de la información.
- La autenticación verifica que un usuario sea quien dice ser, mientras que la autorización determina qué acciones o recursos ese usuario puede acceder. 

# **Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional**
<img width="290" height="161" alt="image" src="https://github.com/user-attachments/assets/b80cfe9d-4cee-421e-808d-000c6ae88a05" />

# **1. -Integración de frontend y backend**
- La interfaz de usuario (UI) de frontend es la parte de una aplicación web o sitio web con la que los usuarios interactúan directamente, incluyendo elementos visuales como botones, menús, imágenes y texto, así como su diseño y comportamiento.
- El manejo de API implica hacer solicitudes (GET, POST, etc.) a un servidor a través de Internet para obtener o enviar datos entre diferentes aplicaciones, usando un conjunto de reglas definidas.
- El proceso de solicitud y respuesta de backend comienza cuando un cliente (navegador o aplicación) envía una solicitud HTTP al servidor. El backend, compuesto por el servidor, la aplicación y la base de datos, procesa esta solicitud validando los datos, ejecutando la lógica de negocio y consultando la base de datos si es necesario. Finalmente, el backend envía una respuesta, a menudo en formato JSON, de vuelta al cliente, que se encarga de presentarla al usuario. 

# **2.- Almacenamiento en Servidor**
- Los tipos de servidores varían según su función y la forma en que se alojan o utilizan, incluyendo los servidores web para sitios web, servidores de correo para email, servidores de bases de datos para almacenar datos, servidores proxy como intermediarios, y los servidores virtuales y en la nube que ofrecen flexibilidad y escalabilidad.  
- Un servidor es una computadora que provee recursos, mientras que el hosting es el servicio que alquila espacio en un servidor para almacenar archivos de un sitio web y hacerlo accesible en Internet. 
- Los principales proveedores de servicios de almacenamiento, como Google Drive, Microsoft OneDrive, Dropbox, iCloud y MEGA, ofrecen soluciones de almacenamiento en la nube para guardar y acceder a archivos desde cualquier lugar.

# **3.-Optimización y rendimiento**
- La optimización de recursos, especialmente de imágenes y scripts, consiste en reducir el tamaño de estos archivos para que una página web cargue más rápido y ofrezca una mejor experiencia al usuario.
- El despliegue de aplicaciones web es el proceso de transferir una aplicación desde un entorno de desarrollo a un entorno de producción, volviéndola accesible para los usuarios finales.
- CI/CD (Integración Continua y Despliegue Continuo) es un método de desarrollo de software que automatiza las etapas de compilación, prueba y entrega de código, permitiendo lanzar actualizaciones de manera rápida, frecuente y fiable. La Integración Continua (CI) implica fusionar los cambios de código en un repositorio compartido varias veces al día y ejecutar pruebas automatizadas para validar cada cambio.
- La documentación de proyectos es la colección de todos los documentos y materiales escritos que describen los objetivos, alcance, presupuesto, riesgos y metodologías de un proyecto.
