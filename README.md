# Clasificación de imágenes de satélite.
 
### :round_pushpin: Equipo: 2

### :round_pushpin: Integrantes: Juan Luis Carrillo, Atenea De La Cruz Brito, Zoé Ariel García Martínez

### Objetivo: Clasificar las áreas urbanas, verdes y cuerpos de agua

### Metodología: Algoritmos de clasificación supervisados y no supervisados

***

## Introducción
<p align="justify">
Actualmente, alrededor de nuestro planeta orbitan cerca de 7460 satélites artificiales (UNOOSA, 2021). Aproximadamente un 10% de éstos tienen entre sus funciones captar imágenes desde el espacio. Dentro de los proyectos de observación que permiten consultar sus imágenes en alta resolución destacan los satélites Landsat de Estados Unidos (NASA, 2021) y Sentinel, perteneciente a Copernicus de la Unión Europea (ESA, 2021).
<p align="justify">
 La disponibilidad de imágenes con alta calidad representa un recurso con gran potencial para diversos fines como protección del medio ambiente, prevención y atención frente a desastres naturales, planeación urbana, entre otros. No obstante, el análisis de las imágenes satelitales representa una labor muy demandante en tiempo y recursos humanos. Afortunadamente, es posible realizar estas tareas de identificación y categorización de imágenes de satélite por medio de algoritmos de Machine Learning.

## **¿Cuál es el propósito y por qué es importante?**
### _Objetivo y justificación_
<p align="justify">
 Por tanto, este proyecto tiene como objetivo clasificar espacios de terreno entre áreas con vegetación, cuerpos de agua y zonas urbanizadas, a partir de imágenes multi-espectrales del satélite Landsat 8. Para ello se aplicaron algoritmos de Machine Learning para la clasificación supervisada y no supervisada, los cuales fueron evaluados según su precisión y tiempo de cómputo.
<p align="justify">
De este modo, se busca contribuir a la resolución de problemáticas ambientales y sociales producto de fenómenos naturales así como acciones humanas. Por ejemplo, la observación del crecimiento de la mancha urbana, el manejo forestal y las alertas de deforestación, el monitoreo de tierras de cultivo y consumo de agua, la identificación de algas tóxicas en cuerpos de agua, la prevención y seguimiento de incendios, la observación de los cambios en los niveles el mar y áreas susceptibles a inundaciones, entre otros.

## **¿Dónde y cómo lo realizamos?**
### _Delimitación, datos y metodología_
<p align="justify">
 Para esta fase en particular del desarrollo, nos enfocamos en la zona sureste del Área Metropolitana de Guadalajara, la cual incluye a los municipios de San Pedro Tlaquepaque, El Salto y Tlajomulco de Zúñiga. Se eligió esta área ya que presenta vegetación de diferente tipo, cadenas montañosas como la Sierra de San Juan Cosalá, cuerpos de agua como la Laguna de Cajititlán y el Lago de Chapala, así como áreas urbanas. No obstante, este proyecto puede aplicarse para la identificación de otros territorios.
 
 <p align="center">
  <img src="/img_files/Guadalajara_1.png" "Área extendida de la zona de estudio" alt="NF"/>
 <p align="center">
  Área extendida de la zona de estudio, Landsat.

<p align="justify">
Se utilizaron imágenes captadas por el satélite Landsat 8, que contienen 7 bandas espectrales, esto es la cobertura o gama de longitudes de onda observadas por los sensores, los cuales se relacionan con la luz visible, infrarrojo cercano, infrarrojo de onda corta, infrarrojo térmico, entre otros (USGS-NASA, 2018). Dichas bandas constituyen conjuntos de datos no estructurados, a partir de los cuales se compone y clasifica la imagen final.
<p align="justify">
Para realizar la identificación se aplicaron algoritmos de Machine Learning. En primer lugar, para la clasificación no supervisada se empleó el K-Means Clustering y análisis de componentes principales. En segundo lugar, para la clasificación supervisada se aplicaron K-Nearest Neighbor Classifier, árboles de decisión y redes neuronales. Estos métodos fueron evaluados según su precisión en la identificación de las características del terreno así como a partir de la rapidez de su cálculo.

## **¿Cuál es su utilidad y alcance?**
### _Consideraciones finales_
<p align="justify">
 En suma, este proyecto se plantea desde un enfoque multipropósito, el cual aprovecha el acceso a imágenes de satélite de alta calidad en conjunto con el potencial de las técnicas de Machine Learning. De este modo, la apuesta es proveer de información útil a los sectores productivos, así como a los tomadores de decisiones en el ámbito público y social, mediante un proceso rápido y oportuno.

## **Referencias:**
<p align="left">
ESA (2021) “About Copernicus”, Bélgica: European Space Agency, ESA. Recuperado de: https://scihub.copernicus.eu/ 

NASA (2021). “The Landsat Program”, Estados Unidos: National Aeronautics and Space Administration, NASA. Recuperado de: https://landsat.gsfc.nasa.gov/

UNOOSA (2021). “Outer Space Objects Index”, Austria: United Nations Office for Outer Space Affairs UNOOSA. Recuperado de: http://www.unoosa.org/oosa/osoindex/search-ng.jspx?lf_id=

USGS-NASA (2018). Landsat, Benefiting Society for Fifty Years. Case Study Book. Estados Unidos: U.S. Geological Survey, USGS-National Aeronautics and Space Administration, pp.60.



  

