# Tratamiento Inteligente de Datos

## Máster en Ingeniería Informática 19-20

### Teoría

* Trabajo y presentación sobre el **algoritmo Monte Carlo**.

### Prácticas

Preprocesamiento y análisis del dataset [**UCI ML Drug Review**](https://www.kaggle.com/jessicali9530/kuc-hackathon-winter-2018#drugsComTrain_raw.csv) aplicando los algoritmos vistos en clase, los cuales se detallan a continuación:

* Análisis exploratorio del conjunto de datos original.
* Preprocesamiento y reducción del conjunto general de datos hasta disponer de 5.000 instancias para cada conjunto.
  - Preprocesamiento de texto aplicado a las *reviews*.
  - Análisis de correlación e influencia de variables para quedarnos solo con los campos útiles.
* Análisis textual.
  - Nube de palabras.
  - Análisis de sentimientos general y específico a un conjunto de hasta 8 sentimientos.
* Reglas de asociación aplicadas a las *reviews*.
* Clasificación aplicada a predecir la enfermedad en función de la *review*.
  - Clasificación Bayesiana.
  - KNN.
  - Árboles de decisión.
  - Random Forest.
* Regresión lineal, logística y polinómica.
  - Aplicada a predecir la efectividad del medicamento en función de su puntuación.
  - Aplicada a predecir la efectividad del medicamento en función de la *review*.
* Agrupamiento y Clustering.
  - Agrupamiento de los fármacos en función de la puntuación de estos.
  - Agrupamiento de los fármacos en funcións de las *reviews* de los pacientes.