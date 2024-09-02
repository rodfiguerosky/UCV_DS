# Universidad Central de Venezuela ![UCV_DS](https://compex.ciens.ucv.ve/producto/ciencia-de-los-datos/ "link Diplomado")  

## Asignacion_01   
   * Fuente de datos (archive_movies_csv.zip): ![data_set_movies_tv_shows](https://www.kaggle.com/datasets/krishnaraj30/movies-and-tv-shows)
   * Se realizo un conteo de ocurrencia de las categorias (i.e. el campo Listed In), por ejemplo: Comedy, Drama, etc.

## Asignacion_02
   * Exploracion_Viz: 5 graficos con matplotlib  de las Peliculas y Series

   * Fuente de datos (archive_movies_csv.zip)

## Asignacion_03 (random naive bayes)
   * Classificacion Bayesiana (Naive)
   * Proyecto: Identificacion segun el genero del publico consumidor 

   Clasificación “automática”

    Nuestra clasificación consistirá en asignar un puntaje (score) que adjudique si la película en cuestión está orientada al público masculino o femenino.

    Cuanto más alto se cifre el puntaje en la escala positiva, cuanto mayor en escala la película estará más orientada al público masculino. Y por tanto, la película se clasificará con +1.

    Cuanto más alto se cifre el puntaje en la escala negativa, denotara que la película en cuestión estará más orientada al público femenino. La película se clasificará con -1, para el público femenino.

    Cuanto más cercano a 0 en el puntaje en la escala implicará que la película estará clasificada como de orientación neutra; ie. La película está orientada tanto para el género masculino como para el femenino.

Para calcular el puntaje (score):

    Tomaremos los campos cast y listed_in:

    En cast lo que pretendemos es identificar el genero (masc ó fem) del elenco cast en cada una de las peliculas.

    Sí los nombres en cast son masculinos o femeninos se le adjudicará un puntaje de +1/-1 respectivamente. Para adjudicar el género se tomará la última letra del nombre de los participantes. Las terminaciones en: e, o, d, h, n, m, l, g, ó sus combinaciones pares, por ej. 'en', 'hn','oh','on', etc. en cada uno de los nombres serán clasificadas con un puntaje de +1 (masculino). Todas las terminaciones distintas a las antes mencionadas !(e, o, h, n, m, l, g) serán clasificadas con un puntaje -1 (femenino).

**Nota: Ciertamente las reglas de pre-procesamiento para indentificar el genero del elenco de en la variable cast necesita una elaboración más rigurosa. No obstante, para fines ilustrativos las consideraremos en esta asignación.** 

## Analisis de Cluster (pendiente)



## Asignacion_04 (FP Growth)
   * Algoritmos de asociacion, en este caso se utilizo (Frequent Pattern Growth) -FP Growth-
   * Se reliazo una propuesta para un sistema de recomentacion de peliculas segun las preferiencias el genero (ie. Comedia, Drama,... )
   * Fuente de datos (archive_movies_csv.zip)

## Asignacion_05 (textmine)
   * Fuente de datos: ![Miguel de Cervantes - El Quijote - ](https://www.gutenberg.org/cache/epub/15115/pg15115.txt)
   * Se separaron el cap 10 y 11; (cap_10_cervantes.txt) (cap_10_cervantes.txt)
   * Realizamos un conteo relativo de palabras y frases tanto en capitulo 10 y 11.   

## Proyecto_Final_DS
   * Proyecto; Analisis de clasificario de topicos jerarquizados en los distintos buscadores segun palabras clave. 
   
   Procedimiento de busqueda de datos:

    Las consultas se realizaron en el meta-buscador: ![searx](https://metasearx.com/)
    Realizamos consultas de la ultima semana de noticias respecto al dia de hoy '19-09-2032' con la palabra o termino "Venezuela": http://searx.thegpm.org/?q=venezuela&categories=news&time_range=week&language=en
    Las busquedas resultantes en formato *.json (vease: Projecto_final_DS_data_json )



