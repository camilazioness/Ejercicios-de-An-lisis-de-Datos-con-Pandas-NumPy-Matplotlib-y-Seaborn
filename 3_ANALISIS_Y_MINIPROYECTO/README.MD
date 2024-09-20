# Ejercicios de Análisis de Datos con Pandas, NumPy, Matplotlib y Seaborn

Aquí tienes una serie de ejercicios para practicar **Pandas**, **NumPy**, **Matplotlib** y **Seaborn**, desde lo básico hasta lo avanzado. Los primeros ejercicios incluyen una mini-guía para ayudarte a empezar.

## Ejercicios

### 🧮 **1. Operaciones básicas con NumPy**

**Objetivo**: Crear y manipular arrays.

**Enunciado**:
1. Crea un array de NumPy de 10 elementos con valores entre 1 y 10.
2. Calcula la media, mediana, y desviación estándar de los valores.
3. Multiplica cada valor por 2.

**Mini-guía**:
- Usa `np.array` para crear un array.
- Métodos útiles: `np.mean()`, `np.median()`, `np.std()`.

### 📊 **2. Operaciones con Pandas DataFrames**

**Objetivo**: Crear y manipular un DataFrame.

**Enunciado**:
1. Crea un DataFrame con 3 columnas (A, B, C) y 5 filas con números aleatorios enteros.
2. Renombra las columnas a Col1, Col2, Col3.
3. Añade una nueva columna que sea la suma de las columnas Col1 y Col2.
4. Elimina todas las filas donde el valor de Col3 sea menor que 10.

**Mini-guía**:
- Métodos útiles: `pd.DataFrame()`, `df.rename()`, `df['NewCol']`, `df.drop()`.

### 📈 **3. Visualización básica con Matplotlib**

**Objetivo**: Crear un gráfico de línea y un histograma.

**Enunciado**:
1. Genera 100 números aleatorios con distribución normal (media = 0, desviación estándar = 1).
2. Haz un gráfico de líneas con los primeros 50 números.
3. Crea un histograma de los 100 números.

**Mini-guía**:
- Usa `np.random.normal()` para generar números.
- Métodos útiles: `plt.plot()`, `plt.hist()`, `plt.show()`.

### 🌈 **4. Visualización avanzada con Seaborn**

**Objetivo**: Visualizar datos categóricos.

**Enunciado**:
1. Carga el dataset `tips` de Seaborn.
2. Realiza un gráfico de barras mostrando la propina promedio (tip) por día.
3. Crea un gráfico de caja para analizar la distribución de propinas (tip) por día.

**Mini-guía**:
- Usa `sns.load_dataset('tips')`.
- Métodos útiles: `sns.barplot()`, `sns.boxplot()`, `plt.show()`.

### 📉 **5. Análisis estadístico con Pandas**

**Objetivo**: Realizar análisis estadístico descriptivo.

**Enunciado**:
1. Carga el dataset `titanic` de Seaborn.
2. Encuentra la media, mediana, y moda de la edad de los pasajeros.
3. Encuentra cuántos pasajeros sobrevivieron y cuántos no.
4. Calcula el porcentaje de supervivencia por clase (1ª, 2ª, 3ª clase).

**Mini-guía**:
- Métodos útiles: `df.describe()`, `df['column'].mean()`, `df['column'].value_counts()`.

### 🧹 **6. Limpieza de datos con Pandas**

**Objetivo**: Limpiar y manipular datos faltantes.

**Enunciado**:
1. Crea un DataFrame con datos faltantes en algunas celdas.
2. Llena los valores faltantes con la media de la columna.
3. Elimina las filas que tengan más de 2 valores faltantes.

**Mini-guía**:
- Métodos útiles: `df.fillna()`, `df.dropna()`.

### 🔍 **7. Análisis de correlación con Seaborn y Pandas**

**Objetivo**: Explorar la correlación entre variables.

