# proyecto-2-imagenes
En el proyecto se hizo eleccion de la base de datos CIFAR-10 para aplicarle el filtro
FIND_EDGES que funciona para realizar la deteccion basica de los bordes en las imagenes
Se realizo de tres formas por mera curiosidad, se realizo la aplicacion del filtro con 
una conversion a escala de grises donde se vieron como resultados, una porcentaje de 
acierto muy bajo, por lo que se procedio a realizar una 2da aplicacion del filtro pero 
ahora se realizo con RGB que mantiene la saturacion de colores originales dando una
visaulizacion mejorada de los bordes de las imagenes. 
Para finalizar se realizó con las imagenes un analisis de bordes pero ahora con una red convolucional, 
ya que presenta una mejor interaccion con la idea del proyecto, identificar los objetos que se encuentran en las imagenes. 

Haciendo una comparativa sobre las 3 tecnicas utilizadas, se puede decir que el uso de una CNN es necesaria, ya que presenta una mejor 
precision a la hora de dar un resultado sobre lo que se encuentra en las imagenes, a pesar de que se quedo el aprendizaje en un 71% de presicion
es aceptable y mejor que sus versiones que fueron de forma manual, por lo que podemos decir que el uso del machine learning para esta tarea es necesario o el 
mas optimo para la tarea de analisis de imagenes. 
