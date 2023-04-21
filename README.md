# Laboratorio # 3 | Computacion paralela y distribuida

## Instrucciones de ejecucion y de compilacion

#### Ejecucion del programa secuencial
Compilacion
mpicc <nombre_del_programa>.c -o <nombre_del_ejecutable>
Ejecucion
./<nombre_del_ejecutable>

#### Ejecucion del programa paralelo
Compilacion
gcc <nombre_del_programa>.c -o nombre_del_ejecutable -fopenmp
Ejecucion
./<nombre_del_ejecutable>