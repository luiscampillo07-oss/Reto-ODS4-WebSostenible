## Arquitectura de la Solución Web

### Nombre de la Web
**FastNotes Cloud**

### Funcionalidades Principales

1. **Biblioteca de PDFs:** Los profesores pueden subir apuntes en PDF para que los alumnos los tengan organizados por asignaturas.
2. **Acceso sin conexión:** Los PDFs se almacenan en la nube y también se pueden guardar temporalmente en el dispositivo para abrirlos incluso sin conexión a internet.
3. **Búsqueda rápida de documentos:** Los alumnos pueden buscar rápidamente apuntes por nombre de asignatura o tema para no perder tiempo en clase.

### Entidades de Datos Básicas

| Entidad | Descripción | Ejemplo de datos |
| :--- | :--- | :--- |
| Usuarios | Almacena a los estudiantes y profesores registrados en la plataforma | ID_usuario, nombre, email, contraseña, rol |
| PDFs | Guarda los archivos PDF subidos por los profesores | ID_pdf, título, asignatura, ruta_archivo |
| Asignaturas | Organiza los documentos según la materia | ID_asignatura, nombre_asignatura |

### Prototipo de Interfaz (Frontend)

A continuación se muestra el wireframe de nuestra aplicación:

![Prototipo de la Interfaz Web](prototipo.png)

**Breve explicación:** La página principal muestra una lista de asignaturas y los PDFs disponibles. Los alumnos pueden abrir los documentos rápidamente o descargarlos para verlos incluso sin conexión.