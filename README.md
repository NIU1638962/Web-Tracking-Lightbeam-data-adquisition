
# *Web Tracking*
19 Dec 2024 10:30 CET

Joel Tapia Salvador

Jaume Puigpiqué Sánchez

# ¿Qué es el *Web Tracking*?

Hoy en día, con la red digital, las páginas webs y terceras partes (normalmente anunciantes o agentes malintencionados) se concentran en guardar información de los usuarios que visitan sus páginas y lo que hacen en ellas para ganar información en quién es el usuario o ambientes más personales de este.

Estos mecanismos son utilizados, ya que en la web no sé conoce quién un individuo es. Por su naturaleza, en la web, los individuos no pueden llegar a ser separados e identificados como uno podría hacer, por ejemplo en una tienda en la vida real, puesto que puede haber múltiple gente utilizando la misma IP pública, VPNs o incluso la misma persona utilizando diferentes dispositivos para visitar un sitio, etc.

# ¿Para qué se usa el *Web Tracking*?

Uno podría preguntarse, pero para qué es necesario saber esto o por qué las páginas web estarían interesadas en esto, y como siempre, puede haber razones de interés legítimo y otras que no tanto. 

## Usabilidad de la página

A veces, especialmente en páginas que su objetivo es permitir al usuario hacer una tarea, es necesario ver si el usuario puede completar la tarea que ha venido a hacer. 

Por ejemplo, si un usuario ha entrado a descargar una serie de archivos, si ha sido capaz de descargarlos todos completamente, o hay algo que mejorar de como la página ofrece el servicio o de la robustez y funcionamiento propio del sistema.

## Elecciones del usuario

En páginas que, por ejemplo, que guardan información temporalmente de un usuario o elecciones de este y es necesario saber qué había hecho o elegido el usuario anteriormente y quién es cada usuario.

Por ejemplo, el carrito de la compra, los mecanismos de *Web Tracking* permiten a la página saber qué usuario está revisitando la página y cuál era el estado de su carrito en visitas anteriores. O enseñar la página al usuario tal y como este ha decidido previamente verla, color, tamaños o etc. que el usuario puede llegar a personalizar en la página.

## Identidad del usuario

Hay páginas que ofrecen información o servicios que requieren la verificación del usuario, saber que quien intenta acceder a estos es quien dice ser. Normalmente, esto se hace utilizando una contraseña o algo similar, pero hacer esto constantemente, incluso en cada página interna del servicio puede llegar a ser mucho para el usuario, por eso se utilizan estos mecanismos para conservar, al menos temporalmente, esta verificación del usuario para que no tenga que repetirla tantas veces.

## Fuerzas de seguridad

Las fuerzas de seguridad a veces hacen que las páginas web guarden y compartan según que información sobre los usuarios que les puede ayudar a resolver crímenes que han sucedido y, a veces, espiar en la probación.

## Anunciantes

Los anunciantes recogen y guardan información sobre las visitas y acciones de los usuarios para así poder hacer publicidad especialmente diseñada para el usuario con el fin de aumentar la influencia sobre el usuario (normalmente con fines monetarios, pero también hay políticos y más).

## Recomendaciones

Algunas páginas webs recogen información sobre las visitas e interacciones de un usuario para ofrecer contenido dirigido a las preferencias del usuario, normalmente para aumentar el tiempo que el usuario pasa dentro de la página.

## Alteración de precios

También hay sitios que utilizan la información obtenida del usuario, como su nivel económico, o las veces que ha visitado, y por lo tanto interés del usuario, para que individualmente alterar el precio de un servicio o producto, para hacer al usuario pagar más por estos.

## Crímenes

Actores maliciosos utilizan la información recogida y vendida por páginas para robar la identidad de usuarios o hacer acoso a individuos u otras intenciones maliciosas, como también identificar posibles víctimas fáciles de crímenes.

# Mecanismos actuales de *Web Tracking*

