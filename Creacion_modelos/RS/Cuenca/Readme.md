# Modelado de la radiación solar
1. [Análisis de la serie temporal:](UDLA3.ipynb) Se analiza la radiación solar como serie temporal. Se observa su estacionariedad y estacionalidad.
3. [Creación de un modelo AR de referencia:](Udla_6.ipynb) Se crea un modelo autorregresivo para compararlo con el modelo LSTM.
4. [Creación de un modelo LSTM univariado:](Udla9.ipynb) Se crea un modelo LSTM utilizando sólo la radiación solar.
5. [Análisis del error al extender la ventana de predicción:](Udla9_5.ipynb) Se utiliza el mejor modelo univariado para predecir más de una hora hacia el futuro.
6. [Feature selección para otras variables:](Udla10.ipynb) Se utiliza Random Forest para determinar otras variables que puedan ayudar al modelo univariado.
7. [Creación de un modelo LSTM multivariado:](Udla11.ipynb) Se utilizan las variables seleccionadas para crear un modelo LSTM multivariado.
8. [Gráfico interactivo de resultados:](./Udla17.ipynb) Se utilizan los mejores modelos obtenidos para predecir el conjunto de test y comparar sus resultados.