# Negociación y discusión de requisitos

Resultados de la discución con el cliente, obteniendo lo necesario para el desarrollo gracias a la entrevista realizada:

RQ0001:

Descripción del requisito → Registro de notas y cálculo automático de promedios.

Tipo de conflicto / Ambigüedad → No estaba claro si el cálculo debía ser personalizable según la institución o fijo.

Partes involucradas → Cliente (profesora), Equipo de Desarrollo.

Discusión / Análisis → Se analizó la necesidad de que cada institución pueda configurar el tipo de promedio (ponderado, simple) para evitar que el sistema sea rígido.

Acuerdo final → Se decidió implementar cálculo de promedios configurable en parámetros del sistema.

Revaluación Post-Implementación → Verificar si la configuración cubre todos los escenarios de la docente.

RQ0002:

Descripción del requisito → Creación de fichas de trabajo de manera automática.

Tipo de conflicto / Ambigüedad → Generar fichas dinámicas requiere más tiempo de desarrollo y podría aumentar el costo del sistema.

Partes involucradas → Cliente (profesora), Equipo de Desarrollo.

Discusión / Análisis → Se discutió si debía incluirse en la primera versión o dejarse para una futura iteración, considerando la carga de trabajo y presupuesto.

Acuerdo final → Se incluyó un módulo básico de repositorio de problemas, dejando la generación automática avanzada para futuras versiones.

Revaluación Post-Implementación → Evaluar si la docente necesita ampliar este módulo para cubrir más contenidos.


RQ0003:


Descripción del requisito → Seguridad del sistema.

Tipo de conflicto / Ambigüedad → La profesora indicó que no requiere alta seguridad, pero los datos de alumnos son sensibles y deben protegerse.

Partes involucradas → Cliente, Equipo de Desarrollo.

Discusión / Análisis → Se discutió el riesgo de filtración de datos y la obligación de proteger información personal por normativa educativa.

Acuerdo final → Se acordó implementar un nivel de seguridad mínimo: usuarios con contraseña y encriptación básica de datos.

Revaluación Post-Implementación → Revisar si este nivel de seguridad es suficiente o si debe incrementarse según normativa escolar.
