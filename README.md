# Cajamar UniversityHack 2023 Equipo Unity
Nuestro propósito, y objetivo de **UniversityHack 2023**, es plantear una previsión de la producción de uvas en el año 2022 mediante algoritmos de predicción. Para ello, se dispone de un conjunto de datos con histórico de producciones de los viñedos que conforman la cooperativa La Viña, así como histórico de la climatología de los mismos de The Weather Company.

## Instrucciones de uso
Este proyecto se ha realizado en los lenguajes de programación de **Python** y **R**. El análisis exploratorio y el tratamiento de los datos se ha hecho en R utilizando librerías como *tidyr*, *dplyr* o *ggplot2*, y la selección de modelos se ha realizado en Python utilizando paquetes como *sklearn*.

En total el proyecto se compone de un script en rmd, llamado **exploratory.rmd**, y un script en un Notebook de Jupyter, llamado **exploratory.ipynb**, para el análisis exploratorio y pruebas realizadas durante todo el concurso. Por otro lado, un script en rmd para el proceso de extracción, transformación y carga de los datos llamado **prediction.rmd**, y un Notebook de Jupyter llamado **prediction.ipynb** para la predicción del modelo propuesto.

Antes de comenzar, se deben instalar las librerías y los paquetes necesarios. Para los .rmd se debe ejecutar al comienzo la instalación de las librerías necesarias, y para los Notebooks de Jupyter se dispone de un archivo requirements.txt con los paquetes necesarios. Para disponer de estos paquetes se debe ejecutar el siguiente comando en la terminal:

    pip install -r requirements.txt