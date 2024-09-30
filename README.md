# Universidad Central de Venezuela ![UCV_DS](https://compex.ciens.ucv.ve/producto/ciencia-de-los-datos/ "link Diplomado")
<img src="https://compex.ciens.ucv.ve/wp-content/uploads/2024/02/2.png" width="500">

## Asignacion_01   
   * Fuente de datos (archive_movies_csv.zip): ![data_set_movies_tv_shows](https://www.kaggle.com/datasets/krishnaraj30/movies-and-tv-shows)
   * Se realizó un conteo de ocurrencia de las categorías (i.e. el campo Listed In), por ejemplo: Comedy, Drama, etc.

## Asignacion_02
   * Exploracion_Viz: 5 gráficos con matplotlib  de las películas y series

   * Fuente de datos (archive_movies_csv.zip)

## Asignacion_03 (random naive bayes)
   * Clasificación Bayesiana (Naive)
   * Proyecto: Identificación según el género del público consumidor 

Objetivo: Clasificación “automática”   
Nuestra clasificación consistirá en asignar un ***puntaje-score*** que adjudique si la película está orientada al público masculino 🚹 o femenino 🚺.

Cuanto más alto se cifre el puntaje en la escala positiva, cuanto mayor en escala la película estará más orientada al público masculino. Y, por tanto, la película se clasificará con +1.

Cuanto más alto se cifre el puntaje en la escala negativa, denotará que la película en cuestión estará más orientada al público femenino. La película se clasificará con -1, para el público femenino.

Cuanto más cercano a 0 en el puntaje en la escala implicará que la película estará clasificada como de orientación neutra; ie. La película está orientada tanto para el género masculino como para el femenino.

Para calcular el puntaje (score):
Tomaremos los campos 'cast' y 'listed_in':

En cast lo que pretendemos es identificar el género (masc ó fem) del elenco cast en cada una de las películas.

Si los nombres en 'cast' son masculinos o femeninos, se le adjudicará un puntaje de +1/-1 respectivamente. Para adjudicar el género se tomará la última letra del nombre de los participantes. Las terminaciones en: e, o, d, h, n, m, l, g, ó sus combinaciones pares, por ej. 'en', 'hn','oh','on', etc. en cada uno de los nombres, serán clasificadas con un puntaje de +1 (masculino). Todas las terminaciones distintas a las antes mencionadas, (e, o, h, n, m, l, g) serán clasificadas con un puntaje -1 (femenino).

**Nota: Ciertamente, las reglas de pre-procesamiento para identificar el género del elenco de en la variable cast necesitan una elaboración más rigurosa. No obstante, para fines ilustrativos las consideraremos en esta asignación.** 

## Analisis de Cluster (pendiente)

## Asignacion_04 (FP Growth)
   * Algoritmos de asociación, en este caso se utilizó (Frequent Pattern Growth) -FP Growth-
   * Se realizó una propuesta para un sistema de recomendación de películas según las preferencias, el género (ie. Comedia, Drama,... )
   * Fuente de datos (archive_movies_csv.zip)

## Asignacion_05 (textmine)
   * Fuente de datos: ![Miguel de Cervantes - El Quijote - ](https://www.gutenberg.org/cache/epub/15115/pg15115.txt)
   * Se separaron el cap 10 y 11; (cap_10_cervantes.txt) (cap_10_cervantes.txt)
   * Realizamos un conteo relativo de palabras y frases tanto en capítulo 10 como 11.   

## Proyecto_Final_DS
   * Proyecto: Análisis de clasificatorio de tópicos jerarquizados en los distintos buscadores según palabras clave. 

  * Procedimiento de búsqueda de datos:Las consultas se realizaron en el meta-buscador: ![searx](https://metasearx.com/)
Realizamos consultas de la última semana de noticias respecto al día de hoy '19-09-2023' con la palabra o término "Venezuela": http://searx.thegpm.org/?q=venezuela&categories=news&time_range=week&language=en
  *  Las búsquedas resultantes en formato *.json (véase: Projecto_final_DS_data_json )




