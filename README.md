# Proyecto Videojuegos

Este proyecto se centra en el análisis de una plataforma de videojuegos con el propósito de identificar los videojuegos que reciben buenas reseñas o reviews, determinar cuáles son los videojuegos y categorías que generan mayores ingresos, y analizar en qué fechas los usuarios de los videojuegos tienden a hacer más reseñas. Para llevar a cabo este análisis, se utilizan tres archivos JSON:

1. **australian_user_reviews**: Contiene todas las reseñas realizadas por los usuarios.

2. **output_steam_games**: Este archivo incluye el catálogo completo de videojuegos y sus respectivas categorías.

3. **australian_users_items**: Contiene información sobre todos los usuarios de la plataforma.

## Análisis de Sentimiento de las Reseñas

En el archivo denominado `video_games.ipynb`, se detalla el proceso de carga de nuestros archivos. Además, se lleva a cabo el análisis de sentimiento de las reseñas utilizando la biblioteca NLTK. Para lograr esto, se realizó un proceso de preparación de los datos para que NLTK pueda realizar un análisis de sentimiento más confiable.

## ETL (Extracción, Transformación y Carga)

El archivo `depurado_funciones.ipynb` contiene todo el proceso de ETL que aplicamos a nuestros datos. Esto nos permite posteriormente desarrollar funciones que serán de gran utilidad para nuestra API.

En el archivo `funciones.ipynb`, encontraremos las funciones creadas en el archivo `depurado_funciones`. Además, se proporcionan ejemplos de cómo utilizar estas funciones de manera efectiva.

**Nota Importante**:
Cada uno de los notebooks proporciona un detallado paso a paso de cómo se desarrolló el código, así como consideraciones clave que se tuvieron en cuenta durante su elaboración.
