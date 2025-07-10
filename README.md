# 🚕 Predicción de la demanda de taxis por hora

Este proyecto busca predecir la cantidad de pedidos de taxi para la siguiente hora, usando técnicas de regresión y series temporales. Está basado en el caso de negocio ficticio **Sweet Lift Taxi**, con el objetivo de ayudar a optimizar la disponibilidad de unidades durante horas pico.

## 🎯 Objetivo

Construir modelos de regresión que logren una métrica **RMSE menor o igual a 48** en el conjunto de prueba, para anticipar la demanda por hora de taxis.

## ⚙️ Tecnologías utilizadas

- Python 3
- pandas, numpy
- matplotlib, seaborn
- scikit-learn
- CatBoost, LightGBM
- Jupyter Notebook
- datetime (para ingeniería de variables temporales)

## 🧠 Modelos evaluados

- Regresión lineal
- Árboles de decisión
- Random Forest
- Gradient Boosting (CatBoost, LightGBM)

## 🛠️ Ingeniería de características

- Extracción de hora, día, día de la semana
- Variables categóricas (hora codificada)
- Eliminación de outliers

## 📁 Estructura del repositorio
taxi-demand-prediction/

├── Proyecto_15.ipynb

├── README.md

├── requirements.txt

⚠️ **Nota sobre los datos:**  
El dataset no está incluido en el repositorio por razones de tamaño, pero todas las transformaciones y pasos están desarrollados completamente en el notebook.

📊 Resultados
Se logró un RMSE por debajo del umbral establecido, cumpliendo con los requerimientos del proyecto. Se probaron múltiples modelos, evaluando no solo la precisión sino también la velocidad.

✍️ Autor
Jorge Elian Mendoza Pujol
📧 jelianmpujol@gmail.com

🔗 [LinkedIn](www.linkedin.com/in/jorge-elian-mendoza-pujol-359500283)  

