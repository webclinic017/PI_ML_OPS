Introduction:
This project consists of creating an API that will use a recommendation model for Steam, a multinational video game platform based on machine learning. The goal is to create a video game recommendation system for users. The API provides an intuitive interface that allows users to retrieve information for the recommendation engine and data about large or frequent events.

Herramientas Utilizadas

Pandas
matplotlib
Nampi
Seaborn
Word cloud
NLTK
Yuvicorn
Render
FastAPI
Python
Scikit-Learn
Paso paso:
1. ETL
We implement the ETL (Extract, Transform and Load) process in the form of extracted data from different objects, then the transformations required for the project, and ultimately loading for analysis and subsequent use. Las herramientas primordiales use fueron python, pandas, sklear and FastApi

2. API Deployment
If the API uses the FastAPI Python module, create 5 functions that can be retrieved:

def PlayTimeGenre(genero : str ): You can jump to multiple hours of play for general playback. Input example: random
def UserForGenre(genero : str ): You should pass the user who has accumulated more hours of work for the total dado and list of accumulated hours ago. Example input: action
def UsersRecommend(año: int): Check out the top 3 games MÁS recommends to users for the past year. (reviews.recommend = True and positive/neutral comments) Example input: 2012
def UsersNotRecommend( formerly : int ): Check out the top 3 MENOS games recommended by users for the previous day. (reviews.recommend = False and negative comments) Example input: 2009
def sentiment_analysis (formerly: int): Starting from last year, you will develop a list with candidad of user registries that will be categorized with sentiment analysis. Example input: 2014
We will now implement the deployment of this API using Render. Using fuerons: Uvicorn, Render, FastAPI

3. EDA
We implement an EDA (exploratory data analysis) process that explores and analyzes comprehensive data to generate insights, identify patrons, trends and connections, and make fundamental decisions based on the information obtained. Multiple points can be obtained to create a new ML model. Functions used: Numpy, Pandas, Matplotlib, Seaborn, Wordcloud, NLTK.

4. Machine learning model
We implement a machine learning model to summarize game recommendations, use algorithms and technical tools similar to academic and scientific training, searching for personalized recommendations and accurate background knowledge for each user and preferences. If this is a point-to-point recommendation system:

def recomendacion_juego(id de producto): By including the product id ('id), you will get a list of 5 recommended games similar to the one you added.
Usage example: 70 If this is a user recommendation system:

def recomendacion_usuario(id de usuario): By including the user id ('user_id'), you will get a list of 5 recommended games for your user. User phone number: 76561198030567998.
Using the library: Scikit-Learn with libraries: TfidfVectorizer, Linear_kernel, Cosine_similarity. Additional consultations and API.

Links:

# PI_ML_OPS
# <h1 align=center> **PROYECTO INDIVIDUAL Nº1** </h1>

# <h1 align=center>**`Machine Learning Operations (MLOps)`**</h1>

<p align=center><img src=https://www.folio3.ai/wp-content/uploads/2023/03/Asset-4-788x301.png><p>

## **Introducción:**
Este proyecto consiste en crear una API que utiliza un modelo de recomendación para Steam, una plataforma multinacional de videojuegos, basado en Machine Learning. El objetivo es crear un sistema de recomendación de videojuegos para usuarios. La API ofrece una interfaz intuitiva para que los usuarios puedan obtener informacion para el sistema de recomendacion y datos sobre generos o fechas puntuales. 

## **Herramientas Utilizadas**
+ Pandas
+ Matplotlib
+ Numpy
+ Seaborn
+ Wordcloud
+ NLTK
+ Uvicorn
+ Render
+ FastAPI
+ Python
+ Scikit-Learn

## **Paso a paso:**
### 1. ETL
Realizamos un proceso de ETL (Extracción, Transformación y Carga) en el que extrajimos datos de diferentes fuentes, los transformamos según las necesidades del proyecto y los cargamos en un destino final para su análisis y uso posterior. Las herramientas primordiales utilizadas fueron python, pandas, sklear y FastApi
### 2. Deployment de la API
Creamos una API utilizando el módulo FastAPI de Python, creando 5 funciones para que puedan ser consultadas:
- def PlayTimeGenre( genero : str ): Debe devolver año con mas horas jugadas para dicho género.
  Ejemplo de input: casual
- def UserForGenre( genero : str ): Debe devolver el usuario que acumula más horas jugadas para el género dado y una lista de la acumulación de horas jugadas por año.
  Ejemplo de input: action
- def UsersRecommend( año : int ): Devuelve el top 3 de juegos MÁS recomendados por usuarios para el año dado. (reviews.recommend = True y comentarios positivos/neutrales)
  Ejemplo de input: 2012
- def UsersNotRecommend( año : int ): Devuelve el top 3 de juegos MENOS recomendados por usuarios para el año dado. (reviews.recommend = False y comentarios negativos)
  Ejemplo de input: 2009
- def sentiment_analysis( año : int ): Según el año de lanzamiento, se devuelve una lista con la cantidad de registros de reseñas de usuarios que se encuentren categorizados con un análisis de sentimiento.
  Ejemplo de input: 2014
  
Luego realizamos el deployement de esta API utilizando Render. 
Las herramientas utilizadas fueron: Uvicorn, Render, FastAPI
### 3. EDA
Realizamos un proceso de EDA (Exploratory Data Analysis) en el que exploramos y analizamos los datos de manera exhaustiva con el objetivo de obtener insights, identificar patrones, tendencias y relaciones, y así tomar decisiones fundamentadas en base a la información obtenida. Intentando asi obtener alguna pista para crear nuestro modelo de ML
Las herramientas utilizadas fueron: Numpy, Pandas, Matplotlib, Seaborn, Wordcloud, NLTK
### 4. Modelo de Machine Learning
Realizamos un modelo de Machine Learning para generar recomendaciones juegoss, utilizando algoritmos y técnicas como la similitud del coseno y scikit-lear, con el fin de brindar recomendaciones personalizadas y precisas basadas en los gustos y preferencias de cada usuario.
 Si es un sistema de recomendación item-item:

- def recomendacion_juego( id de producto ): Ingresando el id de producto ('id), deberíamos recibir una lista con 5 juegos recomendados similares al ingresado.

 Ejemplo de uso: 70
 Si es un sistema de recomendación user-item:

- def recomendacion_usuario( id de usuario ): Ingresando el id de un usuario ('user_id'), deberíamos recibir una lista con 5 juegos recomendados para dicho usuario.
 Ejemplo de uso: 76561198030567998


La herramienta utilizada fue: Scikit-Learn con las librerias: TfidfVectorizer, linear_kernel, cosine_similarity
Tambien son consultables en la API

## **Links:**
- [Deploy de la API en Render](https://ml-ops-alex.onrender.com/)
- [Video de youtube explicando el proyecto](https://www.youtube.com/watch?v=nlaxe0ni62g&ab_channel=AlexisAlvarez)
## **Canales de contacto:**
+ Linkedin: [Alexis Alvarez](https://www.linkedin.com/in/alvarezalexiscv/)
+ Mail : Alexisalvarezcv@outlook.com
