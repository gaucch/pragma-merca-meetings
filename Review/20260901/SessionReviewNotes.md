sept 1, 2026
Review de crecimiento - Transcripción
00:00:00

Jaime Gallo: entender qué es lo que se busca y colaboro con eh ya sea pues los diseños de las pruebas de concepto o las estimaciones a alto nivel de lo que se vaya a hacer pues a nivel comercial.
Andrés Useche: Listo. Entonces, ahí parafraseando un poco. Sí, tú estás actualmente como líder técnico, ¿sí? Pero como líder técnico, pues estás trabajando en ciertas definiciones de arquitectura de estos proyectos, pero a la final también eh pues gran parte estás llevando a cabo, gran parte de tu tiempo estás llevando a cabo esa implementación. Sí, estás ahí también pues ya metiendo también un poco tanto pues en el camino que estás tomando acá, ¿sí? como en el chapter de arquitectura, dentro de tu rol de arquitecto para ir creciendo en ese sentido y estás con ese nuevo reto también a nivel de back implementando APIs porque tu chapter principal es es el de front.
Jaime Gallo: Así es.
Andrés Useche: Listo, listo. Sú. Bueno, eh dentro pues ahí revisando un poco también tu mapa de crecimiento, ¿sí? enfocado en lo que es el chapter de arquitectura. Sí, porque pues digamos acá este espacio pues es ya va vamos es enfocado en esas actividades o esos pinitos de arquitectura ya que estás realizando, que vienes realizando dentro de la cuenta. Sí. Entonces, eh no sé si tengas de pronto de lo último que hayas realizado en este periodo, entiendo que tu última review o tu Sí, fue sobre marzo más o menos.


00:01:41

Jaime Gallo: Ok.
Andrés Useche: Sí. Entonces, eh de esa review, pues digamos ahí tenemos en el mapa de crecimiento eh unas unas capacidades pues que se evaluaron, ¿sí? y tenías, digamos, ciertas oportunidades de mejora. Sí. No sé si de pronto tengas Sí. O haya o que hayas traído de lo que has hecho un poco de esos diseños de arquitectura para que revisemos un poco, ¿sí?, de cómo has ya planteado, documentado esas arquitecturas y empezamos ahí a a conversar y a trabajar sobre sobre
Jaime Gallo: Sí, claro que sí.
Andrés Useche: eso.
Jaime Gallo: Quiero quiero proponer empezar por el por el que tengo más bajito, ¿vale? Y y quiero y quiero ir comentando cómo los vengo atendiendo. El que tengo más bajito es el de arquitectura de datos, el último.
Andrés Useche: Mhm. Sí.
Jaime Gallo: En ese yo vengo haciendo un proceso de mentoría con Eduardia. ¿Listo?
Andrés Useche: Okay.
Jaime Gallo: Entonces esa entrada sigue ahí,
Andrés Useche: Mm.
Jaime Gallo: ¿no? Mejor dicho, estoy ahí en proceso, no tengo nada por ahí. Vale.
Andrés Useche: Dale, Pero y pero claro, ese lo tienes bajito. Bueno, ahí hay uno en arquitectura de datos, hay uno que no está evaluado, ¿si?


00:03:10

Andrés Useche: Y me imagino que es el que habla del ciclo de vida de la información. Sí, ese no está evaluado porque cambió el mapa.
Jaime Gallo: H
Andrés Useche: Entonces, en la review anterior pues no se te evaluó. Sí,
Jaime Gallo: Ok.
Andrés Useche: pero de lo que has adelantado por tener el contexto con Edward, ¿qué o o qué es lo que tienes planteado, digamos, dentro de esa mentoría para empezar a abordar, pues, digamos, este frente? Sí, como para entender también en qué vas un poco y y pues poderte también pues no sé porque pues está sin evaluar, pero sí valdría la pena, no sé, ya hemos estudiado o me planteo pues esto con dentro de la mentoría este plan con Edward, de pronto que nos comentes ahí un poco.
Jaime Gallo: Claro que sí. Eh,
Andrés Useche: Ah.
Jaime Gallo: yo estoy basándome en el recurso que tenemos en Alejandría de arquitectura de datos. ¿Listo? Allí encontramos temas sugeridos por Senority y por y por temas puntuales y por categorías. Estoy enfocado principalmente en el de modelado datos, creo que es el primero, de senior, no, perdón, de junior y advans. Esos son los temas que hay. Entonces ahí que estoy encontrando repasos conceptuales de SQL, introducciones a bases de datos, no SQL, SQL, estoy haciendo el ejercicio del recorrido completo para saltarme conceptos.


00:04:37

Jaime Gallo: Sí. Entonces, estoy ahí,
Andrés Useche: Ok.
Jaime Gallo: estoy ahí. Eh, nada, creo que ese es el punto donde estoy de Ya definimos el plan de trabajo y estoy revisando material. ¿Qué esperamos en la mentoría con Edward? que salga algún entregable, sea dentro del chapter o sea a nivel de la cuenta, que me permita demostrar cómo estoy ya reforzando el tema arquitectura.
Andrés Useche: Vale,
Jaime Gallo: Veamos.
Andrés Useche: vale, genial. Listo, listo. S, listo. Entonces, eh, ¿con cuál quieres continuar? Sí.
Jaime Gallo: Listo,
Andrés Useche: O o o qué tienes ahí de pronto ya para que nos compartas un
Jaime Gallo: listo. Eh,
Andrés Useche: poco.
Jaime Gallo: el debox,
Andrés Useche: Vale,
Jaime Gallo: el deb. Listo. Entonces, ¿qué tenemos debox? Dame un segundito, les comparto. Eh,
Andrés Useche: perfecto.
Jaime Gallo: yo con eh César tuve tuve un feedback muy bacano eh el el espacio anterior y y fue si en la aplicación de la arquitectura desde mi rol es poca, ¿cierto? Yo sí puedo meterme en la película y tratar de documentar lo que más pueda. Entonces, he hecho eso con lo que he venido montando a nivel de mostrar.


00:05:58

Andrés Useche: Super.
Jaime Gallo: Yeah. Este no es es este de
Andrés Useche: Listo.
Jaime Gallo: acá.
Andrés Useche: Mhm.
Jaime Gallo: Listo. Entonces, este es el proyecto de Tools IA, ¿vale? eh la la arquitectura de solución que se nos ha eh compartido. Yo yo la he estado tratando de de documentarlo lo que más he podido de la parte de box. Entonces, ya ahorita les muestro esto porque quisiera es cuando ya pasáramos a la parte de observabilidad. En la parte de BOBS, yo me he enfocado bastante en primero repasar los conceptos desde desde el deps, ¿cierto? Y cómo el banco está aplicando esto y me lo traigo al proyecto, ¿sí? y empiezo a forzar o o a promover mejor esas prácticas que el banco está indicando y a poderlas reflejar en el proyecto. Entonces, lo primero que hago aquí es poder documentar, ¿cierto? Se que yo soy bien gráfico aquí con estos temas de los diagramas y todo, entonces me gusta eh pintarlo de esta manera. Entonces, por aquí por el tema del Pel que que he realizado como líder técnico en el proyecto, asegurarme de que esos lineamientos y esas prácticas de checks que tienen en el banco sí las estemos cumpliendo. Sí. Y posteriormente diseñando y configurando el pil donde veo que hay que ajustar.


00:07:30

Jaime Gallo: Nosotros esto lo hacemos múltiples veces porque el proyecto aquí nos bueno, si aquí nos damos cuenta de que tenemos múltiples repositorios, entonces casi que esa configuración del piline de de los pipelines realmente nos toca hacerla una, dos, tres veces y nos llega ya con algún servidor en específico, ya digamos adelantado, nos toca revisar y ajustar. Entonces, eso es lo que tenemos acá. Entonces, montamos un peline de integración por el lado de los pulls, donde aquí pues demostramos qué podemos hacer y cuándo se ejecuta y quién lo hace. Sí. Y tenemos ya el piline como tal, el de integración, el que ya cuando estamos en la rama estable, pues nos configura el artefacto, nos prepara los archivos de configuración pues de de Cubern y eh nos deja pues el aprovisionamiento para el tema de de la telemetría, ¿cierto? Y pues posteriormente nos publica por la parte del Peline también estuve revisando el tema, ¿cierto? y documentando de acuerdo a lo que veníamos aplicando en el proyecto. Y tenemos este Pand, básicamente tenemos tres estelles. Eh, nosotros desplegamos eh a lo que hacemos es en cada en cada ambiente eh preparamos la imagen, ¿cierto? la subimos a SR y desplegamos en los ambientes y corremos su su respectiva entonces tenemos el mismo escenario en en los tres acá como podemos ver con las particularidades pues de que ya por ejemplo en CUA si ejecutamos todo un proceso de certificación completo, ¿cierto?


