# Promedio de edades primer matrimonio
## Datos respecto a promedio de edades de mujeres al contraer su primer matrimonio año 2022

Este conjunto de datos fue elegido desde MakeOverMonday, para el año 2022 (https://www.makeovermonday.co.uk/data/data-sets-2022/)
Estos datos representan la edad promedio en la cual las mujeres de diversos estados y países contrajeron su primer matrimonio.

### Diccionario de datos
- *Name*: país 	
- *Type*: define si el país es State o Country 
- *TimeFrame*: selecciona por rango de tiempo, existe de 2006 a 2010 y de 2015 a 2019	
- *Median Age*: edad promedio de casamiento
- *Population Density per Sq Mi*: densidad de población por milla

### Contenido del código
1. Limpieza de base de datos: revisión de duplicados y nulos. 
2. Tipo de datos: revisión de definición de tipo de datos de cada columna
3. Visualización gráfica de resultados
  - *Mapa de calor*: búsqueda de correlación por variables 
  - *Histograma*: distribución por edades
  - *Scatter*: edad media de matrimonio en relación con la densidad de la población
  - *Subplots gráfico de barra*: relación entre países, edad promedio de matrimonio y TimeFrame
