# Título del Proyecto

En este proyecto realizamos la detección de objetos en video usando el modelo Retinanet, entrenando una red neuronal convolucional ResNet50 preentrenada.


### Pre-requisitos 📋

      _Anaconda
      _Jupyter notebook o google colab
      _Tensorflow 
      _Keras
      _Keras Retinanet (https://github.com/fizyr/keras-retinanet)
      _labelImg (https://github.com/tzutalin/labelImg.git)

### Instalación labelImg (Windows + Anaconda)🔧

      git clone https://github.com/tzutalin/labelImg.git
      cd labelImg
      conda install pyqt=5
      pyrcc5 -o libs/resources.py resources.qrc
      python labelImg.py


### Descripción del directorio

1. ...\Hand-Detection-Retinanet\keras-retinanet\images

      Directorio donde estan las imagenes para el entrenamiento

2. ...\Hand-Detection-Retinanet\keras-retinanet\snapshots
      
      En este directorio debe encontrarse el modelo entrenado de extensión .h5

3. ...\Hand-Detection-Retinanet\keras-retinanet

      En este directorio deben encontrarse los archivos .csv que contienen la información del dataset de entrenamiento y pruebas
        annotations.csv
        classes.csv
        annotations_test.csv

4. ... El modelo .h5 debe guardarse en el directorio ...\keras-retinanet\snapshots