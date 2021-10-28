+++
author = "ParajeInnova"
title = "Estudios hidrológicos, hidráulicos y de inundabilidad"
date = "2017-07-31"
image = "img/blog/inundacion-agricola.jpg"
description = "reunión de cartógrafos de orientación"
tags = [
    "Estudios hidrológicos",
    "GIS",
    "LiDAR",
    ]
+++
## Estudios hidrológicos, hidráulicos y de inundabilidad
Para hacernos una idea de la necesidad de los estudios hidrológicos, repasaremos brevemente cómo ha sido el año 2016 en materia de inundaciones. Así este año se ha caracterizado, al menos en el área central de la región castellano leonesa de la que provenimos, por un invierno y una primavera muy lluviosos y un verano tremendamente seco, en relación con esas mismas estaciones en otros periodos, como podemos ver en la web de [AEMET](http://www.aemet.es/es/serviciosclimaticos/vigilancia_clima/analisis_estacional?w=1&l=2422&datos=prec).

La gran cantidad de precipitación caída durante la primavera, junto con el deshielo de las últimas nieves, provocaron el **desbordamiento de ríos y arroyos** durante varias semanas consecutivas de abril y mayo.

Estos desbordamientos son la causa de importantes **daños** en infraestructuras y terrenos de cultivo aledaños a los ríos, produciendo también grandes pérdidas en la agricultura. Así, este año, lo tardío de las fechas de las crecidas afectó de manera importante a terrenos recién sembrados.
### ¿En qué consisten los estudios hidrológicos, hidráulicos y / o de inundabilidad?
Este conocimiento sobre las **áreas de inundación** y la peligrosidad provocadas por las avenidas, lo que ayuda a definir los riesgos que causan las crecidas, debe ser plasmado en documentos técnicos. Éstos, firmados por ingenieros competentes, son denominados normalmente **Estudios hidrológicos** e hidráulicos y habitualmente contienen, siendo muy escuetos:
+ El análisis de la **precipitación máxima** para periodos de retorno determinados.
+ El estudio hidrológico de la **cuenca vertiente** a un punto de salida concreto del cauce en estudio, determinando los caudales producidos en ese punto por la lluvia caída en la cuenca. Como ejemplo, la siguiente imagen:

![cuenca vertiente GIS](/img/blog/cuenca_vertiente.jpg "cuenca vertiente GIS")
+ La **modelización y simulación** de cómo se comporta ese volumen de agua circulante a lo largo de un tramo concreto del río o arroyo, tomando como referencia un Modelo Digital del Terreno (MDT), que representará la orografía del cauce y las riberas o márgenes de los ríos. Son necesarios además otros muchos datos adicionales como presencia de estructuras o construcciones que impidan el paso del agua, las características de la vegetación de ribera, etc. que son finalmente integrados y representados en un Sistema de Información Geográfica (GIS).
Como resultado de un estudio de este tipo, bien realizado, podremos saber entre otras cosas, cómo es la lámina de inundación producida por un determinado cauce:

![lámina inundación estudio hidrológico](/img/blog/lamina_inundacion.jpg "lámina inundación estudio hidrológico")
### Datos disponibles sobre zonas inundables
En la región donde residimos, la labor realizada por la **Confederación Hidrográfica del Duero** (a veces injustamente criticada) con su amplia red de aforos, permite ver el [caudal circulante incluso en tiempo real](http://www.saihduero.es/main.php) de buen número de cauces de su competencia, así como conocer las áreas de inundación de gran cantidad de ríos y arroyos de entidad en amplias zonas de nuestra geografía. Este trabajo es desarrollado en el marco del [Sistema Nacional de Cartografía de Zonas Inundables](https://www.magrama.gob.es/es/agua/temas/gestion-de-los-riesgos-de-inundacion/snczi/), impulsado por el Ministerio de Agricultura, Alimentación y Medio Ambiente. Así, en el visor [GIS](http://sig.magrama.es/snczi/visor.html?herramienta=DPHZI) del MAGRAMA podemos observar estas capas de interés de una forma cómoda y georreferenciada:

![snczi GIS visor](/img/blog/snczi.jpg "snczi GIS visor")

Para los que somos usuarios habituales de cartografía digital, también podemos descargar toda esta cartografía en formato shapefile para su integración en nuestro GIS. Sin embargo, y para hacernos una idea de la cantidad de información cargada y accesible en el sistema, para un periodo de retorno de 50 años, sólo es posible acceder a la delimitación de la zona de inundación del 2,8 % de los cauces representados en la [cartografía 1:25.000 del Instituto Geográfico Nacional](http://www.magrama.gob.es/es/cartografia-y-sig/ide/descargas/agua/zi-lamina.aspx). Y si nos referimos a los caudales máximos en régimen natural, «sólo» están ya calculados los de los cauces con cuenca vertiente superior a los 50 kilómetros cuadrados.
### La necesidad de los estudios hidrológicos, hidráulicos y de inundabilidad
Esta circunstancia de cierta ausencia de información sobre las zonas inundables y sobre los caudales máximos circulantes aún en muchos lugares, no es extraña dada la inmensa magnitud del trabajo a realizar, y ni siquiera estará disponible en otros países. Además, en ciertas circunstancias las Confederaciones Hidrográficas solicitan a los propietarios de terrenos aledaños a los cauces o a los promotores de nuevas obras y planificaciones (por ejemplo, construcción de naves agrícolas junto a arroyos, planificación urbanística, etc.), que muestren la afección concreta de éstas a las áreas inundables. También son necesarios los estudios hidrológicos e hidráulicos cuando se trate de diseñar **medidas correctoras** o de defensa de las inundaciones, ya que éstas pueden provocar cambios en los regímenes de circulación del agua tanto aguas arriba como aguas abajo del área afectada, siendo necesario prever estos cambios.

![sección estudio hidrológico hecras](/img/blog/seccion_calculo_hecras.jpg "sección estudio hidrológico hecras")

### Otras consideraciones
Como hemos dejado caer anteriormente, para la realización de estos análisis completos y de calidad es fundamental el uso de las mejores fuentes de datos posibles. Entre ellas citaremos las oficiales, entre las que podemos destacar por su aplicación concreta en este ámbito el PNOA – LiDAR, para la obtención de los MDT. Pero también suele ser necesaria información adicional como la obtenida ex profeso como por ejemplo, a partir de **levantamientos topográficos** llevados a cabo con [drones]({{< ref "blog/drones-experiencias.md" >}}), GPS o estación total, según las circunstancias, y los datos de batimetría.

Ya sabéis que podéis contactar con nosotros si necesitáis más información adicional sobre lo publicado en este artículo y también si requerís de la realización de un estudio hidrológico hidráulico completo o de la obtención de algunos de sus datos de partida.