# Especificación de requisitos de software

## Requisitos funcionales
Los requisitos funcionales se expresan en lenguaje técnico a partir de los requisitos funcionales mandatorios que se han identificado en la categorización de requisitos de usuario.
Ello implica el desarrollo de los siguientes puntos:
  
- ***Módulos individuales por estudiante:*** cada estudiante contará con un módulo que registre su historial académico y de asistencia. El sistema permitirá añadir observaciones personalizadas.
  
- ***Registro de notas con cálculo automático de promedios:*** el sistema deberá almacenar notas por asignatura y calcular el promedio automáticamente considerando el peso de cada nota.
  
- ***Registro de asistencias:*** el sistema permitirá registrar asistencia diaria.
  
- ***Agrupación automática de estudiantes:*** el sistema conformará grupos de manera automática según criterios definidos (ejemplo: número de estudiantes por grupo).
  
- ***Generación de reportes básicos:*** el sistema deberá generar reportes en PDF o Excel con el registro de notas y asistencia.

- ***Generador de fichas de trabajo:*** Basado en un repositorio de ejercicios (problemas, crucigramas, rompecabezas y textos), deberás agilizar la creación de materiales. Las fichas generadas deberán poder descargarse en formato Word o PDF.
  
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