00:09:16

Jaime Gallo: de de por ejemplo de performance y de la securities, teniendo en cuenta pues esas prácticas ya como tal de seguridad a través de todo el ciclo de del desarrollo que nos dice CCOs. Por la parte de PDN, nada, aquí tenemos un paso a producción a través de una aprobación manual que también pues hace alusión a a esas prácticas que nos indica eh DevOPS, ¿cierto? de formalizar cómo es que se manejan estos procedimientos. Y eh algo que tenemos aquí que también fue ya propuesta de nosotros y algo que gustó eh en el banco fue que nosotros entramos en el proyecto y en el en el en la EBC, que es como una gran organización, pero dentro del banco, no tenían contemplado todavía cómo era la estrategia de rolp de esos servidores MSPs. Nosotros la propusimos y propusimos pues una versión uno, ¿cierto? El evolutivo ya hace parte del banco, pero la podemos definir acá. ¿Qué tenemos aquí? Cuando el el el PO en este caso aprueba el paso a producción, ¿cierto? Y ese paso se hace de manera exitosa y él confirma de que todo está okay. Eh, lo que estamos nosotros haciendo desde el pipeline es subir tal cual quedó los archivos de la aplicación, ya con los secretos a nivel, por ejemplo, de de de variables y de configuraciones. Todo eso lo subimos a Actifactory y marcamos de manera manual una versión estable, ¿cierto?, de de ese artefacto y eso nos permite a nosotros en caso de requerir pues un un rollback pues poderlo acceder de manera pues sencilla, ¿cierto?


00:11:10

Jaime Gallo: ¿Por qué digo que hay una versión uno? Porque el próximo paso eh y la recomendación de nosotros ayer al banco fue esto, hay que empezar a revisar cómo podemos evolucionarlo de cara a evitar tiempos muertos, ¿cierto? o redespliegues que tengan afectación en el servicio con alguna estrategia pues de deployment que podamos adoptar en el banco.
Andrés Useche: Okay. Y un y listo. y toda esta documentación, o sea, te estoy entendiendo, hay un área encargada en el banco de hacer la implementación como tal de los pilines. Sí. y digamos que pues en conjunto pues vanu de acuerdo a la necesidad del proyecto, pues cada uno de los stage o jobs, pues que requiere cada peline, la configuración de aprobaciones, todo esto sí lo trabajarías un un equipo ya del banco como tal o cómo funciona ahí.
Jaime Gallo: El banco de alineamiento base.
Andrés Useche: Sí.
Jaime Gallo: Lo que hacemos cuando ya llegamos a los proyectos es revisar qué tan congruente o qué tan pertinente es lo que se tiene desde la línea base y lo adoptamos. Entonces, por ejemplo, ¿qué encontramos? RBA no había. Listo, ya lo lo determinamos. Por ejemplo, particularidades como la security en algunos proyectos aplican algunos no. Sí, eso ya depende pues de restricciones, de del alcance que se tiene el proyecto.


00:12:48

Jaime Gallo: Entonces ahí es donde nosotros a partir de ese lineamiento base nosotros entramos y revisamos y diseñamos si esto nos aplica, si esto no nos aplica y vamos ajustando y vamos ajustando y lo vamos adoptando al proyecto. ¿Qué lo hace?
Andrés Useche: Okay.
Jaime Gallo: Nosotros, nosotros ya
Andrés Useche: Ah, pero ustedes mismos van construyendo y van personalizando,
Jaime Gallo: entramos.
Andrés Useche: customizando el pil de acuerdo a la necesidad. Ah, okay, okay.
Jaime Gallo: Sí.
Andrés Useche: S, listo. No, pues de mi parte yo no tengo aquí inquietudes. Sí, pues veo, digamos que eh en pues ahí digamos era más un poco esa práctica de conocer muy bien esa práctica de lo que es integración continua, todo el proceso de de pruebas, eh, y pues veo pues digamos que tienen ya muy buena base ahí también y pues están buscando siempre esas oportunidades de mejora sobre el proceso de integración continua, despliegue continuo y pues creo que ya conceptualmente ente, pues digamos ahí eh tienes ya un dominio, ¿sí? Eh, y pues has entrado un poco a conocer en detalle cómo es el proceso.
Jaime Gallo: Así es, así es. Fíjate que en en como front, cuando estaba como front, no como líder técnico, sino como front, también tuve el acercamiento, pero saben qué me faltaba la parte de seguridad.


00:14:19

Jaime Gallo: Entonces, ya aquí ya empiezo yo a ser consciente, miren, el pil se no rompe, si por ejemplo las las unitarias no nos alcanzan la cobertura o por ejemplo si las mutation no nos pasan o qué pasa con el licenciamiento si estamos incumpliendo algo. as cositas ya empieza uno a tenerlas en cuenta para tener todo el ciclo de énfasis en nivel de seguridad y creo que eso me ha ayudado bastante a complementar lo que tenía yo a nivel conceptual y práctico de de todo este tema de de integración y desplieg Venga.
Andrés Useche: Claro. Y y ya y ya vas lo vas viendo, ¿no? Es un R. de de usuario, ¿sí? que genera un un pull request y sabes pues que te vas a apoyar en un pilem, sino también de contribuir en cómo se puede optimizar el flujo, qué es lo que le sirve al proyecto y las necesidades que tiene el proyecto,
Jaime Gallo: Así es, así es,
Andrés Useche: ¿no? Sperime.
Jaime Gallo: Fácil.
Andrés Useche: Listo. digamos que bueno y esta parte de EPSECOP pues bueno, yo creo que que pues has tenido un avance pues interesante y conociendo pues entendiendo conceptualmente y entendiendo pues realmente la importancia de cada
Jaime Gallo: Ok.
Andrés Useche: uno de los pasos o de los jobs, ¿sí?, que se van definiendo y el y el origen y el y digamos y la finalidad como tal de cada de cada uno de estos pasos.


00:15:53

Andrés Useche: Listo. Entonces, si quieres continuemos.
Jaime Gallo: Listo. Déjame revisar aquí que tengo la cabeza todavía en otro lado. Eh, infraestructura. Listo. Eh, de arquitectura para listo, ¿no? Eh, de cara a la distribución de tráfico. Ah, bueno, entonces les voy a mostrar ahora sí la arquitectura que tenemos acá y les muestro que hemos revisado por estos lados. Uno de los de los comentarios que recibía de parte de César la vez pasada era cómo yo podía reflejar desde la arquitectura esas decisiones a nivel de redes, ¿cierto? Yo estoy indagando bastante con el tema en el banco y resulta que ellos tienen su propia nomenclatura para para documentar esos sistemas, ¿cierto? Ellos tienen especialistas en ciberseguridad y no estuve de acuerdo en adoptar eso mismo para traerlo como parte del de los espacios de crecimiento porque no quisiera ser experto en algo que es muy propio, ¿cierto? Entonces, de cara a la seguridad o por ejemplo el balanceador, hablemos de pronto del balanceador. Creo que no hay mucha cosa por comentar acá, más de de poder saber la diferencia entre el balanceador de
Andrés Useche: Ô
Jaime Gallo: carga y el balanceador de red y cómo dentro del proyecto a nosotros una vez No. configuramos nos empezó a hacer de utilidad. Ha sido poco el acercamiento que tenemos aquí, pero pero no no tengo pues realmente más por estos lados.


00:18:12

Jaime Gallo: ¿Qué tengo aquí? El balanceador, ¿cierto? Eh, si ustedes se fijan acá, esto lo que nos está representando es esos clientes que vamos a tener nosotros de día generativa en el banco, cómo se pueden conectar a todos estos servidores MSPs que están pues agrupados de acuerdo a a unos dominios de información y que a su vez esos MCPs consumen esas APIs que les comentaba, ¿cierto? ya son lápiz existentes en el barco. Entonces esto viene evolucionando de cara a cómo nosotros podemos distribuir esa carga en este EK y tiene que ver con este balanceador, ¿cierto? Lo que yo he encontrado y el aprendizaje que he tenido es que es de vital importancia poder tener ese punto de entrada antes de que llegue nuestro tráfico a la red. En este caso, pues la red del closer acá. Porque nosotros eh necesitamos un lugar central para poder controlar qué es lo que vamos a estar realizando dentro de las aplicaciones y dónde podemos nosotros redirigir el tráfico para aplicar políticas de seguridad y autenticación, que es lo que ya nos da el que tendríamos pues dentro de cada pod, pero acá pues se ve reflejado.
Andrés Useche: Vale, ahí de pronto sí sí v la pena que explores un poco realmente eh cuál es el objetivo, ¿sí? Por detrás en cuanto a atributos de calidad que te da tener un balanceador de carga.


