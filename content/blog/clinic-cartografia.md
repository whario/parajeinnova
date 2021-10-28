+++
author = "ParajeInnova"
title = "IX Clinic de cartografía de orientación"
date = "2017-05-25"
image = "img/blog/Toledo.jpg"
description = "reunión de cartógrafos de orientación"
tags = [
    "Cartografía",
    "LiDAR",
    "opensource",
    "orientación",
    "Sentinel2",
    ]
+++
## IX Clinic de cartografía de orientación
El fin de semana del 27 y 28 del pasado mes de noviembre, se llevó a cabo en el magnífico entorno del Castillo de San Servando (Toledo) el [IX Clinic de Cartografía, CARTOFEDO 2016](https://www.fedo.org/web/ultimas-noticias/2576-clinic-de-cartografia-cartofedo). Este evento, que se viene realizando desde 2007  organizado por el [Comité de Cartografía de la Federación Española de Orientación](https://www.fedo.org/web/), consiste en celebrar una reunión para cartógrafos de este deporte, contando en esta ocasión con 28 asistentes. En este congreso se tratan las últimas técnicas y novedades cartográficas relacionadas con la confección de los mapas de orientación, los singulares y en mi opinión casi artísticos o – mapas. Así, tienen lugar ponencias que versan por ejemplo, desde el software para su creación, los dispositivos móviles asistidos por GPS para ayudar en el duro trabajo de campo, y por supuesto, sobre las distintas fuentes cartográficas disponibles para su elaboración.
### Ponencias
Este año, como siempre, el programa contenía un gran número de intervenciones relevantes, cuyas presentaciones estarán próximamente a disposición de cualquier interesado en la página web de la FEDO. (n. del a.: las ponencias ya se pueden descargar desde el enlace:  http://www.fedo.org/web/cartografia/ponencias). A continuación, un escueto resumen de las mismas:
+ Introducción histórica de los Clinics precedentes, a cargo de Javier Arufe.
+ Planes LiDAR del IGN, impartida por J. Carlos Ojeda, técnico de la institución, que habló tanto del manejo esta tecnología (incluyendo software) como de la cartografía disponible actualmente. Muy interesantes resultaron los planes futuros del Instituto Geográfico Nacional, como son los nuevos vuelos PNOA – LiDAR de 1 y 2 puntos por metro cuadrado, la captación del infrarrojo para distinguir la vegetación, etc.
+ Los ficheros LAS desde dentro, todo un viaje al interior de este formato de distribución de datos LiDAR y sus implicaciones informáticas, por Javier Arufe.
+ La impresión digital de o – mapas, por Santiago Chóliz.
+ El empleo de cartografía del Catastro de urbana para la realización de los mapas base para la disciplina de sprint, por L. Alberto Jiménez.
+ La creación de mapas de la disciplina rogaine y cuestiones sobre la generalización y la simbología en los o – mapas, a cargo de Pablo F. Liria.
+ La creación de mapas base (con vegetación, cortados, arroyos, curvas de nivel y sombreados) a partir de datos LiDAR manejados con software libre (o al menos parcialmente) como SAGA, QGIS y LasTools. Arturo Murúa, autor del blog NABESAR y de magníficos tutoriales para el tratamiento de la información que animamos a leer y que podéis encontrar en dicha página web, impartió esta ponencia.
+ Experiencias en el manejo de Open Orienteering Mapper para Android y en la realización de todo un proyecto cartográfico mediante la versión de escritorio de ese mismo software, por parte de Daniel Mayoral, autor del blog Orienta – TIC.
+ El proyecto de la Colmena Cultural, similar al geocaching con códigos QR.
+ El software OCAD 12 y la gestión de los Modelos Digitales de Elevaciones, haciendo hincapié en la importación de datos LiDAR y la creación de Modelos Digitales del Terreno (MDT) y Modelos Digitales de Superficies (MDS), a cargo de Javier Arufe. Él mismo impartió después una ponencia sobre sus experiencias de trabajo de campo en la realización de mapas de disciplina O – BM.
+ Cartografía para la promoción de la orientación en centros escolares, por Juan Plata.
### Nueva cartografía y técnicas para la elaboración del mapa base: Sentinel-2
Esta vez, al igual que en los precedentes VIII Clinic CARTOFEDO 2015 y el XIII Curso Nacional de Cartografía Nivel II, donde mis intervenciones se centraron en el manejo de datos LiDAR del PNOA empleando sotware libre para la confección de los mapas base y la definición del parámetro runnability (penetrabilidad de la vegetación), fui invitado a impartir una ponencia.

En esta ocasión, hablé en parte sobre una de las fuentes de datos de libre disposición que pueden ser de utilidad en la confección de los mapas y con las que en Paraje Innovación y Consultoría estamos trabajando mucho en los últimos meses, junto con las escenas del satélite **Landsat 8**. Se trata de las imágenes del satélite [Sentinel-2](https://sentinel.esa.int/web/sentinel/missions/sentinel-2), que gracias a su buena resolución espacial (10 metros), temporal (5 – 10 días) y espectral, junto con la mayor disponibilidad y facilidad de manejo que nos brindan los avances de Internet y el desarrollo del software open source, suponen un gran avance tanto cartográfico como para la obtención de datos de interés para el **medio natural, agrícola y forestal**.\
\
Además de indicar en qué consiste esta fuente de información, desde dónde descargarla y sus posibles aplicaciones en algunas disciplinas de la orientación, se mostraron ejemplos de tratamiento de las bandas de las que se componen las imágenes del satélite, procesándolas «en directo» mediante QGIS obteniendo composiciones RGB (bandas 4, 3, 2) e índices de vegetación (NDVI).
![imagen RGB Sentinel 2 Navaleno](/img/blog/composicion.jpg "imagen RGB Sentinel 2 Navaleno")
*Composición ortofotografía, imagen RGB Sentinel 2 y o-mapa de Navaleno (Soria).*
### SVF: visualización de datos LiDAR
Una vez analizadas la usabilidad y las ventajas que proporciona esta información sobre todo en cuanto a actualización de las imágenes y la zonificación de eventos (incendios, tratamientos selvícolas…) que pueden alterar el terreno donde se va a disputar la carrera, se plantearon posibles combinaciones (a futuro) de esta información tratada conjuntamente con los datos LiDAR. Esta fusión de informaciones dio pie a hablar sobre las nuevas formas de visualización mejorada de los sombreados de MDT y MDS obtenidos a partir de sus nubes de puntos, empleando la metodología **Sky View Factor** (SVF) desarrollada por el Institute of Anthropological and Spatial Studies de Eslovenia (más información en este [enlace](https://iaps.zrc-sazu.si/en/svf#v)).\
\
Para terminar, un comentario sobre el aumento del rendimiento en la creación de mapas base que pueden proporcionar las nuevas tecnologías, a pesar de su necesaria curva de aprendizaje.\
\
![Aplicación de SVF a MDT](/img/blog/urbasa.jpg "Aplicación de SVF a MDT")\
*Aplicación de SVF a MDT de 2 m de resolución obtenido a partir de PNOA – LiDAR, en Urbasa (Navarra).*\
\
Como puede verse, destacó por el número de ponencias implicadas y entre otras temáticas, el empleo de los datos LiDAR y otras fuentes para el mapa base, el uso del software libre y la introducción en la cartografía de orientación de los Sistemas de Información Geográfica (GIS) como alternativa a los software específicos de o – mapas. En conjunto, resultó una reunión en la que se transmitió y recibió gran cantidad de información muy aprovechable en distintos ámbitos de la cartografía (no sólo de orientación). Esto, unido al habitual buen ambiente reinante en el entorno de este sano deporte y la fantástica organización, hizo que resultase un fin de semana de lo más agradable. Agradecer al Comité de Cartografía y en especial a Mario Vidal, su invitación para participar en este interesante evento.\
\
![asistentes al Clinic Cartofedo 2016](/img/blog/IMG_7024.jpg "asistentes al Clinic Cartofedo 2016")\
*Algunos de los asistentes al Clinic Cartofedo 2016.*
