# Multivariado Operativo

Repositorio de apuntes, hojas de ruta y ejercicios del cursado de la materia
Multivariado.

El material está organizado por bloques temáticos. Cada tema suele tener:

- `.qmd`: fuente editable en Quarto.
- `.html`: versión navegable.
- `.pdf`: versión lista para leer o imprimir.
- `*_files/`: recursos generados por Quarto para los HTML, como figuras,
  estilos y bibliotecas.

## Índice general

- [Bloque 1: Exploración y ordenamiento](#bloque-1-exploracion-y-ordenamiento)
- [Bloque 2: Clustering y clasificación](#bloque-2-clustering-y-clasificacion)
- [Bloque 3: Diferenciación y ejercicios integradores](#bloque-3-diferenciacion-y-ejercicios-integradores)
- [Otros archivos](#otros-archivos)

## Bloque 1: Exploración y ordenamiento

### 01 Iris

Hoja de ruta operativa para datos continuos con `iris`. Recorre la
estructura del dataset, preparación de matriz, distancias, PCA, PCoA, NMDS,
t-SNE, UMAP e interpretación.

- [Fuente QMD](Bloque_01/01_iris/Hoja_Ruta_Iris.qmd)
- [Versión HTML](Bloque_01/01_iris/Hoja_Ruta_Iris.html)
- [Versión PDF](Bloque_01/01_iris/Hoja_Ruta_Iris.pdf)
- [Recursos del HTML](Bloque_01/01_iris/Hoja_Ruta_Iris_files/)

### 02 Dune

Hoja de ruta operativa para datos de abundancia con `dune`. Trabaja
transformaciones, presencia/ausencia, disimilitudes, CA, PCoA, NMDS y criterios
para evaluar la representación.

- [Fuente QMD](Bloque_01/02_dune/Hoja_Ruta_Dune.qmd)
- [Versión HTML](Bloque_01/02_dune/Hoja_Ruta_Dune.html)
- [Versión PDF](Bloque_01/02_dune/Hoja_Ruta_Dune.pdf)
- [Recursos del HTML](Bloque_01/02_dune/Hoja_Ruta_Dune_files/)

## Bloque 2: Clustering y clasificación

### 01 USArrests

Apunte sobre clustering jerárquico y k-means con `USArrests`, orientado a
formar grupos de observaciones parecidas y evaluar si esos grupos tienen
sentido.

- [Fuente QMD](Bloque_02/01_usarrests/Clustering_kmeans_usarrests.qmd)
- [Versión HTML](Bloque_02/01_usarrests/Clustering_kmeans_usarrests.html)
- [Versión PDF](Bloque_02/01_usarrests/Clustering_kmeans_usarrests.pdf)
- [Recursos del HTML](Bloque_02/01_usarrests/Clustering_kmeans_usarrests_files/)

### 02 GMM, DBSCAN y OPTICS

Apunte comparativo sobre mixturas gaussianas, métodos basados en densidad y la
lectura conceptual de distintos modelos de agrupamiento.

- [Fuente QMD](Bloque_02/02_GMM_DBSCAN_OPTICS/GMM_DBSCAN_OPTICS.qmd)
- [Versión HTML](Bloque_02/02_GMM_DBSCAN_OPTICS/GMM_DBSCAN_OPTICS.html)
- [Versión PDF](Bloque_02/02_GMM_DBSCAN_OPTICS/GMM_DBSCAN_OPTICS.pdf)
- [Recursos del HTML](Bloque_02/02_GMM_DBSCAN_OPTICS/GMM_DBSCAN_OPTICS_files/)

### 03 LDA, EDDA y clasificación semisupervisada

Apunte de clasificación supervisada y semisupervisada con `iris`, incluyendo
LDA, EDDA y mixturas gaussianas semisupervisadas.

- [Fuente QMD](Bloque_02/03_LDA_EDDA_semisupervisada/clasificacion_supervisada_semisupervisada_iris.qmd)
- [Versión HTML](Bloque_02/03_LDA_EDDA_semisupervisada/clasificacion_supervisada_semisupervisada_iris.html)
- [Versión PDF](Bloque_02/03_LDA_EDDA_semisupervisada/clasificacion_supervisada_semisupervisada_iris.pdf)
- [Recursos del HTML](Bloque_02/03_LDA_EDDA_semisupervisada/clasificacion_supervisada_semisupervisada_iris_files/)

### 04 Wholesale

Trabajo sobre el dataset `wholesale`, con exploración, PCA, clustering
jerárquico, k-means, GMM, DBSCAN, OPTICS, clasificación y análisis de
sensibilidad frente a outliers.

- [Fuente QMD](Bloque_02/04_wholesale/wholesale.qmd)
- [Versión HTML](Bloque_02/04_wholesale/wholesale.html)
- [Versión PDF](Bloque_02/04_wholesale/wholesale.pdf)
- [Recursos del HTML](Bloque_02/04_wholesale/wholesale_files/)

## Bloque 3: Diferenciación y ejercicios integradores

### 01 Diferenciación multivariada

Apunte introductorio sobre diferenciación multivariada: MANOVA, permutaciones,
ANOSIM, PERMDISP y Mantel.

- [Fuente QMD](Bloque_03/01_diferenciacion/diferenciacion.qmd)
- [Versión HTML](Bloque_03/01_diferenciacion/diferenciacion.html)
- [Versión PDF](Bloque_03/01_diferenciacion/diferenciacion.pdf)
- [Recursos del HTML](Bloque_03/01_diferenciacion/diferenciacion_files/)

### 01 Diferenciación multivariada, parte 2

Apunte practico con `dune` sobre MRPP, PERMANOVA, PERMDISP, NMDS, RRPP,
comparaciones de a pares y comparación final entre métodos.

- [Fuente QMD](Bloque_03/01_diferenciacion/diferenciacion_parte2.qmd)
- [Versión HTML](Bloque_03/01_diferenciacion/diferenciacion_parte2.html)
- [Versión PDF](Bloque_03/01_diferenciacion/diferenciacion_parte2.pdf)
- [Recursos del HTML](Bloque_03/01_diferenciacion/diferenciacion_parte2_files/)

### 02 Ejemplo: obesidad y hábitos

Ejercicio integrador sobre hábitos, antecedentes familiares, edad y condición
corporal. El análisis recategoriza `NObeyesdad` en grupos con y sin exceso de
peso.

- [Fuente QMD](Bloque_03/02_ejemplos/obesidad.qmd)
- [Versión HTML](Bloque_03/02_ejemplos/obesidad.html)
- [Versión PDF](Bloque_03/02_ejemplos/obesidad.pdf)
- [Dataset CSV](<Bloque_03/02_ejemplos/obesidad y habitos.csv>)
- [Recursos del HTML](Bloque_03/02_ejemplos/obesidad_files/)

### 02 Ejemplo: penguins

Ejercicio integrador con mediciones morfológicas de pingüinos. Evalúa
diferencias entre especies, islas y sexo mediante métodos de diferenciación
multivariada.

- [Fuente QMD](Bloque_03/02_ejemplos/penguins.qmd)
- [Versión HTML](Bloque_03/02_ejemplos/penguins.html)
- [Versión PDF](Bloque_03/02_ejemplos/penguins.pdf)
- [Recursos del HTML](Bloque_03/02_ejemplos/penguins_files/)

## Otros archivos

- [Licencia](LICENSE)
