# Detección de fraudes usando autoencoders

Código fuente de [este](https://youtu.be/aLcDJoG0pec) video, en donde se muestra cómo detectar transacciones fraudulentas en tarjetas débito y crédito usando un autoencoder.

El set de datos se puede descargar en [este enlace](https://www.kaggle.com/mlg-ulb/creditcardfraud/downloads/creditcardfraud.zip/3) y contiene 284,315 registros con transacciones normales y 492 fraudulentas. Una vez entrenado el autoencoder se logrará un recall igual a 0.92.

Este código está basado en el post de [David Ellison](https://www.datascience.com/blog/fraud-detection-with-tensorflow)

## Dependencias
matplotlib==2.0.0
numpy==1.15.4
pandas==0.19.2
Keras==2.2.4
seaborn==0.9.0
scikit_learn==0.21.0