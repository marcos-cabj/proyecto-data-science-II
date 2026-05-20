# Análisis Predictivo y Machine Learning: Los Angeles Lakers (2014-2024) 🏀

Este proyecto es la Entrega Final para el curso de Data Science. 
Contiene un análisis exploratorio de datos (EDA) completo y la implementación de algoritmos de Machine Learning para predecir las victorias de Los Angeles Lakers en la NBA basándose en estadísticas de juego.

## Novedades de la Entrega Final:
Se modeló el caso como un problema de clasificación. Se realizó ingeniería de atributos (encoding, estandarización con StandardScaler) y se entrenaron modelos predictivos optimizando hiperparámetros mediante GridSearchCV. 
* **Modelos entrenados:** Random Forest Classifier y XGBoost.
* **Métricas:** Random Forest resultó el modelo ganador con un AUC-ROC de 0.86 y un 80% de Accuracy.
* **Explicabilidad:** Se utilizó la librería SHAP para identificar qué variables estadísticas (como el FG% y las Asistencias) tienen mayor impacto en las victorias del equipo.

## Archivos del repositorio:
* **`DataScienceII.ipynb`**: Notebook principal con el código en Python (extracción de la API, limpieza, EDA, entrenamiento de Machine Learning y conclusiones).
* **`lakers_10_temporadas.csv`**: Dataset crudo con el historial de los partidos de la última década (casi 1000 registros).

## Herramientas utilizadas:
Python, pandas, matplotlib, seaborn, scikit-learn, xgboost, shap, nba_api.
