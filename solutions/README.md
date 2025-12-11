# Soluciones a los Ejercicios

En esta carpeta (o sección) encontrarás las soluciones detalladas a los ejercicios propuestos en cada notebook.

> **Recomendación Pedagógica**: Intenta resolver los ejercicios por tu cuenta antes de consultar soluciones. El esfuerzo productivo es clave para el aprendizaje.

## Solución Ejercicio 2.5 (Cálculo Simbólico)
Resolución de $ax^2 + bx + c = 0$.

```python
import sympy as sp
a, b, c, x = sp.symbols('a b c x')
ecuacion = a*x**2 + b*x + c
soluciones = sp.solve(ecuacion, x)
print(soluciones)
# Output: [(-b + sqrt(-4*a*c + b**2))/(2*a), -(b + sqrt(-4*a*c + b**2))/(2*a)]
```

## Solución Ejercicio 1.4 (Pandas - Ventas)
```python
import pandas as pd
ventas_data = {
    'Producto': ['A', 'B', 'C', 'D'],
    'Venta': [150, 300, 100, 250],
    'Region': ['Norte', 'Sur', 'Este', 'Oeste']
}
df_ventas = pd.DataFrame(ventas_data)
ventas_altas = df_ventas[df_ventas['Venta'] > 200]
print(ventas_altas)
```
