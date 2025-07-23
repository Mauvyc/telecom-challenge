# TelecomX LATAM Churn Analysis

## Descripción del proyecto
Este repositorio contiene el análisis exploratorio de datos (EDA) y tratamiento de datos del conjunto de clientes de TelecomX LATAM, con el objetivo de identificar patrones asociados a la evasión de clientes (churn) y generar insights que permitan diseñar estrategias de retención.

## Estructura del repositorio
├── data/
│ └── telecomx-latam.pdf # Descripción del dataset y licencia
├── notebooks/
│ └── churn_analysis.ipynb # Notebook con limpieza, análisis y visualizaciones
├── README.md # Este archivo
└── requirements.txt # Dependencias de Python

## Contenido del Notebook
- **Introducción**: Objetivo del análisis y descripción del problema de churn.
- **Limpieza y Tratamiento de Datos**: Pasos de carga, normalización, conversión de tipos y manejo de valores faltantes.
- **Análisis Exploratorio de Datos**:
  - Distribución general de churn.
  - Recuento de churn por variables categóricas y numéricas.
  - Gráficos (barplots, boxplots, histogramas, violin plots).
- **Análisis de Correlación (Opcional)**: Matriz de correlaciones y variables derivadas (gasto diario, número de servicios).
- **Conclusiones e Insights**: Principales hallazgos del análisis.
- **Recomendaciones**: Sugerencias estratégicas para reducir churn.

## Requisitos y dependencias
Se recomienda crear un entorno virtual con Python 3.8 o superior. Instala las dependencias con:

```bash
pip install -r requirements.txt
