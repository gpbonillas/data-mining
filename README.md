# data-mining using R

Este repositorio contiene los enunciados y soluciones de cada actividad propuesta para aprobar la asignatura Minería de Datos de la Maestría en Ciencia de Datos de la [Universitat Oberta de Catalunya](https://www.uoc.edu/portal/es/index.html) (UOC) del periodo septiembre 2020 - enero 2021. 

En cada carpeta hay 2 directorios:

1. Enunciado: Es el archivo *.Rmd* (se abre y ejecuta con RStudio) y que contiene las indicaciones que se deben cumplir para resolver la actividad. En algunos casos se incluye un dataset en formato *CVS*.

2. Solucion: Incluye el archivo *.Rmd* que contiene el código R que resuelve las instrucciones dadas por el enunciado. Además se incluyen los archivos *PDF*, *HTML* o *DOCX* que se generan desde RStudio a partir del archivo *.Rmd*. Para algunos casos fue necesario obtener otros datasets que también se incluyen en este directorio.

Un breve resumen de lo que trata cada actividad es: 

## Actividad 1

En esta actividad se tiene un ejercicio teórico y uno práctico. Para el ejercicio práctico la rúbrica de evaluación es: 

- Se carga la base de datos, se visualiza su estructura y se explican los hechos básicos.
- Se estudia si existen atributos vacíos, y si es el caso, se adoptan medidas para tratar estos atributos.
- Se transforma algún atributo para adaptarlo en un estudio posterior. 
- Se realiza alguna discretitzación de algún atributo.
- Se crea un indicador nuevo a partido otros atributos 
- Se analizan los datos de forma visual y se extraen conclusiones tangibles. Hay que elaborar un discurso coherente y con conclusiones claras. 
- Se trata en profundidad algún otro aspecto respecto a los datos presentado en el módulo 2 
- Se ha buscado información adicional, se ha incluido en el documento de respuesta y las fuentes se han citado correctamente 

> La solución a la Actividad 1 está en el siguiente [archivo](https://github.com/gpbonillas/data-mining/blob/main/PEC%201/Solucion/gbonillas-PEC1.Rmd)


## Actividad 2

Para esta actividad la rúbrica de evaluación es:

### Ejercicio 1.1
- Se explican los campos de la base de datos, preparación y análisis de datos
- Se aplica el algoritmo de agrupamiento de forma correcta.
- Se prueban con diferentes valores de k.
- Se obtiene una medida de lo bueno que es el agrupamiento.
- Se ponen nombres a las asociaciones.
- Se describen e interpretan los diferentes clústers obtenidos.
- Se presenta el código y es fácilmente reproducible.

### Ejercicio 1.2
- Se prueba un algoritmo diferente al kmeans.
- Se prueba otro algoritmo diferente al kmeans.
- Se comparan los resultados del kmeans y los otros dos métodos probados en este ejercicio.
- Se presenta el código y es fácilmente reproducible.

### Ejercicio 2.1
- Se realiza un resumen de los datos incluidos en la base de datos.
- Se preparan los datos de forma correcta.
- Se aplica el algoritmo de reglas de asociación.
- Se realizan diferentes pruebas variando algunos parámetros.
- Se explican las conclusiones que se obtienen.
- Se presenta el código y es fácilmente reproducible.

> La solución a la Actividad 2 está en el siguiente [archivo](https://github.com/gpbonillas/data-mining/blob/main/PEC%202/Solucion/gbonillas-PEC2.Rmd)

## Actividad 3

Para esta actividad la rúbrica de evaluación es la siguiente: 

- Se explica de forma clara la base de datos seleccionada y la razón de su elección.
- Hay un estudio sobre los datos de los que se parte y los datos son preparados correctamente.
- Se aplica un árbol de decisión de forma correcta y se obtiene una estimación del error.
- Se muestra de forma gráfica el árbol obtenido.
- Se explican las reglas que se obtienen.
- Se usa el modelo para predecir con muestras no usadas en el entrenamiento y se obtiene una estimación del error.
- Se prueba otro modelo de árbol o variantes diferentes del C50 obteniendo mejores resultados.
- Se presenta el código y es fácilmente reproducible.
- Se presenta unas conclusiones donde se expone el conocimiento adquirido tras el trabajo realizado.

> La solución a la Actividad 3 está en el siguiente [archivo](https://github.com/gpbonillas/data-mining/blob/main/PEC%203/Solucion/gbonillas-PEC3.Rmd)

## Práctica 1

Esta actividad se complementa con la actividad PRA 2, por lo que la rúbrica de evaluación es:

- Justificación de la elección del juego de datos donde se detalle el potencial analítico que se intuye. 
- Información extraída del análisis exploratorio. Distribuciones, correlaciones, anomalías, entre otras.
- Explicación clara de cualquier tarea de limpieza o acondicionado que se realiza. Justificando el motivo y mencionando las ventajas de la acción tomada.
- Se realiza un proceso de PCA o SVD donde se aprecia mediante explicaciones y comentarios que el estudiante entiende todos los pasos y se comenta extensamente el resultado final obtenido.

> La solución a la Práctica 1 está en el siguiente [archivo](https://github.com/gpbonillas/data-mining/blob/main/PRA%201/Solucion/75.584-PRA1.Rmd)

## Práctica 2

Esta actividad es la continuación de la PRA 1, cuya rúbrica de evaluación es la siguiente: 

- Se generan reglas y se comentan e interpretan las más significativas. Adicionalmente se genera matriz de confusión para medir la capacidad predictiva del algoritmo.  
- Se genera modelo no supervisado, se muestran y comentan medidas de calidad del modelo generado y se comentan las conclusiones.  
- Se genera modelo no supervisado con métrica de distancia distinta al anterior. Se muestran y comentan medidas de calidad del modelo generado y se comentan las conclusiones. Adicionalmente se comparan los dos modelos no supervisados con métricas de distancia distinta.  
- Se genera un modelo supervisado sin PCA/SVD previo, se muestran y comentan medidas de calidad del modelo generado y se comenta extensamente el conocimiento extraído del modelo.  
- Se genera un modelo supervisado con PCA/SVD previo, se muestran y comentan medidas de calidad del modelo generado y se comenta extensamente el conocimiento extraído del modelo.    
- Se compara la capacidad predictiva de los dos modelos supervisados y se comenta la diferencia de rendimiento en base al efecto PCA/SVD.  

> La solución a la Práctica 2 está en el siguiente [archivo](https://github.com/gpbonillas/data-mining/blob/main/PRA%202/Solucion/gbonillas-PRA2.Rmd)
