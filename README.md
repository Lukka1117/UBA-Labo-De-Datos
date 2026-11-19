# Laboratorio de Datos — FCEN (UBA)

Repositorio con las resoluciones de las guías prácticas y trabajos prácticos de la materia **Laboratorio de Datos** (Facultad de Ciencias Exactas y Naturales, Universidad de Buenos Aires).

Todos los trabajos incluyen su código fuente en **R Markdown (`.Rmd`)** y su correspondiente informe compilado en **PDF (`.pdf`)**.

---

## Contenido del Repositorio

### Guías Prácticas

| Práctica | Tema | Contenidos principales |
| :--- | :--- | :--- |
| **Práctica 1** | Funciones y Datos Faltantes | Vectores en R, estadística descriptiva básica, definición de funciones personalizadas e indexación con manejo de `NA`. |
| **Práctica 2** | Dataframes y Dplyr | Manipulación y transformación de datos con `dplyr` (`mutate`, `select`, `filter`, `group_by`, `summarise`), bucles `for` vs. `sapply` para conteo de `NA` (`nycflights13`). |
| **Práctica 5** | Visualización | Gráficos exploratorios y comparativos con `ggplot2` (scatterplots, escalas logarítmicas, `facet_wrap`, boxplots, gráficos de violín y barras de error) sobre `gapminder`. |
| **Práctica 6** | Regresión Lineal Simple | Ajuste e interpretación de modelos lineales (`lm`), $R^2$, ECM/RMSE, centrado de variables, extrapolación, transformaciones log-log, Cuarteto de Anscombe y Paradoja de Simpson (`palmerpenguins`, `mtcars`, `iris`, `gapminder`). |
| **Práctica 7** | Regresión Polinómica y Validación | Ajuste de polinomios (`poly`), sesgo-varianza y overfitting, Validation Set Approach, Leave-One-Out Cross-Validation (LOOCV) y k-Fold Cross-Validation con `boot` (`mtcars`, `gapminder`, `Auto`). |
| **Práctica 8** | Validación Cruzada y Selección de Variables | Selección de grado óptimo por k-Fold CV (LIDAR), variables dummy, matrices de correlación y selección *Forward* paso a paso evaluada con validación cruzada. |
| **Práctica 9** | Clasificación, KNN y Métricas | Clasificación con K-Nearest Neighbors (`class` y `tidymodels`), estandarización, matrices de confusión, métricas (Accuracy, Precision, Recall, F1) y Árboles de Decisión con poda (`rpart`, `ISLR`). |
| **Práctica 10** | Análisis de Agrupamiento | Aprendizaje no supervisado con K-means (`stats` y `tidyclust`), distancia euclidiana, estandarización z-score, coeficiente de Silhouette, método del codo y perfilado de clusters (`factoextra`, `mtcars`, `palmerpenguins`). |

---

### Trabajos Prácticos

#### 1. Análisis de Resultados Aprender 2024
* **Descripción:** Análisis exploratorio y descriptivo del desempeño educativo en Lengua y Matemática de estudiantes de nivel secundario en Argentina (Operativo Aprender 2024), cruzado con datos de inversión educativa estatal por jurisdicción.
* **Enfoque:** Limpieza y filtrado institucional, estadística descriptiva, distribuciones de frecuencias, análisis comparativo por sector (estatal/privado), ámbito (urbano/rural), nivel educativo materno y correlación con presupuesto educativo.
* **Autores:** Barrios Uma, Lorenzo Luciana, Temelini Mateo.

#### 2. Precios de Viviendas en CABA y GBA
* **Descripción:** Modelado predictivo y segmentación del mercado inmobiliario en Capital Federal y Gran Buenos Aires a partir de datos de Properati (2020).
* **Enfoque:** Análisis exploratorio y detección de valores atípicos, modelos de Regresión Lineal Simple (especificación log-log), comparación de modelos de Regresión Lineal Múltiple con interacciones mediante 10-Fold Cross-Validation, y segmentación de propiedades en CABA utilizando K-means.
* **Autores:** Barrios Uma, Lorenzo Luciana, Temelini Mateo.

---

## Tecnologías y Librerías Utilizadas

* **Lenguaje:** R / R Markdown (compilado a PDF mediante XeLaTeX)
* **Manipulación y visualización:** `tidyverse`, `dplyr`, `tidyr`, `ggplot2`, `readr`, `patchwork`, `gridExtra`, `ggrepel`, `corrplot`, `ggcorrplot`, `GGally`
* **Modelado, validación y machine learning:** `tidymodels`, `tidyclust`, `caret`, `boot`, `class`, `rpart`, `rpart.plot`, `cluster`, `factoextra`
* **Tablas y reportes:** `knitr`, `kableExtra`
* **Datasets incluidos en paquetes:** `nycflights13`, `gapminder`, `palmerpenguins`, `ISLR`, `ISLR2`

---
