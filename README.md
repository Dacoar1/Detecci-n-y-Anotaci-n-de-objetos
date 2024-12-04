# Notebook de evaluación, detección y anotación de objetos

En este notebook se van a aplicar diferentes métricas de evaluación de las más empleadas en diferentes problemas que pueden resolverse mediante aplicación de redes neuronales. Especifícamente se van a analizar problemas relativos a procesado de imagen (detección de objetos, segmentación, detección de keypoints), procesado de texto (análisis de textos generados) y métricas para medir como de buenas son imágenes generadas por una red neuronal generativa. 

Se van a proporner diferentes datos de partida en cada caso y se propone que se apliquen las métricas vistas en clase empleando código proporcionado u otro código desarrollado por el alumnos.  La idea fundamental es aplicar las mñetricas a los datos proporcionados y las etiquetas generadas y comentar en detalle todos los resultados que se obtengan.

## Algoritmo YOLO

En el primer apartado se emplea el algoritmo YOLOv8 para la detección de distintos objetos en imagenes.

El resultado de esas detecciones se comparará con la anotaciones del dataset COCO (ya proporcionadas) con la comparación de las bounding boxes mediante su IoU.

En el siguiente apartado se van a realizar unas segmentaciones manuales para compararlas con las que nos propone el algoritmo YOLOv8

En el tercer apartado se realiza lo mismo pero esta vez definiendo keypoints del esqueleto de distintas iamgenes de personas.

Por ultimo se experimenta con el funcionamiento de una IA generativa
