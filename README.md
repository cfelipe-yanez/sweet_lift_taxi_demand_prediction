# sweet_lift_taxi_demand_prediction
Este es el repositorio en el que se creará todo para el proyecto del sprint 16 del curso de Triple Ten 
# Sweet Lift Taxi Demand Prediction

## Descripción del proyecto
Sweet Lift Taxi ha recopilado datos históricos sobre pedidos de taxis en los aeropuertos. El objetivo de este proyecto es predecir la cantidad de pedidos de taxis para la próxima hora, con el fin de optimizar la asignación de conductores durante las horas pico.

## Objetivo
Construir un modelo de machine learning que prediga la demanda horaria de taxis. La métrica RECM en el conjunto de prueba no debe ser superior a 48.

## Instrucciones del proyecto
1. Descargar y remuestrear los datos de tal forma que cada punto de datos caiga dentro de intervalos de una hora.
2. Analizar los datos y explorar patrones relevantes.
3. Entrenar diferentes modelos con distintos hiperparámetros.
4. Evaluar los modelos usando una muestra de prueba (10% del conjunto de datos original).
5. Sacar conclusiones basadas en los resultados de la predicción.

## Datos
- Archivo: `/datasets/taxi.csv`
- Columna objetivo: `num_orders` — número de pedidos de taxis.

## Librerías recomendadas
- `pandas`, `numpy` para manipulación de datos
- `matplotlib`, `seaborn` para visualización
- `scikit-learn`, `xgboost`, `lightgbm` para modelado

## Resultados esperados
- Modelo que prediga la demanda horaria de taxis con RECM ≤ 48.
- Gráficos y análisis de patrones de demanda.
