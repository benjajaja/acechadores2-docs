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
* publi adsense no abusiva a pié de página, nunca abusar de publicidad
* otras ideas para otro tipo de comentarios, menos tipo foro: http://news.ycombinator.com/ http://reddit.com -> los comentarios precisamente lo habia pensado tipo reddit, aunque sin tipo arbol, pudiendo quotear para seguir la linea 

* threads NSFW no muestra imagenes en vista general, requiere pulsar boton de advertencia tipo [“candado.abierto.o.cerrado”NSFW] al abrirlo se abre en todos los treads. guarda cookies ;)

comentarios
===========

* Anidados? mucha mas claridad, fomenta la discusion, el tema se puede desviar sin molestar al hilo en general.
pero es dificl de captar para usuarios inexpertos!
* Dajar muy claro que se esta *replicando a un comentario* en concreto, o *comentando en general*
* los comentarios podran contener imagenes que el servidor comprobara tamaño
de la imagen y con un limite de peso la mostrara o mostrara un texto tipo quote con enlace a la imagen y si es posible
una miniatura generada por el servidor
* se podra quotear 1 post o comentario. -> en mi humilde opinion, quotear es algo negativo: disminuye la legibilidad
(al menos cuando se quotea un comentario entero, no solo una linea en concreto) y fomenta que se discuta "con tal
de discutir", alienando los demas usuarios (piensa en un rollo como "ejercicios de argumentacion" del cole, a ver
quien es el mas listo).
* Si optamos por comentarios en arbol, quotear será mucho menos necesario (y probablemente solo lo usen los usarios
muy enzarzados en una discusion)
* Dicho lo anterior, sí que debe estar la posibilidad de quotear (ya que siempre puede copypastear simplemente), pero
seria un proceso mas manual
* los comentarios iran ordenados de mayor a menor puntuacion por defecto. alternativas seleccionables serian, tiempo y *???*
* tendran un umbral, si la puntuacion es menor que x, no serán cargados (pero el user puede pinchar en algo pa hacerlo)
* al ser manual el quote, las imagenes no se quotean, a no ser que el usuario vuelva a poner la misma, vamos
* los comentarios tendran un limite de texto o podran ser resumidos y pulsando como en la pag principal para que se agrande dinamicamente -> si
* los comentarios profundos (en la estructura de arbol) no se cargaran, solo al click en un enlace que diga "cargar 20 comentarios mas" p.ej.
