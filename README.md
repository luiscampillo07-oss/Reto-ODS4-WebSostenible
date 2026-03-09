# Reto-ODS4-WebSostenible

**Problema**

> En muchas clases los profesores comparten apuntes en formato PDF que los estudiantes deben abrir desde moodle o descargarlos en el momento. Sin embargo, en algunos centros educativos la conexión a internet es lenta o inestable.

> Esto provoca que los archivos PDF tarden mucho en cargarse o incluso no se abran durante la clase. Como consecuencia, se pierde tiempo esperando a que los documentos se descarguen y parte del tiempo de clase se desperdicia.

**A que afecta**

> Este problema afecta al acceso eficiente a los materiales educativos y dificulta el seguimiento del contenido durante la explicación del profesor.

**Propuesta**

> Nuestra propuesta es desarrollar una plataforma web que almacene los documentos educativos en un sistema en la nube y permita a los estudiantes acceder a los PDFs incluso cuando la conexión a internet sea limitada o inexistente, reduciendo así las interrupciones durante la clase.

**Medidas sostenibles**
<br> Medidas de sostenibilidad de la plataforma:</br>

1.Sistema de almacenamiento en la nube que permita guardar previamente los PDFs para acceso rápido.

2.Posibilidad de visualizar los documentos en modo offline una vez cargados.

3.Optimización del tamaño de los archivos PDF para reducir el consumo de datos.

4.Interfaz ligera para que la plataforma funcione correctamente incluso con conexiones lentas.

5.Reducción del tiempo perdido en clase al acceder a materiales educativos.

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
=======