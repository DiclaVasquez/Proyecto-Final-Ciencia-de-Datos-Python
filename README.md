# Proyecto-Final-Ciencia-de-Datos-Python
### Integrantes De grupo No. 7:
* Dicla Vásquez - Carné: 21006243 -
* Carlos Miranda  - Carné : 9812939 -


#### Origen: [https://www.kaggle.com/datasets](https://)

# Descripción del proyecto "USDA Producción Suministro y Distribución"

---
### Alcance del proyecto: 
###### Desarrollar una Ingeniería de datos, utilizando las herramientas impartidas durante el proceso de aprendizaje.


---
### Descripción de la Fuente de Información:

##### Definiciones:
###### USDA: Departamento de Agricultura de los Estados Unidos. Su propósito es desarrollar y ejecutar políticas de ganadería, agricultura y alimentación.


---



#### Acerca de Dataset
###### La base de datos presentada, contiene información básica sobre la produccción, el suministro y la distribución de productos básicos blandos (principalmente agrícolas).

---


### Objetivo: 
###### Con los datos  que contiene el dataset, se podrán cruzar las variables que se desean analizar  y obetener información sobre pronósticos meteorológicos, tendencias de consumo, eventos geopolíticos.

###### La parte más interesante de este conjunto de datos, contiente todas las revisiones publicadas por el USDA, para una combinación de tablas  como país  o productos. 


---
### Exploración de la Data: 
* El data set cuenta con 9 variables 
* Datos históricos desde el año 1960 al 2022
* El dataset cuenta 5 millones de observaciones.




### Variables importantes para generar métricas de información:
* Commodity "tipo de Commodity"
* Valor de importación o exportación
* Descripción (uso del commodity)
* Años (información histórica)
* Ciudad 



---

## Métricas que el modelo de datos puede responder:
* Tendencias de consumo de granos básicos
* Valor de exportaciónes o importaciones de Commodityes 
* Valor de importaciones o exportaciones por País
* Crecimiento o decrecimiento anual de cultivos de mayor producción. 
* Estimaciones de producción de cultivos representativos.

---
## Modelado de datos
#### ETL: El proceso de extracción , transformación y carga, se procedio utilizando las siguientes plataformas:

* SQL
* AWS
* Jupyter notebook (Anaconda)
* RDS
* EC2 - Python 
* Redshift - DW

---

## Desarrollo del proyecto ETL 
####### Se procedio a desarrollar el proyecto , utilizando un modelo Datawarehouse, en SQL ( solomante la extración de las tablas) y fue montado en RDS y un archivos de precios internacionales  del café, en formato CSV, almacenados en S3.

![](https://i.imgur.com/qZnYbKl.png)

### Procesamiento y carga:
####### El objetivo es  extraer los registros y transformarlos a un mismo tipo de dato.  realizo en Notebooks, para la construcción de los datos, corriendo el scripts en Python, archivo que se adjunta en este proyecto. 

### Conclusión: 

###### Como lo indicaba el alcance de este proyecto, el objetivo es poner en practica todas las enseñanzas y experiencias compartidas en clase. 

###### En el proceso de la elaboración de este proyecto, nos encontramos con algunas dificultades que impidio que concluyéramos  con el proyecto. 

* Al inicio Cuando se creo la instancia se trabajo, bajo el esquema de SQL, pero no funciono, luego se procedio a trabajarlo con MySQl, pero no funcióno. al final si nos corrio la instancia, trabajandolo con SQL. 

* Al ingresar los paramentros si genera la conexion  con AWS y en Datagrip.

##### En conclusión si nos reconocio la instancia, pero no logramos que nos generará los datos. 

### Anexos:
![](https://i.imgur.com/bqMdy49.png)


![](https://i.imgur.com/Ky2fsvM.png)


![](https://i.imgur.com/TTgO1UM.png)






