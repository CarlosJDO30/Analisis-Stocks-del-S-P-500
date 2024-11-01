# 📊 Análisis de Precios de Stocks del S&P 500 📈

![Python](https://img.shields.io/badge/Python-3.7%2B-blue?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Database-lightgrey?logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Visualization-yellow?logo=powerbi&logoColor=white)

## 📄 Descripción del Proyecto
Este proyecto tiene como objetivo analizar los precios de las acciones de las 500 empresas que componen el índice S&P 500, utilizando datos históricos almacenados en 505 archivos CSV. A través de este análisis, buscamos identificar tendencias y patrones en los precios de las acciones a lo largo del tiempo, proporcionando **insights** para decisiones informadas.

---

## 📂 Estructura del Proyecto

- **`/data`**  
  Contiene los archivos CSV con los datos históricos de los precios de las acciones de las empresas del S&P 500. Cada archivo representa los datos de una empresa específica.

- **`/notebooks`**  
  Incluye los Jupyter Notebooks utilizados para la exploración y análisis de datos. Aquí se documentan los procesos de limpieza, transformación y visualización inicial de los datos.

- **`/sql`**  
  Almacena los scripts y consultas SQL empleados en el proyecto para la creación y manipulación de las bases de datos.

- **`/reports`**  
  Esta carpeta contiene los informes y visualizaciones generados con Power BI, proporcionando representaciones visuales de los resultados del análisis.

- **`/src`**  
  Incluye los scripts en Python desarrollados para el procesamiento y análisis de datos. Aquí se alojan las funciones y procesos automatizados para manejar los datos de los CSV y realizar el análisis.

- **`README.md`**  
  La guía de referencia para el proyecto, que incluye una descripción general, instrucciones de instalación y pasos para la ejecución.

- **`requirements.txt`**  
  Archivo que especifica las librerías de Python necesarias para ejecutar el proyecto. Útil para configurar rápidamente el entorno de desarrollo.

---

## 📋 Requisitos Previos
Antes de comenzar, asegúrate de tener instalados los siguientes programas y librerías:

1. **Python** (Versión 3.7 o superior)
   - **Librerías de Python**: `pandas`, `matplotlib`, `seaborn`, `sqlalchemy`, `jupyter`
   - Puedes instalar las librerías ejecutando:
     ```bash
     pip install -r requirements.txt
     ```
2. **[Power BI](https://powerbi.microsoft.com/es-es/)**: Para la visualización de datos avanzada.
3. **SQL**: Se recomienda un gestor de bases de datos compatible con SQL, como [PostgreSQL](https://www.postgresql.org/) o [SQLite](https://www.sqlite.org/index.html).

--
