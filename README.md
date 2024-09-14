# Clasificador de sonidos, notebooks y desarrollo.

Este repositorio contiene los archivos desarrollados como parte del Trabajo Final de Master con título Evaluación de la influencia del ruido de origen humano en el Parque Natural de la Albufera mediante técnicas de aprendizaje máquina.
El objetivo principal del TFM es la prueba y desarrollo de un motor para la detección de sonidos de origen humano utilizando técnicas de Machine Learning y Deep Learning, con modelos no supervisados y redes neuronales.

## Contenido del repositorio.

/Notebook_memoria: Contiene los notebooks que sirven de guia y acompañamiento para la memoria. En este podemos encontrar varios notebooks que siguen el siguiente orden:
1. Capitulo2_Metodologia.ipynb - Todas las funciones para los cálculos de caracteristicas y procesamiento de señal.
2. Capitulo2a_Unsupervised_Learning.ipynb - Este documento contiene los procesos seguidos para probar y validar las redes no supervisadas.
3. /Arquitecturas_CNN - Esta carpeta contiene las diferentes arquitecturas de redes neuronales probadas en 2 fases enumeradas, así como los datasets utilizados.
4. Capitulo3c_Validacion_CNNs.ipynb - Este notebook contiene las pruebas hechas para validar las redes neuronales.

/data: Datasets útiles para los notebooks, especialmente para el primero.


## Requisitos.
Para ejecutar los scripts y replicar los resultados es necesario tener instalados los siguientes paquetes:

* Python 3.10 o superior.
* Bibioltecas: pandas, numpy, matplotlib, librosa, sklearn, tensorflow y keras
