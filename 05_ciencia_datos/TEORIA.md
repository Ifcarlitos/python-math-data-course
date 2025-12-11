# Teoría 05: Ciencia de Datos con Pandas

## 1. Introducción
**Pandas** es la librería estándar de facto para la manipulación y análisis de datos en Python. Ofrece estructuras de datos flexibles y funciones de alto rendimiento para trabajar con datos estructurados (tabulares), permitiendo realizar el proceso de ETL (Extract, Transform, Load) de manera eficiente.

## 2. Contenido Teórico

### 2.1 Estructuras de Datos Principales
*   **Series**: Array unidimensional con etiquetas (índice). Puede contener cualquier tipo de datos. Similar a una columna de Excel o tabla SQL.
*   **DataFrame**: Estructura tabular bidimensional (filas y columnas). Es una colección de Series que comparten el mismo índice.

### 2.2 Manipulación de Datos
Pandas permite seleccionar y filtrar datos de forma intuitiva.

*   **Indexación**:
    *   `.loc[]`: Selección basada en etiquetas (nombres de índice/columna).
    *   `.iloc[]`: Selección basada en posición entera (0, 1, 2...).
*   **Filtrado**: `df[df['columna'] > 5]` (selección condicional/booleana).
*   **Operaciones Vectorizadas**: Al igual que NumPy, se pueden aplicar operaciones a columnas enteras sin bucles.

### 2.3 Limpieza y Transformación (Data Wrangling)
Antes de analizar, los datos suelen requerir limpieza.

*   **Valores Faltantes**: Detección (`isna()`), eliminación (`dropna()`) o imputación (`fillna()`).
*   **Agrupación (`groupby`)**: Paradigma "Split-Apply-Combine". Divide los datos en grupos, aplica una función (suma, media, conteo) y combina los resultados.
*   **Combinación de Datasets**:
    *   `merge()`: Similar a SQL JOIN (inner, outer, left, right).
    *   `concat()`: Apilar DataFrames vertical u horizontalmente.

### 2.4 Entrada/Salida (I/O)
Pandas soporta leer y escribir en múltiples formatos: CSV, Excel, SQL, JSON, Parquet, etc.
*   `pd.read_csv('archivo.csv')`
*   `df.to_excel('reporte.xlsx')`

## 3. Referencias
*   [Pandas User Guide](https://pandas.pydata.org/docs/user_guide/index.html)
*   [Python for Data Analysis (Wes McKinney)](https://wesmckinney.com/book/)
*   [10 Minutes to pandas](https://pandas.pydata.org/docs/user_guide/10min.html)
