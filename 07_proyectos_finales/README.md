# Nivel 7: Proyecto Final Integrador

En este módulo aplicaremos todo lo aprendido para resolver un problema de negocio real: la predicción de precios de vivienda.

## Caso de Estudio: Predicción de Precios Inmobiliarios

### Objetivo
Construir un modelo de Machine Learning capaz de estimar el precio de mercado de una propiedad basándose en sus características (metros cuadrados, habitaciones, ubicación, etc.).

### Flujo de Trabajo
1.  **Carga y Exploración (EDA)**: Análisis de la distribución de precios y correlaciones con Pandas y Seaborn.
2.  **Limpieza de Datos**: Tratamiento de valores atípicos y nulos.
3.  **Feature Engineering**: Creación de nuevas variables (ej. antigüedad de la vivienda).
4.  **Modelado**: Entrenamiento de un modelo de Regresión Lineal y un Random Forest.
5.  **Evaluación**: Comparación de métricas (MAE, RMSE, R²).

### Dataset
El archivo `data/housing.csv` contiene datos sintéticos con las siguientes columnas:
*   `Precio`: Variable objetivo (target).
*   `Metros_Cuadrados`: Superficie útil.
*   `Habitaciones`: Número de dormitorios.
*   `Baños`: Número de cuartos de baño.
*   `Ubicacion_Centro`: 1 si está en el centro, 0 si está en periferia.
*   `Año_Construccion`: Año de edificación.
