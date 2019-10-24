Documento de metodología PCAM

Particionado 

nuestro problema a trabajar es encontrar los palindromos inversos en una cadena de ADN, de una gran longitud. Lo que hace nuestra aplicación cuando vamos a procesar el archivo en paralelo, es particionar la información de la cadena de ADN almacenada en el archivo, entre el numero de procesadores que le especificamos que íbamos a utilizar.

Comunicación

Después de particionar el problema entre el numero de núcleos a utilizar, debemos mantener una relación de orden entre estos nodos divididos, ya que debemos tener en cuenta en que posición esta el palindromo inverso en el fichero, por ende debemos llevar el orden del archivo completo a la hora de dividir la tarea. 

Aglomeración

En la aglomeración de los datos lo que hacemos es tomar todos los datos procesados por cada procesador y llevarlos a un archivo de salida en el que vamos a poner la posición y la longitud de el palindromo inverso que hemos encontrado en la cadena de ADN y así los vamos listando uno a uno. 

Mapeo 

El fin del proceso es tener un archivo de salida con todas las posiciones y longitudes de los palindromos inversos de la cadena de ADN sobre la que hemos trabajado y así tener todo el archivo procesado por cada procesador 
