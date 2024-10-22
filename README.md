# Universidad de Guadalajara
## Centro Universitario de Ciencias Exactas e Ingenierías
### Ing. Biomédica
#### Materia: Métodos biomédicos de IA
 Profesor: Daniel Farfán

 ### Caso Práctico 3 - CNN: Segmentación de Imágenes con U-Net
 ##### Integrantes del equipo:
  * Héctor Manuel Godínez Lozano
  * José de Jesús González Hernández
  * Diana Romina Miranda Grijalva


Este proyecto está inspirado en el artículo [U-Net: Convolutional Networks for Biomedical Image Segmentation](https://www.nature.com/articles/s41592-019-0612-7). Nuestro objetivo es construir y entrenar un modelo U-Net para la segmentación de imágenes, específicamente para la segmentación de máscaras binarias en imágenes biomédicas.

## Objetivos

- **Construir un modelo U-Net**: Definir y compilar un modelo U-Net utilizando TensorFlow y Keras.
- **Entrenar el modelo**: Utilizar conjuntos de datos de entrenamiento y validación para entrenar el modelo.
- **Evaluar el rendimiento**: Evaluar el rendimiento del modelo en un conjunto de prueba.
- **Visualizar resultados**: Visualizar la arquitectura del modelo y el historial de entrenamiento.
- **Guardar y reutilizar el modelo**: Guardar el modelo entrenado para su uso futuro.

## Estructura del Proyecto

1. **Definición y Compilación del Modelo**: Utilizamos el optimizador `Adam`, la función de pérdida `binary_crossentropy` y la métrica `accuracy`.
2. **Visualización de la Arquitectura**: Utilizamos `plot_model` para graficar la arquitectura del modelo U-Net.
3. **Entrenamiento del Modelo**: Utilizamos el método `fit` para entrenar el modelo con los conjuntos de datos de entrenamiento y validación.
4. **Evaluación del Modelo**: Evaluamos el rendimiento del modelo en el conjunto de prueba.
5. **Visualización del Historial de Entrenamiento**: Graficamos las métricas de entrenamiento y validación.
6. **Guardar el Modelo**: Guardamos el modelo entrenado para su uso futuro.
7. **Predicciones**: Utilizamos el modelo entrenado para hacer predicciones en nuevas imágenes.

## Instalación

### Requisitos

- Python 3.6 o superior
- TensorFlow 2.6.2
- Keras 2.6.0
- Matplotlib
- IPython

### Instalación usando Conda

```bash
# Crear un nuevo entorno virtual
conda create -n unet_env python=3.8

# Activar el entorno virtual
conda activate unet_env

# Instalar las dependencias
conda install tensorflow keras matplotlib ipython
```

## Conjunto de Datos
El conjunto de datos utilizado en este proyecto consiste en imágenes biomédicas y sus correspondientes máscaras binarias. Cada imagen tiene una máscara asociada que indica las regiones de interés para la segmentación.

## Referencias
U-Net: Convolutional Networks for Biomedical Image Segmentation
