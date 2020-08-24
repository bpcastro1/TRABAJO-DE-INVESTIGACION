<H2>INFORME</H2>
<p align="center"><img src="img/logo.png"/></p>
<H3>1. PLANTEAMIENTO DEL PROBLEMA</H3>
<p align="justify">El micro-ordenador Google Coral, entra al mercado ofreciendo ciertos atributos nuevos, los cuales potenciaran la inteligencia artificial para lo cual esta designado este dispositivo. Además, servirá no solo para la creación de nuevas cosas, también puede alimentar el cerebro de inteligencia artificial de dispositivos ya realizados. Coral no solo tiene capacidad para ejecutar redes neuronales en el propio RPI (Raspberry PI) tal cual le permitirá incorporar de manera rápida, eficaz todo aquello sobre inteligencia artificial, evitando el peligro de hacer publico los datos, es decir dándole confidencialidad a todos los datos que lo contiene.</p>

<p align="justify">TPU o Unidad de Procesamiento Tensorial, viene a ser un acelerador de Inteligencia Artificial el cual fue desarrollado por Google, con objetivo en el aprendizaje automático. Además, se usó en el procesamiento de texto de Street View viniendo a proporcionar resultados de búsqueda, en conclusión, TPU viene a acelerar ciertos procesos, unificarlos, procesarlos de mejor manera, siendo uno de los circuitos integrados más importantes.</p>

<p align="justify">Google Colab, entra como una de las tantas herramientas que posee Google, la cual permite ejecutar y programas en Python, mediante el navegador. Es útil ya que no requiere que se configure, ofrece acceso a GPUs de manera gratuita y se puede compartir los contenidos entre cuentas GOOGLE de manera simultánea. Colab también puede ser considerado como un notebook Jupyter pero de manera gratuita, además se debe tomar en cuenta que se almacena en la nube, mediante nuestras cuentas personales y su almacenamiento disponible. También permite el uso de varias bibliotecas de aprendizaje automático.</p>

<H3>2. OBJETIVOS</H3>
<b>Objetivos Generales</b>
<p align="justify">- Realizar un video explicando e identificando los temas relevantes a manera de un tutorial sobre el tema asignado.</p>
<p align="justify">- Conocer los beneficios de usar Google Coral y TPU, mediante Google Colab.</p>
<b>Objetivos Específicos</b>
<p align="justify">- Emplear las herramientas que nos brinda Google Coral y Colab.</p>
<p align="justify">- Analizar la plataforma Google Colab para el uso de TPU.</p>
<p align="justify">- Implementar un ejemplo que verifique la diferencia de rendimiento de una CPU y una TPU.</p>
<p align="justify">- Analizar las características de hardware y software de la tarjeta de desarrollo Google Coral.</p>
<H3>3. ESTADO DEL ARTE</H3>
<b>Notas sobre el uso de Google Colaboratory en la educación de Inteligencia Artificial</b><br>
<p align="justify">Un desafío en el diseño de cursos de inteligencia artificial moderna es elegir herramientas y marcos apropiados para ejemplos en clase y tareas. No sólo es importante que las herramientas sean capaces de cubrir la profundidad del material presentado en el curso, sino lo suficientemente simple como para que los instructores lo implementen en el aula y que los estudiantes mantengan el enfoque en el plan de estudios.<br><br> 
Los cuadernos de Jupyter es decir, documentos interactivos entrelazados con texto y código, son una herramienta cada vez más popular para que los investigadores lleven a cabo y comuniquen los resultados de la investigación, pero lo suficientemente simples como para desarrollar ejemplos en el aula y tareas.<br><br>
Sin embargo, estos portátiles todavía requieren hardware sofisticado para ejecutar muchos de los enfoques populares en la IA hoy en día. Ofrecido como un servicio gratuito de Google, Colaboratory proporciona una interfaz Jupyter Notebook con acceso al hardware de Google. Los blocs de notas se ejecutan en máquinas virtuales basadas en Linux proporcionadas y mantenidas por Google, donde el cálculo se puede realizar con unidades de procesamiento central como lo es el CPU o acelerarse a través de unidades de procesamiento gráfico especializadas como la GPU y unidades de procesamiento de tensores como la TPU.<br><br></p>
<p align="justify">- Fuente: Notes on Using Google Colaboratory in AI Education | Proceedings of the 2020 ACM Conference on Innovation and Technology in Computer Science Education. (n.d.). Recuperado en Julio 23, 2020, de https://dl.acm.org/doi/abs/10.1145/3341525.3393997</p>

