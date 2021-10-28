+++
author = "ParajeInnova"
title = "Big Data y Data Mining en la agricultura. Se aproxima el punto de inflexión"
date = "2017-06-02"
image = "img/blog/tendencia-bigdata.png"
description = "reunión de cartógrafos de orientación"
tags = [
    "Agricultura de precisión",
    "opensource",
    ]
+++
## Big Data y Data Mining en la agricultura. Se aproxima el punto de inflexión
Pocos dudan, al menos entre los que conocen algo del tema, que la utilización del Big Data y Data Mining en la agricultura son claves para su desarrollo. Por el momento son términos de los que se abusa cada vez más en Internet, conferencias, publicaciones y medios de comunicación, y en cierto modo su mención parece cada vez más una moda pasajera.\
\
Pero lo cierto es que lo que quedará en el recuerdo es haber estado en boca de periodistas, expertos y gurús tecnológicos, mientras que las aplicaciones de estas tecnologías perdurarán, casi transparentes a nuestros ojos, pero unidas de forma definitiva a nuestras vidas.\
\
[Chris Hasdwick](https://es.wikipedia.org/wiki/Chris_Hardwick) dio en el clavo en una entrevista en 2012:
“Ya no estamos en la era de la información. Estamos en la era de la gestión de la información.”
Si echamos un vistazo al **proceso que engloba el Big Data**, veremos que es un proceso cíclico en que los datos entran, se normalizan, se analizan mediante técnicas de minería de datos (como el aprendizaje automático) y se almacenan. Como resultado obtenemos información utilizable en nuestra explotación, siendo necesario que ésta sea limpia, precisa, relevante y oportuna.
Analicemos el proceso por partes, y evaluemos si en nuestro sector se está cumpliendo este esquema de funcionamiento.
### Adquisición de datos masivos
Hasta no hace mucho, **la captura de información de un agricultor consistía habitualmente en ver cómo crecía el cultivo en el campo del vecino**. Si lo veía mejor que el suyo, y la relación con el vecino era buena, le preguntaba sobre cuándo había fertilizado y con qué, qué semilla había utilizado o a qué dosis había sembrado, por ejemplo, con el fin de mejorar su propio cultivo en futuras campañas. Probablemente el vecino había hecho lo mismo con otro vecino anteriormente, o bien había probado diversas opciones mediante ensayo-error, o bien se había asesorado en libros, revistas sectoriales, boletines agrarios, foros, jornadas, o con algún técnico en la materia.\
\
Actualmente, en la explotación agrícola media, al menos en mi querida región, el sistema no ha cambiado demasiado, y lo cierto es que aunque es un sistema de «captura y gestión de la información» que puede funcionar medianamente bien, está lejos de ser efectivo. **En plena era digital el campo está un paso por detrás en estos temas, y eso que la disponibilidad y gestión de la información es al menos tan importante como en otros sectores como el industrial o el de servicios**.
### El agricultor necesita su tiempo para otras labores
**El agricultor es en general muy reacio a tomar datos sistemáticos sobre su explotación**. Es un proceso costoso en tiempo y recursos que no suele tener recompensa a corto plazo, por lo que no lo ven como una inversión interesante. Y no les falta razón. **Es necesaria una automatización en la toma de datos**, hacer el proceso transparente para el agricultor. Y se ha de aspirar a que esta sea tan eficiente como las que se están instaurando o se han instaurado en otros sectores.\
\
Desde hace años, más o menos de forma principal en los 90s, han entrado en escena diversos sistemas de captura de datos aplicados en la denominada [Agricultura de Precisión](https://es.wikipedia.org/wiki/Agricultura_de_precisión). Desde sensores de rendimiento en cosechadoras, a muestreadores automáticos de suelos, a sensores de vigor vegetal, humedad o temperatura en tiempo real.
> Nota: Hace 14 años (2002) escribí un pequeño informe interno para [Itagra](https://www.itagra.com/) en el que se hacía un breve repaso a lo que había en el sector en aquél momento. Si alguien tiene curiosidad puede leerlo en este [enlace]({{< ref "blog/drones-experiencias.md" >}}).

También desde hace años están disponibles gran cantidad de satélites con sensores multiespectrales, y últimamente han entrado en escena los drones, que se han convertido en muchos casos en un auténtico hype (permítanme el anglicismo), y que desde Paraje hemos utilizado en diversas ocasiones para la toma de datos, como por ejemplo en este caso.\
\
![Yara N sensor](/img/blog/Yara_N-Sensor_ALS.jpg "Yara N sensor")
*Yara N sensor*
Como vemos, hay multitud de potenciales fuentes de datos, pero sigamos adelante en el diagrama expuesto.
### Normalización y estandarización de los datos
**El Big Data se construye desde el Small Data. Es decir, un verdadero despliegue del Big Data y Data Mining en la agricultura requiere que multitud de datos locales, a nivel parcela, estén disponibles para la «comunidad»**.\
\
Por ejemplo, si dispongo de una red de sensores que, junto con un software determinado, **predicen la probabilidad de aparición de una plaga o enfermedad** en mi parcela, pero en las parcelas de alrededor no disponen de dicho sistema, o lo que es peor, su sistema no es compatible con el mío, y por lo tanto no se comunican, ante una plaga que avanza desde las parcelas vecinas actuaré en mi cultivo reactivamente, y no preventivamente, que es lo deseable.\
\
Otro planteamiento. Si yo dispongo de un **medidor de cosecha instalado en mi cosechadora**, ¿la información recogida es compatible con el resto de mis equipos? ¿Puedo compartir dicha información con un contratista que va a hacerme determinada labor con una máquina de otro fabricante distinto al de la mía? ¿Alguien (o algo) se ha preocupado de calibrar el equipo de medición antes de cada labor de cosecha para asegurarse de que los datos recogidos son precisos y comparables con los tomados por otros sensores?.
### No tenemos aún Big Data
[Mike Duncan](https://www.ncinnovation.ca/team_member/dr-mike-duncan), investigador canadiense experto en agricultura de precisión lo definía perfectamente en una entrevista en febrero de este año:
>En agricultura no podemos hablar realmente de Big Data. Si quieres ver Big Data, ve a una central bancaria. Podrás sentarte allí y observar como millones de transacciones fluyen por sus sistemas cada hora. Eso es Big Data, y nosotros, el sector agrario, no tenemos nada que se asemeje a eso».

Y eso (el Big Data en las transacciones bancarias), es posible gracias a la **estandarización de los formatos de datos**, de forma que los datáfonos de los comercios, los cajeros electrónicos, y los sistemas informáticos de cualquier entidad hablan el mismo idioma.

Lo mismo sucede con el coche autónomo. La base del sistema es que en un futuro no muy lejano todos los vehículos y las infraestructuras viarias se comuniquen entre sí, para lo cual todas las marcas y la Administración deberán acordar un sistema estándar de comunicación y respetarlo. ¿Es factible esto en la agricultura en la que **predominan los sistemas verticales y la incompatibilidad**?. ¿Todas las marcas respetan, por ejemplo, la norma ISOBUS?. ¿Vemos factible la implantación masiva de tractores totalmente autónomos que no compartan información con otros aperos o tractores porque son de otra marca?.

¿Aparecerá el VHS de la agricultura que desplace a todos los sistemas Betamax?.

En definitiva,
+ en lo que no haya una masa crítica de usuarios que dispongan, y utilicen, tecnología de toma de datos automatizada en sus explotaciones,
+ y en lo que esos sistemas de captura, análisis y utilización de los datos no sean compatibles entre sí,
+ y en lo que no haya métodos de comunicación efectivos entre todos esos sistemas en el mundo rural, no podremos hablar de Big Data y Data Mining en la agricultura.

### Minería de Datos
Siguiendo el diagrama propuesto, llegamos a la fase de la **Minería de Datos**. En este punto nos encontramos con una **falta importante de modelos matemáticos**.

El valor de los datos, como he indicado antes, reside en la posibilidad de aprender de ellos, detectar patrones y tendencias, y aplicar ese nuevo conocimiento a nuevas situaciones.

Se han desarrollado gran cantidad de modelos agrícolas (de predicción de plagas, de predicción de cosechas, de fertilización, de riego, de evolución de precios, etc.), pero su utilización da, en general, resultados razonablemente precisos a nivel local, o generalizaciones de precisión muy limitada a nivel regional. Esto es debido a la **cantidad limitada de datos de entrada disponibles para el desarrollo de los modelos**.

Con un auténtico Big Data y Data Mining en la agricultura, los sistemas de aprendizaje automático se alimentarían de miles, centenares de miles o millones de datos procedentes de cada explotación, con lo que los modelos obtenidos serían de muy alta calidad, e incluso **podríamos aspirar a obtener modelos con aplicaciones que ahora no podemos ni imaginar**.
![Minería de datos con Weka en Paraje Innova](/img/blog/IMG_4276.jpg "Minería de datos con Weka en Paraje Innova")
*Desarrollando modelos en Paraje Innova.*
### Almacenamiento
Por último en nuestro diagrama nos encontramos el **almacenamiento**. En un entorno auténticamente de Big Data hay que desterrar memorias USB, tarjetas de memoria o descargas en el PC de casa o la oficina. Lo que se **requiere es acceso móvil, a pie de parcela**, desde nuestros smartphones, así como **descargas directas** en nuestras máquinas y aperos y complementos de abordo en el tractor, al igual que realizan muchos sistemas embarcados en los coches actuales. Lo ideal es que en cuanto un componente (sensor, apero, tractor, etc.) detecte una red WiFi o UMTS, cargue los datos capturados y descargue los datos procesados (lo que sería el [Internet de las Cosas](http://es.wikipedia.org/wiki/Internet_de_las_Cosas) de la agricultura).

Para ello será necesario **ampliar el acceso a la red desde el entorno rural**, que ha mejorado mucho en los últimos años, pero aún adolece de muchas zonas con baja o nula cobertura, y **abaratar de forma importante los costes** de dicho acceso.
### El futuro del Big Data y Data Mining en la agricultura
Si hacemos un repaso a todo lo dicho hasta ahora, veremos que **todas las tecnologías de base necesarias para el desarrollo del Big Data y Data Mining en la agricultura ya están disponibles**. Así pues «solo» es necesario que el sector evolucione adecuadamente en paralelo a otros sectores que ya están recurriendo a estas tecnologías en los últimos años.
#### Lo Open es la clave
**Será necesario un descenso de los precios del hardware y el software relacionados**, algo complicado si las marcas más potentes siguen apostando por sistemas cerrados y verticales. Una apuesta por el desarrollo de sistemas de [código abierto](https://es.wikipedia.org/wiki/Software_libre) (open source) y de [hardware abierto](https://es.wikipedia.org/wiki/Hardware_libre) (open hardware) y compartición de datos entre explotaciones, empresas y la administración (open data o datos abiertos) podría ser el camino.

Para los agricultores sería más accesible la tecnología, ya que la mejora en sus explotaciones ampliaría sus márgenes económicos lo necesario para cubrir los gastos y aun así mejorar sus ingresos, y las empresas de servicios podríamos obtener beneficios por la implantación, el asesoramiento, el mantenimiento y el desarrollo de nuevos equipos, modelos, prestaciones y mejoras.

No es un pensamiento tecnológicamente utópico, habida cuenta de que la inmensa mayoría de sistemas de explotación de Big Data que se utilizan en la actualidad están basados en sistemas abiertos.
#### La información es poder
Cierto es que puede haber cierta resistencia «cultural» a ese flujo de datos. Por ejemplo, entre explotaciones que sean competencia entre sí, o desde las explotaciones a la Administración, que dispondría de información directa y detallada de nosotros, por lo que estaríamos más controlados. Pero también hay que ver la parte positiva, ya que por ejemplo:
+ no habría que rellenar formularios sobre los tratamientos fitosanitarios, ya que nuestros equipos ya se ocuparían de registrar cuándo, dónde, cuánto y con qué habríamos hecho los tratamientos;
+ podríamos recibir previsiones de entrada de nuestra mercancía al mercado, para no saturarlo y poder mantener los precios;
+ nuestro concesionario de maquinaria habitual podría hacer mantenimiento predictivo de nuestros equipos, gracias a un modelo matemático basado en datos de uso y averías de otros usuarios que utilizan el mismo tipo de máquinas;
+ en una compra-venta de una tierra, los datos acumulados asociados a ella podrían componer parte del valor de la operación, ya que el comprador sabría qué está comprando en realidad;
+ y por supuesto, muchas otras prestaciones que nos ofrecerían tanto la agricultura de precisión como otras tecnologías basadas en la información.
#### Una nueva revolución
Así pues, parece claro que el **Big Data** y **Data Mining en la agricultura** es el camino, y probablemente su uso tendrá un impacto similar al que tuvo la [Revolución Verde en su día](https://es.wikipedia.org/wiki/Revolución_verde), si bien habrá de definirse en términos de privacidad, seguridad y ética en el uso de esos datos, al igual que está sucediendo en otros sectores en los que ya se están utilizando, como las compras online, las redes sociales o el marketing.

Por nuestra parte, ya llevamos tiempo caminando con este enfoque, y utilizamos sistemas de Minería de Datos en nuestros proyectos y Open Source y Open Hardware en nuestros desarrollos y en nuestro trabajo diario.

Recientemente hemos puesto también en marcha un curso de introducción a la Minería de Datos, para que aquellos interesados en aprender a exprimir el valor de datos masivos, pueda empezar a hacerlo de una forma práctica.

Veremos lo que nos depara el futuro.