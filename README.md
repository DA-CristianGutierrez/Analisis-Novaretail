# Analisis-NovaRetail+

Este repositorio contiene el análisis de correlación realizado a la empresa NovaRetail+

El dataset `everpeak_retail` incluye 15.000 registros de compras de clientes, el cual incluye valores numéricos, binarios y categóricos.

## 📂 Contenido del repositorio

- `S8 Student Version-Project-NovaRetail.ipynb` 
  → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DA-CristianGutierrez/Analisis-Novaretail/blob/main/S8%20Student%20Version-Project-NovaRetail.ipynb)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `S8 Student Version-Project-NovaRetail.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Objetivo del análisis

Generar un reporte de análisis de correlación claro, responsable y accionable, que permita entender qué comportamientos del cliente están más fuertemente asociados con el ingreso generado, sin caer en interpretaciones causales incorrectas.

## Análisis de correlación no causal

En este proyecto analicé la existencia e intensidad de correlaciones entre distintas variables de comportamiento de usuario, en una plataforma de comercio electrónico con presencia en Latinoamérica. Empecé con una matriz de correlación general entre variables para luego entrar a detalle en una revisión de las correlaciones más fuertes. En base a esto, determiné que variables se activan más y en cuales podría haber una clave más útil que apunte al objetivo. 


## 🛠️ Herramientas y analisis aplicado:

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=seaborn&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

análisis correlacional (exploratorio) no causal.


## Metodología

- Procesamiento de datos: Se exploraron los datos para determinar tipos de variables y si se requería limpieza de estos.
- Separación de variables: Se determinaron variables del mismo y distinto tipo para aplicar la prueba que tuviera compatibilidad en cada correlación.
- Reporte profesional de correlación: Se entregó el resultado con los aspectos clave del tipo de analisis; supuestos previamente definidos, valor del coeficiente, aclaración, implicación de negocio.


## Visualizaciones destacadas

1. Matriz de correlación: Gracias al mapa de calor, el cual corresponde a cada valor de coeficiente, identificamos rapidamente dos clusters de variables las cuales se mueven juntas, una en el centro de la matriz y la otra en la parte inferior o derecha de la imagen. Esto indica que los colores mas diferenciados apuntan a una actividad más intensa y por lo tanto, variables a tener en cuenta.  

<img width="678" height="599" alt="image" src="https://github.com/user-attachments/assets/80d72e3e-14b9-466e-9ae6-355818ab0d8c" />

----------------------------------------------------------------------------------------------------------------------------------------


2. Correlación destacada compras_mes / ingreso_anual: Esta relación entre cantidad de compras registradas e ingreso anual muestra un patrón ordenado (tiene a aumentar) en la visualización de los datos.

<img width="571" height="432" alt="image" src="https://github.com/user-attachments/assets/136efc3c-d32e-4a9c-b2f6-60df9c1bbec6" />

----------------------------------------------------------------------------------------------------------------------------------------


3. Correlación destacada visitas_mes / ingreso: Esta relación entre la cantidad de visitas a la plataforma y los ingresos generados muestra una dispersión regular en los datos.

<img width="571" height="433" alt="image" src="https://github.com/user-attachments/assets/1aa40de9-d503-48e3-8143-eb575196f29b" />


## Conclusiones y recomendaciones
Correlaciones destacadas: Las variables que mejor se asocian con el ingreso anual son compras_mes y visitas_mes.

Acciones recomendadas:

- Determinar si los clientes pueden perderse en alguna etapa de compra. También se puede evaluar si realmente no encuentran lo que están buscando.
