# SesionPDF
Nombre del Proyecto: Sistema de Gestión de Solicitudes con Validación de Sesión y Control de Roles

Objetivo:
Desarrollar un sistema web para la gestión de solicitudes que implementa validación de inicio de sesión mediante cookies y control de acceso basado en roles de usuario.
El sistema permitirá la captura, visualización y descarga de solicitudes en formato PDF, garantizando que los usuarios solo accedan a las funciones y datos que les corresponden según su rol.

Funcionalidades:

Validación de Inicio de Sesión:

Implementación de un sistema de autenticación que utiliza cookies para validar la sesión de los usuarios.
Almacenamiento seguro de credenciales y manejo de sesiones activas.
Control de Acceso Basado en Roles:

Asignación de roles específicos a los usuarios (director, capturista, administrador.).
Las vistas y funcionalidades disponibles estarán determinadas por el rol asignado al usuario.
Restricciones específicas para cada rol:
Director: Acceso a las solicitudes que pertenecen a su dirección específica. Posibilidad de aprobar, rechazar o ver detalles de las solicitudes.
Capturista: Acceso limitado exclusivamente a la captura de solicitudes de requisiciones. No tiene acceso a otras funcionalidades del sistema.
Gestión de Solicitudes:

Captura de solicitudes de requisiciones por parte de los capturistas.
Visualización de solicitudes por parte de los directores según la dirección a la que pertenezcan.
Historial y seguimiento de solicitudes por estado (pendiente, aprobada, rechazada).

Generación y Descarga de Informes:

Opción para descargar la información de las solicitudes en formato PDF.
Generación de informes detallados con los datos de las solicitudes para facilitar la documentación y el análisis.

Beneficios:

Seguridad: Protección de datos sensibles mediante autenticación segura y control de acceso basado en roles.
Eficiencia: Simplificación del proceso de captura y gestión de solicitudes, reduciendo tiempos y errores.
Transparencia: Registro claro y accesible del estado y la evolución de las solicitudes.
Accesibilidad: Interfaz intuitiva y roles bien definidos que facilitan el uso del sistema por parte de los diferentes tipos de usuarios.

Tecnologías Utilizadas:

Backend: ASP.NET MVC con C# y con EntityFramework Core
Frontend: HTML, CSS, JavaScript, Bootstrap
Base de Datos: SQL Server
Generación de PDFs: Rotativa

Equipo del Proyecto:

1 solo desarrollador FullStack (yo)

Este sistema asegurará una gestión eficiente y segura de las solicitudes, adaptándose a las necesidades específicas de cada usuario según su rol dentro de la organización.
