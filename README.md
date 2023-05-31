# LINUX
## LINUX-COMANDOS
### Allison Elieth Alfaro Leon
#### Universidad Latinoamericana de Ciencia y Tecnología-ULACIT
##### 2022
| COMANDO | DESCRIPCION | EJEMPLO |
| ------------ | ------------ | ------------ |
| ps | El comando **ps** muestra por pantalla un listado de los procesos que se están ejecutando en el sistema. | _ps_|
| ps -aux | Esto es una lista estática de información, es decir, es una representación instantánea de los procesos que están en ejecución en el momento de invocar el comando. | _ps -aux_ |
| top | El comando **top** te permite ver las tareas del sistema que se ejecutan en tiempo real. Proporciona un buen resumen de tu sistema para verificar rápidamente si algo se destaca que pueda estar causando problemas con tu sitio web o servidor. | _top_ |
| htop | El comando **htop** es un visor de procesos interactivo que te permite gestionar los recursos de tu máquina directamente desde el terminal. | _htop_ |
| pstree | El comando **pstree** muestra los procesos, desde la línea de comandos, en forma de diagrama de árbol. | _pstree_ |
| man | Muestra la página del manual de cualquier otro comando. | _man ps_ |
| kill -9 | El comando **kill** envía una señal TERM o kill a un proceso que lo termina. Puedes matar procesos introduciendo el PID (ID de los procesos) o el nombre binario del programa. | _kill 533494_ _kill firefox_ |
| ip addr | El comando **ip addr** permite ver las direcciones de interfaz, añadir nuevas direcciones o borrarlas. | _ip addr_ |
| sudo | Este comando significa **superuser do**, y te permite actuar como superusuario o usuario root mientras ejecutas un comando específico. | _sudo apt install gimp_ |
| apt | Basado en **Debian** (Ubuntu, Linux Mint). | _sudo apt install transmission_ |
| yum | Basado en **Red Hat** (Fedora, CentOS). | _sudo yum install transmission_ |
| pacman | Basado en **Arch** (Manjaro, Arco Linux). | _sudo pacman -S transmission_ |
| openssh-server | Recordar: Devices-Network-Bridged Adapter, este comando se utiliza para iniciar el programa cliente SSH que permite la conexión segura al servidor SSH en una máquina. | _sudo apt install openssh-server_ |
| && | Al usar *&&*, el segundo comando se ejecutará solo cuando el primero se haya ejecutado con éxito. | _sudo apt update && sudo apt upgrade_ |
| sudo apt update && sudo apt upgrade | El **update** descarga las listas de paquetes de los repositorios y las “actualiza” para obtener información sobre las versiones más recientes de los paquetes y sus dependencias. El **upgrade** instala paquetes que se agregaron como dependencias de paquetes actualizables.  | _udo apt update && sudo apt upgrade_ |
| ls | Te permite listar el contenido del directorio que quieras (el directorio actual por defecto), incluyendo archivos y otros directorios anidados. | _ls_ |
| ls -l | Agregando la opción **-l** al comando ps se mostrarán distintas informaciones acerca de los procesos actualmente en marcha, incluyendo el estado de cada proceso. Para listar el contenido detallado. | _ls -l_ |
| grep | El comando **grep** busca líneas que coincidan con una expresión regular y las imprime. Puede contar el número de veces que se repite el patrón utilizando el flag -c. | _grep "clase3" semana3.txt_, _grep -c "clase3" semana3.txt_ |
| ps -aux / grep "firefox" | Este comando completo tiene un palito recto en vez de inclinado, lo que realiza es buscar en los procesos el "firefox" | _ps -aux / grep "firefox"_ |
| mkdir | El comando **mkdir** es utilizado para crear un nuevo subdirectorio o carpeta del sistema de archivos.  | _mkdir Allison_ |
| neofetch | El comando **neofetch** es una herramienta CLI (command-line interface) que muestra información sobre tu sistema como la versión del kernel, el shell y el hardware junto a un logotipo ASCII de tu distribución de Linux. | _neofetch_ |
| pwd | El comando **pwd (de las siglas en inglés print working directory, cuya traducción sería imprimir directorio de trabajo)** se utiliza para imprimir el nombre del directorio actual en una sesión de comandos bajo un sistema operativo Unix o derivado. | _pwd_ |
| cd, cd .., cd - | El comando **cd** que significa change directory, **cd** permite moverse entre directorios del sistema. **cd ..** para moverte un directorio por encima de tu posición actual puedes usar el comando cd .., o una secuencia de .. para ir subiendo por la estructura de directorios. **cd -** para regresar al directorio anterior.| _cd Allison/_ |
| sudo adduser | El comando **adduser** es la versión modificada del comando useradd y facilita la posibilidad de especificar algunos parámetros, como por ejemplo, del usuario a crear y el directorio de inicio (home) para asociarlo. NO USAR MAYUSCULAS EN EL NOMBRE DEL USUSARIO O SALE ERROR. | _sudo adduser test_ |
| sudo userdel | El comando **userdel** modifica los archivos de cuentas de usuario del sistema, eliminando todas las entradas que hacen referencia al nombre de cuenta que vamos a eliminar. | _sudo userdel test_ |
| sudo passwd | El comando **passwd** te permite cambiar las contraseñas de las cuentas de usuario. En primer lugar, te pide que introduzcas tu contraseña actual y, a continuación, te pide una nueva contraseña y una confirmación. | _sudo passwd_ |
| sudo passwd root | Cambiará la contraseña al usuario root, siempre tiene que ejecutarse con permisos de root o con sudo. | _sudo passwd root_ |
| su | El comadno **su** se utiliza para cambiar de ususario sin necesidad de salir y abrir una nueva terminal. | _su test_ |
| uname | El comando **uname** imprime la información del sistema operativo, lo que resulta útil cuando se conoce la versión actual de Linux. Se añade un **-a** para mayor informacion. | _uname -a_ |
| whoami | El comando **whoami** (abreviatura de "who am i") muestra el nombre de usuario actualmente en uso. | _whoami_ |
| sudo su | Permite tener privilegios de superusuario para ejecutar los comandos sin necesidad de añadir el sudo. | _sudo su_ |
| exit | Es utilixado para salir del usuario en que actualmente se encuentra. | _exit_ |
| nano | El comando **nano** es un editor de texto. | _nano semana3.txt_ |
| cat | El comando **cat** abreviatura de "concatenate", permite crear, visualizar y concatenar archivos directamente desde el terminal. | _cat semana3.txt_ |
| sudo apt install sl | Este comando no tiene uso pero es para ver un tren pasar. | _sudo apt install sl_ |
| sudo apt install cowsay | Este comando agrega una vaquita al final de cada impresion. | _cowsay hola_  |
| telnet towel.blinkenlights.nl | Visiaulizar una saga de StartWars. | _telnet towel.blinkenlights.nl_ |
| history | El comando **history** muestra una lista enumerada con los comandos que has utilizado en el pasado | _history_ |
| history > | Este comando junto con el **>** es para guardar el historial en un archivo. | _history > test.txt_ |
| head -n | El comando **head** muestra las primeras 10 líneas de un archivo de texto, pero puede establecer cualquier número de líneas que desee mostrar con la flag -n. | _head -n 2 semana3.txt_ |
| tail -n | El comando **tail** imprime el contenido de un archivo con una advertencia importante: sólo imprime las últimas líneas. Por defecto, imprime las últimas 10 líneas, pero puedes modificar ese número con -n. | _tail -n 2 semana3.txt_ |
| cp | El comando **cp** hace la funcion de copiar un archivo. | _cp semana3.txt_ |
| mv | El comando **mv** se utiliza para mover archivos y directorios de una ubicación a otra, también es utilizado para renombrar tanto archivos como directorios y la forma de usar este comando es muy parecida al uso del comando linux cp. | _mv semana3.txt semana3comandos.txt > cambiar nombre_, _ mv semana3comandos.txt ./Allison > mover de directorio_ |
| rm | El comando **rm** se utiliza para eliminar archivos y directorios del sistema de archivos. | _rm semana3comandos.txt_ |
| rm / -R | Este comando elimina todos los archivos. NO USAR | _rm / -R_ |
| rm / -Rf | Este copmando elimina todos los archivos hasta los que estan en ejecucion. | _rm / -Rf_ |
| sudo rm / -Rf --no-preserver-root | Este coamdno elimina todo el Sistema Operativo. | _sudo rm / -Rf --no-preserver-root_ |
| dpkg | El comando **dpkg** es una herramienta utilizada para administrar paquetes a través de su instalación, eliminación y compilación. | _sudo dpkg -i neofetch6.0.0.1.dep_ |
| unzip | El comando **unzip** permite extraer el contenido de un archivo .zip desde el terminal.| _unzip imagenes.zip_ |
| alias | Por medio del comando **alias** los comandos que se usan con frecuencia se pueden ejecutar utilizando un término diferente y personalizado.| _alias cd="moverseotrodirectorio"_ |
| unalias | Este comando nos permite eliminar un alias que hayamos establecido, pero de forma temporal. Es decir, que cuando reiniciemos la sesión de la terminal, los alias que habíamos eliminado con unalias volverán a estar disponibles. | _unalias moverseotrodirectorio_ |
| touch | El comando **touch** se usa principalmente para crear archivos vacíos y cambiar marcas de tiempo de archivos o carpetas. | _touch semana3.txtx_ |
| chmod | Sirve para gestionar los permisos de los archivos o directorios del sistema. Cuando usamos este comando debemos tener presentes los tres niveles de gestión de permisos que existen: Lectura: **R**, Escritura: **W** y Ejecución: **X**.| _chmod 755 Allison/_ , chmod 777 foto.jpg|
| shutdown | El comando **shutdown** te permite apagar tu máquina. Sin embargo, también puede utilizarse para detenerla y reiniciarla. | _shutdown now_ _shutdown 22:30_ |
| shutdown -c | Se utiliza para cancelar un shutdown que se ejecuto anteriormente. | _shutdown -c_ |
| / | Directorio root y que se simboliza por una barra inclinada o /. De este directorio, es desde donde nacen todo el resto de directorios, independientemente que estén almacenados físicamente en discos o unidades separadas | / |
| /bin | Es un directorio estático y es donde se almacenan todos los binarios necesarios para garantizar las funciones básicas a nivel de usuario | /bin |
| /boot |Es un directorio estático e incluye todos los ejecutables y archivos que son necesarios en el proceso de arranque del sistema, y que deberán ser utilizados antes que que el kernel empiece a dar las órdenes de ejecución de los diferentes módulos del sistema| /boot |
|/dev | Este directorio incluye todos los dispositivos de almacenamiento, en forma de archivos, conectados al sistema, es decir, cualquier disco duro conectado, partición, memoria USB, o CDROM conectado al sistema y que el sistema pueda entender como un volumen lógico de almacenamiento| /dev |
| /etc | Encargado de almacenar los archivos de configuración tanto a nivel de componentes del sistema operativo en sí, como de los programas y aplicaciones instaladas | /etc |
|/home | Directorio de los usuarios estándar, y por lo tanto, el destinado a almacenar todos los archivos del usuario, como documentos, fotos, vídeos, música, plantillas, etc | /home |
|/lib| Incluye las bibliotecas esenciales que son necesarios para que se puedan ejecutar correctamente todos los binarios que se encuentran en los directorios /bin y /sbin, así como los módulos del propio kernel|/lib|
|/media|Representa el punto de montaje de todos los volúmenes lógicos que se montan temporalmente, ya sean unidades externas USB, otras particiones de disco, etc|/media|
|/mnt|El directorio /mnt tiene la finalidad de albergar los puntos de montaje de los distintos dispositivos de almacenamiento como por ejemplo discos duros externos, particiones de unidades externas, etc|/mnt|
|/opt|Vendría a ser como una extensión del directorio /usr, pero en este caso van todos aquellos archivos de solo lectura que son parte de programas autocontenidos|/opt|
|/proc|Este directorio contiene información de los procesos y aplicaciones que se están ejecutando en un momento determinado en el sistema, pero realmente no guarda nada como tal, ya que lo que almacena son archivos virtuales, por lo que el contenido de este directorio es nulo|/proc|
|/root|Vendría a ser como el directorio /home del usuario root o superusuario del sistema|/root|
|/sbin|El directorio /sbin se trata de un directorio estático y compartible. Su función es similar al directorio /bin, pero a diferencia del directorio /bin, el directorio /sbin almacena archivos binarios/ejecutables que solo puede ejecutar el usuario root o administrador del sistema|/sbin|
|/run| El directorio /var/run contiene información de la sesión que estamos ejecutando. Ejemplos de la información que contienen los archivos de esta carpeta son los demonios que están en ejecución, los usuarios que están logueados, los procesos que están activos, etc|/run|
|/srv|Sirve para almacenar archivos y directorios relativos a servidores que puedas tener instalados dentro de tu sistema, ya sea un servidor web www, un servidor FTP, CVS, etc|/srv|
|/sys|Al igual que /proc, contiene archivos virtuales que proveen información del kernel relativa a eventos del sistema operativo|/sys|
|/tmp|Sirve para almacenar archivos temporales de todo tipo, ya sea de elementos del sistema, o también de diferentes aplicaciones a nivel de usuario como puedan ser Firefox o Chrome/Chromium|/tmp|
|/usr|El directorio /usr viene de «User System Resources» y actualmente sirve para almacenar todos los archivos de solo lectura y relativos a las utilidades de usuario, incluyendo todo el software instalado a través de los gestores de paquetes de cada distribución|/usr|
|/var|Contiene varios archivos con información del sistema, como archivos de logs, emails de los usuarios del sistema, bases de datos, información almacenada en la caché, información relativa a los paquetes de aplicaciones almacenados en /opt, etc|/var|
|docker images| Este comando despliega las imagenes que se tienen en el contenedor | ~ docker images|
|docker pull|Este comando permite descargar nuevas imagenes para el contenedor| ~ docker pull ubuntu o ~ docker pull ubuntu:14.04 |
|docker ps -a|Muestra los contenedores en ejecuccion (UP) o los que estan en estado exit| ~ docker ps -a|
|docker history |Muestra los cambios realizados y las versiones que esta imagen posee|~ docker history nginx|
|docker info|Muestra la informacion que tiene el docker como la version que se esta utilizando| ~ docker info|
|uname -a|Muestra la version de Kernel que el Docker contiene |uname -a|
|apt-get install -t jessie-backports linux-image-amd64|Si el Kernel es un AUFS, se puede subir la versión del Kernel 4.9 para usar Overlay2|~ sudo apt-get install -t jessie-backports linux-image-amd64|
|docker network ls|Permite visuaclizar el tipo de redes que se tiene por ejemplo, Bridge, Host o Null| ~ docker network ls|
|ifconfig docker0|Muestra la IP Privada, recibe por DHCP y se podrá hacer NAT, para poder conectarse a los contenedores|~ sudo ifconfig docker0|
|docker network create --driver bridge|Este comando se utiliza para crear una red y poder separarlas para los diferentes tipos de contenedores que se van a tener |~ docker network create --driver bridge AlliRed|
|ifconfig -s|Muestra la nueva interfaz de red virtual creada|~ sudo ifconfig -s|
|sudo ifconfig|Muestra la informacion concreta de la red virtual | ~ sudo ifconfig 19373gsjnjdhduy |
|docker versión |Muestra la version del docker que se esta utilizando| ~ docker versión |
|apt-get install|Se actualizan los paquetes de APT ya sea para obtener una actualizacion o una nueva imagen|~ sudo apt-get install|
|add-apt-repository|Añadimos un nuevo repositorio de APT| ~ sudo add-apt-repository|
|docker run|Inicia o empieza a correr una imagen|~ docker run debian|
|docker stop|Para una imagen en ejecucion|~ docker stop debian|
|docker build|Build una imagen en el Dockerfile|docker build|
|docker ps|Muestra las imagenes que se estan ejecutando |~ docker ps|
|docker run -ti|Empieza a correr una imagen de forma interactiva|~ docker run -ti ubuntu:14.04|
| docker run -ti --rm|Corre de forma interactiva la imagen pero cuando salimos esta se borra junto con todo lo que esta tenia configurado| ~ docker run -ti --rm debian|
|busybox|Brinda herramientas, es ejecutable multi tarea|busybox|
|docker find ./|Muestra dockerfiles que se han bajo de repositorios oficiales|docker find ./|
|vim Dockerfile|Deentro del Dockerfile se pueden agregar ficheros, imagenes, variables, ext, se utiliza para dar una serie de ordenes|vim Dockerfile|
|RUN |Se agrega en el Dockerfile que crea una nueva capa para creat una orden, o un ejecutable, como por ejemplo un txt que despliegue "hola" y este siempre va a guardarse en el /root|RUN echo "HOLA" > /root/saludos.txt|
|ADD |Se agrega dentro del Dockerfile y permite agregar nuevos ficheros|ADD ficheros/curso.conf /etc/nginx/conf.d/curso.conf |
|ENV |Se agrega dentro del Dockerfile y es para agregar nuevas variables y sus respectivos valores|ENV variable 2 valor2|
|CMD |Se agrega en Dockerfile y es para poner parametros de arranque de la imagen|CMD ["nginx", "-g", "daemon off;"] |
|EXPOSE |Se agrega en Dockerfile y es para definir el puerto que se va a utilizar|EXPOSE 80|
|vim .gitignore|Es utilizado para evitar que ficheros no deseados terminan en un repositorio|vim .gitignore|
|temp?|Evitar todo aquello que inica con temp|temp?|
|*/temp|Evitar todas las carpetas o ficheros que se llaman temp|*/temp|
|*/*/temp|Esto es para ir evitando en capas mas altas |*/*/temp|
|**/temp|Para evitarlas en todas las capas|**/temp|
|compose vim docker-compose.yml|Se definen todos los contenedores y las relaciones entre ellos|compose vim docker-compose.yml|
|docker service create --name |Crear nuevos servicios en el docker|~ docker service create --name web nginx:1.10|
| docker service scalate |Esto permite escalar para rriba o para abajo algun servicio creado dentro del docker| ~ docker service scalate web=1|
| docker service rm |Esto permite eliminar el servicio dentro del docker| ~ docker service rm web |
|unrar zip unzip p7zip gzip bzip2|Esto permite comprimir y descomprimir archivos|sudo pacman -S unrar zip unzip p7zip gzip bzip2|
|yay|Repositorio AUR (Arch User Repository). Este repositorio permite tener acceso a otros paquetes de software que no están disponibles en el repositorio principal|sudo pacman -S yay, sudo yay -S --needed base-devel|
|apache|Apache es un software especializado en ofrecer servicios de servidor web|sudo pacman -S apache|
|neofetch|Permite ver en la terminal la información básica del hardware y del software instalado|sudo pacman -S neofetch|
|uname -a|Muestra la version de Kernel que se esta ejecutando en el sistema operativo|uname -a|
|useradd -m, -G wheel -p|Permite agregar ususarios con sus respectivas contraseñas|sudo useradd -m nombredeusuario -G wheel -p passworddelusuario|
|rmdir|Permite eliminar directorios|rmdir /home/aalfarol109|
|ln|Permite crear un enlace duro a un archivo|ln target_file link_name|
|ln -s |Permite crear un enlace suave a un archivo|ln -s target_file link_name,  ln -s target_directory link_name|
|contrab|Funciona para reemplazar el archivo contrab con uno nuevo|contrab archivo01|
|contrab -e|Edita la entrada del archivo contrab|contrab -e|
|contrab –l|Su función es obtener un listado con todas las tareas del archivo|contrab –l|
|contrab -r|Borra el archivo contrab de forma permanente|contrab -r|
|contrab -c dir|Indica dónde se almacenará el archivo. Para utilizar este comando, se requiere de ciertos permisos de ejecución|contrab -c dir|
|contrab -u usuarios|Funciona para gestionar el contrab de otros usuarios|contrab -u usuarios|
|du -h|Tamaño del archivo que se va a solicitar|du -h foto.jpg|
|stat|Fecha de creacion, ultimo acceso|stat foto.jpg|
|file|Tipo de archivo (carpeta, archivo, acceso directo)|file foto.jpg|
|chown|Propietario y grupo|chown user1 foto.jpg|
|Gparted|Administra las particiones de un sistema operativo|sudo apt install gparted|
|gnome-disk-utility|Muestra informacion sobre el disco|sudp apt install|
|kill -9|Matar un proceso|kill -9 $PID, kill -9 18374826|
