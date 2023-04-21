# Laboratorio # 3 | Computacion paralela y distribuida

## Instrucciones de ejecucion y de compilacion

#### Ejecucion del programa secuencial
Compilacion
</br>
mpicc <nombre_del_programa>.c -o <nombre_del_ejecutable>
</br>
Ejecucion
</br>
./<nombre_del_ejecutable>

#### Ejecucion del programa paralelo
Compilacion
</br>
gcc <nombre_del_programa>.c -o nombre_del_ejecutable -fopenmp
</br>
Ejecucion
</br>
./<nombre_del_ejecutable>