00:19:53

Andrés Useche: Sí, un balanceador de carga eh por lo menos y y digamos en en EKS, ¿sí? Cuando tú vas a exponer un servicio, ¿sí? En este caso pues vas aquí veo que tienes como bueno, tienen digamos ya como algo de definición por dominios, ¿sí? Segmentados por dominios de información y pues si tienen un EKS es porque tienen ya un pull de pots corriendo. Sí. o de distancias corriendo que van a tender todo el tráfico y cómo ese ese ese, o sea, cómo puede escalar, ¿sí?, en instancias o en réplicas a nivel de pots, ¿sí? Y por detrás, cómo puede cómo esos pots, pues se van soportando finalmente en una infraestructura a nivel de servidores, ¿sí? De de Easy Tool, ¿sí?
Jaime Gallo: Aha.
Andrés Useche: Entonces, de pronto, de pronto sí te falta explorar un poco más, ¿sí? y entender pues realmente eh cómo pueden llegar a a distribuir o a plantear, ¿sí? A decir, listo, pues en función de de la carga operativa que voy a tener o de la carga, sí, de toda esa carga que me va a llegar, ese tráfico de lo que me van a llegar a partir de los agentes, ¿sí? ¿Cómo es que se va generando ese escalamiento?


00:21:14

Jaime Gallo: H
Andrés Useche: Sí. ¿Cuál es el tamaño máximo? Porque claro, digamos, el balanceador de carga, la idea es entender realmente pues su finalidad. Su finalidad es poder llegar a soportar un escalamiento horizontal, ¿sí? También de de en función del tráfico que te va llegando. Sí. Entonces, eh por lo regular,
Jaime Gallo: Ah.
Andrés Useche: entonces eh un microservicio o espace del MCPA, pues va a recibir cierto tráfico. Sí, pero pues eso también hay que definir en cuanto a memoria y CPU, qué tanto va a poder tener ese nodo, ¿sí? y qué tanto va a soportar y empezar a jugar con esos valores para decir,"Listo, yo voy a iniciar siempre voy a tener eh por lo regular se recomienda siempre voy a tener por lo menos dos instancias corriendo en diferentes zonas de disponibilidad. Ahí ya estoy garantizando alta disponibilidad. ¿Sí? Entonces empezar y entender un poco más a nivel también de los servicios de AWS, ¿sí? cómo se soporta y cómo le va pegando también a esos atributos de calidad, ¿sí? A nivel de performance, a nivel de escalabilidad, ¿sí? Y y entonces entender un poco más, ¿sí? Cómo los atributos de calidad entran a jugar acá.


00:22:45

Andrés Useche: Probablemente ya se tiene configurado, ¿sí? y muchas veces llegamos a los proyectos y esto ya está configurado y pues mágicamente tú ya sabes que colocas un pod y de pronto ya hay un escalamiento por unas reglas de escalamiento por defecto. Sí, hay una eh la mayoría de los podores ya se tienen también definido pues eh que tienen pues más o menos esta memoria asignada eh y esta CPU asignada. Sí, las reglas de escalamiento en función también de lo que estemos construyendo. ¿Sí? O definimos que escala es por cuando va llegando a los límites o de memoria o de consumo de CPU.
Jaime Gallo: Ven,
Andrés Useche: Sí.
Jaime Gallo: pero creo que hay dos conceptos ahí. Una cosa es el tema de cómo el balanceador me ayuda y otra es ya las políticas de escalamiento que tengo dentro de mi clúster. Eh, entiendo bien.
Andrés Useche: Sí, sí, sí. Son varios, son varios conceptos.
Jaime Gallo: Eso.
Andrés Useche: Sí. y es entender pues digamos también como parte de esa optimización de la distribución de tráfico, cómo le van pegando todos esos conceptos que a la M. eh los puedes ir aterrizando desde los atributos de calidad. Sí, porque entonces digamos en este caso eh pues ya tienen eh se fueron por el camino de KS, pero probablemente en otro proyecto si tengas que tomar eh entre una decisión entre qué será mejor para el proyecto, entre SS o EKS.


00:24:21

Andrés Useche: Sí, si me voy por algo serverless o algo, pues digamos en donde ya tengo una infra mínima requerida, ¿sí? O ¿por qué tomar de pronto una decisión de aquí de vámonos eh por microservicio o por o por lambdas este tipo de servicios, ¿sí? o este tipo de funcionalidades. Acá pues digamos que para acá el caso seguramente se hizo el análisis y pues se fueron por EKS o ya tienen unas capacidades de EKS y que las quieren realmente aprovechar. Sí, pero pero es todo lo que hay por debajo y cómo se van mapeando todos esos atributos de calidad. Sí,
Jaime Gallo: entiendo.
Andrés Useche: no, pero está está s ahí digamos que lo importante es eso,
Jaime Gallo: Esta
Andrés Useche: ya ir entendiendo, ya vas interactuando, ¿sí? Y conceptualmente vas aterrizándolo así, digamos como como hiciste todo el ejercicio, es darle un poco más de doble clic a estos punticos. es parte del proceso. S listo. Y a nivel de infraestructura, entonces también tenemos todo el tema de topología de red. Sí, ahí no sé de pronto qué has logrado explorar o qué has logrado entender o extraer ya de los proyectos que vienes
Jaime Gallo: No, no, de esa parte no,
Andrés Useche: trabajando.


00:25:55

Jaime Gallo: no logro tener todavía la oportunidad de revisarlo.
Andrés Useche: Vale, hay hay una documentación, yo la busco también de pronto y te la referencio también, que está en Alejandría de digamos y incluso también hay una charla que se llegó a dar en el chapter hace un par de meses por parte del equipo de Cloud Ops, en donde ellos ya tienen también una un explican y digamos ya tienen unos módulos de Terrafone de Terraf que ya soportan una topología de red con una recomendación iones mínimas, ¿sí? Y pues se han aplicado ya en diferentes proyectos. Entonces, si quieres, yo te la dejo también ahora como referencia para que puedas también ir explorando y entender, pues digamos cuándo eh necesitamos de pronto eh o o si eh pues tener, digamos, en diferentes zonas de disponibilidad cómo queda configurado un clúster de KS. Yeah. en las diferentes zonas de disponibilidad dentro de una región. Sí. Eh, para, no sé, definir un plan de recuperación de desastres, ¿qué estrategias se pueden llegar a tener, pero entonces, digamos, como todo como toda la base es entender, sí? Digamos como todas esas nociones a nivel también de networking, ¿sí? y de los servicios de networking que tiene AWS para que puedas, digamos, ir también ahí mapeando pues todas toda eso, ¿no?


00:27:30

Andrés Useche: Pero s listo. El otro que teníamos o o que con cuál quieres continuar de pronto ahí de lo que traías ahí preparado.
Jaime Gallo: Déjame mirar.
Andrés Useche: A ver, tenemos ahí seguridad. Sí.
Jaime Gallo: Eh, listo. Seguridad. Tenemos lo de seguridad. E de seguridad.
Andrés Useche: Ok.
Jaime Gallo: Estuve realizando un curso eh de parte de la compañía de preparación para la certificación de W Security Engine Event. Es eso fue hace como dos mesecitos dos meses y medio más o menos. Ahí pues se nos dio eh el toda la introducción de de los temas de seguridad, de cómo nosotros podíamos de manera efectiva aplicarlo dentro de una arquitectura. Sin embargo, los conceptos los tengo, pero no tengo la posibilidad de aplicarlos. ¿Sí? ¿Por qué? Porque estos lineamientos de seguridad son dominios del equipo de ciber del banco y hasta ya no logro tener alcance. Entonces esa parte, digamos, sí la he reforzado bastante a nivel eh teórico con con el tema que que te comento, pero de manera práctica y aplicada con proyectos y y en los proyectos que estoy actualmente
Andrés Useche: Vale, aunque claro Aunque digamos que dentro del mapa no,
Jaime Gallo: No.
Andrés Useche: pues lo que específicamente digamos ya deberías eh entrar de pronto a revisar, ¿sí?


00:29:29

