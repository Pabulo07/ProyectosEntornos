# Tarea 5: Depuración
##### 1. Explicar QUÉ HACE EL MÉTODO MAIN. 
El programa comienza declarando la variable TAMANYO con un valor máximo de 10, la cual es asignada como tamaño de los dos arrays que se declaran a continuación.

Comienza el método 1 con rellenarArray y los muestra a continuación sin ordenar y ordenados guardando el tiempo que ha necesitado para ejecutar las acciones restando el tiempo que ha durado el algoritmo antes y después de ejecutarse.

En el segundo método también se muestra la lista del vector sin ordenar y ordenado y el tiempo que ha tardado con la diferencia de que para ordenarlo utiliza el método countingSort, reduciendo el tiempo de procesado.

##### 2. Poner un punto de ruptura (breakpoint) en la línea 78 (primer bucle del método intercambio) y, basándoos en los valores que van tomando las variables, explicad cómo funciona el método de ordenación de arrays por intercambio. Podéis crear tablas para ver cómo cambian los valores de los arrays.

La clase intercambio usada para el método 1 usa dos bucles for donde inicia i = 0 en el primero y j = i+1 en el segundo. Se basa en comparar el array en la posición "i" y "j" del for. Si lista[i] es mayor que lista[j] entonces lista[i] se guarda en una variable auxiliar y se convierte en lista[j] por medio de un igual, lista[j] entonces se covierte en la variable auxiliar. Para poder tener en cuenta todo el array y comparar todos los números entra en juego el doble for, el int i se mantiene en 0 hasta que j llega al máximo (longitud lista) y pasa al siguiente. Repite el proceso hasta que todos los números de lista quedan ordenados de menor a mayor.

##### 3. Poner un punto de ruptura (breakpoint) en la línea 94 y explicad cómo funciona el método de ordenación de arrays de conteo. Podéis crear tablas para ver cómo cambian los valores de los arrays.
El primer for se encarga de recorrer el array que le hemos pasado y crea un valor 1 en la posición del mismo valor en un nuevo array llamado count.

##### ARRAY
|  posición |valor   |
|---|---|
|  [0] | 4  |
|  [1] | 1  |
|  [2] | 6  |
|  [3] | 2  |
|  [4] | 6  |

##### COUNT
| posicion  |valor   |
|---|---|
|  [0] |   |
|   [1]|  1|
|  [2] |  1|
|   [3]|  |
|   [4]|  1|
|   [5]|   |
|   [6]|  2|
|   [7]|   |
|   [8]|  |
|   [9]|   |

Comparando i con el array de count y se busca el número que es más pequeño, al coincidir escribe el valor en la posición z del array y se suma uno a z para seguir con la siguiente posición del array.


##### EVOLUCIÓN 
|posicion|ciclo1|ciclo2|ciclo3|ciclo4|ciclo5|
|---|---|---|---|---|---|
|  [0] |   4|  1 | 1  | 1  | 1  |
|  [1] |   1|   1|  2 | 2  | 2  |
|  [2] |   6|   6|  6 | 4  | 4  |
|  [3] |   2|   2|  2 | 2  | 6  |
|  [4] |   6|   6|  6 | 6  | 6  |  

