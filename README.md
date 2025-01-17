# Churn_Data_Teleco
Análisis de Churn
Este repositorio contiene un análisis completo enfocado en identificar y entender los factores que influyen en el churn (deserción de clientes) dentro de un conjunto de datos. El objetivo principal del proyecto es proporcionar insights accionables para minimizar la pérdida de clientes mediante el uso de análisis exploratorios y técnicas avanzadas de machine learning.

Contenido del Notebook
1. Importación de Librerías y Carga de Datos
El análisis comienza con la preparación del entorno de trabajo, incluyendo la importación de las librerías necesarias y la carga del conjunto de datos.

2. Análisis Exploratorio Inicial
Inspección general de la estructura de los datos, incluyendo dimensiones y tipos de variables.
Estadísticas descriptivas para identificar tendencias generales.
Visualización de datos clave mediante gráficos para detectar patrones iniciales.
3. Tratamiento de Valores Nulos y Recodificación de Variables
Identificación y análisis de valores faltantes en el dataset.
Recodificación de variables categóricas y numéricas para optimizar el análisis posterior.
4. Exploración y Análisis de Variables Principales
Análisis detallado de variables clave relacionadas con el churn, como tipo de cliente, zona geográfica y tiempo transcurrido desde la última interacción.
Identificación de correlaciones y relaciones significativas entre variables mediante gráficos y métricas estadísticas.
5. Modelado Predictivo con Machine Learning
Se entrenan y evalúan diferentes modelos de machine learning para predecir la probabilidad de churn:

Regresión Logística: Modelo base para entender la relación entre las variables independientes y el churn.
Naive Bayes: Enfoque probabilístico para clasificar clientes propensos a desertar.
K-Nearest Neighbors (KNN): Clasificación basada en similitudes entre clientes.
Linear Discriminant Analysis (LDA): Análisis discriminante para segmentar clientes.
XGBoost: Algoritmo de boosting para mejorar la precisión de las predicciones.
Red Neuronal Simple: Modelo basado en redes neuronales para capturar relaciones no lineales complejas.
6. Evaluación de Modelos
Cada modelo es evaluado utilizando:

Matrices de confusión para analizar la precisión, sensibilidad y especificidad.
Curvas ROC para medir la capacidad de discriminación de cada modelo.
Métricas de desempeño clave como accuracy, precision y recall.
7. Insights de Negocio y Recomendaciones
Se proporcionan conclusiones prácticas basadas en el análisis y los resultados de los modelos. Estas recomendaciones están diseñadas para ayudar a las empresas a tomar decisiones informadas sobre cómo retener clientes y optimizar recursos.
