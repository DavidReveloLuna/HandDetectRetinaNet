## IMPORTANTE

CREAR UNA CARPETA LLAMADA images en el directorio /labelImg

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

5. CodeTrainPredict.txt contiene el codigo para google colab que entrena la red neuronal

### Modificación importante

      Al clonar el repositorio de keras-retinanet debemos asegurar trabajar con las versiones correctas de keras y tensorflow, para eso ejecutar las siguientes lineas:
      
      !pip uninstall keras -y
      !pip uninstall keras-nightly -y
      !pip uninstall keras-Preprocessing -y
      !pip uninstall keras-vis -y
      !pip uninstall tensorflow -y
      !pip uninstall h5py

      !pip install tensorflow==2.1.0
      !pip install keras==2.3.1
      !pip install h5py==2.10.0
 
      Tipear y, luego enter en el mensaje que aparece después de las instrucciones anteriores
 
# **Canal de Youtube**
[Click aquì pare ver mi canal de YOUTUBE](https://www.youtube.com/channel/UCr_dJOULDvSXMHA1PSHy2rg)
