# Proyecto Análisis de Datos
- Creadora: Diana Cereceres Vidales
- Insitución: BEDU

## Resumen
En el presente proyecto se analizan las ventas y cancelaciones que ocurrieron a lo largo del año 2019, en una empresa que fabrica pintura para plásticos, 
ubicada en la ciudad de Querétaro.

![pinturas](https://img.vixdata.io/pd/jpg-large/es/sites/default/files/imj/lasmanualidades/p/pintar-plastico2.jpg)

## Objetivos
- Identificar a los mejores y peores clientes analizando las operaciones que hicieron en el año
- Identificar los productos que generaron mayores ganancias y los que no
- Tratar de clasificar tanto buenos y malos clientes como productos utilizando Machine Learning

## ¿Qué hay en este repositorio?
En este repositorio encontraras el [Dataset Original](https://) y el archivo .ipynb [Limpieza_Priyecto](https://), donde se limpió el dataset, se hicieron agrupaciones 
y se hizo un primer análisis exploratorio de los datos. En este se encontraron los Top 10 de clientes que más ventas hicieron y que más pérdidas generaron. Lo mismo para los productos.

El segundo paso se encuentra en el archivo [Analisis_de_Proyecto-Copy1](https://), ya con un dataset limpio se buscó implementar un algoritmo de aprendizaje supervisado 
para predecir en qué categoría (venta/cancelación) caería un cliente, sin embargo, la naturaleza de los datos no lo permite. Es por esto que se opta por implementar un algoritmo de 
aprendizaje no supervisado (K-Medias) para un dataset de clientes y otro de productos para ver si de alguna manera se agrupan.

Por último se hace un pequeño análisis exploratorio de los nuevos datasets donde ya se le asignó una categoría a los [clientes](https://) y a los [productos](https://) para posteriormente volver a implementar 
un algoritmo supervisado para predecir en qué cluster o categoría caerá cierto cliente o cierto producto. Nuevamente no se obtuvieron resultados favorables, sin embargo se pueden generar 
algunas conclusiones a partir de la gráfica de dispersión de K-Medias y y las observaciones del primer análisis en [Limpieza_Priyecto](https://).
