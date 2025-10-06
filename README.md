# LedaRojo-EBirds-Proyecto.-IngenieriaDeDatos
</strong>Proyecto de ingeniería de datos -ETL- que extrae datos de la API EBird, los procesa y almacena en un DataLake en formato DeltaLake.</strong>

1. Extracción de una API, como fuente de datos, desde varios endpoints mediante uso de la librería requests.
2. Conversión los datos obtenidos a DataFrames de Pandas 
3. Almacenamiento en formato DataLake y Deltalake de los datos en forma cruda, sin transformaciones o con leves transformaciones.
4. Extracciones incremental y full, según las características del endpoint.
5. Técnicas de procesamiento para limpiar, estandarizar y enriquecer  los datos. 
6. Varios tipos de transformaciones como append, overwrite, merge, etc.

eBird es un proyecto de ciencia ciudadana que recopila datos sobre aves de todo el mundo. La base de datos de eBird incluye más de 100 millones de registros que son de libre acceso y se utilizan para la investigación, la conservación y la educación.
Los datos de eBird se utilizan para:
\
-Investigar y monitorear las aves\
-Planificar la conservación\
-Manejar áreas y hábitats\
-Evaluar poblaciones de especies\
-Proteger hábitats\
-Elaborar leyes y políticas

Los datos de eBird son un recurso poderoso para la ciencia y la conservación.

eBird Argentina se nutre del trabajo voluntario de decenas de personas, quienes día a día se encargan de la curación y revisión de datos, mantienen actualizados canales de comunicación, y responden a las inquietudes de los usuarios y usuarias de la plataforma. Su trabajo es fundamental para garantizar el correcto funcionamiento del sistema, y para que eBird refleje datos de alta calidad, que puedan ser aprovechados por toda persona apasionada por la observación de aves, por educadores/as, por agencias gubernamentales, ONGs, y por la comunidad académica.