Andrés Useche: Pues no, digamos conceptualmente de pronto el curso ya te dio bastante. Sí, aquí si miramos el mapa de crecimiento, eh, nos habla de pronto del del uso efectivo del cifrado simétrico y asimétrico. Sí. Entonces,
Jaime Gallo: Mhm.
Andrés Useche: eh no sé si dentro de lo que has trabajado han logrado ya tener algún cifrado. Si, normalmente pues se entre la integración del fren fronten y el backen o cuando estamos exponiendo un ápis, pues si se maneja algún tipo de cifrado para información sensible, ¿sí? O privada. Entonces, no sé si de pronto ya hayas trabajado con algún tipo de implementación o tengas el conocimiento ya por lo menos de esa
Jaime Gallo: Sí, así es, así es, parce.
Andrés Useche: parte.
Jaime Gallo: Fíjate que cuando yo hablo de que no lo puedo aplicar es yo siendo un un interventor en esas definiciones, pero pero mirémoslo aquí, ¿cierto? Porque cuando yo vengo del del curso de preparación y y vuelvo a revisar una vez la arquitectura, primero ya mí hace sentido dónde tenemos esos servicios de secret managers, de KMS y segundo ya puedo alinear mejor al equipo. Entonces digamos si tengo el acercamiento, pero no la práctica de, bueno, necesito un un tal servicio aquí por esta y esta razón que fue las que vi en el curso de certificación.


00:30:54

Jaime Gallo: Sí, para que me entiendan ahí que digamos tampoco es que esté en cero, ¿cierto? ¿Qué tenemos aquí? ¿Cómo lo usamos nosotros? Eh, sí, estas APIs tienen diferentes tipos de autenticación. Unas tienen cifrado AES, unas tienen una autenticación simple por por client ID, client secret, otras combinan diferentes firmas con JWTs. Dicho, esto es dependiendo de casi que el banco cómo se maneja esas organizaciones. Entonces, sí nos toca jugar mucho con eso. ¿Cómo lo cómo lo trabajamos? Cuando tenemos certificados, los almacenamos. en en en KMX, ¿sí? Cuando ya se requiere pues algo bien puntual que nos permita a nosotros generar algún tipo de de autenticación o algún token temporativo y algunos credenciales si los manejamos en SECR manager, que es donde nos permite a nosotros eh almacenar,
Andrés Useche: H
Jaime Gallo: por ejemplo, todos esos credenciales que tenemos de autenticación a las APIs, desde los postes en particular.
Andrés Useche: okay. Y y digamos esta esta arquitectura de solución, ¿sí? ¿Qué dominios de información o qué o funcionalmente qué estamos resolviendo? Sí. o estos encipis que nos
Jaime Gallo: que no resuelven.
Andrés Useche: resuelven.
Jaime Gallo: Listo. Lo que pasa es que el banco viene con el programa de IA para todos buscando generar aplicaciones basadas en inteligencia artificial.


00:32:33

Jaime Gallo: Y cuando se van al desarrollo de esas aplicaciones encuentran que para consumir las APIs de productos pues hay un gap porque yo no puedo conectar directamente un LLM a pues mi mi API, necesito un puente. Con esta arquitectura se pretende resolver ese gap a través de la implementación. Centralizad. y controlada de los diferentes servidores MSPs. ¿Por qué? ¿Por qué digo centralizado? Porque en teoría estos MSPs deberían de estar acá junto a las AF. Sí, pero como es un equipo diferente y es donde estamos nosotros trabajando el que está desarrollando y manteniendo hasta la fecha esos servidores MCPs. Entonces, lo que se está haciendo es yo lo centralizo dentro de un space particular y los voy desarrollando y posteriormente cuando pasa la producción se los entrego a los equipos.
Andrés Useche: Ok.
Jaime Gallo: Entonces, ¿qué resolvemos con esta arquitectura? Le habilitamos al banco poder eh tener a disposición de las aplicaciones de generativa todo su ecosistema de APIs bancarios.
Andrés Useche: Y y esto la idea entonces es que sea como algo transversal para que todo lo el resto de aplicaciones o productos pues que que van desarrollando lo utilicen de forma centralizada, algo
Jaime Gallo: Así es,
Andrés Useche: así.
Jaime Gallo: así es. Esta es la versión, digamos, con la que nosotros estamos trabajando cuando tenemos acercamientos con el arquitecto que está pues de cara al banco con con estas definiciones, es lo que nos comenta es que el evolutivo es lo que les acabo de comentar, yo ya no tener centralizado mis recursos, sino que cada dueña de su API y conocedora, pues sea la que mantenga su MCP y de esa manera entonces volvemos a descentralizar, pero hasta el momento el modelo de gobierno es centralizado a través de la EBC


00:34:51

Jaime Gallo: de inteligencia artificial, en este caso.
Andrés Useche: Okay. Okay. Listo. Entonces, acá volviendo a a seguridad, entonces digamos eh ahí lo bueno también es ya entender conceptualmente lo que es cifrado simétrico y asimétrico, ¿sí? Y en qué momento se usa. Sí. Entonces, por eso te preguntaba un poco si habías utilizado de pronto algo descifrado al consumir las APIs. Sí, por lo regular pues digamos o en la data sensible pues se se determina o se define un mecanismo descifrado, ya sea a nivel de payó o ya sea nivel de dato. Sí, en donde pues se se pueden definir diferentes estrategias y el uso de cifrado
Jaime Gallo: Hm.
Andrés Useche: simétrico o asimétrico. Sí, en función de la necesidad, digamos que ahí por lo menos ahí ya por lo regular se utiliza tráfico, https y eso lleva su su clave, pues digamos ya KMS que asegura pues digamos ya un cifrador Yeah. canal. Sí. Y pero entonces es es es entender también los diferentes tipos de claves que nos ofrece, por ejemplo, el servicio de KMS, en qué momento los puedo utilizar o cuáles son pues esos esos usos pues más comunes. Sí. Eh, a nivel ahí también de seguridad,


00:36:20

Jaime Gallo: M.
Andrés Useche: entonces tenemos como todos esa implementación de principios de seguridad en arquitectura, información y acceso, ¿sí? Que va muy de la mano también del servicio de IAM, ¿sí? De siempre pues eh tener como esos niveles de autorización buscando siempre eh el principio del mínimo privilegio. Sí. Entonces,
Jaime Gallo: Sí.
Andrés Useche: pues digamos que eso de pronto implícitamente pues eh muchas veces se utiliza, pero no somos tan conscientes de realmente todo lo que hay que hacer o o a nivel, digamos, ya de definición, en algún momento ya cuando te toque, pues definir ese tipo de de reglas, ¿sí? para en una arquitectura para asignar o para ir pues eh definiendo cómo van a ser pues esos accesos a los diferentes servicios, a los diferentes
Jaime Gallo: Fíjate, fíjate, Andrés, que justamente siendo conscientes de eso,
Andrés Useche: recursos.
Jaime Gallo: fíjate que hay dos cosas aquí de cara a la autenticación. Una es el tema de de IAM y el otro el entra id.
Andrés Useche: Mhm.
Jaime Gallo: Cuando nosotros empezamos el proyecto, los micros no tenían autenticación.
Andrés Useche: Okay. O sea, era el APIA expuesta y cualquier
Jaime Gallo: el AP en Qay y cualquiera con VPN ya estaba listo. Empezamos nosotros a indagar en el tema.


00:37:53

Andrés Useche: consumidor.
Jaime Gallo: Listo, le montamos autenticación con cognito, conectamos el ISIO para que pudiéramos eh aplicar esa autenticación en todos los ens. Lo implementamos siendo conscientes de lo que me estás comentando. Y después viene que al entra ido. Yo le levanto la mano al arquitecto y le pregunto, ¿qué pasó?
Andrés Useche: Mhm.
Jaime Gallo: ¿Por qué ese cambio? y me dice que como esos MCP son de uso interno, todos los que estamos desarrollando son de uso interno, ellos ya tienen un Active directory con todos los juguetes.
Andrés Useche: Con todos los usuarios.
Jaime Gallo: Claro, para todos los usuarios internos. Y entonces un cognito implica pues una sincronización si es el caso de de de conectar el aso pues con el con el con el incógnito, pero también implica una configuración manual. Entonces fue un evolutivo que se tuvo y digamos que surgió de cara a nosotros tener la conciencia de primero tenemos una autenticación, unos servicios expuestos aquí sin seguridad y segundo un evolutivo que pues hoy en día ya funciona con con el Entraid como tal.
Andrés Useche: Okay. Okay. Sí. Y a nivel de autorización, pues ya tenían ahí todo pues todos los usuarios ya configurados y y se movió y alcanzaron a configurar el cognito en su momento y migraron ya en 3D por lo que ya tenían los usuarios y y aplicación, o sea, toda la configuración también.


