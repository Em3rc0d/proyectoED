# Proyecto de Gestión de Limpieza de Habitaciones - Residencia Universitaria UNMSM

## Descripción del Proyecto
Este proyecto de gestión de limpieza y reporte de incidencias está diseñado para facilitar el mantenimiento y control de las habitaciones dentro de la residencia universitaria de la Universidad Nacional Mayor de San Marcos (UNMSM). El sistema permite a los administradores registrar incidencias, asignar tareas de limpieza a los estudiantes residentes y generar reportes detallados para análisis y seguimiento.

## Características Principales
- **Registro de Incidencias:** Permite registrar nuevas incidencias relacionadas con las habitaciones, tales como problemas de infraestructura, necesidades de reparación, etc.
- **Modificación de Incidencias:** Posibilidad de actualizar y modificar detalles de las incidencias registradas.
- **Asignación de Tareas de Limpieza:** Automatización en la asignación de tareas de limpieza a los estudiantes residentes.
- **Generación de Reportes:** Capacidad de generar reportes detallados de las incidencias registradas, facilitando el análisis y la toma de decisiones.
- **Exportación e Importación de Datos:** Soporte para guardar y cargar datos desde archivos CSV, asegurando la persistencia de la información.

## Componentes del Proyecto
1. **Modelos:**
   - `Estudiante`: Representa a un estudiante con su identificación y nombre.
   - `Habitacion`: Modelo de habitación que contiene información de hasta dos estudiantes y las incidencias asociadas.
   - `Incidencia`: Modelo que describe una incidencia específica en una habitación.

2. **Estructura de Datos:**
   - `ArbolIncidencias`: Estructura de árbol binario utilizada para almacenar y gestionar las incidencias registradas.

3. **Funcionalidades:**
   - **Registrar Incidencia:** Permite agregar nuevas incidencias especificando la habitación, descripción y gravedad.
   - **Modificar Incidencia:** Facilita la modificación de incidencias existentes según su identificación.
   - **Mostrar Reporte:** Visualización en tiempo real de todas las incidencias registradas.
   - **Guardar y Cargar desde CSV:** Funcionalidades para almacenar y recuperar datos de incidencias en archivos CSV.

## Tecnologías Utilizadas
- **Python:** Lenguaje de programación principal utilizado para la implementación del sistema.
- **Tkinter:** Biblioteca estándar de Python para la creación de interfaces gráficas de usuario (GUI).
- **CSV:** Formato utilizado para el almacenamiento de datos de incidencias de manera estructurada y legible.

## Uso del Proyecto
El proyecto está diseñado para ser utilizado por administradores de la residencia universitaria de la UNMSM para gestionar de manera eficiente las incidencias y tareas de limpieza de las habitaciones. Proporciona una interfaz intuitiva y funcionalidades robustas para asegurar el mantenimiento adecuado de las instalaciones y mejorar la experiencia de los estudiantes residentes.

Este proyecto fue desarrollado como parte del curso de Estructura de Datos de la UNMSM, con el objetivo de aplicar conceptos teóricos en un contexto práctico, mejorando así las habilidades de programación y gestión de datos de los estudiantes.

Para más detalles sobre el funcionamiento y la implementación, por favor consulta la documentación y el código fuente del proyecto.
