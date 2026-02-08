# Preparación de Datos – Módulo 4  
## (Español)

## Descripción del proyecto

Este proyecto corresponde al desarrollo de un flujo completo de preparación de datos, que abarca desde la generación e integración de múltiples fuentes hasta la obtención de un dataset final limpio, estructurado y listo para análisis.

El trabajo fue desarrollado como parte del **Módulo 4 – Preparación de Datos**, y tiene como objetivo aplicar buenas prácticas de limpieza, transformación y organización de datos utilizando Python.

---

## Objetivo

El objetivo del proyecto es construir un dataset confiable y reutilizable a partir de datos con problemas de calidad, aplicando técnicas de imputación, detección de outliers y *data wrangling*, de manera reproducible y documentada.

---

## Justificación del uso de NumPy y Pandas

- **NumPy** se utilizó para la generación de datos ficticios reproducibles y para la ejecución de operaciones numéricas eficientes sobre arreglos.
- **Pandas** se empleó como herramienta principal para el manejo de datos tabulares, permitiendo realizar procesos de limpieza, transformación, categorización y análisis mediante agrupamientos.

Estas librerías constituyen el estándar del ecosistema Python para la preparación y análisis de datos.

---

## Descripción del dataset y fuentes de datos

El proyecto trabaja con un dataset ficticio de clientes y transacciones, generado de forma controlada para simular un escenario realista de comercio electrónico.

Adicionalmente, se incorporó información externa de referencia obtenida desde fuentes oficiales, la cual fue integrada al flujo de trabajo con fines ilustrativos y de enriquecimiento del análisis.

La generación de los datos se realizó utilizando una semilla fija, garantizando la reproducibilidad del proceso.

---

## Técnicas de limpieza y transformación aplicadas

Durante el desarrollo del proyecto se aplicaron las siguientes técnicas:

- Identificación y tratamiento de valores nulos mediante imputación.
- Detección y tratamiento de valores atípicos utilizando el criterio del rango intercuartílico (IQR).
- Creación de variables derivadas relevantes para el análisis.
- Categorización de clientes según niveles de compras y gasto.
- Agrupamientos y generación de tablas resumen por segmento.

---

## Principales decisiones y desafíos

Entre las principales decisiones del proyecto se encuentra la elección de criterios estadísticos estándar para el tratamiento de outliers, priorizando la conservación de la mayor cantidad de información posible.

Uno de los principales desafíos fue equilibrar la limpieza de los datos con la preservación de registros relevantes, evitando la eliminación innecesaria de observaciones.

---

## Resultados y estado final del dataset

Como resultado del proceso, se obtuvo un dataset final limpio, estructurado y enriquecido, exportado en formatos **CSV** y **Excel**, listo para su uso en análisis descriptivos, visualización o modelado de datos.

Asimismo, se generaron tablas resumen que permiten analizar el comportamiento de los clientes según distintos criterios.

---

## Archivos principales del repositorio

- `preparacion_datos_modulo_4.ipynb`: Notebook con el desarrollo completo del proyecto.
- `clientes_final_wrangle.csv`: Dataset final limpio y estructurado.
- `clientes_final_wrangle.xlsx`: Dataset final en formato Excel.

---

## Tecnologías utilizadas

- Python  
- NumPy  
- Pandas  
- Jupyter Notebook  

---

# Data Preparation – Module 4  
## (English)

## Project Overview

This project presents a complete data preparation workflow, covering the generation and integration of multiple data sources and resulting in a clean, structured dataset ready for analysis.

The work was developed as part of **Module 4 – Data Preparation**, focusing on the application of best practices for data cleaning, transformation, and organization using Python.

---

## Objective

The main objective of this project is to build a reliable and reusable dataset from data with quality issues, applying imputation techniques, outlier detection, and data wrangling in a documented and reproducible manner.

---

## Why NumPy and Pandas?

- **NumPy** was used to generate reproducible synthetic data and to perform efficient numerical operations on arrays.
- **Pandas** was used as the primary tool for handling tabular data, enabling cleaning, transformation, categorization, and aggregation processes.

These libraries are considered the standard tools in the Python ecosystem for data preparation and analysis.

---

## Dataset Description and Data Sources

The project uses a synthetic dataset of customers and transactions, generated in a controlled manner to simulate a realistic e-commerce scenario.

Additionally, external reference data obtained from official sources was integrated into the workflow to enrich the analysis.

All data generation processes were executed using a fixed random seed to ensure reproducibility.

---

## Data Cleaning and Transformation Techniques

The following techniques were applied during the project:

- Identification and treatment of missing values through imputation.
- Detection and handling of outliers using the Interquartile Range (IQR) method.
- Creation of derived variables relevant for analysis.
- Customer categorization based on purchase and spending levels.
- Aggregations and generation of summary tables by segment.

---

## Key Decisions and Challenges

One of the main decisions involved selecting standard statistical criteria for outlier treatment while preserving as much relevant information as possible.

A key challenge was balancing data cleaning efforts with the need to avoid unnecessary data loss.

---

## Results and Final Dataset Status

The final outcome of the project is a clean and enriched dataset, exported in **CSV** and **Excel** formats, ready for use in descriptive analysis, visualization, or data modeling tasks.

Summary tables were also generated to support exploratory analysis of customer behavior.

---

## Main Repository Files

- `preparacion_datos_modulo_4.ipynb`: Notebook containing the full project development.
- `clientes_final_wrangle.csv`: Final cleaned and structured dataset.
- `clientes_final_wrangle.xlsx`: Final dataset in Excel format.

---

## Technologies Used

- Python  
- NumPy  
- Pandas  
- Jupyter Notebook  