00:39:41

Jaime Gallo: Sí, así es, así es. Lo que hacíamos en su momento era casi que compartir un token. Quemamos ese token y con eso nos íbamos con cosmito, pero pero posteriormente eso se fue migrando al entraid como tal.
Andrés Useche: Okay. Sí, ¿no? Y ahí aprovechamos también el single sign de las aplicaciones consumidoras y y pues
Jaime Gallo: Es así. Vamos pena.
Andrés Useche: Listo.
Jaime Gallo: Vamos a este que es el nuevo y acá tenemos una
Andrés Useche: Ok.
Jaime Gallo: particularidad y es aquí. Aquí vamos a interactuar con con los unos operadores logísticos que son los encargados de los envíos de las tarjetas. Y justamente pensando en esa seguridad hemos levantado la mano porque primero no sabemos esto cómo se va autenticar de cara a nosotros reportarle las actualizaciones de las tarjetas a los operadores. Y segundo, sí, acá tenemos una interfaz, pero no nos han dado firma y solamente nos están diciendo, tenemos un a 2.0. Entonces, ¿qué te digo yo pues con esto o qué te quiero decir? Uno ya con esa vista de seguridad empieza como que a ver otras cosas de cara a la arquitectura cuando se las empiezan a entregar a uno y y entonces en eso estamos están esas conversas apenas revisando cómo es que va la cosa por estos lados porque no esto ya está ya está y esto qué y cómo es la cosa acá.


00:41:12

Jaime Gallo: Entonces chévere, chévere uno tener esa esa conciencia de ese aspecto de seguridad.
Andrés Useche: Ah, s Sí, sí, ya ahí ya ya va siendo muy consciente, ¿sí? Y de pronto no recibir eso, lo que tú dices, un API que no que no esté sin ningún modelo de autorización, ¿sí? y que sea accesible a todo el mundo ahí también pues cómo se van a a compartir esas credenciales para ese dos.
Jaime Gallo: Adi
Andrés Useche: S listo, listo, Jaime. Bueno, ¿con qué continuamos? Tenemos también por ahí el tema de observabilidad.
Jaime Gallo: Listo.
Andrés Useche: M.
Jaime Gallo: Pase al en la S. Yeah. Nosotros cuando digo EBCS dentro de la estructura organizacional de Ban Colombia ellos se distribuyen por EBCS. Entonces una es de medios de pago, otra es de tarjetas de crédito, otra es de el cliente, otra es de la sucursal virtual y son equipos grandes, ¿cierto? son equipos pues bien grandes que dentro tienen otros equipos y dentro de esta como nosotros estamos apenas incursionando con la implementación de los servidores MS en el banco, hayan muchas cositas como te dice cuenta con con por ejemplo la autenticación e de de de los MCPs y una de las cosas que faltaban era esto, toda la parte de observabilidad. A nosotros nos estaban solicitando ya pasó la producción y y en ese tiempo estaba yo siguiendo el curso de de Open Telemetri, que ahí les cuento pues también que hice pues ya un cursito de Open Telemetri, justamente como parte del feedbac de la sesión anterior.


00:43:02

Jaime Gallo: Levantamos la mano y no podemos salir sin esto porque ya ahora sí entendemos por qué es esto importante. Entonces empezamos nosotros a indagar y a colaborar y lo que descubrimos fue que en el banco se tiene una capacidad que se instala en los clústers llamada Vision y y se compone todas estas herramientas de observaría. Entonces, lo que nosotros hicimos aquí fue solicitar la instalación del clúster, configurar la observabilidad que tenemos, ya les voy a mostrar, y eh instrumentar los servidores MSPs usando Open Element que tenemos acá. Yo miro si les puedo espirar un momentico. Creo que lo había sacado. Me me dicen si se ve por
Andrés Useche: Eh,
Jaime Gallo: no
Andrés Useche: creo que dejaste. Ah, bueno, ahí ya está cargandom Sí, ahí ya se ve.
Jaime Gallo: listo. Listo. Entonces, aquí les muestro eh todo el portal de Vision que les estaba comentando. Y acá tenemos unos logs. estaba haciendo por aquí una hace un ratico de por ejemplo un MCP, ¿cierto? Este que se llama de de intenciones de negocio. Eh, ¿qué qué podemos ver aquí? Que ya tenemos los los configurados y pues más importante de cara al Open Telemetric que tenemos una estructura ya definida, ¿cierto? de cara a, espérenme, yo les muestro acá de cara a cuáles son esas esas esas propiedades, ¿cierto?


00:44:49

Jaime Gallo: Eh, pues algunas instrumentan de cara al closer y otras de cara a la aplicación. Entonces, hemos hecho un trabajo aquí ya también de consolidación de todas esas métricas, logs y trazas en los servidores MSPs. Y lo hemos hecho teniendo en cuenta que la especificación de Open Telemetri para IA hasta la última vez que revisé estaba todavía en proceso de definición. Entonces fue algo que nosotros pues esto no sirve y con esto nos vamos. Ya después revisamos qué pasa en un
Andrés Useche: Listo.
Jaime Gallo: evolutivo.
Andrés Useche: Porque porque aquí básicamente, bueno, ahí tienen toda la telemetría y eso es que que lo hacen con instrumentación automática.
Jaime Gallo: Listo. Entonces,
Andrés Useche: Ahí configuran la instrumentación automática y empieza ya a llevar pues toda la gestión
Jaime Gallo: sí,
Andrés Useche: de
Jaime Gallo: sí, así es. Les voy a mostrar de nuevo el documento y les muestro que eso empieza desde la integración continua.
Andrés Useche: L
Jaime Gallo: Nosotros cuando generamos el artefacto acá, cuando generamos el artefacto, no lo veo. Okay. Acá cuando estamos generando eh el el artefacto ya como tal de el que vamos a subir a Jfg, lo que hacemos es dentro de ese shift que vamos a subir aquí a a Azure
Andrés Useche: Ok.
Jaime Gallo: Artifacts, lo que hacemos es descargar el agente de Open Telemetry para que con la imagen de Docker cuando ya se compile, ¿cierto?, pues pueda eh cogerla y tenemos una instrumentación semiautomática porque nosotros nosotros desde Sprene AI, que es el el digamos la capacidad que tenemos a nivel back para trabajar con los servidores MSPS, está todavía pues cruda la implementación o la madurez diría yo, de de la implementación de Pentelemetric para MCPs y lo que hacemos es adecuarla,


00:46:56

Jaime Gallo: ¿cierto? Entonces, si tenemos una instrumentación semi semiautomatizada, pues ahí de cara a los servidores de
Andrés Useche: Ah,
Jaime Gallo: MC.
Andrés Useche: okay. Sí, si lo preguntaba por eso, porque como está tan nuevo, entonces la autoinstrumentación pues creo que no iba a ser suficiente. Sí. Y les iban a quedar ahí cositas por fuera. Sí. Igual eh porque bueno, ahí veo que tenías en lo que en la arquitectura eso, pues eh tenías ahí todo el tema de Prometeus con grafana y eso eh te apunta ahí también a poder llevar todo el monitoreo de infraestructura, ¿sí? para ir viendo pues no sé la salud de cada pot el rendimiento, pues digamos ya de la carga de los servidores que están soportando el clúster y a nivel también de tráfico de red.
Jaime Gallo: Sc.
Andrés Useche: Eh, pero toda esa parte me imagino que hasta ahora la están viendo. o ya has logrado también interactuar pues con toda esa parte de de monitoreo de
Jaime Gallo: Sí, sí, sí.
Andrés Useche: infraestructura.
Jaime Gallo: Mira que eh cuando nosotros se nos instalan eh en el clúster de toda esta plataforma de Vision, el equipo de monitoreo se encarga de configurar tableros básicos de enfana para todo el tema de la APM.


00:48:23

