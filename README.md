# Udemy_Project
Análisis del Dataset Udemy con pandas, pyspark y koalas

Pandas, koalas y pyspark son bibliotecas que tienen un proposito similar y es el manejo de datos en el lenguaje de programación de python. Por ese motivo, el siguiente proyecto realiza la comparación entre estas tres bibliotecas para la limpieza y manipulación de datos en un dataset.

Como se sabe, pandas es muy útil para datasets pequeños en una sola máquina, mientras que pyspark y Koalas pueden manejar cualquier tamaño de dataset y esto se debe a que spark permite ejecutar operaciones en paralelo utilizando diferentes nodos.  

Este proyecto realizó una misma manipulación de datos pero con una biblioteca diferente y el dataset que se utilizó fue Course_info.csv el cuál esta hospedado en el proyecto Udemy Courses de kaggle.

Las tareas que se hicieron con el archivo fueron las siguientes:

1. Lectura de un archivo csv y creación de un dataframe
2. Cambio del tipo de variable en las columnas
3. Creación de nueva columna
4. Localización de los valores nulos
5. Eliminación de los valores nulos
6. Aplicación de la función describe()
7. Consulta de cuántas categorías diferentes existen 
8. Creación de gráfica de categorías y el número de cursos
9. Consulta de que subcategorías están en la categoría "Development"
10. Creación de gráfica de subcategorias y el número de cursos 
11. Consulta de el número de cursos que Udemy ofrecio por año
12. Gráfica de cursos por año

Para cada tarea se obtuvieron los siguientes tiempos:

### Tiempos 

 Tarea | pandas| pyspark | Koalas
-----:|:-----:|:--------:| -------
Lectura csv |3.12s | 3.1s | 12.3s
Cambio de Dato | 0.29s | 0.18s | 1.13s
Crear columna |0.15s | 0.23s | 0.18s
Valores nulos | 0.21s | 2.20s | 7.74s
Eliminación de valores nulos | 0.17s | 0.30s | 0.67s
Función describe | 0.031s | 0.59s | 1.17s
Consulta de categorías | 16.9s | 2.0s | 0.15s
Gráfica categorías | 0.08s | 10.30s | 2.74s

De la tabla, se tiene que pandas realiza las funciones de manera rápida con una sintáxis sencilla. Sin embargo, cuando se trata de consultas el tiempo que le toma es más grande y quienes tienen una mejora en ese aspecto son pyspark y koalas. Respecto a la sintaxis de estos dos últimos, es muy parecida ya que koalas de cierta manera trabaja con pyspark e incluso para las versiones más actuales ya se incluye "Koalas" como un módulo en pyspark y se llama pyspark.pandas que tiene los beneficios de pandas y koalas.


