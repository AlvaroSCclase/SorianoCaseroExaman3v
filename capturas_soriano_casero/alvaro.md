#se creo el repositorio dentro de la carpeta_examen, ademas se creo la carpeta capturas_soriano_casero dentro y el fichero alvaro.md dentro de la carpeta antes mencionada , alvaro.md fue añadido al area de intercambio#
#tras realizar el git add Todos se encuentran en el mismo estado ya que nunca se a hecho un commit por tanto al añadirlos todos hemos vuelto a cargar el fichero alvaro.md#
#crearemos el fichero gitignore y introduciremos la ruta del fichero alvaro.md para que no lo incluya al hacer un git add . #
#añadiremos al fichero gitignore la ruta de la carpeta de las capturas para que esta no sea incluida en git add . (a mi si me aparacen pero estas no se estan incluyendo realmente)#
#se realizo una instantanea de lo realizado hasta ahora en el repositorio #
#se creo un nuevo fichero llamado trabajo_alvaro y se le añadio dos lineas, este se añadio al area de intercambio#
#se realizo un commit para que se incluyera la creacion y la modificacion del fichero trabajo_alvaro.md#
#se añadio dos lineas mas al fichero trabajo_alvaro.md#
#se crea una instantanea  del fichero trabajo_alvaro.md ahora que posee dos lineas mas#
#mediante el id del commit obtenido del git log se pudo restaurar el fichero trabajo_alvaro.md al momento que solo poseia dos lineas con el comando git -restore #
#tras añadir dos lineas al fichero trabajo_alvaro.md  y hacer el commit podemos ver que este cambia ya que ahora este a cambiado a una version nueva en el nuevo commit#
#se cambio el comentario del commit anterior para indicar que este a cambiado#
#fusionaremos la rama master con la rama_soriano cambiando primero con checkout al master y haciendo un merge#
#se creo la rama_casero con el checkout , se añadio una linea a trabajo_alvaro.md  y se hizo un commit#
#en el git log podemos ver los distintos cambios de las ramas y como se fue modificando el fichero trabajo_alvaro.md (posdata me equivoque y creee la rama main luego la borre)#
#creamos un proyecto de netbeans en el repositorio , creamos la rama netbeansSoriano  y crearemos el metodo que imprimira nuestro nombre#
