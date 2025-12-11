# Teoría 06: Machine Learning con Scikit-Learn

## 1. Introducción
El Machine Learning (Aprendizaje Automático) es una rama de la inteligencia artificial que permite a las computadoras aprender patrones a partir de datos sin ser programadas explícitamente para una tarea específica. En Python, **Scikit-Learn** es la librería más popular para aprendizaje automático "clásico" (no Deep Learning), ofreciendo una API consistente y eficiente.

## 2. Contenido Teórico

### 2.1 Tipos de Aprendizaje
*   **Aprendizaje Supervisado**: El modelo entrena con datos etiquetados (input $X$, output $y$). El objetivo es predecir $y$ para nuevos $X$.
    *   **Regresión**: La variable objetivo es continua (ej. precio de una casa).
    *   **Clasificación**: La variable objetivo es categórica (ej. spam vs no-spam).
*   **Aprendizaje No Supervisado**: Datos sin etiquetas (solo $X$). El objetivo es encontrar estructuras ocultas o patrones.
    *   **Clustering (Agrupamiento)**: Agrupar datos similares (ej. K-Means).
    *   **Reducción de Dimensionalidad**: Simplificar datos complejos (ej. PCA).

### 2.2 Algoritmos Comunes
*   **Regresión Lineal**: Relación lineal entre variables ($y = mx + b$).
*   **Regresión Logística**: Usada para clasificación binaria, estima probabilidades.
*   **Árboles de Decisión y Random Forest**: Modelos no lineales potentes y versátiles.
*   **K-Nearest Neighbors (KNN)**: Clasificación basada en la cercanía a otros puntos.

### 2.3 Evaluación de Modelos
Es crucial medir qué tan bien funciona un modelo en datos no vistos (conjunto de test).

*   **Métricas de Regresión**:
    *   **MSE (Mean Squared Error)**: Error cuadrático medio.
    *   **$R^2$ (Coeficiente de determinación)**: Proporción de la varianza explicada.
*   **Métricas de Clasificación**:
    *   **Accuracy (Exactitud)**: % de predicciones correctas.
    *   **Matriz de Confusión**: Muestra verdaderos positivos, falsos negativos, etc.
    *   **Precision y Recall**: Métricas más detalladas para clases desbalanceadas.

### 2.4 Preprocesamiento y Pipelines
Los datos reales rara vez están listos para el modelo. Scikit-Learn ofrece herramientas de transformación.

*   **Escalado**: Normalizar datos para que tengan la misma escala (`StandardScaler`, `MinMaxScaler`). Importante para modelos basados en distancias (KNN, SVM).
*   **Codificación**: Convertir variables categóricas a numéricas (`OneHotEncoder`).
*   **Pipelines**: Encadenar pasos de preprocesamiento y modelado en un solo objeto para evitar fugas de datos y simplificar el código.

## 3. Referencias
*   [Scikit-Learn User Guide](https://scikit-learn.org/stable/user_guide.html)
*   [Hands-On Machine Learning with Scikit-Learn (Aurélien Géron)](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)
*   [Google Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course)