<b>Consultas relacionales con una unidad de procesamiento de tensor</b>
<p align="justify">Los procesadores de uso general han alcanzado una meta con respecto a la densidad de integración y las velocidades de reloj. Al mismo tiempo, las innovaciones en los sistemas han eliminado las ineficiencias en gran medida.<br><br>
Un enfoque común es el reusar el hardware que está disponible en grandes cantidades a bajo costo, más prominentemente las Unidades de Procesamiento de Gráficos en este caso la GPU. La desventaja aquí es que el diseño de esos dispositivos fue desarrollado para un caso de uso muy diferente, juegos de ordenador 3D, y sólo benefician en parte el caso de uso de procesamiento de datos.<br><br>
La eficiencia en esas tareas se logra con memoria de gran ancho de banda y paralelismo masivo de computación.<br><br></p>
<p align="justify">- Fuente: Relational Queries with a Tensor Processing Unit | Proceedings of the 15th International Workshop on Data Management on New Hardware. (n.d.). Recuperado en Julio 23, 2020, de https://dl.acm.org/doi/abs/10.1145/3329785.3329932</p>

<b>Mejorar la eficiencia energética y la resiliencia de errores de una unidad de procesamiento de tensor de umbral cercano</b>
<p align="justify">Los avances en inteligencia artificial han entrado en un nuevo reino debido al desarrollo de arquitecturas específicas de dominio dedicadas al procesamiento de redes neuronales.<br><br> 
Tensor Processing Unit (TPU), un circuito integrado específico de aplicaciones personalizadas creado por Google, es uno de estos aceleradores.<br><br>
El rápido aumento de las cargas de trabajo exige un aumento de la velocidad de procesamiento y el volumen de implementación. Sin embargo, tiene un costo de un uso intensivo de energía, afectando así la eficiencia energética del sistema.<br><br> 
Los aceleradores como las TPU están diseñados para ofrecer un rendimiento muy alto para cargas de trabajo de inferencia de DNN. Aunque las condiciones de funcionamiento de NTC pueden garantizar un bajo consumo de energía, el rendimiento se reduce en gran medida debido a los transistores más lentos y los retrasos computacionales más largos. <br></p>
<p align="justify">- Fuente: Enhancing Energy Efficiency and Error Resilience of a Near-Threshold Tensor Processing Unit - IEEE Conference Publication. (n.d.). Recuperado en Julio 28, 2020, de https://ieeexplore.ieee.org/abstract/document/9045479</p>

<H3>4. MARCO TEORICO</H3>
<p align="justify">Google Coral, se desarrolló únicamente con el objetivo de realizar tareas de machine learning las cuales se integran en tareas de producción de manera eficaz y rápida. Hace uso de la red neuronal TensorFlow Lite y del modulo Edge TPU. Que es de tipo SOM (System on Module) donde van a estar ensamblados el procesador, la GPU, la RAM, el chip del WiFi y la Flash.</p>

<p align="justify">Coral trabaja para satisfacer las necesidades del cliente, por lo cual idearon dos productos a la venta los cuales son aceleradores y plazas de desarrollo para la creación de prototipos de nuevas ideas, y módulos para alimentar el cerebro de inteligencia artificial de los dispositivos de producción, tales como cámaras inteligentes y sensores.</p>

<p align="justify">Coral es capaz de ejecutar redes neurales en el propio RPI, de forma que “le es posible incorporar de manera rápida y eficaz, sin que sus proyectos representen un peligro para la confidencialidad de datos”.</p>

<p align="justify">Dentro de las especificaciones técnicas, son:</p>
<p align="justify">- CPU: NXP i.MXM 8M SOC (Cortex-A53 quad core)</p>
<p align="justify">- GPU: integrada, GC7000 Lite Graphics</p>
<p align="justify">- Coprocesador: Google Edge TPU</p>
<p align="justify">- RAM: 1 GB LPDDR4</p>
<p align="justify">- Almacenamiento: Flash eMMC de 8 GB</p>
<p align="justify">- Conectividad: WiFi 2×2 MIMO de doble banda y Bluetooth 4.1</p>
<p align="justify">- Dimensiones: 48 x 40 x 5 mm</p>

