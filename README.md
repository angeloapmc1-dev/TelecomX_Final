# Telecom X - Prediccion de Churn

## Objetivo
El proposito de este analisis es predecir la cancelacion de clientes utilizando Machine Learning. Identificamos que factores como el Gasto Total y la Antigüedad son los mas criticos.

## Preparacion de Datos
* Clasificacion de variables numericas y categoricas.
* Uso de get_dummies para codificacion.
* Division de datos: 70% entrenamiento y 30% prueba.

## Resultados del Modelo
* Modelo: Random Forest Classifier.
* Precision (Accuracy): 78.67%.
* Hallazgo principal: El "Gasto Total" es la variable que mas influye en la decision del cliente de irse.

## Como ejecutar
1. Cargar datos_tratados.csv en Google Colab.
2. Ejecutar las celdas de entrenamiento y evaluacion.
