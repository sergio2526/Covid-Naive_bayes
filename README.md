### Algoritmo naive bayes Covid-19 en Colombia 

Se analizo el data set correspondiente de los casos registrados de covid-19 en Colombia
desde la fecha de diagnostico 6/03/2020 - 12/04/2020.

Se obtuvieron los datos del siguiente enlace [Covid-19 Colombia](https://cutt.ly/ttYaOcc)

Con el objetivo de clasificar nuevos casos entrantes en el algoritmo, se baso en los casos denominados Casa, Hospital, Uci, Fallecidos


### Limpieza de datos
Se desarrollo la respectiva limpieza de datos en los cuales se exporto un archivo .csv
con el nombre de Casos-coronavirus-colombia en el cual solo se trabajo con los casos que reportaban Casa, Hospital, Uci, Fallecidos.

### Entrenamiento
Los datos fueron entrenados con 2004 registros equivalentes al 80% y con un numero de prueba de 502 equivalente al 20% de los registros. 

### Entregable
En el archivo prediccion.csv se encuentra como resultado la clasificación trabajado con el algoritmo naive bayes.