<p align="justify">Las especificaciones de la placa base son:</p>
<p align="justify">- Almacenamiento: microSD</p>
<p align="justify">- USB: Un USB C para funcionalidad OTG, un USB C para la alimentación, un USB de tip0o micro USB para consola y un puerto USB A</p>
<p align="justify">- LAN: puerto Gigabit Ethernet</p>
<p align="justify">- Audio: un conector mini jack de 3,5 mm y un terminal de 4 pines para altavoces estéreo</p>
<p align="justify">- Vídeo: Un conector HDMI 2.0a de tamaño completo y un conector de 24 pines para una cámara MIPI-CSI2</p>
<p align="justify">- GPIO: un conector de 40 pines</p>
<p align="justify">- Alimentación: 5 V Corriente continua</p>
<p align="justify">- Dimensiones: 88 x 60 x 24 mm</p>

<p align="justify">El módulo Edge TPU se ha diseñado para proporcionar un gran rendimiento en aplicaciones destinadas al aprendizaje automático, su tamaño compacto y reducido consumo de potencia lo hacen perfecto para ser integrado en sistemas dedicados al IoT, que realizan funciones de reconocimiento de imagen y de texto.</p>

<p align="justify">La incorporación de este chip a la Google Coral hace que se reduzca de manera exponencial el tiempo que requiere la red neuronal para procesar los datos que le son suministrados.</p>

<p align="justify">TensorFlow, se trata de una librería realizada en código abierto, la cual se ha desarrollado con un ecosistema de herramientas y una comunidad detrás de ella, cuyo único objetivo es potenciar el desarrollo de aplicaciones de Inteligencia Artificial y aprendizaje automático. Pero la novedad que presenta Google Coral, es que este pequeño micro PC es capaz de utilizarlo en tiempo real.</p>

<p align="justify">Google Colab, es una herramienta de Google, la cual trata de ser un entorno de maquinas virtuales basado en Jupyter Notebooks. Se pueden ejecutar en la nube, donde podremos escoger si correr en una CPU, GPU o en una TPU, todo esto de manera gratuita. No obstante, hay ciertas restricciones, como por ejemplo que una sesión dura 12 horas, pasado el tiempo se realiza una limpieza y se perderán ciertas variables, archivos que se deberán tener allí.</p>

<p align="justify">Sirve como medio para simular o experimentar con machine learning y Deep learning, pero sin tener que ir por costos de procesamiento de la nube, además el ambiente de trabajo ya tiene librerías instaladas las cuales están listas para utilizar, una de ellas antes mencionada es TensorFlow.</p>

<H3>5. DIAGRAMAS</H3>
<p align="center"><img src="img/diagrama1.png"/></p>
<p align="center"><img src="img/diagrama2.png"/></p>

<H3>6. LISTA DE COMPONENTES</H3>
<p align="justify"><b>Google Coral</b></p>
<p align="justify">- Edge TPU System-on-Module (SoM)<br>
- SoC NXP i.MX 8M (brazo de cuatro núcleos Cortex-A53, más Cortex-M4F)<br>
- Coprocesador acelerador Google Edge TPU ML<br>
- Coprocesador criptográfico<br>
- Wi-Fi 2x2 MIMO (802.11b / g / n / ac 2.4 / 5 GHz)<br>
- Bluetooth 4.2<br>
- EMMC de 8 GB<br>
- 1 GB LPDDR4<br>
- Conexiones USB<br>
- Puerto de alimentación USB tipo C (5 V CC)<br>
- Puerto USB 3.0 Tipo-C OTG<br>
- Puerto host USB 3.0 tipo A<br>
- Puerto de consola serie USB 2.0 Micro-B<br>
- Conexiones de audio<br>
- Conector de audio de 3,5 mm (compatible con CTIA)<br>
- Micrófono digital PDM (x2)<br>
- Terminal de 4 pines de 2,54 mm para altavoces estéreo<br>
- Conexiones de video<br>
- HDMI 2.0a (tamaño completo)<br>
- Conector FFC de 39 pines para pantalla MIPI DSI (4 carriles)<br>
- Conector FFC de 24 pines para cámara MIPI CSI-2 (4 carriles)<br>
- Ranura para tarjeta microSD<br>
- Puerto Gigabit Ethernet<br>
- Cabecera de expansión GPIO de 40 pines<br>
- Admite Mendel Linux (derivado de Debian)<br></p>
<p align="center"><img src="img/googlecoral.png"/></p>
<p align="justify"><b>Google Colab</b></p>
<p align="justify">- IPython Notebook<br>
- Celdas<br>
- Kernel<br>
- Librerías<br>
- VM de Google Compute Engine (la infraestructura de máquinas virtuales de Google en la nube)<br>
- 12 GB de RAM<br>
- 50 GB de almancenamiento en disco disponibles para el uso<br>
- Tiempo-Maximo 12 horas<br>
- Python 2<br>
- Python 3<br>
- GPU<br>
- CPU<br>
- TPU<br></p>
<p align="center"><img src="img/googlecolab.png"/></p>

