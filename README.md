Para este trabajo utilicé la Base SAIJ de Normativa Provincial (https://datos.jus.gob.ar/dataset/basesaij-de-normativa-provincial) 
y llevé a cabo el siguiente procesamiento de datos:

Descargué la base original en formato CSV.

Filtré los registros para conservar únicamente los correspondientes a las provincias de Tucumán, Formosa y Tierra del Fuego.

Limpié el dataset eliminando las columnas vacías o aquellas que no aportaban información valiosa para el análisis.

Filtré los datos para incluir exclusivamente las normativas clasificadas como Ley, Decreto Ley y Texto Ordenado Ley.

Eliminé del conjunto de datos los casos de normativas que se encontraban vetadas.

Reemplacé todos los valores vacíos o nulos por "n/d".

Guardé los resultados finales exportando los archivos en formato .xlsx y .csv (con codificación UTF-8 y separador ",").
