# Sistema de Recomendación de Películas

El presente repositorio se refiere a un curso sobre filtrado colaborativo, impartido en colaboración con el [Colegio de Matemáticas Bourbaki](https://www.colegio-bourbaki.com/) 

El presente repositorio contiene el desarrollo de un modelo de recomendación de películas utilizando técnicas de filtrado colaborativo basado en los rankings que usuarios han dado a las películas vistas. El modelo hace uso de Descomposición de Valores Singulares (SVD, por sus siglas en inglés)  para identificar estructuras latentes que posibilitan la predicción de los gustos y preferencias de la audiencia.

El conjunto de datos se tomó de [Kaggle](https://www.kaggle.com/datasets/netflix-inc/netflix-prize-data). Para este proyecto, se utilizó únicamente uno de los cuatro archivos del dataset del reto de Netflix con calificaciones de usuarios para películas, en una escala de 1 a 5: **combined_data_1.txt**, además de el archivo separado por comas **movie_titles.csv** que contiene para cada id de películas el título y  año de lanzamiento.
Puedes crear un acceso directo de estos archivos en tu drive  desde [este enlace](https://drive.google.com/drive/folders/1jpZD2mhX9DfEdUM75krFLnACT1Ya9Uiy?usp=sharing)

