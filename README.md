- [0. Interactivos17-Relatos en la Espera](#interactivos17-relatos-en-la-espera)
- [1. Idea](#1-idea)
- [2. Implementación](#2-implementación)
- [2.1 Caso-a-estudiar](#2-2-caso-a-estudiar) 
- [3. Desarrollo de los relatos](#3-desarrollo-de-los-relatos) 
- [4. Tecnología](#4-tecnología)
- [5. Experiencia de usuario](#5-experiencia-de-usuario)
- [6. Diseño de producto](#6-diseño-de-producto) 
- [Promotores y colaboradores](#promotores-y-colaboradores)
- [Instrucciones](#instrucciones)
- [Diario del proceso](#diario-del-proceso)
    - [Promotores y colaboradores:](#promotores-y-colaboradores:)
         - [Equipo:](#equipo:)
         - [Colaboradores](#colaboradores)
         - [Autores e Interpretadores de los textos](#autores-e-interpretadores-de-los-textos)
    - [Instrucciones](#instrucciones)
         - [Instrucciones de montaje y desmontaje](#instrucciones-de-montaje-y-desmontaje)
         - [Instrucciones de funcionamiento](#instrucciones-de-funcionamiento)
         - [Instrucciones de mantenimiento](#instrucciones-de-mantenimiento)
    - [Diario del proceso](#diario-del-proceso)
         - [Semana 1](#semana-1)
         - [Semana 2](#semana-2)
         - [Semana 3](#semana-3)

# Interactivos17-Relatos en la Espera  
Antes de empezar a movernos con el transporte público vivimos en la ‘espera’, en un tiempo muerto e insignificante. ¿Qué objeto, suceso o acontecimiento nos puede despertar del letargo de esa espera?
![](LOGOFINAL.jpg)
- [Video presentación del proyecto](https://www.youtube.com/watch?v=_y7_L4MCVnM&feature=youtu.be)

## 1. Idea
Hoy en día los usuarios del transporte público suelen recibir información del tiempo de espera. Un tiempo que hasta ahora está ocupado, principalmente, por el teléfono móvil y la publicidad de las paradas. El proyecto aprovecha ese tiempo de una forma alternativa, involucra al viajero en una experiencia extraña pero enriquecedora que sirve para contextualizar la ciudad que le envuelve. La audición de un relato que dura el tiempo de espera previsto se convierte en el detonante para viajar con la imaginación sin moverse de la parada.

![](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/1-idea/Relatos-de-espera_low.jpg)

## 2. Implementación

### 2.1. Estado del Arte 
Se ha hecho un rastreo de otros proyectos que se han desarrollado en torno al transporte público. Proyectos que unas veces se han centrado en la lectura de un libro, en los anuncios que suelen estar en estas paradas o en lo que ocurre durante el viaje. Para localizar la propuesta de "Relatos en la Espera" en este entorno de referencias, se ha llevado a cabo un "Mapa de usuario" que permite reconocer todas las referencias estudiadas bajo dos parámetros: nivel de relación con el factor tiempo de espera y nivel de importancia de la oralidad. Ambos factores han sido elegidos por su fuerte vinculación con el transporte; el primero por su funcionalidad, el segundo por la capacidad de despertar la imaginación y por favorecer el alejamiento del teléfono móvil o de la publicidad de una ciudadanía volcada exclusivamente en lo visual.  

![](https://github.com/medialab-prado/interactivos17-relatosenlaespera/blob/master/2-1Estado%20del%20Arte/MAPADEUSUARIO.jpg?raw=true)

+ 01 Axe, pantalla interactiva (https://www.youtube.com/watch?v=UIHwHqaY3SY)
+ 02 Expendedora de libros (http://www.lamasbella.es/bellamatic/) 
+ 03 Máquina expendedora de micro-relatos (http://lapiedradesisifo.com/2015/11/14/la-maquina-expendedora-de-relatos-cortos)
+ 04 Cuentos por teléfono (http://maguared.gov.co/project/cuentos-por-telefono-libro-de-gianni-rodari-para-ninos/)
+ 05 Cocacola, pantalla interactiva (https://www.youtube.com/watch?v=ctdYwo55pPA)
+ 06 Apotek, pantalla interactiva. (https://www.youtube.com/watch?v=tdQgsmYKxLM)
+ 07 Best Bus Ever (https://www.youtube.com/watch?v=zpdcUakdQVA)
+ 08 Billetes impresos en libros (https://www.youtube.com/watch?v=1PAkrApvkac) 
+ 09 Kulturbus (https://www.youtube.com/watch?v=W20u8qJWv2M)
+ 10 Viraphone (http://danielperlin.net/#viraphone-with-vito-acconci)
+ 11 Portadas de libros comprometidas (https://www.youtube.com/watch?v=2LyVVbhvStk)
+ 12 Photoshop en la pantalla (https://www.youtube.com/watch?v=jpRmQo1_4Es) 

### 2.2. Caso a estudiar 
De los modos de transporte donde se lleva a cabo la espera, autobús, tren o metro, se decide estudiar el autobús por tener menos elementos de distracción. Actualmente en Madrid, lugar donde se lleva a cabo el prototipo, todas las paradas de metro disponen de pantallas que indican el tiempo de espera, así como en muchas ocasiones televisiones o anuncios que juegan con la presencia del viajero en la parada. Mientras que en autobús, la presencia de pantallas que indican el tiempo de espera es más escaso y los anuncios en las marquesinas suelen ser más genéricos.

De todas las líneas de autobuses que existen en Madrid, se decide la línea 6. Esta línea no es de suministro, es decir no sirve para llevar a los usuarios a centros productivos de la ciudad, sino que es una línea de barrio que alimenta al barrio de Orcasitas y que puntualmente pasa por la ciudad.

![](https://github.com/medialab-prado/interactivos17-relatosenlaespera/blob/master/2-2%20Caso%20a%20estudiar/caso-tranporte-aubobuses-madrid.png)

De todas las paradas que tiene la línea 6, se ha elegido la que está en la plaza Tirso de Molina. Una parada que está en una plaza con bastante vida, cerca de centro Medialab Prado, y que tiene árboles cercanos que dan sombra a la parada. Algo que ayuda al prototipo pues no hay reflejos en la pantalla.

![](https://github.com/medialab-prado/interactivos17-relatosenlaespera/blob/master/2-2%20Caso%20a%20estudiar/plaza-tirso-molina-madrid_01.png)

Para conocer los hábitos de los usuarios de dicha parada se ha llevado a cabo una recogida de datos tanto de forma cuantitativa, basadas en la observación, como de forma cualitativa. Esta segunda ha permitido conocer las características habituales de los usuarios de dicha parada, cuáles son sus hábitos, qué ven desde ella, cómo la habitan. Respecto a la recogida de datos de forma cuantitativa estos son los datos recogidos: 
Hora de llegada/salida, hombre/mujer/otro, solo/acompañado, edad (joven/mediano/mayor), actividad (móvil/libro/bolso/conversación), si está sentado o no lo está.

Así mismo se ha llevado a cabo un cuestionario a pie de parada de autobús que ha permitido reconocer el perfil  del usuario mayoritario de dicha parada: mujer, principalmente sola y de edad avanzada.

![](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/2-2%20Caso%20a%20estudiar/Resumen%20de%20datos%20observados%20(1).jpg)

A parte de esta recogida de datos hemos llevado a cabo una encuesta a través de las redes sociales para saber la reacción ante un posible dispositivo que cuente un relato durante las esperas. En esta ocasión la distribución de edad es mucho más repartida y las actividades que se realizan en general son más variadas. 

![](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/2-2%20Caso%20a%20estudiar/Resumen-Sobre-el-tiempo-de-espera-(6).jpg) 

El resultado de estos documentos nos informa que hay un usuario en las paradas principalmente mujer de mediana o avanzada edad que no usa teléfono móvil. Así mismo se destaca en los cuestionarios el escaso interés de que suceda una actividad en las paradas, sin embargo el alto interés ante que la actividad sea un relato escuchado que permita saber más sobre la ciudad inmediata en torno a ella.

## 3. Desarrollo de los relatos 
A través de redes de contacto se ha localizado a escritores a los que se les ha dado una serie de recomendaciones a seguir: la claridad en la redacción del relato, la simplicidad y sobretodo el objetivo de que las historias sirvan para ampliar la lectura de la ciudad inmediata. Los relatos sirven para construir y para saber más de la ciudad que envuelve a la parada. Se adjunta el mail de invitación que se envió a los autores. En él se especifican la importancia del tiempo del relato, imágenes de lo que se ve desde la parada y una lista de detonantes generales que tienen el objetivo de ayudar a inventar los relatos.

Así mismo, gracias a la colaboración de actores, los textos han sido interpretados para que el contenido tuviera más incidencia en el oyente y realismo.

![](https://github.com/medialab-prado/interactivos17-relatosenlaespera/blob/master/3%20Desarrollo%20de%20los%20relatos/creacion-relatos.jpg) 

Estas son las historias elegidas junto a los relatos producidos. 
Título / Autor / Intérprete / Duración:

+ 1 Se busca poeta / Paloma Diez Temprano /	Manuel Cruz López ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/Se%20Busca%20Poeta.mp3)
+ 2 Besos en la parada /	Paloma Diez Temprano /	Manuel Cruz López ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/Besos%20en%20la%20Parada.mp3)
+ 3 Chofer /	Marta Felipe Soria /	Manuel Cruz López ![Audio](https://github.com/fagtrivino/interactivos17-relatosenlaespera/blob/master/3%20Desarrollo%20de%20los%20relatos/Chofer.mp3)
+ 4 Tarde de Domingo /	Paloma Diez Temprano /	Gonzalo Pendolema ![Audio](https://github.com/fagtrivino/interactivos17-relatosenlaespera/blob/master/3%20Desarrollo%20de%20los%20relatos/Tarde%20de%20domingo.mp3)
+ 5 Un, dos, tres, cuatro vamos a divertirnos un rato /	Fran Carrillo /	Raquel Sánchez ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/Un%20dos%20tres%20cuatro%20vamos%20a%20divertirnos%20un%20rato%20(9.17).mp3)
+ 6 La muerte y la doncella /	Bernardo Gómez /	Mónica Montoro ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/La%20muerte%20y%20la%20doncella.mp3)
+ 7 El flautista /	Julia Livaditi /	Mónica Montoro ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/El%20flautista.mp3)
+ 8 Chocolate con churros /	Marta Felipe Soria /	Marta Felipe Soria ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/Chocololate%20con%20churros.mp3)
+ 9 El tapicero /	Marta Felipe Soria /	Manuel Cruz López (hombre), Elena Peña Parrilla (mujer), Marta Felipe Soria (tapicero)![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/El%20tapicero.mp3)
+ 10 Ocupación para desocupados /	Ángel Muñoz Jiménez,	Manuel Cruz López ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/Ocupaci%C3%B3n%20para%20desocupados.mp3)
+ 11 Como no bailar salsa /	Katerina Psegiannaki /	Monica Montoro ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/Como%20no%20bailar%20salsa.mp3)
+ 12 En un minuto /	Bernardo Gómez ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/En%20un%20minuto.mp3)
+ 13 Bolsa para la compra /	Isabel Martín Ruiz / Isabel Martín Ruiz, Damiana Ruiz 
+ 14 Dos minutos /	MaxCooper /	Monica Montoro ![Audio](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/3%20Desarrollo%20de%20los%20relatos/Dos%20Minutos.mp3)
+ 15 Un fantasma en Zingarella /	Osvaldo Michelón / Osvaldo Michelón

## 4. Tecnología 
Se han barajado distintas tecnologías para llevar a cabo el dispositivo. Desde una App hasta un teléfono analógico que pudiera servir para escuchar los relatos. Dada la vinculación de la espera con el lugar donde se desarrolla, la tecnología del prototipo tendría que dar salida a este requisito. Por lo tanto la solución de una App no ha sido factible por la deslocalización del lugar y por el necesario consumo de datos que supondría trabajar con ella. A priori el uso de la tecnología "nearby" parecía la más óptima: una vibración del móvil personal cuando el viajero se acerca a la parada sería una buena solución para llevarlo a cabo, salgo que para el desarrollo del prototipo es excesivamente complejo.

Por facilidad de ejecución se decide desarrollar una tecnología mixta. Un dispositivo que con apariencia de teléfono permitiera narrar las historias y junto a él una pantalla con la que interaccionar para especificar el tiempo de espera que el usuario estima que va tardar el transporte.

![](https://github.com/medialab-prado/interactivos17-relatosenlaespera/blob/master/4-Tecnologia/desarrollo-tecnologico.jpg)

El producto final ha necesitado de: 
+ Tableta android de 18 pulgadas, en donde se ha desarrollado un interfaz. 
+ Sensor de distancia. [Sensor de ultrasonido](http://www.micropik.com/PDF/HCSR04.pdf)
+ Arduino Uno
+ Batería
+ Micro switch swap
+ Cable OTG

### 4.1. Lets code
#### 4.1.1. [Android App](https://github.com/fagtrivino/relatosEnLaEspera) 
#### 4.2.2. [Arduino y Sensores](https://github.com/fagtrivino/interactivos17-relatosenlaespera/blob/master/4-Tecnologia/sensor2.inoX)
##### Diagrama esquemático
![](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/4-Tecnologia/relatosEsquematico.png)

Conexiones: 
![](https://github.com/medialab-prado/interactivos17-relatosenlaespera/blob/master/4-Tecnologia/sistema-electronico.png)

## 5. Diseño de Interfaz de Usuario en producto digital
Dado el diseño del prototipo, la experiencia de usuario se ha basado en dos puntos importantes: en el diseño de un interface en la pantalla del dispositivo y en la primera experiencia auditiva que recibe el usuario.

![](https://github.com/medialab-prado/interactivos17-relatosenlaespera/blob/master/5-Experiencia%20de%20usuario/ui-app-relatos.jpg)

En el diseño del interface, para una mayor credibilidad, se ha hecho uso del color oficial de la EMT. Así mismo también se ha diseñado un entorno simple y sobrio, con un tamaño de fuente pensado para un usuario de edad avanzada. La primera pantalla es la más importante, la cual invita al usuario a usar el dispositivo, el pictograma de una persona mayor busca empatizar con el usuario habitual. 

Por otro lado la primera experiencia auditiva se vuelve muy importante para empatizar con el usuario. Por ello se ha trabajado con la frase "Hola soy Leo, estoy aquí para hacer tu espera más amena, lo único que necesito de ti es que me selecciones cuánto tiempo vas a esperar". Se ha elegido el nombre de Leo por la ambigüedad de género, así como una frase natural que intente alejarse de las respuestas automatizadas de los servicios telefónicos habituales.

![](https://github.com/medialab-prado/interactivos17-relatosenlaespera/blob/master/5-Experiencia%20de%20usuario/ui-prototipo-relatosenlaespera.jpg)

## 6. Diseño de producto 
El diseño del dispositivo se basa en la integración de una tablet de 18", un sensor de distancia, un arduino, una batería y el cuelgue del mango del teléfono. Un solo elemento que actúa como cabina telefónica, colgado a través de unas cinchas a la altura de una persona sentada. Dado que el dispositivo estará en la parada y que en ocasiones el sol puede llegar generar un brillo que dificulte la lectura en la pantalla, el diseño incluye una pequeña visera que se integra en el diseño final.

![](https://github.com/medialab-prado/interactivos17-relatosenlaespera/blob/master/6-Dise-o%20de%20producto/prototipo-artefacto.jpg)

El material usado para el dispositivo principal es madera DM cortada a laser, de 5 mm de espesor. El diseño del mango telefónico es de madera pero de 3mm de espesor. La madera tanto del manguito como del dispositivo se resuelve con ensambles en L.

El modelo desarrollado no es impermeable, pero sería necesario su planteamiento en el caso de que se llevara a cabo en otra escala.

Para el modelado se ha utilizado el sowftware Solidwords, y para el corte láser DraftSight-3DS. Se adjuntan en la carpeta correspondiente.

![](https://github.com/medialab-prado/interactivos17-relatosenlaespera/blob/master/6-Dise-o%20de%20producto/desarrollo-artefacto.jpg)

## 6. Experiencia de usuario
![](https://github.com/medialab-prado/interactivos17-relatosenlaespera/blob/master/imagenes/experiencia-usuario.jpg)

## 7. Testeo con usuarios
![](https://github.com/medialab-prado/interactivos17-relatosenlaespera/blob/master/imagenes/testeo-relatos-usuarios.jpg)


# Promotores y colaboradores: 
### Equipo: 
+ Katerina Psegiannaki (www.kuneoffice.com/)
+ Francisco García Triviño (http://www.kuneoffice.com/)
+ José Manuel López Ujaque (http://www.kuneoffice.com/)
### Colaboradores
+ Sandra Vivar Maestre (www.sandramind.design/)
+ Katalina Soto Rivera (https://www.behance.net/katakatasoto)
+ Mario Alejandro Alzate López (www.marioalzatelopez.com)
+ Inmanulada Marruecos Payán (www.behance.net/inmarru)
+ Marta Felipe Soria 
### Autores e Interpretadores de los textos
+ Manuel de la Cruz (interprete)
+ Gonzalo Pendolema (interprete)
+ Raquel Sánchez (interprete)
+ Monica Montoro (interprete)
+ Marta Felipe Soria (autora e interprete)
+ Elena Peña Parrilla (interprete)
+ Ángel Muñoz Jimenez (autor)
+ Bernardo Gómez (autor e interprete)
+ Esther Iorfida (autor)
+ Fran Carrillo (autor)
+ Julia Livaditi (autor)
+ Osvaldo Michelón (autor e interprete)
+ Paloma Díez (autor)

# Instrucciones
### Instrucciones de Expo  ***Mirar***
+ Video del proyecto, en la carpeta RELATO ( en el escritorio ). Arranca automatico en ubuntu con el video en fullscreen. 
+ Una Cabina telefónica con un telefono interactivo. 
![](https://github.com/medialab-prado/interactivos17-relatosenlaespera/blob/master/imagenes/espacio-expositivos-RE-01.png)

### Instrucciones de montaje y desmontaje  ***Mirar***
+ Qué material se necesita
1. Cabina de telefono interactiva.
2. Cascos de audio para el vídeo.

+ Cómo se ensambla todo
1. Tenemos un powerBank que alimenta el altavoz bluetooh. 
+ En qué puntos hay que tener cuidado
1. Cable OTG se deconecta facilmente. 
2. La tapa frontal hay que abrirla como si fuera una bisagra a su parte izquierda. 
3. Todos los elementos dejarlos conectados a sus cargadores ( powerback, tablet ) manualmente. 

### Instrucciones de funcionamiento
+ ¿Cómo se enciende? ¿Cómo se apaga? ***Mirar***
1. Colocarse frente el telefono. Hay un sensor que detecta la presencia si estas mas de 4 segundos al frente. 
3. Contestar al telefono si llaman, elegir el tiempo de espera, escuchar el relato, colgar. 

+ ¿Qué hace exactamente? ¿Cómo interactuar con el dispositivo? (pensar que la gente que lo ve no ha estado en el taller). 
Para poder interactuar con el aparato hay que cumplir con las siguientes condiciones con el orden indicado: 
1.	La Tablet encendida y el altavoz encendido
2.	El teléfono tiene que estar colgado para que el switch esté cerrado. 
3.	La App “relatos en la espera” tiene que estar activa.
4.	Conectar el Arduino en la Tablet. En el mensaje: “Allow the app Relatos en la Espera to acces the USB device” cliquear “Use by default for this USB device” y a continuación decir OK.

Una vez todas las condiciones previas cumplan puede empezar la interacción.

La primera pantalla de la app dice: “tenemos una historia que contarte” e invita el usuario a acercarse. 
Al acercarse el usuario a los 60 cm o más cerca el sensor ultrasonido hace que se active la siguiente pantalla que dice: “Hola, te estoy llamando” e invita el usuario descolgar el teléfono que en este momento está sonando.

Al descolgar el usuario el teléfono que está sonando aparece directamente otra pantalla que pregunta: “¿Cuánto tiempo crees que vas a esperar?” y da la posibilidad al usuario a escoger un botón desde 1 minuto hasta más de 10 minutos. También se puede contestar “No lo sé”. Por el telefonillo se oye “Hola soy Leo, estoy aquí para hacer tu espera más amena, lo único que necesito de ti es que selecciones cuanto tiempo vas a esperar”.

Al elegir un botón el usuario se pasa a una nueva pantalla que dice “escúchame”. Por el telefonillo se oye un relato que dura aproximadamente el tiempo de la espera que ha seleccionado el usuario. Esta pantalla sigue así durante todo el tiempo que se oye el relato. 

Una vez acabado el relato aparece una pantalla que dice “FIN” e indica los créditos del relato “Titulo, Autor, Locutor”. Después de un corto tiempo sale automáticamente otra pantalla que dice “Hasta Luego” y pide al usuario volver a colgar el teléfono para que otro usuario pueda seguir interactuando con el aparato. 

![](https://raw.githubusercontent.com/fagtrivino/interactivos17-relatosenlaespera/master/instrucciones/funcionalidad_low.jpg)

### Instrucciones de mantenimiento
+ ¿Tiene batería? ¿Cómo cargarla? ¿Cada cuanto?
1. El altavoz bloutooh está adentro del telefono. Abrir la tapa de arriba y conectar el altavoz ( tiene un boton de ON/OFF) manualmente. 
2. Hay que cargar la bateria de la tablet cada cierto tiempo, ya que la entrada USB se ocupa con el cable OTG y no permite cargar al mismo tiempo. Que hacer ? desconectar el OTG y cargar con el cargador que hay a disposicón. 
3. Encender la tablet si está apagada. -> Tiene un boton de encendido y apagado que se accede por el hueco del telefono. 

+ Si deja de funcionar cuál sería la lista de errores más corrientes: de los más comunes a los más raros. ¿Cómo arreglar cada uno?
Por ver, tiene varios bugs. Por ahora: *VUELVE Y CUELGA*

# Diario del proceso
### Semana 1
Durante la primera semana, el cuestionamiento y la viabilidad del prototipo ha tomado el máximo protagonismo. Las mentorias han cuestionado y no han invitado a concentrarse en las historias para que el dispositivo sea lo más sencillo posible. 
Tanteo de tecnologías a desarrollar. 
### Semana 2
El desarrollo de las historias ha sido lo más importante, la busqueda y la localización de escritores y actores. El desarrollo del dispotivo básico, a pesar de la sencilles, ha necesitamo más tiempo del esperado. 
### Semana 3
Compilación de la información recogida, testeo del producto y planteamiento de la exposición. 

