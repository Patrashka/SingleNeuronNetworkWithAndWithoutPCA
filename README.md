# SingleNeuronNetworkWithAndWithoutPCA
Proyecto de Deep Learning en Google Colab que compara una red neuronal base frente a una optimizada con PCA (95% varianza). Logra un 97% de precisión analizando métricas médicas críticas (Recall y Especificidad) y eficiencia de datos.

# Tarea 4 - Single Neuron Network con y sin PCA
Este repositorio contiene el notebook utilizado para resolver la actividad de la materia *Artificial Intelligence II*.  
El objetivo del trabajo es entrenar y evaluar un modelo de *una sola neurona (single-neuron network)* para clasificar tumores de mama como benignos o malignos, y comparar su desempeño *con y sin reducción de dimensionalidad usando PCA*.

# Dataset
El dataset utilizado es *Breast Cancer Wisconsin Diagnostic*.
Fuente oficial:  
https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

Para usar el dataset:
1. Descargar el archivo ZIP desde el enlace anterior.
2. Extraer el archivo.
3. Localizar el archivo:

wdbc.data
Este archivo es el que se utiliza en el notebook.

---

# Cómo ejecutar el notebook
1. Abrir el notebook en *Google Colab*.
2. Subir el archivo del dataset al entorno de Colab:
   - En el panel izquierdo seleccionar *Files*
   - Presionar *Upload*
   - Subir el archivo wdbc.data
3. Una vez cargado el archivo, ejecutar el notebook completo.
   
En Colab seleccionar:
Runtime → Run all

El notebook ejecutará automáticamente todas las celdas y generará:
- análisis exploratorio del dataset (EDA)
- entrenamiento del modelo de una neurona
- evaluación del modelo
- aplicación de PCA
- comparación entre el modelo original y el modelo con PCA
