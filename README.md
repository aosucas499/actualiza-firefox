### Gracias a [homero10](https://github.com/homero10/actualiza-firefox-guadalinex)

# Descripción
Actualiza Firefox, tiene dos scripts, uno para equipos con derechos de administrador "actualiza-firefox" y otro sin root "actualiza-firefox-noroot. 

1. El uso en sistemas  con privilegios de adminstrador está pensado para viejas distribuciones cuyos repositorios no dejen acceder a versiones actuales, de manera que el script "actualiza-firefox", no borrará la versión del sistema sino convivirá con la versión anterior. 

2. El uso en sistemas sin privigelios root, está pensado para distribuciones Guadalinex que vienen con el usuario root borrado o con el usuario sin derechos de administrador (sudo). 

Versión que descarga: Firefox v.83

# Instrucciones

Hay que seguir los siguientes pasos:

1- Nos bajamos el contenido de este repositorio. Para ello nos situaremos sobre Clone or download (botón verde) y acto seguido haremos clic en Download ZIP. Se nos descargarán los archivos necesarios.

2- Abrimos una terminal.

3- Una vez tengamos abierta la terminal, nos situaremos sobre el directorio Descargas. Escribiremos cd Descargas/

4- Ya estamos en la carpeta correspondiente. Ahora hay que descomprimir el archivador descargado en el paso 1. Al tratarse de un .zip escribirimos la orden apropiada, que será unzip seguido del nombre de nuestro archividador, por tanto teclearemos unzip actualiza-firefox-master.zip

5- ¡Bien! Ya tenemos el archivador descomprimido en una carpeta. Ahora nos tocará acceder a dicho directorio.

6- Para acceder a la carpeta que contiene nuestros archivos descomprimidos teclearemos de nuevo cd actualiza-firefox-master/

7- Es el momento de hacer correr al script, no sin antes darle permisos de ejecución. Esto es relativamente sencillo: 

+ chmod +x actualiza_firefox_noroot.sh (equipos sin root)

+ chmod +x actualiza_firefox.sh (equipos con root o sudo)

8- ¡Ahora sí! Llegó el momento final. Para ejecutar nuestro script simplemente habrá que insertar en la terminal la siguiente orden: 

+ ./actualiza_firefox_noroot.sh (equipos sin root)

+ ./actualiza_firefox.sh (equipos con root o sudo)

9- Antes de hacer nada, el script nos preguntará si queremos realizar el proceso de descarga del nuevo Firefox. Responderemos con el 1 y posteriormente pulsaremos la tecla Intro.

El archivo hará todo el trabajo sin necesidad de que el usuario tenga que intervenir de alguna manera. Cuando haya acabado nos mostrará un OK rojo en pantalla.

Para diferenciar esta versión con la instalada en el sistema (la anterior versión no se borrará y por tanto ambas convivirán perfectamente) se nos creará un acceso directo tanto en el escritorio como en el menú Aplicaciones > Internet. A simple vista se diferencia de la versión incluida en el sistema por el color del logotipo de Firefox que en nuestro caso se trata de un color azul (a diferencia del naranja que viene por defecto con el Firefox de serie).
