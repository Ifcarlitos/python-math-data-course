# Teoría 02: Programación Científica (NumPy y Matplotlib)

## 1. Introducción
El ecosistema científico de Python se basa en librerías optimizadas para el cálculo numérico y la visualización. **NumPy** es la base de casi todas las herramientas científicas en Python, proporcionando estructuras de datos eficientes. **Matplotlib** es el estándar para crear visualizaciones estáticas, animadas e interactivas.

## 2. Contenido Teórico

### 2.1 NumPy (Numerical Python)
NumPy introduce el `ndarray` (n-dimensional array), una estructura mucho más rápida y eficiente en memoria que las listas de Python.

*   **Arrays N-Dimensionales**: Colecciones homogéneas de datos (mismo tipo).
    ```python
    import numpy as np
    arr = np.array([1, 2, 3])
    matriz = np.array([[1, 2], [3, 4]])
    ```
*   **Vectorización**: Capacidad de realizar operaciones en todo el array sin bucles explícitos (ej. `arr * 2` multiplica cada elemento por 2).
*   **Indexación y Slicing**: Acceso eficiente a subconjuntos de datos. `arr[inicio:fin:paso]`.
*   **Broadcasting**: Reglas que permiten operar con arrays de diferentes formas (shapes), "estirando" el más pequeño para que coincida.

### 2.2 Visualización con Matplotlib
Librería inspirada en MATLAB para graficar datos.

*   **Estructura de una Figura**:
    *   `Figure`: El contenedor principal (la ventana o imagen).
    *   `Axes`: El área donde se dibujan los datos (los ejes XY).
*   **Gráficos Comunes**:
    *   `plt.plot()`: Líneas y puntos.
    *   `plt.scatter()`: Diagramas de dispersión.
    *   `plt.bar()`: Gráficos de barras.
    *   `plt.hist()`: Histogramas.
*   **Personalización**: Etiquetas (`xlabel`, `ylabel`), Títulos (`title`), Leyendas (`legend`), Estilos de línea y marcadores.

### 2.3 Buenas Prácticas en Computación Científica
*   **Entornos Virtuales**: Aislar dependencias del proyecto.
*   **Notebooks vs Scripts**: Usar Jupyter para exploración y visualización; Scripts `.py` para código de producción o módulos reutilizables.
*   **Documentación**: Uso de Docstrings y comentarios claros.

## 3. Referencias
*   [NumPy Documentation](https://numpy.org/doc/stable/)
*   [Matplotlib User Guide](https://matplotlib.org/stable/users/index.html)
*   [Python Data Science Handbook (Jake VanderPlas)](https://jakevdp.github.io/PythonDataScienceHandbook/)
