# Negociación y discusión de requisitos

Resultados de la discusión con el cliente, obteniendo lo necesario para el desarrollo gracias a la entrevista realizada:

| **ID Requisito** | **Descripción del requisito** | **Tipo de conflicto / Ambigüedad** | **Discusión / Análisis** | **Acuerdo final** | **Revaluación Post-Implementación** |
|-------------------|--------------------------------|------------------------------------|---------------------------|-------------------|--------------------------------------|
| **RQ0001** | Registro de notas y cálculo automático de promedios. | No estaba claro si el cálculo debía ser personalizable según la profesora o fijo. | Se analizó la necesidad de que la profesora pueda configurar el tipo de promedio (ponderado, simple) para evitar que el sistema sea rígido. | Se decidió implementar cálculo de promedios configurable en parámetros del sistema. | Verificar si la configuración cubre todos los escenarios de la docente. |
| **RQ0002** | Creación de fichas de trabajo de manera automática. | Generar fichas dinámicas requiere más tiempo de desarrollo y podría aumentar el costo del sistema. | Se discutió si debía incluirse en la primera versión o dejarse para una futura iteración, considerando la carga de trabajo y presupuesto. | Se incluyó un módulo básico de repositorio de problemas, dejando la generación automática avanzada para futuras versiones. | Evaluar si la docente necesita ampliar este módulo para cubrir más contenidos. |
| **RQ0003** | Seguridad del sistema. | La profesora indicó que no requiere alta seguridad, pero los datos de alumnos son sensibles y deben protegerse. | Se discutió el riesgo de filtración de datos y la obligación de proteger información personal por normativa educativa. | Se acordó implementar un nivel de seguridad mínimo: usuario con contraseña. | Revisar si este nivel de seguridad es suficiente o si debe incrementarse según normativa escolar. |

