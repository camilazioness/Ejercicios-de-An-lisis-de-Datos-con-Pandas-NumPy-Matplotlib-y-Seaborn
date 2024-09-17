# Ejercicios de NumPy y Pandas 📊📈

## Introducción
Esta es una serie de ejercicios diseñados para practicar tus habilidades con **NumPy** y **Pandas**. Los primeros ejercicios incluyen una pequeña guía para ayudarte a comprender mejor los conceptos y las funciones clave. Los ejercicios posteriores son más avanzados y te permitirán aplicar técnicas de análisis de datos.

---

## Ejercicio 1: Operaciones básicas con NumPy
**Objetivo**: Crear y manipular arrays.

1. Crea un array de NumPy de 10 elementos con valores entre 1 y 10.
2. Calcula la media, mediana, y desviación estándar de los valores.
3. Multiplica cada valor por 2.

**Mini-guía**:

- Usa `np.array` para crear un array.
- Métodos útiles: `np.mean()`, `np.median()`, `np.std()`.

---

## Ejercicio 2: Operaciones con Pandas DataFrames
**Objetivo**: Crear y manipular un DataFrame.

1. Crea un DataFrame con 3 columnas (A, B, C) y 5 filas con números aleatorios enteros.
2. Renombra las columnas a Col1, Col2, Col3.
3. Añade una nueva columna que sea la suma de las columnas Col1 y Col2.
4. Elimina todas las filas donde el valor de Col3 sea menor que 10.

**Mini-guía**:

- Métodos útiles: `pd.DataFrame()`, `df.rename()`, `df['NewCol']`, `df.drop()`.

---

## Ejercicio 3: Estadística descriptiva con Pandas
**Objetivo**: Aplicar análisis estadístico básico.

1. Crea un DataFrame con 100 valores aleatorios entre 0 y 50.
2. Calcula la media, mediana y moda de los valores.
3. Encuentra el valor mínimo y el valor máximo del DataFrame.

**Mini-guía**:

- Métodos útiles: `df.describe()`, `df['column'].mean()`, `df['column'].mode()`.

---

## Ejercicio 4: Indexación y Filtrado
**Objetivo**: Practicar la selección de datos en un DataFrame.

1. Carga un dataset usando Pandas (por ejemplo, `df = sns.load_dataset('tips')`).
2. Selecciona todas las filas donde el valor de la columna `total_bill` sea mayor a 20.
3. Filtra y muestra solo las columnas `total_bill` y `tip`.
4. Ordena el DataFrame por la columna `tip` de mayor a menor.

**Mini-guía**:

- Métodos útiles: `df[df['column'] > valor]`, `df[['col1', 'col2']]`, `df.sort_values()`.

---

## Ejercicio 5: Agrupaciones y funciones de agregación
**Objetivo**: Agrupar datos y aplicar funciones de resumen.

1. Carga el dataset de `titanic` desde Seaborn.
2. Agrupa los datos por la columna `pclass` (clase del pasajero).
3. Calcula la media de las edades (`age`) para cada grupo.
4. Encuentra el número total de pasajeros en cada clase.

**Mini-guía**:

- Métodos útiles: `df.groupby()`, `df['column'].mean()`, `df.size()`.

---

## Ejercicio 6: Manipulación avanzada de DataFrames
**Objetivo**: Aplicar técnicas avanzadas de manipulación.

1. Carga el dataset `diamonds` de Seaborn.
2. Crea una nueva columna que calcule el precio por quilate (`price_per_carat`).
3. Filtra todos los diamantes con un precio por quilate superior a 5000.
4. Ordena el DataFrame por esta nueva columna.

---

## Ejercicio 7: Análisis de series temporales con Pandas
**Objetivo**: Trabajar con fechas y series temporales.

1. Crea un DataFrame con una columna de fechas (usa `pd.date_range()` para generar las fechas).
2. Genera 100 valores aleatorios asociados a estas fechas.
3. Calcula la media móvil de los valores con una ventana de 5 días.

---

## Ejercicio 8: Aplicación de funciones personalizadas
**Objetivo**: Aplicar funciones personalizadas a un DataFrame.

1. Crea un DataFrame con valores aleatorios.
2. Define una función que clasifique los valores como `alto` si son mayores a 0 y `bajo` si son menores o iguales.
3. Aplica esta función a todas las filas de una columna y crea una nueva columna con los resultados.

---

## Ejercicio 9: Limpieza de datos con Pandas
**Objetivo**: Limpiar y manipular datos faltantes.

1. Crea un DataFrame con datos faltantes en algunas celdas.
2. Llena los valores faltantes con la media de la columna.
3. Elimina las filas que tengan más de 2 valores faltantes.

---

## Ejercicio 10: Proyecto Final 🚀
**Objetivo**: Realiza un análisis completo.

1. Elige un dataset de tu interés (puedes usar uno de Seaborn o uno descargado de Kaggle).
2. Realiza un análisis exploratorio: estadísticas descriptivas, visualizaciones y correlaciones.
3. Identifica relaciones interesantes entre las variables.
4. Aplica técnicas avanzadas de visualización.
5. Presenta un informe con gráficos y conclusiones.

---

¡Buena suerte! 💪