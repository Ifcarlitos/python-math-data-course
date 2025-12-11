# Teoría 04: Estadística y Probabilidad

## 1. Introducción
La estadística nos proporciona las herramientas para recolectar, analizar e interpretar datos, mientras que la probabilidad nos permite cuantificar la incertidumbre. En Python, utilizamos principalmente `scipy.stats` y `statsmodels` para realizar análisis estadísticos rigurosos.

## 2. Contenido Teórico

### 2.1 Estadística Descriptiva
Resume y describe las características de un conjunto de datos.

*   **Medidas de Tendencia Central**:
    *   **Media**: Promedio aritmético.
    *   **Mediana**: Valor central que divide los datos en dos mitades. Robusta a outliers.
    *   **Moda**: Valor más frecuente.
*   **Medidas de Dispersión**:
    *   **Varianza y Desviación Típica**: Miden cuánto se alejan los datos de la media.
    *   **Rango Intercuartílico (IQR)**: Diferencia entre el tercer y primer cuartil (Q3 - Q1).
*   **Forma de la Distribución**: Skewness (asimetría) y Kurtosis (curtosis/apuntamiento).

### 2.2 Distribuciones de Probabilidad
Modelos matemáticos que asignan probabilidades a los resultados de un experimento aleatorio.

*   **Discretas**:
    *   **Binomial**: Número de éxitos en $n$ ensayos independientes.
    *   **Poisson**: Número de eventos en un intervalo de tiempo fijo.
*   **Continuas**:
    *   **Normal (Gaussiana)**: La más importante (curva de campana). Definida por $\mu$ (media) y $\sigma$ (desviación).
    *   **T-Student**: Similar a la normal pero con colas más pesadas, usada con muestras pequeñas.

### 2.3 Inferencia Estadística
Permite sacar conclusiones sobre una población basándose en una muestra.

*   **Teorema Central del Límite (TCL)**: Establece que la suma de variables aleatorias independientes tiende a una distribución normal, sin importar la distribución original, si la muestra es grande.
*   **Test de Hipótesis**:
    1.  Plantear **Hipótesis Nula ($H_0$)** (ej. "no hay efecto") y **Alternativa ($H_1$)**.
    2.  Calcular un estadístico de prueba.
    3.  Calcular el **p-valor**: Probabilidad de observar los datos si $H_0$ fuera cierta.
    4.  **Decisión**: Si p-valor < $\alpha$ (nivel de significancia, usualmente 0.05), rechazamos $H_0$.

## 3. Referencias
*   [SciPy Stats Tutorial](https://docs.scipy.org/doc/scipy/tutorial/stats.html)
*   [Think Stats (Allen B. Downey)](https://greenteapress.com/wp/think-stats-2e/)
*   [Introduction to Statistical Learning](https://www.statlearning.com/)
