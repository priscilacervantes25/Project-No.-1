# Fashion MNIST

## Project_No.-1


## 📝 Descripción del Proyecto

El objetivo de este proyecto es clasificar artículos de moda utilizando el dataset Fashion-MNIST mediante diferentes algoritmos de Machine Learning y Deep Learning.

Se busca comparar el desempeño de modelos tradicionales (Logistic Regression, SVM, Random Forest) con redes neuronales (MLP en scikit-learn y CNN en TensorFlow/PyTorch) y analizar su capacidad de generalización frente a imágenes reales tomadas por el equipo.

### ¿Qué es Fashion MINST?

Fashion-MNIST es un conjunto de datos de imágenes de artículos de Zalando, compuesto por un conjunto de entrenamiento de 60,000 ejemplos y un conjunto de prueba de 10,000 ejemplos.
Cada ejemplo es una imagen en escala de grises de 28 x 28, asociada a una etiqueta de 10 clases.

Zalando pretende que Fashion-MNIST sirva como sustituto directo del conjunto de datos MNIST original para la evaluación comparativa de algoritmos de aprendizaje automático. Comparte el mismo tamaño de imagen y la misma estructura de divisiones de entrenamiento y prueba.


---

## 📂 Estructura del Proyecto

├── Project1.ipynb         # Notebook con el desarrollo completo

├── README.md              # Documento de explicación y resultados

└── .gitignore              


---

## 📊 Resultados y evaluación de modelos

| Modelo | Accuracy | F1-Score |
|------------|-------|-------|
| Regresión logística|0.8472|0.8461|  
| SVM                |0.8993|0.8987|
| Random Forest      |0.8651|0.8627|
| Redes Neuronales   |0.8740|0.8744|
| CNN                |0.9019|0.9012|


## 📌 Conclusiones
Dado que el dataset se encuentra balanceado, tanto la exactitud como el F1-Score son métricas adecuadas para evaluar el desempeño de los modelos. Los resultados muestran que la CNN obtuvo el mejor rendimiento (Accuracy = 0.9019, F1 = 0.9012).

En conclusión CNN destacó como el modelo más robusto.