<H3>7. MAPA DE VARIABLES</H3>
<p align="center"><img src="img/variable1.png"/></p>
<p align="center"><img src="img/variable2.png"/></p>

<H3>8. EXPLICACION DEL CODIGO FUENTE</H3>
<p align="justify">Se hara un analisis en la rapidez que se genera en Google Colaba partir de la ejecución por medio de CPU y TPU.</p>
<p align="center"><b>CPU</b></p>
<p align="justify"><b>1. Lectura de Datos</b></p>
<p align="justify">Se hará una lectura de dos archivos que estarán dentro de una ruta, ubicada en Google Drive en la cuenta personal de quien lo compile al código.</p>
<p align="center"><img src="img/c1.png"/></p>
<p align="justify"><b>2. Acceso a datos en Google Drive (Importación y permisos)</b></p>
<p align="justify">Se realizará una importación por medio de la ruta a Google Drive y la Unidad personal de nuestra cuenta. Generará un link el cual nos dará un código de autorización, el cual lo ingresaremos y deberá salirnos “Mounted at (ruta)” en caso de no tener ningún error.</p>
<p align="center"><img src="img/c2.png"/></p>
<p align="justify"><b>3. Reshape de datos para garantizar matrices (No vectores)</b></p>
<p align="justify">Se pondrá los valores en múltiplos de 128 para que sirva en la TPU, pero en este caso deberemos ubicar de igual manera los valores en la CPU, para no generar un favoritismo al momento de realizar la compilación y la comparación entre cada uno de los hardware.</p>
<p align="center"><img src="img/c3.png"/></p>
<p align="justify"><b>4.	Creación del modelo con Tensor Flow 2 + Librería Keras</b></p>
<p align="justify">Se genera 3 capas, en 3 fases diferentes las cuales llevaran ciertos valores. En este caso será Normalización, Conv2D, MaxPooling2D, Dropout. El cual Conv2D llevara diferentes valores en cada una de las fases. Para al final aplanar mediante Flatten el numero de filtros de Dense, al igual que en la salida Dropout.</p>
<p align="center"><img src="img/c4.png"/></p>
<p align="justify"><b>5.	Test de velocidad e impresión</b></p>
<p align="justify">Mediante la función de Python “timeit” se realizará que se guarde en la variable el tiempo que se demoro para poder ejecutar mediante la CPU nuestro código y para finalizar un print de lo que es el tiempo de demora en segundos.</p>
<p align="center"><img src="img/c5.png"/></p>

<p align="center"><b>TPU</b></p>
<p align="justify"><b>1. Lectura de Datos</b></p>
<p align="justify">Se hará una lectura de dos archivos que estarán dentro de una ruta, ubicada en Google Drive en la cuenta personal de quien lo compile al código.</p>
<p align="center"><img src="img/c1.png"/></p>
<p align="justify"><b>2. Acceso a datos en Google Drive (Importación y permisos)</b></p>
<p align="justify">Se realizará una importación por medio de la ruta a Google Drive y la Unidad personal de nuestra cuenta. Generará un link el cual nos dará un código de autorización, el cual lo ingresaremos y deberá salirnos “Mounted at (ruta)” en caso de no tener ningún error.</p>
<p align="center"><img src="img/c2.png"/></p>
<p align="justify"><b>3. Reshape de datos para garantizar matrices (No vectores)</b></p>
<p align="justify">Se pondrá los valores en múltiplos de 128 para que sirva en la TPU, debemos recordar que usamos los mismos valores para la configuracion de la CPU, por lo que vamos a realizar una comparacion de velocidades al ejecutar cada una de ellas. Recordar que esta puesto en 28x28 pixeles de escalas de grises.</p>
<p align="center"><img src="img/c3.png"/></p>
<p align="justify"><b>4.	Configuracion TPU</b></p>
<p align="justify">Se aplica la versión de TensorFlow 2 para poder resolver la compilación de nuestro código y además se agregaran las 3 capas en 3 etapas de la librería Keras con diferentes valores en la capa Conv2D.</p>
<p align="center"><img src="img/t1.png"/></p>
<p align="center"><img src="img/t2.png"/></p>
<p align="justify"><b>5.	Test de velocidad e impresión</b></p>
<p align="justify">Mediante la función de Python “timeit” se realizará que se guarde en la variable el tiempo que se demoro para poder ejecutar mediante la TPU nuestro código y para finalizar un print de lo que es el tiempo de demora en segundos. Esto se realizara a nivel de un float de 32 bytes.</p>
<p align="center"><img src="img/t3.png"/></p>

