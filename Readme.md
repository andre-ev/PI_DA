# Análisis de Siniestros Viales en Buenos Aires

Este proyecto tiene como objetivo analizar los siniestros viales en la Ciudad Autónoma de Buenos Aires, identificar patrones y tendencias en los accidentes y sus víctimas, y proporcionar insights que puedan ayudar en la prevención de futuros siniestros.

## Índice

- [Introducción](#introducción)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Datasets](#datasets)
- [Notebooks](#notebooks)
- [KPIs](#kpis)


## Introducción

El análisis de los siniestros viales es un componente crítico en la elaboración de políticas de seguridad vial. Este proyecto utiliza data histórica de siniestros viales para extraer insights y sugerir medidas que podrían mejorar la seguridad vial en Buenos Aires.

## Estructura del Proyecto

El repositorio está organizado en las siguientes carpetas y archivos principales:

- `Datasets`: Contiene los datasets utilizados en el análisis.
- `Notebooks`: Incluye los Jupyter Notebooks que contienen el análisis exploratorio de datos (EDA) y el proceso de transformación de los datos (ETL).
- `KPIs`: Archivos CSV con los indicadores clave de rendimiento para evaluar los siniestros viales.
- `README.md`: Este archivo, que proporciona una descripción general del proyecto.

## Datasets

Los datasets utilizados en este proyecto son:

- `c2022_caba_est_c1.xlsx`: Datos estadísticos de la población de CABA.
- `homicidios_hechos.csv`: Información sobre los hechos de siniestros viales.
- `homicidios_victimas.csv`: Datos sobre las víctimas de siniestros viales.

## Notebooks

El análisis se lleva a cabo en dos Jupyter Notebooks principales:

- `EDA.ipynb`: Análisis Exploratorio de Datos de los siniestros viales.
- `ETL.ipynb`: Proceso de Extracción, Transformación y Carga de los datos de siniestros viales.

## KPIs

Los KPIs clave para el análisis son:

- `kpi1.csv`: Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior.
- `kpi2.csv`: Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior.
