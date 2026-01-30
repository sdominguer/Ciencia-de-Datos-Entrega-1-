# Análisis Exploratorio de Datos – Netflix Titles
## Descripción del proyecto
Este proyecto presenta un **Análisis Exploratorio de Datos (EDA)** sobre el catálogo de contenidos disponibles en Netflix, utilizando un conjunto de datos que incluye información sobre películas y series, como su tipo, duración, país de origen, elenco, categorías, fechas de lanzamiento y fechas de incorporación a la plataforma.
El objetivo principal es **comprender la estructura del catálogo**, identificar patrones relevantes y generar **insights cuantitativos y cualitativos y graficos representativos**, así como **explicaciones de negocio** basadas en los datos analizados.
---
## Objetivos
- Analizar la distribución de películas y series en Netflix.
- Estudiar la duración de las películas y la cantidad de temporadas de las series.
- Identificar los países, actores y categorías con mayor presencia en el catálogo.
- Analizar la evolución temporal del contenido según el año de lanzamiento y la fecha de incorporación a la plataforma.
- Detectar patrones estacionales en la adquisición de contenido.
- Aplicar una metodología básica de Ciencia de Datos para el análisis.
---
## Dataset utilizado
Se utilizó el dataset **Netflix Titles Overview**, el cual obtuvimos de la plataforma de datos: https://www.kaggle.com/ y contiene:
- **8807 registros**
- **12 columnas**
- Variables numéricas, categóricas y textuales
### Principales columnas:
- `show_id`
- `type` (Movie / TV Show)
- `title`
- `director`
- `cast`
- `country`
- `date_added`
- `release_year`
- `rating`
- `duration`
- `listed_in`
- `description`
El dataset presenta valores faltantes en columnas como `cast` y `director`.
---
## Metodología
El análisis se desarrolló siguiendo una metodología inspirada en **CRISP-DM**, incluyendo las siguientes etapas:
1. Comprensión del problema y de los datos  
2. Preparación y limpieza del dataset  
3. Análisis exploratorio cuantitativo (estadísticas descriptivas y visualizaciones)  
4. Análisis cualitativo de categorías y descripciones  
5. Generación de hipótesis y explicaciones de negocio  
---
## Análisis realizado
### Análisis cuantitativo
- Conteo de películas vs series
- Distribución por país y clasificación (`rating`)
- Análisis de duración de películas (en minutos)
- Análisis de número de temporadas en series
- Análisis de categorías (`listed_in`)
- Actores con mayor número de apariciones
- Análisis temporal:
 - Evolución del contenido por año de lanzamiento
 - Crecimiento del catálogo según fecha de incorporación (`date_added`)
 - Análisis estacional por mes
### Visualizaciones
- Gráficos de barras
- Histogramas
- Gráficos apilados
- Boxplots
- Gráficos temporales
---
## Principales insights
- El catálogo de Netflix presenta una mayor cantidad de películas frente a series.
- La mayoría de las películas tienen duraciones estándar de la industria cinematográfica.
- Las series tienden a tener pocas temporadas, sugiriendo alta rotación de contenido.
- Existen categorías dominantes que concentran gran parte del catálogo.
- El crecimiento del contenido en Netflix ha sido progresivo, con picos claros en determinados años y meses.
- La recurrencia de ciertos actores se explica por su participación en industrias específicas o en contenidos seriados de larga duración.
---
## Tecnologías utilizadas
- **Python 3**
- **Pandas**
- **Matplotlib**
- **Jupyter Notebook**
---
## Estructura del repositorio
├── Netflix.ipynb
├── README.md
├── netflix_titles.csv
