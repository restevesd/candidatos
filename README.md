# Visualizando los candidatos a la presidencia del Ecuador

## Antedecedentes

En Ecuador el mes de Febrero del 2021 son las elecciones presidenciales, elecciones marcadas por un año 2020 de pandemia y recesión económica, por lo que se vuelve una de las más importantes desde el regreso a la vida democrática del Ecuador.

Como particularidad tenemos 16 binomios presidenciales inscritos para la lid electoral, pueden ver los candidatos aquí -> https://es.wikipedia.org/wiki/Elecciones_presidenciales_de_Ecuador_de_2021

## Objetivos 

Necesitamos hacer un seguimiento a todos los candidatos a la presidencia, tanto lo que ellos dicen como lo que dicen de ellos, de esta manera podemos tener una idea más clara de las propuestas de campaña.


### Leer el post completo 

Más información del proyecto lo pueden encontrar aquí -> https://masapp.medium.com/visualizando-los-candidatos-a-la-presidencia-del-ecuador-ac3f499bf58


### Datasets Utilizados 

Para este dashboard se están utilizando dos dataset

• Candidatos: Con los tweets de los candidatos a la presidencia del Ecuador 2021 
• Tweet_Data2: Con los tweets que se menciona las cuentas de los candidatos a la presidencia del Ecuador 2021

Ambos archivos están en formato CSV, el primer dataset tiene +20K registros, el segundo dataset tiene +1M registros

Por un tema de peso el dataset Tweet_Data2 lo encuentran aquí -> https://drive.google.com/drive/folders/1pWSyK1GRfgV3WGey3EYL03fRAlSepEry?usp=sharing

### Columnas

* user_id
* status_id
* created_at
* screen_name
* text
* source
* reply_to_screen_name
* is_retweet
* is_quote
* retweet_count
* quote_count
* reply_count
* hashtags
* mentions_screen_name
* retweet_screen_name
* description
* followers_count
* friends_count
* statuses_count
* favourites_count
* account_created_at
* text_cleaned

## Construido con

* [R](https://cran.r-project.org/bin/windows/base/)
* [R Studio](https://rstudio.com/products/rstudio/download/)
* [MySQL](https://dev.mysql.com/downloads/)
* [Amazon Lightsail](https://lightsail.aws.amazon.com/)
* [Dockers](https://www.docker.com/)

## Autores

Este trabajo es realizado por [Masapp] (http://www.masappec.com) y gracias a la participación de:

* **María Fernanda Jurado** -* FrontEnd*- 
* **Roberto Esteves** - *BackEnd* - https://www.linkedin.com/in/restevesd/

## Licencia

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Licencia de Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />Este obra está bajo una <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">licencia de Creative Commons Reconocimiento 4.0 Internacional</a>.

## Expresiones de Gratitud 

* Síguenos en nuestras redes sociales
* Twitter - https://twitter.com/masappdata
* Facebook - https://www.facebook.com/MasappEC
* LinkedN - https://www.linkedin.com/company/masapp/
* Medium - https://masapp.medium.com/

