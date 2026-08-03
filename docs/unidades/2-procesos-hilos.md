# Unidad 2. Procesos e Hilos

## Descripción

Esta unidad introduce las abstracciones utilizadas por los sistemas operativos para representar y administrar actividades en ejecución.

A partir del concepto de proceso se analiza cómo el sistema operativo organiza la ejecución de múltiples programas, mantiene su estado, administra los recursos asociados y proporciona mecanismos de aislamiento entre distintas actividades.

El estudio de los hilos permite profundizar en la ejecución concurrente dentro de un mismo proceso, distinguiendo los recursos compartidos de aquellos que pertenecen a cada flujo de ejecución. La unidad establece las bases necesarias para abordar posteriormente la planificación del procesador y la coordinación de actividades concurrentes.

## Objetivos de aprendizaje

Al finalizar esta unidad se espera que el estudiante sea capaz de:

- comprender el problema que representa la asignación del procesador entre múltiples procesos o hilos;
- reconocer los distintos objetivos que persiguen las políticas de planificación;
- comprender que diferentes algoritmos responden a distintos criterios de diseño y utilización;
- reconocer los compromisos existentes entre eficiencia, equidad y capacidad de respuesta;
- comprender la influencia de la planificación sobre el comportamiento global del sistema operativo.

## Resultados esperados

Al finalizar la unidad el estudiante:

- explica por qué la planificación constituye un problema central en los sistemas operativos;
- identifica los criterios utilizados para evaluar algoritmos de planificación;
- compara distintas políticas de planificación considerando sus objetivos, ventajas y limitaciones;
- analiza cómo una política de planificación influye en el comportamiento del sistema;
- fundamenta la elección de una política de planificación para distintos escenarios de utilización.

## Contenidos

- Concepto de programa y proceso.
- Estados y ciclo de vida de un proceso.
- Creación y finalización de procesos.
- Representación y contexto de ejecución.
- Recursos asociados a un proceso.
- Concepto de hilo.
- Recursos compartidos y recursos propios de cada hilo.
- Modelos de ejecución basados en procesos e hilos
.