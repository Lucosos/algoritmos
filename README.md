# algoritmos
codigo de las tareas


http://kio4.com/appinventor/



par amecatronica, hacer una apliacion en app inventor 2, intentar descargar la aplicacion offline con el emulador, al aprecer solo esta dissponible wn wind0ows.
en la aplicacion puedo mandarle las ordenes por botones como estaba planificado al principio, 

tambien poner la posibilidad de que se pueda ingrear por texto los comandos

la otra opcion es que se pueda decir los comandos por voz, es decir apretar un boton que reconocera la voz, para decir las ordenes que seguira el robot, tal como avanza 8 metros, gira a la izquierda 30 grados, etc con su respectiva estructura 
la idea es poder dar mas de una orden a la vez: ej, avanza 8 metro, luego gira a la izquierda 90 grados, despues avanza 2 metros etc, entonces se debo leer todas las ordenes y hay que hacer parseo para poder separar el texto entero, en ordenes pueda seguir el robot.

(aca habrá que hacer un parseo y todo lo que conlleva, pasar lo que se dijo por voz y separarla en ordenes)
**(talvez usar distancia entre string (tarea algoritmos)  para hacer que encajen comandos, onda el que tiene la menor distancia entre los comandos disponibles y la palabra dicha, va  a ser el comando que se eligira )


La idea es que en la pantalla del celular se enlisten estas ordenes, por orden en el que se dijo, una sobre otra, 
OJO! como las ordenes no se efectuan de inmediate, se mandará una ordena, y la orden siguiente no se mandara hasta que la ordne ya mandadad se termine , entonce el arduino tiene que madnar un tipo de orden al celular diciendo que esta listo para otra orden, entonces mandar la orden que esta en espera en la cola, ademas de borrar la que ya termino y desplazar la cola.ademas se podria decir en pantalla, que se esta efectuando tal orden .

También se podría incluir un detector ultrasonido para avisar que llego a un obstaculo, ademas se podria agregar un obstaculo sea  un estado dentro del lenguaje, por ej, avanza 8 metros, si hay un obstaculo girar a la izquierda 30 grados,avanzar 3 metros, etc
(SI ES MUY DIFICIL, QUE SOLO AVISE QUE HAYA UN OBSTACULO)


tambien dentro del lenguaje se podria hacer una especia de while, por ej mientras que haya un obstaculo, girar a la izq 20 grados.(INVIABLE)


(INVIABLE) Usar camara y bajarme alguna cosa de internet(?),para que de la imagen pueda "reconocer algun obstaculo" para luego evitarlo 
(INVIABLE)Hacer una especie de trayectoria inteligente,dependiendo de los obstaculos(usando camara o ultrasonido)

(INVIABLE)Hacer que retroceda.Puede ser parte del lenguaje.



