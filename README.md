# Wine-Tasting_Dataset

## Descripción

Este proyecto realiza un proceso completo de limpieza, exploración y análisis de datos sobre un conjunto de vinos. El análisis se centra en estudiar la relación entre variables como precio, puntuación, país de origen y reseñas, utilizando Python y librerías de análisis de datos.

El objetivo principal es extraer conclusiones relevantes a partir de los datos y practicar técnicas de análisis exploratorio y visualización.

## Contenido del proyecto

El análisis se desarrolla en un Jupyter Notebook y sigue los siguientes pasos:

### 1. Importación de librerías
Se utilizan librerías estándar para análisis y visualización de datos:
- Pandas
- NumPy
- Matplotlib
- Seaborn

### 2. Carga y exploración inicial
- Lectura del dataset.
- Inspección de las primeras filas.
- Revisión de la estructura del DataFrame y tipos de datos.

### 3. Limpieza de datos
- Conversión de columnas a tipos numéricos cuando es necesario.
- Detección y tratamiento de valores nulos.
- Filtrado de registros con información relevante disponible (por ejemplo, precio).

### 4. Análisis exploratorio
- Estadísticas descriptivas.
- Distribución de precios y puntuaciones.
- Identificación de valores atípicos.
- Estudio de correlaciones entre variables numéricas.

### 5. Análisis de reseñas
- Cálculo de la longitud de las reseñas.
- Visualización mediante histogramas.
- Relación entre longitud de la reseña y precio del vino.

### 6. Análisis estadístico con NumPy
- Cálculo de percentiles.
- Estudio de la distribución de precios y puntuaciones.

### 7. Visualización de datos
- Histogramas.
- Gráficos de correlación.
- Comparaciones entre países, bodegas y puntuaciones medias.

### 8. Conclusiones
- Relación entre precio y puntuación.
- Países con mayor y menor puntuación media.
- Tendencias generales observadas en el dataset.

## 9.Mini análisis

A lo largo del proyecto se han analizado distintos aspectos del conjunto de datos para entender mejor el comportamiento de los vinos:

- Comparación de la **puntuación media por país**, identificando regiones con vinos mejor y peor valorados.
- Análisis de las **bodegas con mayor puntuación media**, destacando aquellas con una calidad más consistente.
- Estudio de la relación entre **precio y puntuación**, observando si los vinos más caros reciben necesariamente mejores valoraciones.
- Identificación de vinos **sobrevalorados** (precio alto y puntuación baja) y vinos con **buena relación calidad-precio**.
- Análisis específico de los vinos de **España**, comparando los más caros por punto y los más económicos con alta puntuación.
- Comparación de la **puntuación media por variedad de uva**.
- Evaluación del impacto de los **valores nulos en el precio** sobre el análisis.
- Estudio de la influencia de la **longitud de las reseñas** en la puntuación y el precio.

## 10.Gráficos

Para apoyar el análisis, se generaron distintas visualizaciones que facilitan la interpretación de los datos:

- Histogramas de precios y puntuaciones.
- Gráficos de barras de países y bodegas con mayor puntuación media.
- Gráficos comparativos de cantidad de vinos por país.
- Visualizaciones de vinos españoles sobrevalorados y con mejor relación calidad-precio.
- Gráficos de dispersión para analizar la relación entre:
  - Precio y puntuación.
  - Longitud de la reseña y puntuación.

## Tecnologías utilizadas

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Autores

-Diana
-Cassius
