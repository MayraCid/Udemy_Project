# Udemy_Project
Análisis del Dataset Udemy con pandas, pyspark y koalas

Pandas, koalas y pyspark son bibliotecas que tienen un proposito similar y es el manejo de datos en el lenguaje de programación de python. Por ese motivo, el siguiente proyecto realiza la comparación entre estas tres bibliotecas para la limpieza y manipulación de datos en un dataset.  

El dataset que se utilizó fue Course_info.csv y se encuentra en el proyecto Udemy Courses de kaggle.

### Tiempos 

 Caracteristica | pandas| pyspark | Koalas
-----:|:-----:|:--------:| -------
Lectura csv |3.12s | 7.86s | 12.3s
Cambio de Dato | 0.297s | 0.49s | 1.13s
Crear columna |0.156s | 0.09s | 0.185s
Valores nulos | 0.219s | 13.32s | 7.74s
Eliminación de valores nulos | 0.172s | 0.8s | 0.670s
Función describe | 0.0312s | 3.2s | 1.17s
Consulta de categorías | 16.9s | 1.96s | 0.157s
Gráfica categorías | 0.0875s | 27.94s | 2.74s

Existen dos aspectos importantes que hay que resaltar, el primero es que pandas parece realizar las funciones de manera rápida con una sintáxis sencilla. Sin embargo, cuando se trata de consultas el tiempo que le toma es más grande y quienes tienen una mejora en ese aspecto es pyspark y koalas. Respecto a la sintaxis de estos dos es muy parecida ya que koalas de cierta manera trabaja con pyspark e incluso para las versiones más actuales ya se incluye "Koalas" como un módulo en pyspark y se llama pyspark.pandas


