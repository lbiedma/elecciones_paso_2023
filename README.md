# elecciones_paso_2023

Notebook para descargar los resultados de las PASO 2023 como respuesta de la API de Elecciones del gobierno (usado en el [mapa de acá](https://resultados.gob.ar/elecciones/))

Esos datos se guardan en forma de JSON y luego se leen para obtener solamente los resultados por partido (el JSON tiene info por distrito).

Librerías usadas: 
- json
- pandas
- requests
