# ModelosClimaticos_MGCC_PED

Material práctico (PED) del bloque 1 (“Modelos climáticos”) de la asignatura
*Modelos, Escenarios y Datos Climáticos* del Máster Universitario en Gestión del
Cambio Climático (UNED).

El objetivo de estas prácticas es analizar, mediante modelos climáticos
conceptuales implementados en Python, la respuesta del sistema climático a
forzamientos externos, el papel de las retroalimentaciones y la aparición de
comportamientos no lineales y de variabilidad interna.

---

## Organización del repositorio

El repositorio está organizado en dos bloques principales, correspondientes a
las dos Pruebas de Evaluación a Distancia (PED) del bloque de modelos:

- **PED1_EBM_1D/**  
  Modelo climático de balance energético unidimensional (1D) en latitud,
  implementado con la librería `climlab`.  
  Incluye notebooks sobre:
  - introducción al modelo y al uso de climlab,
  - respuesta al forzamiento radiativo con albedo constante,
  - retroalimentación hielo–albedo e histéresis.

- **PED2_ENSO/**  
  Modelo conceptual del fenómeno ENSO, basado en un oscilador de recarga.  
  Incluye notebooks sobre:
  - dinámica determinista del modelo,
  - efecto del ruido y variabilidad interna.

Cada carpeta contiene un breve README con el orden recomendado de ejecución de
los notebooks.

---

## Forma de uso

Estos notebooks están diseñados para ejecutarse **online mediante Binder**,
sin necesidad de instalación local ni descarga del repositorio.

- Ejecutar siempre los notebooks en el orden indicado.
- No es necesario (ni recomendable) modificar el código salvo cuando se indique
  explícitamente en las instrucciones.
- Las figuras generadas sirven como apoyo para el análisis y la interpretación,
  y no constituyen un resultado a entregar por sí mismas.

---

## Evaluación

La evaluación **no se basa en la programación**, sino en la interpretación
conceptual de los resultados obtenidos con los modelos.

El estudiante debe entregar un documento independiente (PDF o Word) con
respuestas razonadas y personalizadas a las cuestiones planteadas en cada PED,
apoyándose en las figuras que considere relevantes.

Las instrucciones detalladas, las preguntas a responder y los criterios de
evaluación se encuentran en el documento oficial de la asignatura.

---

## Requisitos técnicos

El entorno de ejecución está definido en el archivo `requirements.txt`.
Los notebooks se ejecutan mediante Binder.  
Consulta los README de cada PED para acceder directamente a los notebooks.




