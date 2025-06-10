# Módulo 3: Ejercicio de Evaluación Final 

Este repositorio contiene la resolución del ejercicio de evaluación final del Módulo 3 de Data Analytics, centrado en el análisis del comportamiento de clientes dentro de un programa de lealtad de una aerolínea.


## Descripción del Proyecto

El objetivo de este ejercicio es explorar, limpiar, visualizar y analizar dos conjuntos de datos relacionados con un programa de lealtad de aerolíneas. Los datos describen la actividad de vuelo de los clientes y sus perfiles demográficos/de membresía.

El proyecto se divide en tres fases principales:

1.  **Exploración y Limpieza de Datos**: Identificación y tratamiento de valores nulos, inconsistencias y ajustes de tipos de datos. [cite_start]Unión eficiente de los dos conjuntos de datos proporcionados.
2.  **Visualización de Datos**: Creación de diversas visualizaciones para responder preguntas específicas sobre la distribución de vuelos, relación entre distancia y puntos, distribución geográfica de clientes, comparación de salarios por nivel educativo, proporción de tipos de tarjetas de fidelidad y distribución por estado civil y género.
3.  **Evaluación de Diferencias en Reservas de Vuelos por Nivel Educativo (BONUS)**: Análisis estadístico para determinar si existen diferencias significativas en el número de vuelos reservados según el nivel educativo de los clientes.

## Conjunto de Datos

Se utilizan dos archivos CSV principales:

* **`Customer Flight Analysis.csv`**: Este archivo contiene información sobre la actividad de vuelo de los clientes, incluyendo el número de vuelos reservados, la distancia volada, puntos acumulados y redimidos, y costos asociados a los puntos redimidos.
* **`Customer Loyalty History.csv`**: Este archivo proporciona un perfil detallado de los clientes, incluyendo su ubicación, nivel educativo, ingresos, estado civil, y detalles sobre su membresía en el programa de lealtad (como el tipo de tarjeta, valor de vida del cliente, y fechas de inscripción y cancelación).

Ambos archivos se pueden correlacionar mediante el `Loyalty Number`.


## Requisitos

Para ejecutar el código en este repositorio, necesitarás las siguientes librerías de Python:

* `pandas`
* `matplotlib`
* `seaborn`
* `scipy` (para la fase BONUS de prueba estadística)

## Uso

Para utilizar este repositorio y completar el ejercicio:

1. Crea un nuevo repositorio desde GitHub Classroom usando el enlace proporcionado y clónalo en tu ordenador.
2. Abre el archivo [Ejercicio Final Modulo 3 Laura].ipynb en tu entorno de desarrollo preferido (Jupyter Notebook, VS Code, etc.).
3. Ejecuta las celdas (o el script completo) para proceder con la exploración, limpieza, visualizaciones y el análisis estadístico de los datos.
