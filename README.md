# lab-av_02
Códigos y archivos para la investigación de Laboratorio Avanzado 2

Estas son las descripciones de los archivos que se encuentran en este repositorio

## Códigos

### plots.ipynb
En este archivo están todos los códigos para cada una de las gráficas realizadas

### pixels\_wcs.ipynb
En este archivo se encuentra un código para convertir del formato HH:MM:SS y DD:MM:SS las coordenadas RA y DEC respectivamente de la tabla shallow, utilizada como base del proyecto

### Parametros.ods
Tabla con todos los parámetros para cada una de las corridas realizadas con SoFiA para los distintos cubos

### t_shallow.ods
Tabla de las mediciones realizadas por la profesora Mónica

### t_mc.ods
Tabla con todos los matches entre las detecciones realizadas con SoFiA (t\_sc.ods) y la tabla shallow (t\_shallow). Ademàs se incluyen los parámetros de cada detección

### t_mp.ods
Tabla procesada de todos los matches entre las detecciones de SoFiA (t\_sc.ods) y la tabla shallow (t\_shallow), sin tomar en cuenta repeticiones, al descartar aquellas con un reliability más bajo. Ademàs se incluyen los parámetros de cada detección

### tsc_parcial.ods
Tabla con todas las deteciones realizadas por SoFiA tomando en cuenta ciertas condiciones para poder ser analizadas

## tm_parcial.ods
Tabla con todas las detecciones realizadas por SoFiA, además de que coincidieron con las detecciones de la tabla t\_shallow\_corregida.csv. Estos datos se escogieron tomando en cuenta ciertas condiciones para poder ser analizados

### t_shallowB.ods
Tabla de las mediciones realizadas por la profesora Mónica de la sección B

### t_shallowb.ods
Tabla con las mediciones realizadas por la profesora Mónica de la sección B, incluyendo únicamente la región donde se obtuvieron detecciones utilizando los parámetros estudiados

##Archivos csv

### tabla\_shallow\_corregida.csv
Es la tabla que se usa como base pero, se le agregan las coordenadas RA y DEC en grados hecho con TOPCAT para poder ser comparada. Guardada en formato csv

### t_shallow.csv
Tabla de las mediciones realizadas por la profesora Mónica en formato csv

### t_mc.csv
Tabla con todos los matches entre las detecciones realizadas con SoFiA (t\_sc.ods) y la tabla shallow (t\_shallow). Ademàs se incluyen los parámetros de cada detección  en formato csv

### t_mp.csv
Tabla procesada de todos los matches entre las detecciones de SoFiA (t\_sc.ods) y la tabla shallow (t\_shallow), sin tomar en cuenta repeticiones, al descartar aquellas con un reliability más bajo. Ademàs se incluyen los parámetros de cada detección. En formato csv

### tsc_parcial.csv
Tabla con todas las deteciones realizadas por SoFiA tomando en cuenta ciertas condiciones para poder ser analizadas en formato csv

## tm_parcial.csv
Tabla con todas las detecciones realizadas por SoFiA, además de que coincidieron con las detecciones de la tabla t\_shallow\_corregida.csv. Estos datos se escogieron tomando en cuenta ciertas condiciones para poder ser analizados en formato csv

### t_shallowB.csv
Tabla de las mediciones realizadas por la profesora Mónica de la sección B en formato csv

### t_shallowb.ods
Tabla con las mediciones realizadas por la profesora Mónica de la sección B, incluyendo únicamente la región donde se obtuvieron detecciones utilizando los parámetros estudiados en formato csv

### shallow_1845+26.csv
Subset de la tabla shallow corregida para la sección del cubo zoa1845+26

### shallow_1900+22.csv
Subset de la tabla shallow corregida para la sección del cubo zoa1900+22

### shallow_1900+26.csv
Subset de la tabla shallow corregida para la sección del cubo zoa1900+26

### shallow_1915+22.csv
Subset de la tabla shallow corregida para la sección del cubo zoa1915+22

### shallow_1915+26.csv
Subset de la tabla shallow corregida para la sección del cubo zoa1915+26

### shallow_1945+26.csv
Subset de la tabla shallow corregida para la sección del cubo zoa1945+26

### shallow_2000+26.csv
Subset de la tabla shallow corregida para la sección del cubo zoa2000+26

## Otros archivos

### README.md
Es este archivo con la documentación del repositorio

### tesis.pdf
Capitulo 5 de la tesis de la profesora Mónica

### reunion.txt
Notas de una de las reuniones realizada el 05/oct

### token
Token para poder subir los archivos al repositorio en github

## Carpeta Archivos viejos
En esta carpeta están las tablas antiguas:

-original_cat.ascii: Es la tabla de una corrida de un cubo antes de ser corregida

-original_cat.csv: Es la tabla de una corrida de un cubo antes de ser corregida

-original_cat.xml: Es la tabla de una corrida de un cubo antes de ser corregida

-prueba2_cat.ascii: Es la tabla original corregida en formato .ascii

-prueba2_cat.csv: Es la tabla original corregida en formato .csv

-prueba2_cat.xml: Es la tabla original corregida en formato .xml para poder ser leida en TOPCAT

-tabla shallow.xml: Es la tabla que se usa como base para la investigación en formato .xml


-tabla\_sofia\_completa.csv: En esta tabla se incluyen todas las carridas de todos los cubos que fueron revisados en un archivo de formato .csv

-tabla\_sofia\_final.csv: En esta tabla se incluyen los mejores resultados sin repeticiones de la revisión completa en un archivo de formato .csv. Estos se escogieron utilizando el reliability como parámetro para elegir el "mejor dato".

-tabla\_sofia\_final.xlsx: En esta tabla se incluyen los mejores resultados sin repeticiones de la revisión completa en un archivo de formato .xlsx. Estos se escogieron utilizando el reliability como parámetro para elegir el "mejor dato".

-tabla\_sofia\_final_stats.csv: Es una tabla generada en TOPCAT con las estadísticas de ciertas columnas de la tabla\_sofia\_final

## Carpeta Tablas cubos
Posee las tablas de todas las detecciones realizadas por SoFiA y las coincidencias encontradas con TOPCAT