Los mecanismos actuales de seguimiento web (web tracking) son diversos y avanzados. A continuación, se describen algunos de los métodos más comunes:

***Cookies***: Son archivos temporales que un sitio web almacena en tu navegador con el fin de recordar tus interacciones en el sitio. Hay diferentes tipos:

* ***Cookies*** **de sesión**: Temporales y se eliminan al cerrar el navegador.  
* ***Cookies*** **persistentes**: Permanecen en el dispositivo hasta que caducan o se eliminan manualmente.  
* ***Cookies*** **de terceros**: Colocadas por dominios distintos al sitio web que el usuario está visitando, comúnmente utilizadas para publicidad y seguimiento en múltiples sitios.

***Fingerprinting***: Técnicas utilizadas para identificar y caracterizar sistemas y dispositivos de forma única y distintiva. Cada elemento tiene una huella digital única basada en sus características específicas. El *fingerprinting* puede incluir diversas técnicas, como:

* **Escaneo de puertos**: Identificar puertos abiertos en un sistema.  
* **Análisis de servicios**: Determinar qué servicios y versiones están corriendo en esos puertos.  
* **Detección de sistemas operativos**: Identificar el sistema operativo y su versión.

![Fingerprinting schema](/fingerprinting.png)

***Supercookies***: Funcionalmente similares a las cookies convencionales, pero mucho más complicadas de eliminar. Pueden almacenarse fuera del navegador, como en el almacenamiento del dispositivo o en la caché.

**Píxel de seguimiento**: Es una imagen que tiene el tamaño de un píxel (1×1), de ahí su nombre, que se inserta en el código fuente de una web, email, o publicidad *online* para medir una acción-reacción en concreto, monitorear el comportamiento de un usuario y acceder a métricas como conversiones y tráfico web, entre otras. Estos permiten recopilar datos como:

