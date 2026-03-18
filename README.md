# ETL - Análisis ECOBICI 2012 (CDMX)

## Descripción
Pipeline ETL sobre datos abiertos de ECOBICI 2012. Incluye limpieza, transformación con PySpark, consultas SQL y visualizaciones de patrones de uso: horas pico, demanda por estación, comportamiento por género y edad.

## Stack tecnológico
Python | PySpark | SQL | Jupyter Notebook | Matplotlib | HDFS

## Estructura del pipeline
1. Extracción de CSVs desde clúster HDFS (previamente descargados al clúster de HADOOP mediante CURL -L)
2. Normalización y limpieza de datos
3. Segmentación en DataFrames especializados
4. Consultas analíticas (SQL y API DataFrame)
5. Visualizaciones

## Hallazgos principales
- Top 10 estaciones con mayor demanda 
- Horas pico: 8-9h, 14-15h, 18-19h
- Hábitos de uso por edad y género y comparativa entre los mismos
