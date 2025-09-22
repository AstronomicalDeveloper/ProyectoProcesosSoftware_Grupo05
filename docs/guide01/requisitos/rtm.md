# Especificación de requisitos de software

## Requisitos funcionales
Los requisitos funcionales se expresan en lenguaje técnico a partir de los requisitos funcionales mandatorios que se han identificado en la categorización de requisitos de usuario.
Ello implica el desarrollo de los siguientes puntos:
  
- ***Módulos individuales por estudiante***
Descripción: Cada estudiante contará con un módulo único que almacenará su información académica y de asistencia.
Entradas:
Datos personales del estudiante (ID, nombre, apellido, grado, etc.).
Registros de notas por asignatura.
Registros de asistencia diarios.
Observaciones personalizadas ingresadas por el docente.
Proceso:
El sistema relaciona automáticamente al estudiante con sus notas y asistencias.
Permite añadir, modificar o eliminar observaciones específicas.
Salidas:
Visualización consolidada del historial académico y de asistencia del estudiante.
Reporte individual exportable (PDF o Excel).
- ***Registro de notas con cálculo automático de promedios***
Descripción: El sistema permitirá registrar notas por asignatura y calcular automáticamente los promedios ponderados.
Entradas:
Notas por actividad (examen, práctica, proyecto, etc.).
Peso o valor asignado a cada nota.
Proceso:
Almacenamiento de cada nota en la base de datos.
Aplicación de la fórmula de promedio ponderado según los pesos definidos.
Actualización automática del promedio en el módulo del estudiante.
Salidas:
Promedio parcial y final de cada asignatura.
Visualización de calificaciones detalladas y globales.
Inclusión de las notas en reportes grupales o individuales.
- ***Registro de asistencias***
Descripción: El sistema permitirá registrar la asistencia diaria por estudiante.
Entradas:
Fecha de clase.
Estado del estudiante (Asistió, Falta, Tardanza, Justificada).
Proceso:
El docente marca la asistencia en una interfaz de lista.
El sistema guarda automáticamente la asistencia en el historial del estudiante.
Posibilidad de editar registros pasados con autorización.
Salidas:
Listado diario de asistencia por curso o grupo.
Reporte mensual o bimestral de asistencia.
Alertas sobre ausencias frecuentes.
- ***Agrupación automática de estudiantes***
Descripción: El sistema podrá formar grupos automáticamente según criterios predefinidos.
Entradas:
Criterios de agrupación (ejemplo: cantidad máxima de estudiantes por grupo, nivel de notas, asistencia, etc.).
Proceso:
El sistema distribuye automáticamente a los estudiantes en grupos según el criterio definido.
Posibilidad de ajustes manuales por parte del docente.
Cada grupo puede tener notas y observaciones propias.
Salidas:
Listado de grupos generados con sus respectivos integrantes.
Reportes de actividades o evaluaciones grupales.
- ***Generación de reportes básicos***
Descripción: El sistema deberá generar reportes académicos y de asistencia en formatos PDF o Excel.
Entradas:
Selección de periodo (diario, mensual, bimestral, anual).
Selección de estudiantes (individual, curso completo, grupo).
Tipo de reporte (notas, asistencias, observaciones).
Proceso:
El sistema extrae la información desde la base de datos.
Formatea la información en tablas y gráficos simples.
Genera el archivo en PDF o Excel listo para impresión o distribución digital.
Salidas:
Reporte académico con promedios y detalle de notas.
Reporte de asistencia individual o grupal.
Exportación automática a PDF o Excel.

  
## Requisitos no funcionales
- Portabilidad del software

- Compatible con Windows 10 o superior y navegadores web modernos (Chrome, Firefox, Edge).
  
- Facilidad de mantenimiento: Que implica el grado de conocimiento de la herramienta de desarrollo del software, así como de la disponibilidad de personal técnico apropiado entre otros.

- Código estructurado en capas (presentación, lógica de negocio, datos).
  
- Documentación técnica para facilitar la incorporación de nuevo personal.
  
- Usabilidad del software

- Interfaz gráfica intuitiva y amigable para docentes sin experiencia técnica.
  
- Uso de íconos y menús claros para minimizar la curva de aprendizaje.
  
- Velocidad de procesamiento de datos

- Operaciones de registro y consulta deben ejecutarse en menos de 3 segundos para 200 alumnos.
  
- Restricciones técnicas del software: Por ejemplo, restricciones de diseño debido al sistema operativo utilizado, el entorno de la plataforma, problemas de compatibilidad con alguna aplicación interna o
  externa a la organización, estándar para alguna aplicación determinada, entre otros.
  
- Uso de base de datos relacional (MySQL/PostgreSQL).

- Compatibilidad con exportación a formatos estándar (PDF, Excel).

- Limitación inicial a entorno monousuario (en PC docente), con opción futura a cliente-servidor.


# Tips para mayor claridad
## Propósito
Definir los requisitos técnicos mínimos (RTM) del proyecto de software.

## Qué se espera
- Que sea el imput para el desglose de tareas de la planificación del proyecto, para su posterior diseño e implementación.
