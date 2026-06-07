# Wine-Quality-Prediction
Proyecto de Machine Learning para predecir la calidad del vino mediante modelos de clasificación supervisada.
# Wine Quality Prediction

## Descripción

Proyecto de Machine Learning cuyo objetivo es predecir la calidad del vino utilizando modelos de clasificación supervisada.

## Objetivos

* Explorar el conjunto de datos.
* Preparar la información para el modelado.
* Comparar distintos algoritmos de clasificación.
* Seleccionar el modelo con mejor desempeño.

## Dataset

WineQT Dataset.

* 1.143 registros.
* 11 variables predictoras.
* Variable objetivo: Quality.

## Técnicas utilizadas

### Exploración de datos

* Estadística descriptiva.
* Distribución de clases.
* Matriz de correlación.

### Preprocesamiento

* Eliminación de variables irrelevantes.
* División entrenamiento-prueba estratificada.
* Escalamiento mediante StandardScaler.

### Modelos evaluados

* K-Nearest Neighbors (KNN).
* Regresión Logística.
* Random Forest.

## Resultados

| Modelo              | Accuracy | F1 Macro |
| ------------------- | -------- | -------- |
| KNN                 | 0.694    | 0.338    |
| Random Forest       | 0.664    | 0.405    |
| Regresión Logística | 0.437    | 0.278    |

Random Forest fue seleccionado como el modelo final debido a su desempeño más equilibrado.

## Variables más importantes

* Alcohol.
* Volatile acidity.
* Sulphates.
* Total sulfur dioxide.

## Cómo ejecutar el proyecto

1. Descargar el repositorio.
2. Instalar las dependencias necesarias.
3. Ejecutar el notebook principal en Google Colab o Jupyter Notebook.

## Autora

Karla Caroca Henríquez.
Proyecto desarrollado para la asignatura de Machine Learning.
