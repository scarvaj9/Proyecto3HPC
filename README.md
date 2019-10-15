# Proyecto3HPC
Locating Restriction Sites Solution with large dataset using mpi4py running on HPC

#### ¿Cómo ejecutar los programas?
1. Secuencial
*Si se quiere ejecutar el programa en serial se debe poner la siguiente línea, python3 SecuencialProyecto3.py*

2. Paralelo
*Si se quiere ejecutar el programa en paralelo se debe poner la siguiente línea, mpirun.openmpi -np  (número de nucleos)  python3 ParallelProyecto3.py*
# 1. Realizado por:
1. Mateo Alexander Zabala Gutierrez - mzabala1@eafit.edu.co
2. 	Smith Alexis Carvajal Orozco - scarvaj9@eafit.edu.co
### Estudiantes de la Universidad EAFIT
# 2. Introducción:
En éste repositorio se encuentran dos programas (uno en serial o secuencial y otro en paralelo) que sirven para encontrar el complemento inverso que ala vez nos sirve para encontrar el
 palindromo inverso de una cadena de ADN.
 
 Un ejemplo de esto es: GCATGC el cual es un palindromo inverso ya que su complemento inverso es GCATGC. 
 
 El programa devuelve la posición y la longitud de cada palindromo inversoen la cadena de texto que es pasada.

# 3. Análisis de solución:
*Al correr los dos programas, cada uno con el mismo documento con la misma cantidad de datos se observaron los siguientes aspectos*
1. ![Comando HTOP corriendo el programa en serial](/imagenes/secuencial.png)
2. ![Tiempo de ejecución del programa en serial](/imagenes/paralelo.png)
# 6.Bibliografía:
1. https://pythonprogramming.net/sending-receiving-data-messages-mpi4py/?completed=/mpi4py-size-command-mpi/
2. https://pypi.org/project/mpi4py/
3. https://mpi4py.readthedocs.io/en/stable/tutorial.html
