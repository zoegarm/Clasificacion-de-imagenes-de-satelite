# Clasificación no supervisada de imágenes de satélite y radar.
 
### :round_pushpin: Equipo: 2

### :round_pushpin: Integrantes: Juan Luis Carrillo, Atenea De La Cruz Brito, Zoé Ariel García Martínez

### Objetivo: Clasificar las áreas urbanas, verdes y cuerpos de agua

### Metodología: Algoritmo no supervisado, K-Nearest Neighbor Classifier

El proyecto de Machine Learning que llevaremos a cabo se plantea a partir de una problemática ambiental y social de gran importancia para nuestro país, los cambios en el medio natural y sus efectos en el territorio. Con cambios nos referimos a todos los fenómenos medioambientales como temporales, huracanes, entre otras manifestaciones naturales, así como aquellos que son producto de la acción humana como sobre-explotación de las cuencas y cuerpos de agua, incendios provocados, crecimiento de la mancha urbana, entre otros. Para este proyecto en particular, nos abocaremos a los cambios provocados por aumento del caudal de los ríos e inundaciones, no obstante, este desarrollo puede aplicarse para la identificación de otros cambios en el territorio. El propósito de este proyecto es clasificar con un algoritmo no supervisado, las áreas urbanas, verdes y cuerpos de agua en periodos regulares así como los terrenos inundados en temporadas de lluvia a partir de imágenes de satélite.

México es un país con gran diversidad en su territorio, tanto en clima como en flora y fauna. La República Mexicana se ubica entre las zonas tropicales y templadas. Además de tener una posición latitudinal que contiene grandes desiertos, con un relieve y posición entre dos océanos que permite una distribución de climas con presencia de corriente marítimas cálidas y frías (Labastida y Ruiz, 2010). Asimismo, las temperaturas y la precipitación en el territorio presentan grandes contrastes tendiendo a los extremos, con promedios anuales de lluvia de sólo 50 mm en las zonas y temporadas más secas hasta 5,500 mm en promedio anual para las áreas y meses más húmedos (Rzedowski, 2006). El área de estudio de nuestro proyecto se ubica en este segundo tipo y corresponde a la zona oeste de Villahermosa en el estado de Tabasco.

En el estado de Tabasco se encuentran al menos catorce puntos críticos de inundación catalogados por la Comisión Nacional del Agua y el Centro Nacional de Prevención de Desastres (CONAGUA-CENAPRED, 2018). El área ha sufrido diversas inundaciones, en años recientes hemos sido testigos de los efectos devastadores de las inundaciones en dicha zona. El suceso más reciente ocurrió en octubre de 2020, y tuvo como saldo ocho fallecimientos, más de noventa mil personas damnificadas, pérdida de cultivos y daños materiales por millones de pesos en dicho estado.

<p align="center">
  <img src="/img_files/Captura_radar.PNG" "Atlas de Riesgos, Gobierno Federal, CENAPRED." "Atlas de Riesgos, Gobierno Federal, CENAPRED." alt="NF"/>
Atlas de Riesgos, Gobierno Federal, CENAPRED.
  
Debido a lo anterior, nuestro proyecto de Machine Learning de clasificación de imágenes de satélite busca servir como base para la distinción y análisis de la información proveniente del monitoreo satelital para identificar los riesgos naturales que se presentan con más frecuencia en nuestro país mediante un proceso rápido y oportuno.

Para desarrollar este proyecto planteamos aplicar un algoritmo no supervisado para la clasificación de imágenes del satélite Sentinel-2 instrumento multi-espectral Nivel A2, las cuales se obtendrán por medio de Copernicus Open Access Hub. Para la aplicación se propone emplear el clasificador de K-Vecino más próximo (K-Nearest Neighbor Classifier, K-NN).

```
Fuentes:
 
Labastida, Jaime y Ruiz, Rosaura (coord.) (2010). "El Territorio Mexicano. 7.1.3. Factores que influyen en la distribución de los climas y la biodiversidad en México" en 

Enciclopedia de Conocimientos Fundamentales: UNAM-Siglo XXI, Vol. 3 Historia, Geografía. México: Universidad Nacional Autónoma de México.

Rzedowski, Jerzy (2006). Vegetación de México. 1ra. Edición digital. México: Comisión Nacional para el Conocimiento y Uso de la Biodiversidad, CONABIO. Primera Edición, 1978, 
 
Limusa. 504 pp.

CONAGUA-CENAPRED (2018). Puntos críticos de inundación en "Sistema de información sobre riesgos". México: Comisión Nacional del Agua, CONAGUA y Centro Nacional de Prevención de Desastres, CENAPRED. Disponible en: http://www.atlasnacionalderiesgos.gob.mx/archivo/visor-capas.html 
 ```
