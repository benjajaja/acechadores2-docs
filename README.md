meta
====

Reddit, hecho en 3 semanas por dos carapanes, ahora es "la portada de internet". muchisimos usuarios, y usuarios que
abren reddit.com como primera pagina cuando abren el navegador. queremos ser lo mismo pero pa españoles.
lo que yo creo que son las claves de exito de reddit:

* usabilidad
* legibilidad
* fiabilidad


algoritmo acechadores 
=====================

* 3 dias? -> 
* votaciones x hora posteado? -> 
* votaciones totales en total de dias? -> 
* caducidad de votos a partir de 3 dias los votos valen -½ y al 4º no cuentan, aunque siempre se mostrara el total -> 
* se fomentará los vosotos nuevo que mantendran vivo el thread? ->
* solo votos positivos o tambien negativos? los negativos valen ½? y no se contabilizaran? ->
* *hemos de obtener un "algoritmo" de portada sofisticado, todas estas ideas son interesantes y creo que algunas no
se han probado* -> en general, lo que queria era hacer un agoritmo con todas esas ideas o mas xD

diseño acechadores
==================

* html5 TODO dinamico -> 
* conexión websockets. permite al servidor enviar datos al cliente *sin* que el cliente tenga que "sondear"
en un intervalo. por ejemplo, se hace un post nuevo, a todos los clientes viendo la portada, se les inserta, algo
similar a facebook
* los threads se veran desde la misma pagina principal pulsando titulo o contenido para ver mas
* de hecho, *toda* la aplicacion sera de "pagina unica" - no se recarga nunca, las "paginas" subsecuentes se cargan
por XHR/Websockets -> eso es justo lo que queria :)
* mostrara 10 “threads” la pagina principal -> ok
* los comentarios se veran de 10 en 10 divididos por paginas, podran contener imagenes que el servidor comprobara tamaño
de la imagen y con un limite de peso la mostrara o mostrara un texto tipo quote con enlace a la imagen y si es posible
una miniatura generada por el servidor ->
* se podra quotear 1 post o comentario. ->
* en primera pagina de coments se veran los ultimos y tambien se pueden mostrar hasta 2 destacados a demas de los otros 10 ->
* en caso de quotear coment con imagen la imagen se redimensionará al tamaño del ejemplo de la imagen de gran peso. ->
* en caso de que con el voto el thread debiera con el calculo actual superar algun otro thread, se movera dinamicamente ->
* los comentarios destacados estaran los 2 primeros y se veran destacados
* los comentarios tendran un limite de texto o podran ser resumidos y pulsando como en la pag principal para que se agrande dinamicamente ->
* publi adsense no abusiva a pié de página, nunca abusar de publicidad
* otras ideas para otro tipo de comentarios, menos tipo foro: http://news.ycombinator.com/ http://reddit.com -> los comentarios precisamente lo habia pensado tipo reddit, aunque sin tipo arbol, pudiendo quotear para seguir la linea 

* threads NSFW no muestra imagenes en vista general, requiere pulsar boton de advertencia tipo [“candado.abierto.o.cerrado”NSFW] al abrirlo se abre en todos los treads. guarda cookies ;)