* Tipo de navegador, versión y sistema operativo.  
* Dispositivo usado (móvil, ordenador…).  
* Información acerca del [*customer journey*](https://www.unir.net/revista/marketing-comunicacion/customer-journey-map/) (cómo es la navegación en un sitio web, qué buscan y dónde hacen clic).  
* Dirección IP y ubicación.  

![Esquema píxel de seguimiento](/pixel_de_seguimiento.png)

***Local Storage***: Permite a los sitios web almacenar datos en el navegador del usuario. Forma parte de la especificación HTML5 y proporciona una manera para que las aplicaciones web almacenen datos dentro del navegador del usuario. A diferencia de las cookies, los datos almacenados no se envían de vuelta al servidor con cada solicitud HTTP, lo que lo hace más eficiente para almacenar grandes volúmenes de datos que no necesitan ser transmitidos constantemente al servidor.

***Device tracking***: Es una técnica que utiliza identificadores únicos de un dispositivo para monitorizar la actividad del usuario. De esta forma, es capaz de recopilar información como, por ejemplo, el sistema operativo o el tipo de navegador que utiliza el dispositivo.

# ¿Cómo puede mitigarse o evitar el *Web Tracking*?

Para mitigar estos mecanismos de seguimiento, se pueden tomar varias medidas:

1. **Hacer uso de las funciones de navegación privada.**

   Esta función está disponible en la mayoría de los navegadores web. Los beneficios de utilizarla son que no se guarda el historial de navegación, no se almacenan cookies, datos de sitios web ni información introducida en formularios. Es como si fueras invisible, sin dejar rastro.

2. **Utilizar una Red Privada Virtual (VPN).**

   Al conectarnos a una VPN, nuestras huellas digitales se vuelven invisibles. Esto se debe a que nuestro tráfico pasa a través de un túnel encriptado en cuyo interior nadie puede ver. De esta forma, la VPN oculta tu dirección IP, creando una capa de invisibilidad digital. También nos permite disfrutar de una amplia gama de contenido sin preocuparnos por ser rastreados. Es muy recomendable su uso cuando utilizas una red pública wifi, ya que encripta tus datos y los protege de posibles hackers**.**

3. **Navegar utilizando un navegador enfocado en la privacidad.**

   Hay motores de búsqueda que están enfocados en proteger tu privacidad. Estos navegadores no almacenan tus datos ni rastrean tu comportamiento en línea, ni tampoco venden tus datos a los anunciantes, como lo hacen otros motores de búsqueda muy populares como Google. DuckDuckGo y StartPage son dos de los motores de búsqueda más populares que cumplen los requisitos para ser considerados navegadores enfocados en la privacidad.

4. **Navegar de forma anónima con TOR**

   Otra forma de luchar contra el web tracking es la navegación anónima con TOR.

   Aunque no es un método infalible, TOR ofrece un nivel alto de privacidad, ya que, el objetivo de TOR es que ningún nodo individual sea capaz de conocer tanto el origen como el destino final de los datos. Por lo tanto, es una herramienta diseñada para proteger nuestra identidad en línea.

   En algunos casos sí que es vulnerable, por ejemplo, puesto que las páginas web aún pueden usar técnicas como el fingerprinting para identificar al usuario.

# Demostraciones

Utilizaremos la herramienta *Thunderbeam/Lightbeam* en cada uno de los navegadores (Microsoft Edge, Google Chrome, Firefox, Opera, OperaGX y Brave) para analizar la cantidad de web tracking realizado por las mismas páginas en cada uno y *cookies syncing*. Los círculos blancos indican las *cookies* de la página web, los triángulos blancos las *cookies* de terceros, las líneas blancas que *cookies* utilizan que otras *cookies* y las líneas rojas las *cookies* sincronizadas.

Para hacer la comparación justa, empezamos con una instalación de zero de cada uno de los navegadores en un usuario nuevo de Windows, sin tocar ninguna configuración, sin iniciar cuenta en ninguno de los navegadores (cuenta Microsoft, cuenta Google, cuenta Mozilla, cuenta Opera, etc.) y sin ninguna extensión instalada nada más que *Thunderbeam/Lightbeam*.

Nuestro objetivo es ver si aquellos navegadores que promocionan más privacidad y protección nativa al *Web Tracking*, de verdad funciona y también cómo se compara al uso de extensiones (uBlock Origin, uBlock Origin Lite and Privacy Badger).

Las páginas a las que navegaremos serán las siguientes (todas aquellas sin enlace, son búsquedas hechas en el motor de búsqueda por defecto del navegador):

* new fridge  
* [https://uab.cat](https://www.uab.cat)   
* sale games  
* [https://youtube.com/feed/trending](https://youtube.com/feed/trending)   
* [https://thesun.co.uk/news/32334704/car-flies-through-air-smashes-house](https://www.thesun.co.uk/news/32334704/car-flies-through-air-smashes-house)   
* last news  
* [https://docs.python.org/3/library/exceptions.html](https://docs.python.org/3/library/exceptions.html)   
* [https://numpydoc.readthedocs.io/en/latest/format.html](https://numpydoc.readthedocs.io/en/latest/format.html)   
* [https://stackoverflow.com/questions/15301999/default-arguments-with-args-and-kwargs](https://stackoverflow.com/questions/15301999/default-arguments-with-args-and-kwargs)   
* [https://facebook.com](https://www.facebook.com/)    
* [https://reddit.com/r/popular](https://www.reddit.com/r/popular)   
* [https://en.wikipedia.org/wiki/Web\_tracking](https://en.wikipedia.org/wiki/Web_tracking)   
* [https://amazon.com/s?k=christmas+tree](https://www.amazon.com/s?k=christmas+tree)   
* [https://chatgpt.com](https://chatgpt.com)   
* [https://theguardian.com/us-news/2024/dec/16/wisconsin-school-shooting-madison](https://theguardian.com/us-news/2024/dec/16/wisconsin-school-shooting-madison)   
* [https://m.economictimes.com/magazines/panache/what-is-carbon-monoxide-poisoning-and-its-symptoms-12-indians-suspected-to-have-died-from-it-at-georgia-resort/articleshow/116375662.cms](https://m.economictimes.com/magazines/panache/what-is-carbon-monoxide-poisoning-and-its-symptoms-12-indians-suspected-to-have-died-from-it-at-georgia-resort/articleshow/116375662.cms)   
* [https://dailymail.co.uk/sport/football/article-14196831/Robert-Lewandowski-barcelona-leganes.html](https://dailymail.co.uk/sport/football/article-14196831/Robert-Lewandowski-barcelona-leganes.html)   
* [https://minecraft.fandom.com/wiki/Minecraft](https://minecraft.fandom.com/wiki/Minecraft) 

## Microsoft Edge

| Default Privacy Configuration | Highest Privacy Configuration and uBlock Origin |
| :---: | :---: |
| ![Microsoft Edge Default Privacy Configuration Cookie Graph](/Thunderbeam/Microsoft%20Edge/Default/Thunderbeam%20Microsoft%20Edge%20Default.png) | ![Microsoft Edge Highest Privacy Configuration and uBlock Origin Cookie Graph](/Thunderbeam/Microsoft%20Edge/Highest/Thunderbeam%20Microsoft%20Edge%20Highest.png) |
| 695 third party cookies | 69 third party cookies |

## Google Chrome

| Default Privacy Configuration | Highest Privacy Configuration and uBlock Origin Lite |
| :---: | :---: |
| ![Google Chrome Default Privacy Configuration Cookie Graph](/Thunderbeam/Google%20Chrome/Default/Thunderbeam%20Google%20Chrome%20Default.png) | ![Google Chrome Highest Privacy Configuration and uBlock Origin Cookie Graph](/Thunderbeam/Google%20Chrome/Highest/Thunderbeam%20Google%20Chrome%20Highest.png) |
| 577 third party cookies | 61 third party cookies |

## Firefox

| Default Privacy Configuration | Highest Privacy Configuration, uBlock Origin and Privacy Badger |
| :---: | :---: |
| ![Firefox Default Privacy Configuration Cookie Graph](/Thunderbeam/Firefox/Default/lightbeam%20Firefox%20Default.png) | ![Firefox Highest Privacy Configuration and uBlock Origin Cookie Graph](/Thunderbeam/Firefox/Highest/lightbeam%20Firefox%20Highest.png) |
| 422 third party cookies | 50 third party cookies |

## Opera

| Default Privacy Configuration | Highest Privacy Configuration and uBlock Origin |
| :---: | :---: |
| ![Opera Default Privacy Configuration Cookie Graph](/Thunderbeam/Opera/Default/Thunderbeam%20Opera%20Default.png) | ![Opera Highest Privacy Configuration and uBlock Origin Cookie Graph](/Thunderbeam/Opera/Highest/Thunderbeam%20Opera%20Highest.png) |
| 358 third party cookies | 73 third party cookies |

## OperaGX

| Default Privacy Configuration | Highest Privacy Configuration and uBlock Origin |
| :---: | :---: |
| ![OperaGX Default Privacy Configuration Cookie Graph](/Thunderbeam/OperaGX/Default/Thunderbeam%20OperaGX%20Default.png) | ![OperaGX Highest Privacy Configuration and uBlock Origin Cookie Graph](/Thunderbeam/OperaGX/Highest/Thunderbeam%20OperaGX%20Highest.png) |
| 124 third party cookies | 73 third party cookies |

## Brave

| Default Privacy Configuration | Highest Privacy Configuration and uBlock Origin |
| :---: | :---: |
| ![Brave Default Privacy Configuration Cookie Graph](/Thunderbeam/Brave/Default/Thunderbeam%20Brave%20Default.png) | ![Brave Highest Privacy Configuration and uBlock Origin Cookie Graph](/Thunderbeam/Brave/Highest/Thunderbeam%20Brave%20Highest.png) |
| 81 third party cookies | 62 third party cookies |

## Conclusiones

Podemos observar que los navegadores que son anunciados como más privados tienen ligera mejor protección contra cookies de terceros, marginalmente, excepto Brave y OperaGX que ofrecen similares servicios que Opera. Pero, estos dos, sus instalaciones por defecto, vienes con muchas opciones de privacidad ya activadas, al contrario que Opera o Firefox, donde se tiene que activar o instalar respectivamente, cosa que el usuario medio puedo no saber hacer o percatarse.

Podemos ver que los navegadores que ofrecen opciones de privacidad, si estas están activadas, tienen una efectividad similar a utilizar las extensiones como uBlock Origin, aunque es mejor instalarlas, ya que añaden un extra. Podemos ver que de momento, a pesar del cambio al Manifiest V3 por parte de Google Chrome, muchos otros navegadores ofrecen otros servicios para instalar extensiones que no cumplen con él, garantizando la protección de privacidad que estos ofrecen. Aunque a pesar de que uBlock Origin Lite ofrezca menos opciones de protección que uBlock Origin, en esta prueba no se ha quedado muy atrás parando cookies de terceros.

# Webgrafia

1. Contentsquare, "Website Tracking: A Guide to Understanding How Websites Track You," \[Online\]. Available: [https://contentsquare.com/guides/website-tracking/](https://contentsquare.com/guides/website-tracking/).  
2. K. H. A. Mehdizadeh, "How VPNs Can Prevent Apps from Tracking You," CyberGuy, \[Online\]. Available: [https://cyberguy.com/security/vpn-prevent-apps-tracking/](https://cyberguy.com/security/vpn-prevent-apps-tracking/).  
3. Adfixus, "13 Effective Strategies to Minimize Online Data Tracking," \[Online\]. Available: [https://www.adfixus.com/post/13-effective-strategies-to-minimize-online-data-tracking](https://www.adfixus.com/post/13-effective-strategies-to-minimize-online-data-tracking).  
4. Thunderbeam-Lightbeam for Chromium: [https://chromewebstore.google.com/detail/thunderbeam-lightbeam-for/hjkajeglckopdkbggdiajobpilgccgnj?hl=en-GB](https://chromewebstore.google.com/detail/thunderbeam-lightbeam-for/hjkajeglckopdkbggdiajobpilgccgnj?hl=en-GB)  
5. Lightbeam for Firefox: [https://addons.mozilla.org/en-US/firefox/addon/lightbeam-chikl/](https://addons.mozilla.org/en-US/firefox/addon/lightbeam-chikl/)   
6. uBlock Origin and uBlock Origin Lite webpage: [https://ublockorigin.com/](https://ublockorigin.com/)   
7. Privacy Badger for Firefox: [https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/](https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/)   
8. Microsoft Edge: [https://www.microsoft.com/en-us/edge/download](https://www.microsoft.com/en-us/edge/download)   
9. Google Chrome: [https://www.google.com/intl/en\_pk/chrome/](https://www.google.com/intl/en_pk/chrome/)   
10. Firefox: [https://www.mozilla.org/en-US/firefox/new/](https://www.mozilla.org/en-US/firefox/new/)   
11. Opera: [https://www.opera.com/download](https://www.opera.com/download)  
12. OperaGX: [https://www.opera.com/gx](https://www.opera.com/gx)   
13. Brave: [https://brave.com/download/](https://brave.com/download/)   
14. Thunderbeam-Lightbeam execution results: [https://github.com/NIU1638962/Web-Tracking-Lightbeam-data-adquisition](https://github.com/NIU1638962/Web-Tracking-Lightbeam-data-adquisition) 