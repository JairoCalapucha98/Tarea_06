# Tarea_06
Repositorio para la Tarea_06
# Detalles de la actvidad
ACTIVIDADES REALIZADAS
Creamos un módulo llamado alelos.py para trabajr con las tres funciones solicitadas:

##Función 1. Creacción de la población
Debemos crear una función de simulación "build.population" importando datos del modulo scipy considerando como tamaño de entrada la población (N) y una variable de salida la probabilidad de tener un alelo "A" o "a"(p). Se crea un listado vación llamado "population" y para cada elemnto dentro del rango "N". Se crea dos alelos el "A" y "a", el calculo y la combinaciones se realiza si son > p.

##Función 2. Cuantificación de frecuencias de alelos
Creamos la función "compute_frecuencias" para calcular las frecuencias genotipicas utilizando el argumento de entrada los datos de población (population) que contiene combinaciones alelicas de "AA" "Aa", "aA" y "aa".

##Función 3. Creación de la población hijo (100 generaciones)
Creamos la función "reproduce_populatión" que toma la población actual y genera la proxima generación de individuos. Se crea un listado vación llamado "new_generation" y dentro del rango N, se realiza una combinación aleatorio, creando asi los progentiores llamado "dad" "mom" . luego, secruza los cromosomas del padre y de la madre, creando asi una nueva generación.

##Resultados
Se obtuvieron 100 generaciones, y los resultados dan individuos homocigotos y heterocigotos. Durante las tres primeras generaciones obtienen indivudos Homogicotos dominantes ("AA"), individuos homogicotos recesivos ("aa"), y algunos inidivuos heterocigotos "aA" y "Aa".
