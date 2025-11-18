# Modelo de IA para detectar transformaciones urbanas mediante segmentacion satelital

![Banner del proyecto](Banner.png)

## Autores
Johan Sebastian Diaz Mesa, David Esteban Suarez Lozano, Nicolás Rivera Leon

## Objetivo
Desarrollar e implementar un sistema automatizado basado en técnicas de deep learning que segmente de manera precisa zonas edificadas a partir de imágenes satelitales.

## Dataset
El dataset fue tomado de https://huggingface.co/datasets/blanchon/INRIA-Aerial-Image-Labeling

Cuenta con un total de 360 imagenes RGB de tamaño 5000x5000 px con un resolucion por pixel de 0.3 m y cuenta con las clases semanticas de 'building' y 'not building' las imagenes estan en formato .tif y georefenciadas.

## Modelos Supervisados

  * GaussianNB
  * Decision Tree
  * Random Forest

Se evaluó el rendimiento de cada uno de los modelos, obteniendo los mejores resultados con Random Forest, sobre el cual se ajustaron los hiperparámetros para equilibrar precisión y eficiencia computacional. 

## Modelos No Supervisados