Jaime Gallo: Entonces, eso nos sirve especialmente a nosotros cuando estamos haciendo eh pruebas de aceptación y pruebas de performance eh para revisar cómo es que se está comportando el sistema. Déjenme, yo miro si les
Andrés Useche: Y ahí que hacen pruebas de de carga y estrés sobre las fature que van liberando.
Jaime Gallo: puedo eh nosotros sí, nosotros hacemos tres línea base, eh carga y estrés más las aceptan y lo hacemos por
Andrés Useche: Okay.
Jaime Gallo: tool, por tool del MCP.
Andrés Useche: Mhm.
Jaime Gallo: por el MSPamos una serie de pruebas ahí y eso es lo que
Andrés Useche: Ok.
Jaime Gallo: revisamos y también lo usamos la observabilidad. En el banco tenemos algo que se llaman ambientes efímeros y es un pil que a partir de un openapi me configura un S2 temporal y me permite montar un MOC de esa especificación y eso lo usamos nosotros para certificar cuando tenemos inestabilidad en los ambientes de de preproducción. Eso nos ayuda también cuando tenemos eh temas de performance de pues cuando ya las pruebas están fallando de performance justamente por ambiente a revisar y a entender qué es lo que está pasando eh en esos ambientes efíulos y pues lograr pues la la certificación.
Andrés Useche: Okay. Ahí de perdón.
César Augusto Moncada Calderón: Equipo tengo que mover a otro espacio.
Andrés Useche: Dale,
Jaime Gallo: Gracias,


00:50:00

Andrés Useche: dale.
César Augusto Moncada Calderón: Ya terminas con Andrés y después también igualmente converso con él y ya pues también la idea es que Andrés haga la calibración y pues ahí yo estaré también apoyando la calibración. Listo.
Andrés Useche: Listo,
César Augusto Moncada Calderón: Muchas gracias.
Andrés Useche: listo, César. Vale, muchas gracias.
Jaime Gallo: César.
Andrés Useche: Listo. Ahí a nivel de observabilidad, eh, no sé si has revisado algo de monitoreo sintético. Sí, también. Y si aplica aquí en las tools, por ejemplo, en este proyecto, en las tools que que lo están haciendo, están ahí, pues no sé si tienen algunos casos de
Jaime Gallo: No, no en este proyecto no. En el de la SP sí lo aplicaba,
Andrés Useche: Sí.
Jaime Gallo: la SP.
Andrés Useche: Ok.
Jaime Gallo: Lo que hacíamos con el monitoreo sintético a través de Aina 3 era que se configuraban varios puntos, varios varios puntos, pues, y se configuró un robot y con ese monitoreo No.
Andrés Useche: Ok.
Jaime Gallo: sintético lo que hacía es de manera periódica nos iba visitando el sitio. Era un monitoreo sintético a nivel de front, pero lo que hacía era nos permitía conocer a el microbrón del home se cayó, ¿cierto?


00:51:12

Jaime Gallo: Y esa era la notificación que nos llegaba a nosotros, pues cuando estábamos en el momento por allá tirando, ¿no? Entonces, de cara a a a Daina 3, ahí dice como dos mundos, todo el tema de Gravana y y Daina 3.
Andrés Useche: H
Jaime Gallo: En preproducción se usa grafano y ya en producción cuando los servicios son expuestos al cliente se usa todo el tema de de y allá en la CP como estamos expuestos al cliente sí trabajamos con el tema del monitoreo sintético.
Andrés Useche: Bueno, porque el monitoreo sintético va también un poco más allá, ¿no? Y es poder también pues eh eh simular esas interacciones del usuario, ¿sí? y mediante automatización para ir haciendo pruebas de disponibilidad o o no sé, tener un scope de transacciones sintéticas de pronto de un flujo funcional o una interacción eventual o más común del usuario.
Jaime Gallo: Yeah.
Andrés Useche: Sí, para alertar de forma temprana de que ojo, este flujo funcional o este esta transacción sintética empezó a fallar. Sí, pues claro,
Jaime Gallo: Sí,
Andrés Useche: como complemento pues un poco también del monitoreo de
Jaime Gallo: de acuerdo, de acuerdo contigo.
Andrés Useche: infraestructura.
Jaime Gallo: Y y mira que nosotros usamos más de cara a lo funcional pensando en la disponibilidad.
Andrés Useche: Sí.
Jaime Gallo: Porque cuando yo te decía el monitoreo lo configurábamos de cara a el 11 cayó era ya había entrado por el microautenticación, el microfron de autenticación y a través de ese microfron de autenticación una vez nos bloqueábamos que ahí donde viene la automatización se redirigía al home.


00:53:04

Jaime Gallo: Si el microfon del home, el microground de autenticación o el shell tenían errores, que era casi que el 80% de las transacciones que tenía la sucursal virtual en ese momento, pues teníamos un buen eh monitoreo de cara pues a lo que estaba sucediendo en la aplicación web, no tanto digamos de cara a Sí, sí, más de cara a lo funcional realmente fue lo que aplicamos en el el monitoreo sintético
Andrés Useche: Listo. de pronto y bueno, de observabilidad,
Jaime Gallo: parmh
Andrés Useche: no sé si también has tenido la oportunidad ya de ver todo el tema de costos de infraestructura o todo el tema de FINOPS, ¿sí? O en eso pues digamos que que ese también es es bueno empezar también a revisarlo. Sí. Yeah.
Jaime Gallo: Mhm. Sí, cuando inició el proyecto has dicho,"No, no lo he revisado,
Andrés Useche: Sí.
Jaime Gallo: pero soy consciente de ello." Y te cuento que qué pasó con el proyecto, pues o mi acercamiento hasta el momento, eh, con el proyecto de los MCPs, a nosotros nos tocó desplegar toda la infra, o sea, la infra nos tocó,"Venga, muéstr la arquitectura y voy allá con mi, no con IAC, sino con un portal de backstage que tiene el banco propio.Aamos
Andrés Useche: Mhm.


00:54:29

Jaime Gallo: Y y sabes qué, nos empezamos a dar cuenta que el consumo mensual de de del de los servidores MSPs estaba ascendiendo a los $,000. Pero eso fue a cálculo, ¿cierto? A cálculo de nosotros, pilas,
Andrés Useche: Sí.
Jaime Gallo: que por acá va hay algo que revisar. Por la parte de Fins, nosotros no participamos. Esos son equipos de auditoría del banco que son los que se encargan ya de revisar cuando ellos monitorean a través de todos los tags, de todo el tema de tener bien configuradas las cuentas y los grupos en los recursos, nos levantan la mano. Entonces, digamos, soy consciente del tema, quisiera profundizarlo bastante y eso es todo lo que tengo
Andrés Useche: Sí, listo. Igual hay, claro, digamos que hay hay bastante en dentro del MCP
Jaime Gallo: Pas.
Andrés Useche: de hay un NCP, digamos, que ya tiene el equipo de Cloud Ops. Sí. Eh, él también incluso eh desde el código de la IAC te genera ya una estimada de costos teniendo en cuenta pues digamos un posible cantidad de usuarios, eh tráfico o a nivel de transacciones y nos puede llegar a estimar probablemente, claro, en este proyecto de pronto no. Sí, pero de cara ya a este camino que estás tomando de arquitectura, pues un poco la recomendación es empezar también a revisar como toda esa parte de FinOPS.


00:56:06

Andrés Useche: Sí, porque pues digamos uno de pronto has interactuado ya con la calculadora de AWS, me imagino, sí, pero pues va un poco más allá porque es poder llegar a dimensionar,
Jaime Gallo: Sí.
Andrés Useche: ¿sí? ¿Cuánto nos va a costar un consumo o cuánto nos va a costar la operación de esta arquitectura de solución que estoy proponiendo?
Jaime Gallo: Mira que mira que en las nosotros hemos hecho varias varias estimaciones,
Andrés Useche: Sí.
Jaime Gallo: ¿cierto? Eh, con el equipo de Alianza, que es cuando cuando vamos por allá a a entregarles el show. de de las po que hemos hecho. Ya nos toca Dios y entregarles cómo es que va la cosa, ¿cierto? de cara a las estimaciones, pero para mí un próximo paso yo considero que es como tener un monitoreo continuo vivo de lo que está pasando con mis con mi presupuesto en mi sistema. Yo creo que para allá apunta fino esto por dónde
Andrés Useche: Claro.
Jaime Gallo: es.
Andrés Useche: Eh, pero pero claro, pero ese ese sí es un monitoreo continuo y normalmente pues ya tenemos unos tableros de FINOPS. Sí, incluso aquí en Pragma pues se trabaja bastante con datado y el equipo de Clobs, por ejemplo, ellos ya eh hay ellos ya tienen digamos también hay un módulo de datado doc monitoreando costos y te proyecta costos.


00:57:42

