### Commandos utiles de MatLab
- Para ejecutar una instruccion sin que nos salga el resultado, tenemos que anadir **;**.
- Para crear un vector, hay que escribir los elementos del vector entre corchetes y separados por un espacio, por ejemplo:  
```
x = [3 5] == 3 5
```
- Para crear una matriz, hay que escribir los elementos entre corchetes, separados por espacios para las columnas y **;** para las filas, por ejemplo:  
```
x = [3 4 5;6 7 8] ==  
        3 4 5  
        6 7 8
```
- Otra manera de crear vectores es escribiendo el primer elemento, el intervalo y el ultimo elemento separado por **:**, por ejemplo  
```
x = 1:0.5:2 == 1.0 1.5 2.0
```
- Para transponer una matriz, simplemente hay que anadir el operador **'**, por ejemplo:  
```
x = [3 4 5;6 7 8]' == 
        3 6
        4 7
        5 8
```
- save **nombre\_del\_archivo** **variable** o **funcion**, guarda la **variable** o **funcion** en un archivo llamado **nombre\_del\_archivo**.
- load **nombre\_del\_archivo**, carga todas las funciones o variables que estaban guardadas en el archivo **nombre\_del\_archivo**.
- Extraer elementos de una matriz:
```
x = M(i,j)
```
los indices empiezan con 1, tambien se puede usar la palabra **end** que representa el ultimo indice.
- Para extraer todos los elementos de una dimension hay que usar el operador **:**, por ejemplo:  
```
x = M(i,:)
```
x contiene todos los elementos de la fila i.
- Para diferenciar los operadores entre matrices y elementos de un vector, hay que anadir *.* delante de la operacion, por ejemplo:  
```
x = [3 4] .* [10 20] == 30 80
```
- Algunas funciones como el max(x), pueden devolver multiples salidas, como por ejemplo:  
```
[xMax,idx] = max(x)
```
xMax tendra el valor maximo del vector x y idx tendra la posicion del valor maximo del vector x.
- Para buscar informacion de las funciones de MatLab: **doc fcName**.
### Funciones utiles
- linespace(primero,ultimo,numero\_de\_elementos), por ejemplo:  
```
x = linespace(0,1,5) == 0.00 0.25 0.50 0.75 1.00
```
- rand(n,[m]), devuelve una matriz de n filas y m columnas con elementos aleatorios entre 0 y 1, si no se especifica m, se considera que la matriz es cuadrada.
- zeros(n,[m]), devuelve una matriz de n filas y m columnas de 0, si no se especifica m, se considera que la matriz es cuadrada.
- max(x), devuelve el numero maximo de un vector.
- round(x), devuelve el numero redondeado a partir de 0.5.
- plot(x,[y],[...]), dibuja un grafico 2D, para dibujar encima del mismo grafico, hay que escribir la instruccion **hold on** y para dejar de dibujar encima **hold off**.
    - Opciones para dibujar el grafico:
        - 'r': Color rojo
        - '-': Linea continua
        - '--': Linea discontinua
        - 'LineWidth',**num**: Grosor de la linea.
