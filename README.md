# Gentrificación en la Ciudad de Málaga
## Autora: Macarena Palomares Pastor
### Fecha: 05/2023

Estudio de nivel de gentrificación de los barrios de Málaga

Contenido del repositorio:
  1. Directorio **Code**: Contiene el codigo del proyecto, así como los ficheros fuentes y los de resultado
     - **Gentrification.ipynb**: Fichero de jupiter notebook con el código del proyecto
     - **Gentrification.html**: Exportación en HTML del resultado de ejecutar el fichero de jupyter notebook
     - **Graficos.zip**: Fichero comprimido con los graficos generados por la ejecución del fichero de jupyter notebook
     - **Datos**: Directorio que contiene los datos del proyecto. 
     - **Datos/Barrios**: contienes los ficheros CSV con los datos que se cargan en el fichero de notebook. Hay un fichero para cada serie anual (2015 a 2020)
     - **Datos/Base**: contiene los shapefiles de Barrios_ZU, que se utiliza como base para realizar las uniones de los datos en el fichero de jupyter notebook y generar los shapefiles de resultados, y Areas, que se utiliza de base de representación en los mapas generados en los dashboards del proyecto
     - **Datos/Finales**: contiene los shpaefiles generados tras la ejecución del jupyter notebook, que son indice_gentrificacion (resultado del PCA), k-means_3 (resultado de k-means con 3 clústers), k-means_4 (resultado del k-means con 4 clústers), k-means_6 (resultado del k-mean con 6 clústers)

El proyecto se complementa con los siguientes dahboards creados en ArcGIS online:
1. **Análsis de las variables**: https://www.arcgis.com/apps/dashboards/e9d2e1106d2c4cb78a91765ad555e901
2. **Variación de las variables**: https://www.arcgis.com/apps/dashboards/16724f8dae5a44a3987971082a66c0a2
3. **Resultados**: https://www.arcgis.com/apps/dashboards/402eda0328094a95b8ac23f0612ce461
       
    
  