<H3>9. DESCRIPCION DE PRERREQUISITOS Y CONFIGURACION</H3>
<p align="justify">Se necesita una cuenta de Google colab donde nosotros podremos guardar nuestros códigos y permitir que nuestros compañeros puedan acceder y modificar nuestros diferentes códigos, la cual puede ser una cuenta institucional o una cuenta personal donde solo debemos llenar nuestra información y posteriormente elegir nuestro tipo de código que queremos realizar (Python 2 o Python3) nuestro tipo de procesador que queramos (CPU, GPU o TPU) y listo ya podemos usar Google colab al 100%</p>

<H3>10. APORTACIONES</H3>
<b>SOM</b>
<p align="justify">Coral System-on-Module (SoM) es un sistema completamente integrado que lo ayuda a construir dispositivos integrados que exigen inferencias de aprendizaje automático (ML) rápidas. Contiene el sistema en chip (SoC) iMX 8M de NXP, memoria eMMC, LPDDR4 RAM, Wi-Fi y Bluetooth, pero su potencia única proviene del coprocesador Edge TPU de Google para la inferencia de aprendizaje automático de alta velocidad. (Google Coral, 2019)</p>
<b>Edge TPU</b>
<p align="justify">Edge TPU permite desplegar inferencias de aprendizaje automático de alta calidad en el perímetro por medio de diversos productos de producción y prototipado de Coral.</p>
<p align="justify">La plataforma de aprendizaje automático en el perímetro de Coral refuerza las TPU de Google Cloud y Cloud IoT para proporcionar una infraestructura completa (de hardware y software, y de la nube al perímetro) que facilita el despliegue de las soluciones basadas en IA de los clientes. La plataforma de Coral no solo incluye el entorno de programación de código abierto TensorFlow Lite, sino que también proporciona un kit de herramientas para desarrolladores que te permite compilar tus propios modelos o volver a preparar varios modelos de IA de Google para Edge TPU. De esta manera, se aúnan nuestros conocimientos avanzados tanto en IA como en hardware. (Merino, 2019)</p>
<p align="justify">Edge TPU complementa las CPU, GPU y FPGA, además de otras soluciones ASIC, a fin de ejecutar la IA en el perímetro.</p>

<b>Python</b>
<p align="justify">Python es un lenguaje de programación interpretado cuya filosofía hace hincapié en la legibilidad de su código. Se trata de un lenguaje de programación multiparadigma, ya que soporta orientación a objetos, programación imperativa y, en menor medida, programación funcional. Es un lenguaje interpretado, dinámico y multiplataforma.Es administrado por la Python Software Foundation. Posee una licencia de código abierto, denominada Python Software Foundation License, que es compatible con la Licencia pública general de GNU a partir de la versión 2.1.1, e incompatible en ciertas versiones anteriores(Knowlton, Jim (2009)).</p>

<b>Edge Computing</b>
<p align="justify">El edge computing es un tipo de informática que ocurre en la ubicación física del usuario, de la fuente de datos, o cerca de ellas. Al establecer servicios de computación cerca de esas ubicaciones, los usuarios obtienen servicios más rápidos y confiables, y las empresas aprovechan la flexibilidad del cloud computing híbrido. Con el edge computing, una empresa puede usar y distribuir un conjunto común de recursos en una gran cantidad de ubicaciones. (Merino, 2019)</p>

