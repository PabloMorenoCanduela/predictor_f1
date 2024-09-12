# Predictor posición de formula 1

# 📊 Predictor de la Posición de Fernando Alonso en la Fórmula 1 🏎️

## Descripción del Proyecto

Este proyecto tiene como objetivo predecir la posición final de Fernando Alonso en la clasificación de la Fórmula 1 al final de la temporada. Utilizando datos históricos de sus resultados en carreras desde 2001 y simulando las carreras restantes, se crea un modelo que proyecta su posible rendimiento en las carreras que faltan por disputarse.

Este proyecto es un excelente ejemplo de cómo los datos históricos y las simulaciones pueden utilizarse para generar predicciones precisas dentro del ámbito deportivo.

## ¿Qué se utiliza?

- **Dataset**: Los datos históricos de carreras de Fórmula 1 fueron obtenidos de [Kaggle](https://www.kaggle.com/datasets/rohanrao/formula-1-world-championship-1950-2020?select=circuits.csv).
- **Lenguajes**: Python.
- **Librerías principales**:
  - `pandas`: Para manipulación y análisis de datos.
  - `matplotlib` y `seaborn`: Para visualización de datos.
  - `scikit-learn`: Para la creación y evaluación del modelo predictivo.
  
## Estructura del Proyecto

1. **Obtención de Datos**: Los datos de todas las carreras de Fernando Alonso se recogen y procesan.
2. **Análisis Exploratorio de Datos (EDA)**: Visualizamos y analizamos los datos para identificar tendencias clave en el rendimiento del piloto.
3. **Simulación de Carreras Faltantes**: Utilizando los datos históricos, simulamos las carreras restantes para predecir la posición final de Alonso en la temporada.
4. **Modelo Predictivo**: Aplicamos diversas técnicas de **machine learning** para realizar predicciones basadas en datos históricos. 

## ¿Cómo ejecutar el proyecto?

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/PabloMorenoCanduela/predictor_f1.git

2. Instalar las dependencias:
   ```bash
    pip install -r requirements.txt

3. Ejecutar el archivo Jupyter Notebook (ElNano33_final.ipynb) para ver el análisis completo y los resultados de la predicción.





