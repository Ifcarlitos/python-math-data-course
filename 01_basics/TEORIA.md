# Teoría 01: Fundamentos de Python

## 1. Introducción
Python es un lenguaje de programación de alto nivel, interpretado y de propósito general. Se destaca por su sintaxis legible y limpia, lo que facilita el aprendizaje y el mantenimiento del código. Es ampliamente utilizado en ciencia de datos, desarrollo web, automatización y machine learning.

Al ser **interpretado**, el código se ejecuta línea por línea, lo que facilita la depuración pero puede ser más lento que lenguajes compilados como C++. Sin embargo, para ciencia de datos, las librerías numéricas suelen estar optimizadas en C, combinando la facilidad de uso de Python con la velocidad de bajo nivel.

## 2. Contenido Teórico

### 2.1 Variables y Tipos de Datos
En Python, no es necesario declarar el tipo de variable explícitamente (tipado dinámico).

*   **Enteros (`int`)**: Números sin decimales (ej. `10`, `-5`).
*   **Flotantes (`float`)**: Números con decimales (ej. `3.14`, `1.0`).
*   **Booleanos (`bool`)**: Valores de verdad (`True`, `False`).
*   **Cadenas (`str`)**: Texto encerrado en comillas simples o dobles (ej. `"Hola Mundo"`).

### 2.2 Operadores
*   **Aritméticos**: `+` (suma), `-` (resta), `*` (multiplicación), `/` (división), `//` (división entera), `%` (módulo/resto), `**` (potencia).
*   **Lógicos**: `and` (y), `or` (o), `not` (negación).
*   **Comparación**: `==` (igual), `!=` (diferente), `>`, `<`, `>=`, `<=`.

### 2.3 Estructuras de Control de Flujo
Permiten decidir qué código ejecutar basándose en condiciones y repetir bloques de código.

*   **Condicionales (`if-elif-else`)**:
    ```python
    if x > 0:
        print("Positivo")
    elif x == 0:
        print("Cero")
    else:
        print("Negativo")
    ```

*   **Bucles (`Loops`)**:
    *   **`for`**: Itera sobre una secuencia (lista, string, rango). Ideal cuando se conoce la cantidad de iteraciones.
    *   **`while`**: Repite mientras una condición sea verdadera. Cuidado con los bucles infinitos.

### 2.4 Funciones y Modularidad
Las funciones permiten encapsular código reutilizable.

*   **Definición**: Se usa la palabra clave `def`.
*   **Parámetros**: Variables que recibe la función.
*   **Retorno**: Valor que devuelve la función usando `return`.
*   **Funciones Lambda**: Funciones anónimas pequeñas, útiles para operaciones rápidas. Ex: `doble = lambda x: x * 2`.

**Módulos**:
Los archivos `.py` se conocen como módulos. Se pueden importar funciones y clases de otros módulos usando `import nombre_modulo` o `from nombre_modulo import funcion`.

## 3. Referencias
*   [Documentación Oficial de Python 3](https://docs.python.org/3/)
*   [Python Tutorial (W3Schools)](https://www.w3schools.com/python/)
*   [Real Python - Tutoriales y Guías](https://realpython.com/)