<H3>11. CONCLUSIONES</H3>
<p align="justify">Realizada la investigación sobre los puertos de entrada y salida en la Raspberry Pi  y además la simulación en brainbox, se llegó a las siguientes conclusiones::<br>
-	Mediante la investigación y la implementación del ejemplo funcional en la plataforma de barín box se logró determinar varios de las herramientas que la plataforma presenta para la simulación de circuito y otros temas.<br>
-	Los simuladores de entrada y salida de datos para la  Raspberry Pi tienen con base el uso de los puertos GPIO mediante los cuales pueden mandar y recibir impulsos eléctricos los cuales nos ayudan a generar  programas de manera funcional.<br>
-	Se implementó de manera exitosa un  ejemplo funcional sobre la entrada y salida de datos en los puertos GPIO además de conocer de manera más formal el simulador brainbox.<br>
-	Durante el desarrollo de la implementación del ejemplo en brainbox se nos mostró varias de las herramientas presentadas mediante las cuales la plataforma nos permite realizar varias funciones como las simulación de circuitos integrados y otras como la simulación de elementos más avanzados como la webcam entre otros.<br>
Después de haber logrado los objetivos específicos se llegó a la conclusión que gracias a estos objetivos específicos se lograra llegar a la implementación y la realización de los objetivos generales:<br>
- Los puertos GPIO presentes en la Raspberry Pi tienen diferentes características entre las cueles encontramos el no tener protección a las cargas eléctricas recibidas además de estar enumerados por su posición físicas o también pueden estar enumerados por la posicion de un chip..</p>
- Se logró manejar de manera satisfactoria el uso de nuevas plataformas de simulación en este caso en específico la plataforma virtual Brainbox.</p>

<H3>12. RECOMENDACIONES</H3>
<p align="justify">-	Durante esta situación de cuarentena y para evitar el consumo innecesario de dinero es considerado de buena manera el uso de simuladores de circuitos además de permitir la corrección de errores los cuales de manera física se tendrían problemas para ubicarlos.<br><br>
-	Conocer las diferentes formas en las cuales se puede hacer el ingreso y la salida de datos atreves de los puertos GPIO y mostrar la salida de la información mediante controladores o diferentes tipos de hardware adicional.<br><br>

<H3>13. CRONOGRAMA</H3>
<p align="center"><img src="img/cronograma.png"/></p>

<H3>14. BIBLIOGRAFIA</H3>
<p align="justify">- JORGE CACHO HERNÁNDEZ, «Raspberry Pi: tutoriales Servidor web, ownCloud y XBMC.,» 27 Enero 2008. [En línea]. Available: file:///C:/Users/home/Downloads/102190284-Raspberry-Pi-tutoriales-servidor-web-ownCloud-y-XBMC.pdf<br><br>
- C. Muñoz, «Historia de la informatica “Raspberry Pi,» Blog sobre Historia de la Informática, 18 Diciembre 2013. [En línea]. Available: https://histinf.blogs.upv.es/2013/12/18/raspberry-pi/#:~:text=Raspberry%20PI%20es%20una%20placa,de%20la%20inform%C3%A1tica%20en%20las<br><br>
 - C. Muñoz, «Historia de la informatica “Raspberry Pi,» Blog sobre Historia de la Informática, 18 Diciembre 2013. [En línea]. Available: https://histinf.blogs.upv.es/2013/12/18/raspberry-pi/#:~:text=Raspberry%20PI%20es%20una%20placa,de%20la%20inform%C3%A1tica%20en%20las<br><br>
- Maria Sol Vicet Illas, «Historia y defincion de software libre en el mundo e lainformatica inicial,» Ecured.cu, Ecuador, 2017 Available: https://www.ecured.cu/Software_libre#:~:text=Seg%C3% BAn%20la%20Free%20Software%20Foundation,programa%2C%20con%20cualquier%20prop%C3%B3sito%3B%20de<br><br>
- Moya, F., 2020. Entradas Y Salidas Digitales · Taller De Raspberry Pi. [online] Franciscomoya.gitbooks.io. Available at: <https://franciscomoya.gitbooks.io/taller-de-raspberry-pi/content/es/elems/gpio.html> [Accessed 22 August 2020].<br><br>
- Diec.unizar.es. 2020. [online] Available at: <http://diec.unizar.es/~tpollan/libro/Apuntes/digap8.pdf> [Accessed 22 August 2020].<br><br>

<H3>15. ANEXOS</H3>
<H3>15.1 MANUAL DE USUARIO</H3>
<p align="justify">Adjunto en la carpeta Manual de Usuario.</p>
<H3>15.2 HOJAS TECNICAS</H3>
<p align="justify">Adjunto en la carpeta Hojas Técnicas.</p>
