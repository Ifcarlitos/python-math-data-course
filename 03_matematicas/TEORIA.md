# Teoría 03: Matemáticas Computacionales

## 1. Introducción
Python permite resolver problemas matemáticos complejos mediante computación numérica (aproximaciones) y simbólica (exacta). En este módulo, nos centramos en **SciPy** para algoritmos matemáticos avanzados y **SymPy** para álgebra computacional manipulando símbolos matemáticos.

## 2. Contenido Teórico

### 2.1 Álgebra Lineal Computacional
Uso de librerías para manipular vectores y matrices.

*   **Sistemas de Ecuaciones Lineales**: Resolver $Ax = b$ eficientemente.
*   **Descomposiciones Matriciales**:
    *   **LU**: Descompone en matriz triangular inferior (L) y superior (U). Útil para resolver sistemas múltiples.
    *   **QR**: Descompone en matriz ortogonal (Q) y triangular superior (R). Base para mínimos cuadrados.
    *   **SVD (Descomposición en Valores Singulares)**: Fundamental en reducción de dimensionalidad y compresión de datos.
*   **Autovalores y Autovectores**: Esenciales estudiar transformaciones lineales y estabilidad de sistemas dinámicos.

### 2.2 Cálculo Simbólico (SymPy)
A diferencia de NumPy (que usa números aproximados), SymPy usa símbolos para resultados exactos.

*   **Símbolos**: Definición de variables `x, y = sympy.symbols('x y')`.
*   **Cálculo**:
    *   `diff()`: Derivadas exactas.
    *   `integrate()`: Integrales definidas e indefinidas.
    *   `limit()`: Cálculo de límites.
*   **Resolución de Ecuaciones**: `solveset()` o `solve()` para encontrar raíces exactas de polinomios o ecuaciones trascendentales.

### 2.3 Métodos Numéricos (SciPy)
Cuando no existe solución analítica cerrada, usamos métodos iterativos de aproximación.

*   **Optimización**: Encontrar mínimos/máximos de funciones (`scipy.optimize.minimize`). Fundamental en Machine Learning.
*   **Integración Numérica (Cuadratura)**: Calcular el área bajo la curva numéricamente (`scipy.integrate.quad`).
*   **Raíces de Ecuaciones**: Métodos como Newton-Raphson para encontrar ceros de funciones no lineales.

## 3. Referencias
*   [SciPy Lecture Notes](https://scipy-lectures.org/)
*   [SymPy Documentation](https://docs.sympy.org/latest/index.html)
*   [SciPy Reference Guide](https://docs.scipy.org/doc/scipy/reference/)
