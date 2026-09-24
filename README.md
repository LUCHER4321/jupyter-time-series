# Proyecto de Series Temporales y Forecasting

Este repositorio contiene un conjunto de prácticas, laboratorios y un proyecto final centrados en el análisis y pronóstico de series temporales (Time Series Forecasting) utilizando Python y Jupyter Notebook.

## Estructura del Proyecto

El repositorio está compuesto por los siguientes archivos y conjuntos de datos:

### Notebooks de Jupyter

- **`Proyecto_Series_Temporales.ipynb`**: Notebook principal del proyecto final donde se desarrolla el análisis completo y el modelado predictivo de las series de tiempo.
- **`Laboratorio_04_Series_Temporales.ipynb`**: Ejercicios prácticos y de laboratorio enfocados en la manipulación, visualización y análisis exploratorio de series temporales.
- **`Control_Técnico_3_Series_temporales_y_forecasting.ipynb`**: Evaluación o control técnico que abarca conceptos clave de modelado y forecasting.

### Conjuntos de Datos (Datasets)

- **`ventas_mensuales.csv`**: Dataset original que contiene los registros de ventas agrupados por meses.
- **`month_sells_clean.csv`**: Versión limpia y preprocesada del dataset de ventas, lista para ser consumida por los modelos de machine learning y estadística.

### Otros Archivos

- **`.gitignore`**: Archivo de configuración para omitir archivos no deseados en el control de versiones de Git (como entornos virtuales, archivos temporales de Jupyter, etc.).

## Tecnologías y Librerías Utilizadas

Para ejecutar los notebooks de este proyecto, se recomienda tener instaladas las siguientes librerías de Python (comunes en análisis de series temporales):

- [Python 3.x](https://www.python.org/)
- [Jupyter Notebook](https://jupyter.org/) o JupyterLab
- [Pandas](https://pandas.pydata.org/) (Manipulación de datos)
- [NumPy](https://numpy.org/) (Cálculos numéricos)
- [Matplotlib](https://matplotlib.org/) / [Seaborn](https://seaborn.pydata.org/) (Visualización de datos)
- [Statsmodels](https://www.statsmodels.org/) (Modelos estadísticos como ARIMA, SARIMA, etc.)
- [Scikit-Learn](https://scikit-learn.org/) (Métricas de evaluación y machine learning)

## Cómo ejecutar el proyecto

1. **Clonar el repositorio:**

   ```bash
   git clone https://github.com/LUCHER4321/jupyter-time-series/tree/project
   cd jupyter-time-series-project
   ```

2. **Crear un entorno virtual (Opcional pero recomendado):**

   ```bash
   python -m venv env
   source env/bin/activate  # En Linux/Mac
   env\Scripts\activate     # En Windows
   ```

3. **Iniciar Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

4. Abre cualquiera de los archivos `.ipynb` en tu navegador para ver el código, los gráficos generados y las explicaciones.

## Notas Adicionales

- Asegúrate de que los archivos `.csv` se encuentren en el mismo directorio que los notebooks (o ajusta las rutas de lectura en el código con `pd.read_csv()`) para evitar errores de archivo no encontrado.