Andrés Useche: Sí. y se van configurando, pues digamos también alertas tempranas en donde eh si el costo
Jaime Gallo: Hm.
Andrés Useche: estimado es tanto y ya voy en en mi presupuesto super llegando a un 40% y apenas pues estoy iniciando el mes, se genera de pronto un primer nivel de alertamiento. Sí, pero incluso nace desde el diseño de arquitectura,
Jaime Gallo: Sí.
Andrés Useche: ¿sí? en donde tú puedas proyectar y estimar unos costos asociados de tener, eh, no sé, este clúster de base de datos. Estoy aquí, digamos, también eh con un clúster de rediscaché por acá, ¿sí? Ir generando, digamos, el el coste base, ¿sí? Y el coste transaccional, ¿sí? Entonces, por eso también es muy importante y ahí es donde tú empiezas ya a alimentar, ¿sí?, todo lo que necesitas para definir una arquitectura de solución. Sí. Entonces, digamos que que parte un poco de eso. Entonces, eh por eso digamos acá en Pragma tenemos lo que es ese documento de arquitectura con diferentes vistas de arquitectura. ¿Sí? Entonces, digamos,
Jaime Gallo: Mhm.
Andrés Useche: un poco la recomendación es tratar de llevar hacia eso un poco, ¿sí?


00:59:03

Andrés Useche: ¿Qué nos faltaría para poder documentar una solución completa teniendo como base pues digamos tener toda esa arquitectura de solución? Sí, porque pues digamos que eh en los pinitos que ya vienes dando y en el crecimiento que estás dando, pues ya te has enfocado y ya vas identificando la importancia de documentar o de pensar en cómo contribuir en esas decisiones de arquitectura, porque la son decisiones de arquitectura que se están tomando. Sí, a veces de pronto lo has hecho implícitamente. Si lo bueno es que veo que ya estás siendo consciente de cómo tomar esas decisiones de arquitectura y de pensar en temas de seguridad, en temas de, digamos, ya de de entrar a entender lo que es eh la disponibilidad, el tráfico de red. Sí. Entonces empiezas ya a ser consciente de ese tipo de decisiones de arquitectura. Sí, pero entonces lo lo que lo que veo que de pronto te falta a nivel de documentación de
Jaime Gallo: Sí.
Andrés Useche: arquitectura es empezar a bajar y eh lo que lo que te recomiendo un poco es tomar como tal, o sea, la estructura del documento de arquitectura, ¿sí? Y ahí empiezas a ver la identificación de los dominios, por ejemplo, y empiezas a bajar desde una vista funcional, ¿sí?, de lo que va a aplicar, ¿sí? Es tratar de de ir haciendo ese ejercicio, ¿sí?, como pequeña para para ir siendo un poco más consciente de que ya vas identificando.


01:00:42

Andrés Useche: Entonces, primero vas teniendo, por ejemplo, ese business model canvas que eh vas identificando del negocio, ir bajando eh de pronto ya los KPIs, sí, que tiene el proyecto eh identificando todos los stakeholders porque digamos un documento también de arquitectura va a diferentes stakeholders. Sí.
Jaime Gallo: Hm.
Andrés Useche: Y las vistas que se proponen es para diferentes eh stakeholders de la organización, pues que les interesa ciertos dominios de información o de documentación específica. Sí, por el momento eh veo que y de acuerdo pues también a a al progreso, ¿cómo vas? lo vas muy bien, pero sí te recomiendo un poco revisar, sí, el SAT, sí, incluso ya tenemos el NCP, no sé si si estuviste en los dos últimos chapter
Jaime Gallo: en
Andrés Useche: de arquitectura, en donde se presentó el MCP de arquitectura, en donde ya trabaja lo que es la arquitectura de solución o o arquitectura de alto nivel y arquitectura de bajo nivel. Sí. Entonces empieza, pero entonces es empezar a mirar es todas esas diferentes vistas en donde ya tienes una vista de contexto, una vista de información, ¿sí? Que eso te va te va a colindar ahí con lo que con el esfuerzo que estás haciendo ahí de todo ese tema de arquitectura de datos, ¿sí? que estás trabajando ahí en la mentoría, pero tratar de ir viendo cómo yo puedo o qué puedo alimentar o qué puedo complementar de lo que estás documentando frente a lo que se plantea ya desde el SAT.


01:02:32

Andrés Useche: Sí.
Jaime Gallo: S.
Andrés Useche: y puedes y puedes aprovechar el MCP de arquitectura que ya tiene Bragma, que ese ya tiene unas definiciones y tú puedes eh colocarle y dar,
Jaime Gallo: Ah.
Andrés Useche: digamos, ese insumo para validar parte de las decisiones que ya estás tomando. Sí. Y, incluso hay un formato ahí de decisiones de arquitectura, ¿sí? ¿Cómo documentar adecuadamente? porque pues digamos que Eh, las decisiones de arquitectura lo ideal es tener pues digamos las alternativas de solución que se evaluaron, ¿sí? Eh, la justificación del por qué estoy tomando esta decisión y dejar como esa trazabilidad documentada. Si me quiero volver, ah, ¿por qué? ¿Por qué me decidí en algún momento por un incógnito y me tocó cambiarme a un asure? ¿Qué consecuencias pues o o qué impacto me está generando en el proyecto? Sí, ese tipo de cosas ahí.
Jaime Gallo: Aha.
Andrés Useche: No te pregunté, Jaime, eh, a nivel de certificaciones de AWS, ¿ya tienes alguna certificación o cómo lo vas o o has explorado ya algún algunas certificación aparte, pues digamos que de los entrenamientos que has tenido puntuales?
Jaime Gallo: Parce, yo me he preparado múltiples ocasiones para la para las deoper y la de ¿Cuál es que es la primera?


01:04:00

Andrés Useche: La de associate,
Jaime Gallo: El de la de no,
Andrés Useche: solución architect associate.
Jaime Gallo: pero no la de arquitecto.
Andrés Useche: Ah, la de Sí,
Jaime Gallo: Primerita, primerita se me va eso practiciones.
Andrés Useche: la de practitioner. Mhm.
Jaime Gallo: E yo he encontrado hasta que inicié la la mentoría con Edward, mi pensamiento era, yo aplico lo que ya voy a presentar, no necesito presentarlo y lo he cancelado tres veces, dos veces el developer y una social. Entonces, eh me siento preparado, pero no las he realizado hasta que no me aterrizó. Primero porque en el banco si quiero continuar por mi lado revisando y creyendo aún más, el banco dentro de sus exigencias, pues tiene el tema de gente que esté certificada porque la industria es lo que pide, ¿cierto? Y segundo, porque pues no va a ser lo mismo. Yo me preparé para un curso a mi certificación el tema.
Andrés Useche: Mhm. Sí,
Jaime Gallo: Entonces me ha ayudado a a generar conciencia de de eso.
Andrés Useche: exacto.
Jaime Gallo: Entonces, en resumen, no tengo, soy consciente de que debo de hacerla y es el próximo paso después de que termine la mentoria.
Andrés Useche: Dale. No, igual si ya, o sea, es que si presentas la de associate, eh, puedes presentar la de developer.


01:05:26

Jaime Gallo: Ok.
Andrés Useche: El gap de información para presentarla de developer ya es muy pequeño porque es que pues claro, se enfoca más de pronto la developer se enfoca más en los servicios, digamos ya de desarrollo de lambdas, de de digamos ya de entrar ahí de KS o sí, en cambio la de la de arquitecto pues ya te da todo ese background. Yeah. o puedes hacer una primero y luego la otra y ya el salto es muy sencillo y casi que presentas una y ahí investigas sobre el gap de servicios que debes estudiar y te preparas para la otra y son, o sea, son muy similares. Sacando una sacas la otra y ya tendrías ahí las dos,
Jaime Gallo: De acuerdo.
Andrés Useche: pues. Pero pero dale. Igual aquí también eh pues desde el chapter de arquitectura,
Jaime Gallo: Esh
Andrés Useche: pues claro, va a interesar más que hagas la de arquitectura, pero las dos igual son pues son muy, o sea, son complementarias, pero muy muy buenas. Ahí sí vale la pena de pronto ya que métetelo ahí como como reto también hacerlo y ahí queda queda
Jaime Gallo: De acuerdo, de acuerdo. Y y sabes también echando aquí cabeza,
Andrés Useche: soo
Jaime Gallo: ¿por qué no lo haya hecho? Porque después no me lo cuenta para los logros.


01:06:58

