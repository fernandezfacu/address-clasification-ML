# adress-clasification-ML

Predicción sobre si una dirección IP es VPN o Proxy con modelos de Machine Learning. Proyecto para la materia Ciencia de Datos de la carrera de Ingeniería en Informática de la FIUBA, basado en una [competencia de Kaggle](https://www.kaggle.com/competitions/vpn-classification/overview).

El proyecto se divide en dos partes: 

- Análisis exploratorio de datos y visualizaciones sobre el dataset.
- Modelos de Machine Learning para la predicción (baseline con un perceptrón, modelo con un árbol de decisión y otro con LightGBM).

El trabajo fue de una gran dificultad debido a ser la primera experiencia en el campo de la ciencia de datos y particularmente en machine learning y las limitaciones de memoria al usar google colab para el desarrollo del proyecto en conjunto al enorme tamaño del dataset de la competencia de kaggle en la que se participó. Debido a esto el criterio de aprobación fue la obtención de un f1_score mayor a 0.6 (que no es el mejor, el ganador de la competencia obtuvo un 0.79962) en los dos modelos que no eran un perceptrón, pero las correcciones hicieron foco en la correcta construcción de los modelos, al tratamiento del dataset (en especial el feature engineering), la búsqueda de hiperparámetros, entre otros criterios.
