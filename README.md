# Proyecto de Programación para el análisis de datas.

## Presentación

1. Objetivo: 
   
   1. Mercado inmobiliario
   
   2. Buscamos un portal
   
   3. determinamos el objetivo

## Estructuras de datos que utilizaremos

Repasamos

1. Listas
   
   1. Ejemplo

2. Diccionarios
   
   1.  Ejemplo

## Web

1. HTML request / response =>   www.wikipedia.org  / index.html

2. Sintaxis de un elemento HTML

3. Identificar que necesito.... 
   
   1. inspeccionar en el browser

## Manos a la obra, vamos al code

### Web Scraping - Obtenemos los datos

1. import request   #  Para obtener los datos de la web
   
   from bs4 import BeatifulSoup
   
   import numpy as np  # para 
   
   import re  # para buscar texto dentro de otro texto mayor

2. def trasnform_html_to_data(soup):
   
   1. explicarla

### Data Cleaning - Limpiamos los datos

1. Convertir datos en DataFrame

2. Buscar `df.isna()` y eliminar `df.dropna(inplace=True)`  registros sin algún dato 

3. Buscar y eliminar Outliners (observación anormal y extrema en la muestra)

### Visualización de Datos

# hola

```python
import seaborn as sns
import ploty.express as px
```

1. px. scatter()

2. sns.coutplot()

3. sns.catplot()

4. sns.regplot()

### Exportar a .csv

.to_csv


fuente: 

https://github.com/sbuffose/data-webinar/blob/master/data-workshop.ipynb