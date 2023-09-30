# Neurona_LSTM_prediccion_demanda_energia_COES

Modelo LSTM para predecir la demanda de energía

Este código implementa un modelo LSTM para predecir la demanda de energía en Perú. El modelo se entrena en un conjunto de datos de 8 años de datos de demanda de energía, desde 2015 hasta 2023. El conjunto de datos se divide en un conjunto de entrenamiento y un conjunto de prueba. El modelo se entrena en el conjunto de entrenamiento y se evalúa en el conjunto de prueba.

Requisitos

Python 3.8 o superior
TensorFlow 2.8 o superior
NumPy
Pandas
Instalación

pip install -r requirements.txt
Uso

python main.py
Este comando entrenará el modelo y evaluará su rendimiento en el conjunto de prueba. El modelo se guardará en el directorio model5/.

Resultados

El modelo obtuvo un error cuadrático medio (RMSE) de 0,0258 en el conjunto de prueba. Esto significa que el modelo predice la demanda de energía con un error promedio de 25,8 kW.
![image](https://github.com/Barbathoss/Neurona_LSTM_prediccion_demanda_energia_COES/assets/81935896/f5ca3382-93c0-45e8-a00c-540dd3f1f998)

Mejoras potenciales

El modelo se puede mejorar de varias maneras, incluyendo:

Usar una arquitectura de LSTM más compleja
Usar un conjunto de datos más grande
Utilizar un conjunto de datos de validación para monitorizar el rendimiento del modelo durante el entrenamiento
