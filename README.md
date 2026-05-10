# Caso-practico-de-Python_25-de-abril
Ejercicios prácticos de programación y análisis desarrollados en Python
# Análisis de Tuberculosis mediante Python
Este proyecto tiene como finalidad realizar un análisis de datos relacionados con la tuberculosis (TB) utilizando Python como herramienta principal para el procesamiento, depuración y visualización de información estadística.

## Descripción del proyecto

La tuberculosis es una enfermedad infecciosa provocada por la bacteria *Mycobacterium tuberculosis*, la cual afecta principalmente el sistema respiratorio. En este trabajo se emplearon bases de datos proporcionadas por la OMS junto con registros de población para estudiar distintos aspectos relacionados con la enfermedad, tales como:
- Número de casos de tuberculosis por país y periodo
- Clasificación por sexo, edad y tipo de diagnóstico
- Cálculo de la tasa de incidencia por cada 100,000 habitantes
- Evolución de los casos a través del tiempo

## Fuentes de datos

- `who.csv`: Registro de casos de tuberculosis
- `population.csv`: Información poblacional por país y año

## Tecnologías utilizadas: Python, Pandas, NumPy, Seaborn, Plotly

## Procesamiento y transformación de datos

Durante el desarrollo del proyecto se llevaron a cabo diferentes etapas de análisis y preparación de datos:

### Limpieza de datos
- Corrección de datos inconsistentes
- Tratamiento de valores nulos
- Verificación y validación de registros

### Transformación de datos
- Conversión de columnas a filas mediante `melt`
- Creación de variables relacionadas con:
  - Género
  - Tipo de diagnóstico
  - Grupo de edad

### Integración de información
- Unión de datasets para incorporar datos de población
- Elaboración del dataset final `tuberculosis.csv`

## Análisis realizado

Se realizaron distintos análisis estadísticos y descriptivos, entre ellos:
- Distribución de casos por género
- Comparación por método de diagnóstico
- Clasificación por grupos de edad
- Identificación de países analizados
- Determinación del periodo de estudio

Asimismo, se calculó la tasa de incidencia utilizando la fórmula:

Tasa de incidencia = (casos / población) * 100,000. Tanto a nivel global como por país y año.

## Visualizaciones

Para representar la información obtenida se desarrollaron distintas gráficas y visualizaciones, incluyendo:
- Gráficas de tendencia de incidencia
- Visualizaciones interactivas
- Comparaciones estadísticas por categorías
Elaborado por: Valeria Monserrat Urzua Leyva
