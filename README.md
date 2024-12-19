#                                          Elecciones 2023 - Resultados

Este repositorio contiene el análisis de datos por sección correspondientes al Ballotage de las elecciones en Argentina en 2023.

##    Proceso de ETL (Extracción, Transformación y Carga)

###    Extracción
Se emplearon herramientas de análisis de datos en Python, específicamente la librería Pandas, para extraer los datos desde un archivo CSV que contenía los resultados de las elecciones por sección.

###    Transformación
Durante la fase de transformación, se llevaron a cabo diversas operaciones, entre ellas:
- Suma de los votos por sección para cada agrupación política ('LA LIBERTAD AVANZA' y 'UNION POR LA PATRIA').
- Ordenamiento de los datos de mayor a menor según el total de votos.
- Exportación de los datos transformados a un archivo CSV para facilitar su utilización en herramientas de visualización.

###    Carga
Los datos transformados se exportaron como un archivo CSV con el propósito de ser cargados en herramientas de visualización, como Power BI.

El objetivo principal es posibilitar un análisis más profundo y una visualización interactiva de los resultados.

##    Archivos en el Repositorio

- **votos_por_seccion.csv:** Contiene los datos transformados con los votos por sección para cada agrupación política.

##    Herramientas Utilizadas

- **Python (Numpy, Pandas, Matplotlib, Seaborn):** Para la manipulación y análisis inicial de los datos.
- **Power BI:** Como herramienta de visualización para un análisis más detallado y visual.

##    Uso

1. **Extracción:** Los datos pueden obtenerse desde la fuente original o mediante el uso del archivo CSV proporcionado en este repositorio.
   
2. **Transformación:** Utilizar el archivo CSV "votos_por_seccion.csv" para llevar a cabo análisis y visualizaciones en Power BI u otras herramientas de visualización.

3. **Carga:** Importar el archivo CSV en Power BI para explorar los datos y realizar análisis detallados.
