+++
author = "ParajeInnova"
title = "Aplicación de la teledetección para evaluar el vigor vegetativo de las masas forestales"
date = "2017-08-11"
image = "img/blog/compo3.jpeg"
description = "tecnología novedosa mediante la cual es posible obtener pequeñas cantidades de energía de una forma limpia, basándose en la actividad vital de las bacterias"
tags = [
    "Teledetección",
    "cartografía",
    "GIS",
    "Sentinel2",
    ]
+++

## Aplicación de la teledetección para evaluar el vigor vegetativo de las masas forestales
>Introducción (n. de Luis Carlos Fernández García):\
>___
>En [Paraje Innovación y Consultoría](https://www.parajeinnova.com/), contamos de vez en cuando con personas que buscan desarrollar sus capacidades profesionales en nuestra empresa, tras haber llevado a cabo su periodo de estudios. Así, contamos con personas en prácticas procedentes principalmente de la Universidad de Valladolid.  En esta ocasión contamos para este artículo enfocado en aplicaciones de la Teledetección en ámbitos forestales, con la colaboración de [María Eugenia Martínez Tottil](https://www.linkedin.com/in/maria-eugenia-martinez-tottil-973646aa/), Ingeniera Ambiental y recientemente egresada, con muy buenas calificaciones, del Máster en Tecnologías Avanzadas para el Desarrollo Agroforestal, que se imparte en la Escuela Técnica Superior de Ingenierías Agrarias de Palencia. Como ya sabréis los que nos seguís, una de nuestras principales áreas de actividad reside en la cartografía y las aplicaciones de los GIS y la teledetección en el sector agroforestal. Por ello el interés que suscita para nosotros este trabajo, del que fui Director. Sin más, a continuación podéis disfrutar de este interesante artículo y no dudéis en poneros en contacto con nosotros si deseáis más información sobre estos servicios, aplicables por ejemplo, a explotaciones forestales comerciales (choperas, etc.):
### El seguimiento de masas forestales mediante teledetección
En este artículo se presenta de forma general los resultados obtenidos tras aplicar herramientas de **teledetección** en el seguimiento de medidas aplicadas a un **bosque mediterráneo** que venía sufriendo a lo largo de los años una disminución de su vigor vegetativo. Estos bosques, dentro de un contexto de **cambio climático**, donde el aumento de las temperaturas con el consiguiente aumento de la evapotranspiración de la vegetación y una disminución de la precipitación, pueden sufrir una serie de problemas como es el caso del **decaimiento forestal**, que conlleva a una impactos que atentan contra su sostenibilidad y su potencialidad para ser sumideros de carbono.\
\
Dentro de este contexto se ha desarrollado el proyecto **LIFE11 ENV/ES/535 – Operation CO2**, en un bosque de pino silvestre (Pinus sylvestris) bajo manejo en Lleida, Cataluña, donde se han implementado cortas de adaptación al cambio climático a fin incrementar la fijación de carbono, entre julio y noviembre de 2015. Con el fin de evaluar que efectos han tenido dichas medidas, se han utilizado **Índices de Vegetación** obtenidos a partir de imágenes satelitales de libre distribución, gratuitas y desarrolladas para su aplicación agroforestal, como son las procedentes de los satélites **Sentinel-2** y **Landsat 7 y 8**. Las fechas de análisis necesarias para la evaluación o seguimiento de las masas son lógicamente anteriores (2010, 2014 y 2015) y posteriores (2016 y 2017) a la realización de los trabajos forestales y de ello la necesidad de usar los tres satélites, ya que Sentinel-2 fue lanzado en 2015 mientras que Landsat 8 lo fue en 2013.
![Zona de estudio aplicación forestal de la teledetección](/img/blog/zona_estudio.jpg "Zona de estudio aplicación forestal de la teledetección")
*Zona de estudio aplicación forestal de la teledetección*
### Los índices de vegetación
Los índices de vegetación se pueden definir como parámetros calculados a partir de los valores de reflectancia obtenidos a partir de imágenes satelitales y que buscan extraer información relacionada con la vegetación minimizando otros factores externos como son las propiedades ópticas del suelo o la irradiancia solar. A partir de los índices de vegetación determinados se puede evaluar el vigor de la vegetación. Para el presente estudio se utilizaron dos índices, uno de los cuales es el más usado y conocido en teledetección durante las dos últimas décadas, el NDVI, y el SAVI, similar al anterior pero que busca minimizar el efecto de la reflectancia del suelo mediante la introducción de un factor L en la formula del NDVI. Estos índices utilizan los valores de reflectancia de las bandas del infrarrojo cercano y del rojo visible.
### Corrección atmosférica y topográfica de las imágenes
Estos índices fueron diseñados para poder calcularse a partir de reflectancia de superficie (reflectancia BOA),es decir imágenes corregidas atmosféricamente, por lo que fue necesario procesar las imágenes Sentinel-2 empleando su algoritmo [Sen2Cor](https://step.esa.int/main/third-party-plugins-2/sen2cor/), ya que dadas las fechas necesarias para el análisis, estaban disponibles entonces sólo en valores de reflectancia por encima de la atmósfera o reflectancia TOA (recordad que desde hace un par de meses es posible descargarlas en valores de reflectancia BOA: [enlace](https://sentinels.copernicus.eu/web/sentinel/missions/sentinel-2/news/-/article/sentinel-2-l2a-products-available-over-eea-39)). Este procesamiento no fue necesario para las imágenes Landsat ya que éstas se encuentran disponibles para su descarga ya con la corrección atmosférica realizada. Por otro lado, a fin de poder comparar imágenes de diferentes fechas también es necesaria la corrección del efecto atmosférico, por lo que este procesamiento tiene un doble objetivo.\
\
Además, al tratarse de una zona con acusado relieve, se consideró necesario realizar una corrección topográfica con la que compensar las diferencias en la radiancia que detecta un sensor remoto como consecuencia de la distinta pendiente y orientación de las laderas. Por ello, todas las imágenes satelitales utilizadas pasaron también por este pre procesamiento.
### Resultados
Una vez procesadas las imágenes se pudo determinar ambos índices de vegetación empleando la ecuación correspondiente para cada una de ellas, y finalmente fueron reclasificadas en cinco categorías (desde muy bajo a muy alto vigor) para facilitar la comparación visual de cada una de las imágenes, obteniéndose los siguientes resultados:

![Secuencia NDVI 2010 – 2017](/img/blog/secuencia_ndvi.jpg "Secuencia NDVI 2010 – 2017")
*Secuencia NDVI 2010 – 2017*

![Secuencia SAVI 2010 - 2017](/img/blog/secuencia_savi.jpg "Secuencia SAVI 2010 - 2017")
*Secuencia SAVI 2010 – 2017*

En los resultados mostrados por ambos índices, se puede evaluar claramente cómo ha ido evolucionando la masa forestal en términos de vigor vegetativo. Y es posible también identificar claramente las cortas ejecutadas entre julio y noviembre de 2015, que muestran sus efectos en la imagen del 2016. Así también tras dos años posteriores a las acciones implementadas, se puede inferir alguna mejora en el vigor de la vegetación del bosque, observando la imagen de 2017. Se aprecia que para la zona de estudio, ambos índices de vegetación presentan un similar comportamiento, difiriendo en su sensibilidad a la corrección topográfica.\
\
Como podemos apreciar con los resultados obtenidos, la **teledetección** puede constituir una herramienta muy importarte para el seguimiento de la actividad vegetativa y la sanidad de los bosques, así como para la verificación de la funcionalidad de las medidas silvícolas aplicadas a las masas **forestales**. Por otro lado, la mejora en la resolución de las imágenes que se produce entre las procedentes del Landsat (30 metros sin pansharpening) y el Sentinel-2 (10 metros) constituye en sí misma un grandísimo avance en la adquisición de datos que como en este caso son de libre distribución.\
\
Por último, indicaros que podéis acceder al trabajo completo en este [enlace](https://goo.gl/FLDn8Y).