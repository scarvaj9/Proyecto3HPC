Documento de metodología PCAM


El problema sobre el cual vamos a trabajar es sacar el polindromo inverso de una cadena de ADN,
para el los dataset tomamos los registros de ADN de la pagina https://www.ncbi.nlm.nih.gov 
en la cual usamos registros de bacterias moscas entre otros.


Partición 
lo que buscamos hacer en la partición de los datos, es después de leer un archivo en el cual 
esta la cadena de ADN a procesar, buscamos que el total de la cadena de ADN del archivo sea 
dividida por el numero de procesadores y así quede en tamaños iguales para que sea asignado 
a cada procesador y así poder hacer un procesamiento mas rápido y eficaz del palindromo inverso.  


comunicación 
después de el procesamiento de los datos en bloques dividido en el numero de procesadores lo que
hacemos es una concatenación de dichos bloques en el orden de llagada para imprimir los datos en 
un fichero de salida que nos da la posición y la longitud de los palindromos inversos que 
estábamos procesando.


Aglomeración.
Todos los datos a medida que se van procesando en los bloques y se concatena en el fichero de 
salida se van imprimiendo todos los datos de posición y longitud de los palindromos inversos 
que es lo que estamos procesando. 


Mapeo 
después de tener el archivo de salida en esta tenemos los datos pedidos concatenados y listados 
en orden después de el procesamiento completo de todo el fichero de entrada. 
