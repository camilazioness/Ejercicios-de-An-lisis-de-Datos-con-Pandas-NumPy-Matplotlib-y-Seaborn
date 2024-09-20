# Ejercicios para Practicar con Matplotlib y Seaborn 📊

Aquí tienes una serie de ejercicios para que practiques tus habilidades con las librerías `Matplotlib` y `Seaborn`, aplicando conceptos de estadística básica para el análisis de datos. Los ejercicios están ordenados de menor a mayor dificultad. Los primeros ejercicios tienen una mini-guía para ayudarte, pero los últimos te dejarán explorar de forma autónoma.

---

## Ejercicio 1: Gráfico de Líneas con Matplotlib 📈
### Objetivo:
Visualizar la tendencia de una serie de datos.

1. Crea una serie de datos aleatorios (entre 0 y 100) de tamaño 50.
2. Usa `Matplotlib` para graficar los datos en un gráfico de líneas.
3. Añade título, etiquetas a los ejes y una leyenda.
4. Cambia el color de la línea a rojo y usa un estilo de línea punteado.

### Mini-guía:
- Usa `np.random.randint()` para generar los datos.
- Métodos útiles: `plt.plot()`, `plt.title()`, `plt.xlabel()`, `plt.ylabel()`, `plt.legend()`.

---

## Ejercicio 2: Gráfico de Barras con Seaborn 🧮
### Objetivo:
Visualizar datos categóricos.

1. Carga el dataset `tips` de Seaborn.
2. Realiza un gráfico de barras que muestre el total de las cuentas (`total_bill`) agrupadas por día.
3. Añade etiquetas a los ejes y un título.

### Mini-guía:
- Usa `sns.load_dataset("tips")` para cargar los datos.
- Métodos útiles: `sns.barplot()`, `plt.xlabel()`, `plt.ylabel()`, `plt.title()`.

---

## Ejercicio 3: Histograma con Matplotlib 🛠️
### Objetivo:
Visualizar la distribución de datos numéricos.

1. Genera 1000 números aleatorios con distribución normal (media = 0, desviación estándar = 1).
2. Crea un histograma usando Matplotlib para visualizar la distribución.
3. Ajusta el número de "bins" del histograma para que la visualización sea clara.

### Mini-guía:
- Usa `np.random.normal()` para generar los números.
- Métodos útiles: `plt.hist()`, `plt.grid()`, `plt.show()`.

---

## Ejercicio 4: Gráfico de Caja (Boxplot) con Seaborn 🎁
### Objetivo:
Visualizar la distribución de datos y posibles outliers.

1. Usa el dataset `tips` de Seaborn.
2. Realiza un gráfico de caja (`boxplot`) que muestre la distribución de las propinas (`tip`) por día.
3. Añade título y etiquetas a los ejes.

### Mini-guía:
- Métodos útiles: `sns.boxplot()`, `plt.title()`, `plt.xlabel()`, `plt.ylabel()`.

---

## Ejercicio 5: Scatter Plot con Matplotlib 🟢
### Objetivo:
Visualizar la relación entre dos variables.

1. Usa el dataset `iris` de Seaborn.
2. Crea un gráfico de dispersión (`scatter plot`) para visualizar la relación entre el ancho del sépalo (`sepal_width`) y la longitud del sépalo (`sepal_length`).
3. Añade colores diferentes según la especie de flor.

### Mini-guía:
- Métodos útiles: `plt.scatter()`, `plt.color()`.

---

## Ejercicio 6: Heatmap con Seaborn 🔥
### Objetivo:
Visualizar la correlación entre variables numéricas.

1. Usa el dataset `iris` de Seaborn.
2. Calcula la matriz de correlación de las variables.
3. Crea un heatmap para visualizar la matriz de correlación.

---

## Ejercicio 7: Gráfico de Línea con Media Móvil 📊
### Objetivo:
Visualizar series temporales.

1. Genera una serie temporal de 100 días con valores aleatorios.
2. Calcula la media móvil de los últimos 10 días y gráficala junto a la serie original.
3. Usa diferentes colores para la serie original y la media móvil.

---

## Ejercicio 8: Gráfico de Pares (Pairplot) con Seaborn 🌟
### Objetivo:
Visualizar relaciones entre múltiples variables.

1. Usa el dataset `tips` de Seaborn.
2. Crea un `pairplot` que visualice la relación entre `total_bill`, `tip` y `size`.
3. Usa diferentes colores para representar el día.

---

## Ejercicio 9: Visualización de Datos Temporales con Análisis Estadístico 🔄
### Objetivo:
Trabajar con series temporales y calcular estadísticas.

1. Genera una serie temporal de 200 días con valores aleatorios.
2. Calcula la media y la desviación estándar de la serie temporal.
3. Visualiza la serie junto con las bandas de desviación estándar (es decir, la media ± 1 desviación estándar).

---

¡Buena suerte con los ejercicios! 🚀🧠 Si completas todos estos desafíos, estarás más que preparado para aplicar `Matplotlib` y `Seaborn` en proyectos de análisis de datos.