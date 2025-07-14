# Clasificación de Medicamentos con Modelos de Ensamble

Este repositorio contiene un proyecto de machine learning enfocado en la predicción de medicamentos para pacientes, utilizando sus características clínicas. Se aplican distintos métodos de ensamble para comparar su rendimiento y mejorar el poder predictivo respecto a enfoques previos.

## Objetivo

Utilizar modelos de clasificación supervisada para predecir el medicamento más adecuado con base en variables como edad, sexo, presión arterial, colesterol y la relación sodio-potasio.

## Modelos aplicados

- Random Forest  
- Gradient Boosting  
- AdaBoost  
- Bagging Classifier  

## Preprocesamiento de datos

- Codificación de variables categóricas con `LabelEncoder`
- Definición de variables predictoras y objetivo
- División de conjunto de datos en entrenamiento y prueba

## Evaluación de modelos

Cada modelo fue evaluado mediante:

- Reporte de clasificación (precisión, recall, F1-score)
- Matriz de confusión
- Gráficos de importancia de características

## Comparación y resultados

- **Random Forest y Gradient Boosting:** rendimiento perfecto (100%) con alta interpretabilidad
- **Bagging:** también obtuvo exactitud perfecta, incluso con diferentes configuraciones
- **AdaBoost:** presentó resultados más variables, con un 85% de exactitud en prueba y menor desempeño en clases minoritarias

La mejora respecto a modelos simples de árboles de decisión es notable, con ensambles mostrando mayor estabilidad y precisión promedio en predicción.

## Requisitos

- Python 3.x  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn

## Conclusión

Este proyecto demuestra cómo los métodos de ensamble pueden potenciar la capacidad predictiva de modelos de clasificación, especialmente en contextos médicos donde la precisión por clase es fundamental.