Jaime Gallo: Entonces, entonces esperarme ahora a que se reinicien
Andrés Useche: dale dale que eso ahora mismo ya Es ya.
Jaime Gallo: para
Andrés Useche: Bueno, como cambió también el sistema de logros, pues a la final ya no ya no tendrías que hacer los pues toda la cantidad para subir de de qué de senority, sino pues ya es por cada por cada review que vas a programar, pues tienes que hacer un unos logros,
Jaime Gallo: así es.
Andrés Useche: ¿no? Pero dale, anímate, anímate. Y sí, como recomendación, pues esa parte sí revíate bien todo el tema del SAT. No sé si llegaste o o qué conocimiento ya tienes o qué dominio tienes de los framework e que tenemos acá en Pragma, que está el de observabilidad, el de desarrollo, el de arquitectura. No sé si los has eh ya revisado, los conoces y los has ejecutado. Sí,
Jaime Gallo: Mira, Andrés,
Andrés Useche: los framework de madurez.
Jaime Gallo: sí, sí, sé que existen, no los conozco a detalle. El que sí me he leído es el SAT, ¿vale? Pero pero tengo una perspectiva muy personal de cara a dónde
Andrés Useche: Mhm.
Jaime Gallo: empiezo yo a involucrarme con los documentos y la forma de trabajo del arquitecto en Pragma y dónde queda mi rol.


01:08:30

Jaime Gallo: Porque si tú me lo preguntas a mí, todavía no soy arquitecto. Yo yo esperaría aplicarlo cuando lo sea. Esa es como mi perspectiva, pero ahorita yo quiero primero cerrar las brechas, tener un buen fundamento y que sea lo del SAS, lo del framework, es como ese complemento para ya tener todo definido. Entonces, por eso no lo he indagado los
Andrés Useche: Sí. lo que sí puedes hacer, sí,
Jaime Gallo: pacientes.
Andrés Useche: porque mira que de todas formas el mapa de crecimiento está estructurado por niveles de madurez dentro de un seniority, ¿sí? Y por seniorities,
Jaime Gallo: Ok.
Andrés Useche: ¿sí? Pero a la final es que a medida que vayas avanzando ya vas teniendo la en el mapa de crecimiento vas teniendo la capacidad de poder ir generando un documento de arquitectura de solución como lo promueve Pragma.
Jaime Gallo: Ok.
Andrés Useche: Sí. Entonces se y iba subiendo el nivel de exigencia a nivel de las capacidades que debes ir dominando, ¿sí? En el mapa de crecimiento. Entonces, está bien. O sea, probablemente tú digas,"Ah, mira, de pronto esta en el SAT hay una vista de infraestructura. Esto me pega aquí con el frente de infraestructura. Entonces ahí ya puedo ver, puedo y y lo y lo y lo puedes ir también mapeando.


01:10:01

Andrés Useche: Entonces decir, listo, no me voy a generar un SAT completo, pero sí voy a trabajar el capítulo de la vista de infraestructura. Sí.
Jaime Gallo: Mhm.
Andrés Useche: Y esto ya te va te va a obligar y te va a dar también los elementos de ver, pues digamos lo que es toda la topología de red, ¿sí? Y entonces en esa vista de infraestructura ya estás tomando decisiones de arquitectura. Y está el capítulo también ahí del SAT de decisiones de arquitectura. Sí. Y te lleva y te y te da la guía de cómo documentar unas las decisiones de arquitectura o qué tener en cuenta durante la evaluación de esas decisiones de arquitectura
Jaime Gallo: M.
Andrés Useche: que que debas tomar.
Jaime Gallo: Ok.
Andrés Useche: Sí. Pero si sigues el mapa es tratarlo de ir mapeando.
Jaime Gallo: Ok.
Andrés Useche: Si. Y empezar a y meter también aquí a las herramientas de Pragma. Si, entonces ya tenemos un NCP de arquitectura. Empieza a jugar también con el NCP de arquitectura de Pragma.
Jaime Gallo: Ok.
Andrés Useche: Sí. Entonces, eso ver eh las tools que nos ofrece el NCP de arquitectura y le puedes pasar el contexto del proyecto y generar y el mismo NCP te lo te genera, pues digamos un documento de arquitectura con el insumo que le des del proyecto,


01:11:18

Jaime Gallo: Mhm.
Andrés Useche: pero como para ir entendiendo, ir jugando y ahí pues eso también te puede ir ayudando.
Jaime Gallo: Todo
Andrés Useche: Pero pero si sigues el mapa es eso.
Jaime Gallo: 20.
Andrés Useche: Y revísate también lo de los framewor de madurez, en especial pues digamos el de arquitectura, observabilidad y y qué y seguridad, ¿sí? Que son, digamos, pues ahí está el de Clouds, está el de desarrollo, pero pues digamos que a nivel de Cloudop, pues bueno, ya viniste haciendo un ejercicio en donde ya adquiriste, pues digamos un conocimiento y pues lo lograste documentar y conceptualmente ya lo aterrizaste bastante. Sí. Ev. Entonces, eso entonces viene también esta la vista de información también ahí en el chat y vienes con el tema ahí de arquitectura de datos. De pronto terminas de hacer ese programa ahí con que vienes manejando con con Edward y pues dices,"Listo, voy a generar una vista de información, voy a tener muy claros estos dominios de información,
Jaime Gallo: Ah.
Andrés Useche: el ciclo de vida de la información." Sí. y empiezas ya a generar eh y a y a y hacerlo por pedacitos, no tienes que enfocarte en todo el sado. El SAD es grandísimo.


01:12:31

Andrés Useche: Sí, pues porque tú tienes que tener ya un contexto y se revisa y va orientado es mu a soluciones probablemente pues o a proyectos de pronto de cierta dimensión y pues que igual tienes que tener toda la documentación y proyectos nuevos. Sí, acá estás ya trabajando sobre una base, pero puedes ir trabajando por capítulos. Sí. y vas mapeando contra contra las capacidades que debes pues que quieres mejorar en el mapa de
Jaime Gallo: Entiendo, entiendo. Creo que eso va a ser un un factor clave,
Andrés Useche: crecimiento.
Jaime Gallo: Andrés, para para este próximo espacio de crecimiento, el tema del SAT. Creo que es hora de de empezar a usarlo y a revisarlo
Andrés Useche: Eso y eso, eso no, dale. Igual, claro, es, o sea, es un proceso. Sí, es un proceso. Has venido ya, pues veo que has venido trabajando en esas brechas, ¿sí? constantemente, eh, pero no, pues hay que seguir y pues muy chévere lo de la maestría también dale, o sea, dale la importancia también a las certificaciones, eso se valora mucho también en el mercado, en los clientes y como parte de tu crecimiento también en Pragma también pues lo valoran mucho porque pues cuando piden de pronto hojas de vida, pues lo primero que mira un cliente realmente, ah, mira, está certificado.


01:14:03

Andrés Useche: Entonces, pues por lo Sí.
Jaime Gallo: Sí, sí, sí,
Andrés Useche: Eso da mucho valor también a a tu crecimiento y a tu hoja de vida.
Jaime Gallo: sí.
Andrés Useche: Y pues digamos que para presentarlas pues tú ya que has estudiado sabes que realmente se va adquiriendo el conocimiento. Sí. Y y es ir poniéndolo en práctica. Lo bueno es que pues estás practicando con muchos de los servicios.
Jaime Gallo: Así es, así es, así
Andrés Useche: Bueno, Jaime, yo creo que no,
Jaime Gallo: es.
Andrés Useche: por mi parte yo no tengo más preguntas. No sé si tienes algo también que agregar.
Jaime Gallo: Andrés, eh te encomiendo, porfa lo del recurso de anterioridad de de lo de la topología de red.
Andrés Useche: Listo.
Jaime Gallo: Sería por muchas gracias.
Andrés Useche: Sí, listo. Yo yo te organizo ahí también y te paso entonces lo de los framework de madurez, el pues también del SAT que todo está en Alejandría y te y te paso ahí un listadito de
Jaime Gallo: Okay,
Andrés Useche: recursos ahí que te recomiendo.
Jaime Gallo: Muchas
Andrés Useche: Listo, listo. Jaime, ¿no? Muchas gracias a ti por el espacio y y nada,
Jaime Gallo: gracias,
Andrés Useche: ahí seguir seguir creciendo. Chévere el camino que ya estás tomando y tienes todavía mucho por aprender y y s, yo creo que y si te te apasiona el tema, pues s aquí en el chapter hay mucho conocimiento también que eh también aprovechar mucho a Edward que también sabe bastante. Sí, aprovéchalo ahí en esa mentoría.
Jaime Gallo: Claro que sí, vale.
Andrés Useche: Listo.
Jaime Gallo: Muchas gracias.
Andrés Useche: Bueno, ahí estamos hablando que estés bien.
Jaime Gallo: Que te vaya bien. P. Chao. Muchas gracias.
Andrés Useche: Vale,
Jaime Gallo: Yeah.
Andrés Useche: chao.


La transcripción finalizó después de 01:15:46

Esta transcripción editable se generó por computadora y puede contener errores. Los usuarios también pueden cambiar el texto después de que se cree.
