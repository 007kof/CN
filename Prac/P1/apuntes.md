### Commandos utiles de MatLab
- Para ejecutar una instruccion sin que nos salga el resultado, tenemos que anadir ";".
- Para crear un vector, hay que escribir los elementos del vector entre corchetes y separados por un espacio, por ejemplo:  
```
x = [3 5] == 3 5
```
- Para crear una matriz, hay que escribir los elementos entre corchetes, separados por espacios para las columnas y ";" para las filas, por ejemplo:  
```
x = [3 4 5;6 7 8] ==  
        3 4 5  
        6 7 8
```
- Otra manera de crear vectores es escribiendo el primer elemento, el intervalo y el ultimo elemento separado por ":", por ejemplo  
```
x = 1:0.5:2 == 1.0 1.5 2.0
```
- Para transponer una matriz, simplemente hay que anadir el operador "'", por ejemplo:  
```
x = [3 4 5;6 7 8]' == 
        3 6
        4 7
        5 8
```
- save *nombre\_del\_archivo* *variable o funcion*, guarda la _variable_ o _funcion_ en un archivo llamado _nombre\_del\_archivo_.
### Funciones utiles
- linespace(primero,ultimo,numero\_de\_elementos), por ejemplo:  
```
x = linespace(0,1,5) == 0.00 0.25 0.50 0.75 1.00
```
- rand(n,[m]), devuelve una matriz de n filas y m columnas con elementos aleatorios entre 0 y 1, si no se especifica m, se considera que la matriz es cuadrada.
- zeros(n,[m]), devuelve una matriz de n filas y m columnas de 0, si no se especifica m, se considera que la matriz es cuadrada.