**Enunciado**:
1. Carga el dataset `iris` de Seaborn.
2. Calcula la matriz de correlación entre las variables.
3. Crea un heatmap con el resultado de la correlación.

**Mini-guía**:
- Métodos útiles: `df.corr()`, `sns.heatmap()`, `plt.show()`.

### 📊 **8. Visualización conjunta con Matplotlib y Seaborn**

**Objetivo**: Crear visualizaciones combinadas.

**Enunciado**:
1. Carga el dataset `tips` de Seaborn.
2. Crea un gráfico de dispersión (scatter plot) entre el total de la cuenta (total_bill) y la propina (tip).
3. Añade una línea de regresión con Seaborn a la gráfica.

**Mini-guía**:
- Métodos útiles: `plt.scatter()`, `sns.regplot()`.

### 📅 **9. Análisis de datos temporales**

**Objetivo**: Trabajar con series temporales.

**Enunciado**:
1. Crea una serie temporal de 100 días con valores aleatorios entre 50 y 100.
2. Calcula la media móvil con una ventana de 10 días.
3. Grafica la serie temporal original y la media móvil en la misma gráfica.

**Mini-guía**:
- Métodos útiles: `pd.date_range()`, `df.rolling()`.

### 📈 **10. Aplicar técnicas de Estadística descriptiva**

**Objetivo**: Trabajar con distribución de frecuencias y medidas de tendencia central.

**Enunciado**:
1. Carga el dataset `diamonds` de Seaborn.
2. Calcula la frecuencia de los diferentes cortes de diamantes.
3. Encuentra la media, mediana y moda de los precios de los diamantes.
4. Visualiza la distribución del precio con un gráfico de densidad.

**Mini-guía**:
- Métodos útiles: `df['column'].value_counts()`, `df['column'].mean()`, `sns.kdeplot()`.

### 🧩 **11. Agrupaciones y operaciones complejas**

**Objetivo**: Trabajar con agrupaciones y operaciones avanzadas.

**Enunciado**:
1. Carga el dataset `titanic` de Seaborn.
2. Agrupa los datos por clase y sexo, y calcula la media de la edad y el precio del billete.
3. Crea un gráfico de barras que muestre la media del precio del billete por clase.

**Mini-guía**:
- Métodos útiles: `df.groupby()`, `df.mean()`, `sns.barplot()`.

### 🔄 **12. Visualizaciones interactivas con Plotly o Streamlit**

**Objetivo**: Crear gráficos interactivos.

**Enunciado**:
1. Carga el dataset `gapminder` de Seaborn.
2. Crea un gráfico interactivo de dispersión con Plotly donde el eje X sea la esperanza de vida y el eje Y el PIB per cápita.
3. Añade interactividad permitiendo filtrar los datos por continente.

**Mini-guía**:
- Métodos útiles: `plotly.express.scatter()`, `plotly.graph_objects.Figure()`, `st.plotly_chart()`.

### 🎯 **13. Proyecto final (sin guía)**

**Objetivo**: Realiza un análisis completo con visualizaciones y estadística.

**Enunciado**:
1. Elige un dataset de tu interés (puede ser de Kaggle, Seaborn, etc.).
2. Realiza un análisis exploratorio: estadísticas descriptivas, visualizaciones y correlaciones.
3. Identifica relaciones interesantes entre las variables.
4. Aplica técnicas de visualización avanzadas (Seaborn, Matplotlib o Plotly).
5. Presenta un reporte con gráficos y conclusiones.

---

**Estadísticas importantes para aplicar en los ejercicios**:
- Media, Mediana, Moda.
- Varianza y Desviación estándar.
- Distribución normal y Distribuciones de probabilidad.
- Correlación y Regresión.
- Análisis de frecuencias y Tablas cruzadas.

¡Espero que estos ejercicios te ayuden a mejorar tus habilidades en análisis de datos y visualización! 🚀📊
