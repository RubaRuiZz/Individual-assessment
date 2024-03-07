He creado las dos imagenes, los dos contenedores.

Uno para el Grobid, que tiene la funcionalidad de coger la biblioteca de globid con un Dockerfile que hace un From de globid.

Y otro que sirve como cliente, donde encontramos el script con las funciones pedidas, una carpeta con todos los papers, y luego diferentes carpetas que sirven par guardar los ficheros de salida.

ficheros de salida: los xml, la imagen de la lluvia de ideas, el esquema del numero de figura de cada paper y los links que se encuentran en cada paper.

Ambos contenedores estan conectados mediante una network.
   docker network create name_network

Esta es la idea que he tenido y no he llegado a conseguir el resultado esperado.

Seguramente si durante esta semana lo consigo lo subire aunque no este en fecha, por si hay alguna manera de entregarlo en la extraordinaria.
