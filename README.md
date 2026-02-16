# 📊 TelecomX: Análisis de Fuga de Clientes (Churn)

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Libraries](https://img.shields.io/badge/Library-Pandas%20%7C%20Seaborn%20%7C%20Matplotlib-orange)
![Status](https://img.shields.io/badge/Status-Completado-green)

> **Autor: Niko Vidovic. Proyecto realizado para el programa Alura ONE - Grupo 9 (G9).**


## 📖 Descripción del Proyecto

Este proyecto tiene como objetivo analizar el comportamiento de los clientes de la empresa de telecomunicaciones **TelecomX** para identificar las causas principales de la **tasa de abandono (Churn)**. 

A través de un análisis exploratorio de datos (EDA) y técnicas de visualización avanzada, buscamos responder preguntas clave: ¿Por qué se van los clientes? ¿Cuándo se van? ¿Qué factores económicos o de servicio influyen en su decisión?¿Cuales son sus caracteristicas?

## 🎯 Objetivos

1.  **Limpieza de Datos:** Transformar datos crudos, manejar valores nulos y estandarizar tipos de datos.
2.  **Análisis Exploratorio (EDA):** Identificar patrones en variables demográficas y de servicio.
3.  **Visualización de Impacto:** Crear gráficos que comuniquen claramente la "historia" detrás de la fuga.
4.  **Estrategia de Retención:** Proponer acciones de negocio basadas en datos.

## 🛠️ Tecnologías Utilizadas

* **Python:** Lenguaje principal.
* **Pandas:** Manipulación y limpieza de datos (ETL).
* **Matplotlib & Seaborn:** Visualización de datos estática y estadística (KDE plots, Heatmaps).
* **NumPy:** Cálculos numéricos.

## 🔍 Hallazgos Clave (Insights)

Tras analizar el dataset, llegamos a 3 conclusiones críticas:

### 1. Muerte temprana
Descubrimos un patrón de mortalidad temprana. La gran mayoría de las fugas ocurren en los primeros meses de contrato. Si el cliente supera este umbral, la probabilidad de fidelización aumenta drásticamente.

### 2. El Riesgo del Contrato Mensual 📅
El análisis de densidad (KDE) mostró que los usuarios con contrato **mensual** son extremadamente volátiles, mientras que los contratos de 1 y 2 años muestran una estabilidad casi total.

### 3. Sensibilidad al Precio y Fibra Óptica 💸
Existe una correlación directa entre **cargos mensuales altos** y la fuga. Específicamente, los usuarios de **Fibra Óptica** (el servicio más caro) son los que más abandonan, lo que sugiere una insatisfacción con la relación calidad-precio.

## 📈 Visualizaciones Destacadas

*El proyecto incluye visualizaciones avanzadas como:*

* **Matriz de Correlación:** Para medir el impacto numérico de cada variable en el Churn.
* **Gráficos de Densidad (KDE):** Para visualizar la probabilidad de fuga a lo largo del tiempo según el contrato.
* **Mapas de Riesgo (Scatter Plots):** Relacionando Valor Mensual vs. Antigüedad.

## 🚀 Recomendaciones de Negocio

Basado en la data, se sugieren las siguientes estrategias:

1.  **Programa de Onboarding Intensivo:** Crear un plan de acompañamiento durante los primeros 90 días para reducir la "mortalidad temprana".
2.  **Migración de Contratos:** Incentivar a los usuarios mensuales a pasar a contratos anuales mediante descuentos estratégicos.
3.  **Auditoría de Fibra Óptica:** Revisar la calidad técnica y el precio del servicio de Fibra para reducir la fuga en el segmento de alto valor.

