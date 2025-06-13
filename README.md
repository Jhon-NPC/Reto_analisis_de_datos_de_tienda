# 📊 Análisis del desempeño de las tiendas - Alura Store

Este proyecto tiene como objetivo ayudar al Sr. Juan, dueño de la cadena **Alura Store**, a tomar una decisión estratégica sobre cuál de sus cuatro tiendas debería vender para destinar los recursos a un nuevo emprendimiento.

Se analizaron múltiples factores clave del rendimiento de cada tienda usando Python y herramientas de visualización de datos como **Pandas**, **Matplotlib** y **Seaborn**.

## 📌 Objetivo

Identificar cuál de las tiendas de Alura Store presenta el **menor desempeño general**, considerando criterios financieros, operativos y de satisfacción del cliente. 

## 📁 Archivos del proyecto

- `ChallengeDataScienceStore.ipynb` → Notebook con análisis, visualizaciones y conclusiones  
- `README.md` → Este documento explicativo
- `Carpeta Graficos` → Contiene las imágenes generadas por el análisis.

## 🧪 Tecnologías utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-2E86C1?style=for-the-badge&logo=seaborn&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=black)

## 🚀 Cómo ejecutar el proyecto en Google Colab

### 🔗 1: Abrir directamente desde GitHub

Haz clic en el siguiente botón para abrir el notebook directamente en Google Colab:

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Jhon-NPC/Reto_analisis_de_datos_de_tienda/blob/main/ChallengeDataScienceStore.ipynb)

### 🧭 Opción 2: Subir manualmente el archivo a Google Colab

1. Accede a [Google Colab](https://colab.research.google.com/)
2. En el menú superior, selecciona **Archivo > Subir notebook**
3. Descarga el archivo `ChallengeDataScienceStore.ipynb` que se encuentra en este repositorio.
4. Busca y selecciona el archivo `ChallengeDataScienceStore.ipynb` que has descargado previamente
5. El notebook se abrirá y estará listo para ejecutarse en la nube

## 🔍 Criterios de análisis

1. **Facturación total**  
2. **Ventas por categoría**  
3. **Calificación promedio de clientes**  
4. **Producto menos vendido**  
5. **Costo promedio de envío**

## 📈 Resultados por criterio

### 1. Facturación total

El primer aspecto evaluado es la facturación total de cada tienda. A través del tratamiento de datos con Python, se obtuvieron los siguientes resultados:

![Gráfico0](https://github.com/Jhon-NPC/Reto_analisis_de_datos_de_tienda/blob/main/Graficos/grafico0.png)
![Gráfico1](https://github.com/Jhon-NPC/Reto_analisis_de_datos_de_tienda/blob/main/Graficos/grafico1.png)

| Tienda   | Ingresos Totales        |
|----------|--------------------------|
| Tienda 1 | $1,150,880,400.00        |
| Tienda 2 | $1,116,343,500.00        |
| Tienda 3 | $1,098,019,600.00        |
| **Tienda 4** | **$1,038,375,700.00** |

📉 La **Tienda 4** presenta la facturación más baja, lo cual representa una señal clara de bajo rendimiento. La diferencia respecto a la tienda líder, Tienda 1, es de **$112,504,700.00**, una brecha significativa que refuerza la necesidad de evaluación.

### 2. Ventas por categoría

A continuación, se analizaron las ventas por categoría para cada tienda, destacando aquellas con menor desempeño:

![Gráfico2](https://github.com/Jhon-NPC/Reto_analisis_de_datos_de_tienda/blob/main/Graficos/grafico2.png)  
![Gráfico3](https://github.com/Jhon-NPC/Reto_analisis_de_datos_de_tienda/blob/main/Graficos/grafico3.png) 

**Tienda 1**:
- Artículos para el hogar: \$12,698,400.00 (171 productos vendidos)  
- Libros: \$8,784,900.00 (173 productos vendidos)

**Tienda 2**:
- Juguetes: \$15,945,400.00 (313 productos vendidos)  
- Muebles: \$176,426,300.00 (442 productos vendidos)

**Tienda 4**:
- Electrodomésticos: \$283,260,200.00 (254 productos vendidos)  
- Electrónicos: \$409,476,100.00 (451 productos vendidos)  
- Deportes y diversión: \$33,350,100.00 (277 productos vendidos)  
- Instrumentos musicales: \$75,102,400.00 (170 productos vendidos)

🔎 Se evidencia que la **Tienda 4** tiene el peor desempeño en 4 de las 8 categorías clave, lo que refuerza su debilidad en volumen de ventas.

### 3. Calificación promedio de clientes

El siguiente punto es la valoración promedio otorgada por los clientes:

![Gráfico4](https://github.com/Jhon-NPC/Reto_analisis_de_datos_de_tienda/blob/main/Graficos/grafico4.png)

| Tienda   | Calificación Promedio |
|----------|------------------------|
| Tienda 1 | 3.977                  |
| Tienda 2 | 4.037                  |
| Tienda 3 | 4.048                  |
| **Tienda 4** | **3.996**          |

📉 Si bien la calificación de la **Tienda 4** no es la más baja, se encuentra por debajo del promedio general, lo que sugiere una experiencia de cliente ligeramente más débil respecto a sus competidoras.

### 4. Producto más y menos vendido

En cuanto a los productos menos vendidos, la **Tienda 4** reporta como producto con menor venta a la "Guitarra eléctrica", perteneciente a la categoría de **instrumentos musicales**, una categoría que ya refleja un bajo rendimiento en esta tienda.

![Gráfico5](https://github.com/Jhon-NPC/Reto_analisis_de_datos_de_tienda/blob/main/Graficos/grafico5.png)

### 5. Costo promedio de envío

Finalmente, se compararon los costos promedio de envío:

![Gráfico6](https://github.com/Jhon-NPC/Reto_analisis_de_datos_de_tienda/blob/main/Graficos/grafico6.png)

| Tienda   | Costo Promedio Envío |
|----------|------------------------|
| Tienda 1 | $26,018.61             |
| Tienda 2 | $25,216.24             |
| Tienda 3 | $24,805.68             |
| **Tienda 4** | **$23,459.46**     |

⭕ La **Tienda 4** destaca por tener el costo de envío más bajo, lo que podría interpretarse como una ventaja logística. Sin embargo, esta fortaleza no compensa el resto de sus debilidades en facturación, ventas por categoría y calificación.

## ✅ Conclusión y recomendación

Con base en el análisis integral de los cinco criterios evaluados, se concluye que la **Tienda 4 presenta el menor desempeño general** dentro de la cadena Alura Store.

### 📌 Recomendación

**Se recomienda considerar el cierre y posterior venta de la Tienda 4, destinando los recursos obtenidos al inicio de un nuevo emprendimiento.**
