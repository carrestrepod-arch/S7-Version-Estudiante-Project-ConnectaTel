# S7-Version-Estudiante-Project-ConnectaTel
Objetivo del proyecto: Evaluar el comportamiento de los clientes de una empresa de telecomunicaciones en Latinoamérica (ConnectaTel) utilizando información registrada hasta el año 2024 para construir un perfil estadístico, detectar comportamientos atípicos y crear segmentos de clientes que permitan diseñar estrategias de retención y mejoras en los planes.

Datasets utilizados:

plans.csv: Información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).

users_latam.csv: Información de los clientes (edad, ciudad, fecha de registro, plan, churn).

usage.csv: Detalle del uso real de los servicios (llamadas y mensajes).

Etapas del análisis realizadas:

Carga y exploración inicial de la estructura de los datasets (shape, info, .head()).

Identificación de problemas de calidad de datos (conteo y proporción de valores nulos, detección de sentinels y revisión/estandarización de fechas).

Limpieza básica de datos (corrección de sentinels en age y city, manejo de fechas fuera de rango y análisis de nulos MAR en duration y length).

Agregación y resumen estadístico de uso por usuario, combinando la información con el dataset de usuarios.

Visualización de distribuciones mediante histogramas por tipo de plan y boxplots para la detección de outliers.

Segmentación de clientes en función del uso (grupo_uso) y de la edad (grupo_edad), seguida de su respectiva visualización gráfica.

Cómo ejecutar el notebook:

Descarga el archivo del notebook (.ipynb).

Súbelo a tu entorno de trabajo preferido, como Google Colab (File -> Upload notebook).

Asegúrate de contar con la estructura de directorios correcta o carga los archivos CSV en la ruta /datasets/ tal como lo requiere el código.

Guía de reproducción:

Clonar o acceder al repositorio del proyecto en GitHub.

Abrir el notebook interactivo en Google Colab o Jupyter Notebook.

Ejecutar secuencialmente cada una de las celdas de código para reproducir la carga de librerías, la lectura de los tres archivos de datos, los procesos de limpieza, las agrupaciones estadísticas y la generación de gráficos analíticos.
