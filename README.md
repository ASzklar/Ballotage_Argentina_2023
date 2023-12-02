# Elecciones 2023 - Resultados 
Este repositorio contiene el análisis de datos correspondientes a resultados del Ballotage en las elecciones por sección en 2023 en Argentina.

Proceso de ETL (Extracción, Transformación y Carga)
El proceso de manipulación y preparación de datos se realizó siguiendo los pasos de ETL:

Extracción
Se utilizaron herramientas de análisis de datos en Python, específicamente la librería Pandas, para la extracción de datos.
Los datos se leyeron desde un archivo CSV que contenía los resultados de las elecciones por sección.
Transformación
Se procedió a realizar varias operaciones de transformación de datos:
Suma de los votos por sección para cada agrupación política ('LA LIBERTAD AVANZA' y 'UNION POR LA PATRIA').
Ordenamiento de los datos por el total de votos de mayor a menor.
Exportación de los datos transformados a un archivo CSV para facilitar su uso en herramientas de visualización.
Carga
Los datos transformados se exportaron como un archivo CSV para poder ser cargados en herramientas de visualización como Power BI.
El objetivo es permitir un análisis más profundo y una visualización interactiva de  
Archivos en el Repositorio
votos_por_seccion.csv: Contiene los datos transformados con los votos por sección para cada agrupación política.
Herramientas Utilizadas
Python (Pandas) para la manipulación y análisis inicial de los datos.
Power BI como herramienta de visualización para un análisis más detallado y visual.
Uso
Extracción: Los datos pueden ser obtenidos desde la fuente original o utilizando el archivo CSV provisto en este repositorio.
Transformación: Utilizar el archivo CSV votos_por_seccion.csv para realizar análisis y visualizaciones en Power BI u otras herramientas de visualización.
Carga: Importar el archivo CSV en Power BI para explorar los datos y realizar análisis detallados.
