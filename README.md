# Proyecto Henry MLOps: Sistema de Recomendación de Películas

## Visión General

El objetivo principal de este proyecto es desarrollar un sistema completo que permita gestionar y analizar datos de películas mediante un proceso ETL (Extracción, Transformación y Carga). Además, se implementa una API para acceder a la información procesada y un modelo de Machine Learning (ML) que sugiere películas basadas en las preferencias del usuario.
Contenidos

1.	Descripción del Proyecto
2.	Configuración e Instalación
3.	Enfoque Metodológico
4.	Análisis Exploratorio de Datos (EDA)
5.	Origen de los Datos
6.	Organización del Proyecto
7.	Autor
   
## Descripción del Proyecto

Este proyecto se centra en la creación de una solución integral para el análisis de datos de películas. A través de un proceso ETL, se preparan los datos para su posterior uso en una API. Adicionalmente, se ha desarrollado un modelo de ML que realiza recomendaciones de películas según las preferencias individuales de los usuarios, mejorando la experiencia personalizada.

## Configuración e Instalación
Requisitos
Para poner en marcha este proyecto, se debe instalar los siguientes componentes:
•	Python 3.7 o una versión superior
•	FastAPI
•	Uvicorn
•	Scikit-learn

Pasos de Instalación
1.	Clona el repositorio desde GitHub:
bash
Copiar código: git clone 

2.	Crea un entorno virtual en tu sistema:
bash
Copiar código: python -m venv venv

3.	Activa el entorno virtual para trabajar dentro de él:
o	Windows: venv\Scripts\activate
o	macOS/Linux: source venv/bin/activate

4.	Instala todas las dependencias necesarias para ejecutar el proyecto:
bash
Copiar código: pip install -r requirements.txt

## Enfoque Metodológico

El proyecto utiliza técnicas avanzadas de ingeniería de datos para asegurar que los datos sean limpios, precisos y listos para ser analizados. El proceso ETL es fundamental para transformar los datos originales en información estructurada y de alta calidad, lista para su uso en modelos de ML y en la API. 
Análisis Exploratorio de Datos (EDA)

Una vez que los datos fueron limpiados, se llevó a cabo un análisis exploratorio de datos (EDA) para investigar las relaciones entre las variables y detectar posibles outliers o anomalías. Durante el EDA, se exploraron patrones relevantes que podrían ser útiles para el desarrollo del sistema de recomendación. Entre las visualizaciones realizadas, se destacan:

•	**Nubes de Palabras**: Se generaron nubes de palabras para analizar las palabras más frecuentes en los títulos de las películas. Esta información es crucial para mejorar las recomendaciones, ya que permite identificar tendencias y temas recurrentes en las películas.

![Nube de Palabras](imagenes/nube%20de%20palabras.JPG)

•	**Gráficas de Distribución y Correlación**: Se crearon gráficos para visualizar la distribución de las variables clave y su correlación, lo cual ayuda a entender mejor los datos y guiar el desarrollo del modelo de ML.

Este EDA permitió obtener una comprensión de los datos y fundamentar la creación del sistema de recomendación de películas, que se basa en la similitud entre películas. El modelo entrenado devuelve una lista de las 5 películas más similares a la consultada, y esta funcionalidad ha sido integrada como una extensión de la API.
Origen de los Datos

Los datos utilizados en este proyecto provienen de un conjunto de datos seleccionado para garantizar su relevancia y amplitud en relación con el análisis de películas. Estos datos se someten a un proceso de limpieza y transformación antes de ser utilizados en los modelos y en la API.

## Organización del Proyecto

•	**dataset/**: Carpeta que contiene los dataset utilizados en el proyecto

•	**imagenes/**: Gráfica Nube de Palabras 

•	**notebooks/**: Incluye el proceso ETL,  el EDA y el modelo Machine learning

•	**reports/**:reporte escrito del análisis EDA

•	**src/**: Directorio con el código de la API 

•	**README.md**: Documento de referencia para la documentación del proyecto.


## Autor
El proyecto ha sido desarrollado por:

•	Bruno Peretti

