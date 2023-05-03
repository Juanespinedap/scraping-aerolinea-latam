# Scraping de Aerolinea LATAM

Este Proyecto tiene como objetivo extraer información de los vuelos de la pagina web https://www.latamairlines.com/co/  (aerolínea) utilizando la metodología ETL (Extraer, Transformar, Cargar) 

El proceso de este proyecto es que el código escrito en cada notebook extrae información de cada vuelo son su respectivo itinerario, horas de vuelo, tarifas y confirmación de escalas

El archivo llamado web_latam.ipynb recopila en una función las tareas de
```
    1. Navegar con un driver en el navegador Chrome
    2. Entrar a la página de vuelos por medio de una url suministrada por el usuario
    3. Extracción de la información
    4. Presentación de la información en el archivo vuelo.json
```
