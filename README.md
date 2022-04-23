# comandos-linux
Repositorio de comandos de Linux

COMANDOS SEM #3

* Comando man: Se mostrarán las instrucciones manuales del comando tail.
* Comando tail: El comando tail mostrará las últimas diez líneas de un archivo de texto. Por ejemplo, tail -n nombredearchivo.ext.
* Comando mv: El uso principal del comando mv es mover archivos
* Comando head: Mostrará las primeras diez líneas, pero puedes cambiar este número a tu gusto. Por ejemplo, si solo deseas mostrar las primeras cinco líneas, escribe   head -n 5 nombredearchivo.ext.
* Comando Less: Less es una utilidad de línea de comandos que se utiliza para ver el contenido de un archivo o la salida de un comando, una página a la vez
* Comando CP: La función principal de CP es sencilla: copiar uno o más archivos a una ubicación especificada por el usuario.
* Comando PS AX: El comando ps ax muestra una lista de los procesos que se encuentran actualmente en el sistema, incluyendo los procesos que pertenecen a otros usuarios.
* Comando sudo: El comando (sudo su) permite a los usuarios ejecutar programas con los privilegios de seguridad de otro usuario (normalmente el usuario root) de manera segura, convirtiéndose así temporalmente en súper usuario.
* Comando rm: El comando rm («eliminar») se usa para eliminar archivos. -r ,-R ,–recursive: Eliminar directorios y sus contenidos recursivamente.
* Comando history: "History" es un comando muy útil para averiguar los últimos comandos que se han ejecutado en un Servidor. 
* Comando mkdir: Es un comando para crear directorios.
* Comando Dir: Muestra o cambia de directorio, es similar al comando dir de MS-DOS.
* Comando cp: El comando cp en Linux crea una copia.
* Comando ps -aux: El comando ps (estado del proceso) se utiliza para proporcionar información sobre los procesos que se están ejecutando actualmente, incluidos sus números de identificación de proceso (PID), USUARIO, TTY,% CPU,% MEM y comando.
* Comando Grep: Grep es una herramienta de línea de comandos que los usuarios de Linux utilizan para buscar cadenas de texto.
* Comando whoami: El comando whoami es un comando del tipo Unix, proviene de la concatenación de las palabras en inglés ¿Who am I? que significa, ¿Quién soy?. Es un comando simple, utilizado para imprimir el nombre de usuario efectivo del usuario actual cuando se invoca, que se entiende como el nombre de el usuario en sesión.
* Comando useradd: Añade nuevo usuario al sistema linux, con el nombre de usuario especificado. Cuando se añade un nuevo usuario una entrada correspondiente se crea en los archivos /etc/passwd, /etc/group y /etc/shadow.
* Comando TOP: El comando top es muy útil ya que te puede ayudar a averiguar el estado de tu servidor, proporcionándote información sobre la carga actual, el número de días que lleva encendido sin reiniciarse, el número de usuarios conectados por SSH, y en definitiva, información sobre tu servidor en tiempo real.
* Comando passwd: Es una utilidad del sistema que se utiliza para establecer o cambiar la contraseña de una cuenta de usuario. Este comando usa una función de hashing para cifrar la nueva contraseña, y guardar solo la versión cifrada.
* Comando alias: Indica a la terminal de Linux que reemplace una cadena por otra al ejecutar comandos. Básicamente los alias se utilizan para personalizar la interfaz de la terminal de la sesión. Al usar un alias, los comandos que se usan con frecuencia se pueden invocar utilizando un término diferente y preferido.
* Comando ls: Listar solamente ficheros ordenados por fecha de modificación
* Comando IP ADDR: Comando que puedes usar para obtener una dirección IP de un sistema y otras estadísticas de interfaz:
* telnet towel.blinkenlights.nl: Muestra una animacion sobre la pelicula de star wars 
* Instalar/Desinstalar archivos .deb: Los archivos de paquetes asociados con kubuntu tienen todos el sufijo .deb debido a la estrecha relación de Kubuntu con la distribucíon de GNU/Linux llamada Debian. Usted podrá descargar e instalar archivos de paquetes .deb. Para ello, necesitará permisos de administrador (véase “Usuario "root" y sudo”).
* Snap: Snap (ágil) es un sistema de implementación de software y administración de paquetes para Ubuntu y otras distribuciones de Linux. Fue introducido por Canonical desde la versión Ubuntu 16.04 LTS.
El software Snap son paquetes independientes con todas las bibliotecas dependientes incluidas, lo que hace que la instalación sea mucho más sencilla. Como los paquetes están en contenedores, las aplicaciones se aíslan y los cambios no afectarán a otros sistemas
* SUDO APT UPDATE: Apt-get update sirve para actualizar los repositorios que definimos en el archivo /etc/apt/sources.list. Se actualizan los listados de paquetes disponibles en las fuentes definidas en el archivo sources.list, pero no instala nada.
* sudo apt install snapd: Instalar snapd en Archlinux
* snap find: consultará la tienda y enumerará los resultados con su número de versión, nombres de desarrollador y descripción.
* sudo snap install: Para hacer una instalación, el proceso es sencillo, sólo se ha de escribir «nombre paquete» y se procederá a la instalación de dicho programa.

COMANDOS SEM #6:

Comandos para montar una Unidad RAM Disk:
*sudo mkdir /mnt/ram_disk
*sudo mount -t tmpfs -o size=1024m new_ram_disk /mnt/ram_disk
Instalar Volatility:
*apt-get install volatility

COMANDOS SEM #7:
* df -h : Mostrar el espacio en disco usado
* mount: Montaje de dispositivos en el sistema de archivos
  ○ /etc/fstab mount /dev/cdrom /mnt
* Gparted: Administra las particiones
  ○ sudo apt install gparted
* gnome-disk-utility: Muestra información sobre el disco
* kill -9 $PID: Matar un proceso
* ps -aux: Mostrar los procesos
* pwd: Mostrar el directorio actual

COMANDOS SEM #10
* docker build: construye una imagen desde un archivo de docker
* docker images: muestra todas las imagenes disponibles en el host de Docker
* docker run +(version): Pone a correr la imagen que le solicitemos
* docker ps: muestra el estado de todas las instancias
* docker stop: para detener instancias en estado running
* docker rm +(nombre): Remover instancias
* docker rmi: remueve imagen
* docker pull+(version): descargar imagen

COMANDOS SEM 11:
* curl:  Curl están diseñados para funcionar como una forma de verificar la conectividad a las URL y como una gran herramienta para transferir datos.
* git clone: clonar repositorios de Github
* wget: bajar archivos de un URL
Auxiliares para manipulacion de archivos:
* head: mostrar al principio de un archivo (de texto)
* tail: leer los comandos finales de un archivo
* less: mostrar el texto en la pantalla del terminal
* more: muestra texto una pantalla a la vez
Auxiliares de busqueda:
* find: búsqueda de archivos y directorios
* locate: busca archivos en Linux mediante el nombre de archivo
* updatedb: actualiza la base de datos slocate
Networking:
* nmap: herramienta de escaneo de red y un escáner de puertos.
* nslookup: se utiliza principalmente para obtener un nombre de host utilizando una dirección IP o viceversa.
* ip addr: obtener direccion ip
* netstat: imprime información sobre conexiones de red, tablas de enrutamiento, estadísticas de interfaz, conexiones enmascaradas y asociaciones de multidifusión.
Utilitarios:
* history: Ver o listar historial de comandos en Linux
* shutdown now: El comando Shutdown puede reiniciar, detener o apagar.
* reboot: restart the operating system
* tar unrar: extrae archivos comprimidos con formatos de compresión TAR, TAR.gz, TAR.BZ2
* dd: instrucción que usamos en Linux para realizar copias de seguridad de particiones o discos
* ffmpeg: software que consiste en un conjunto de bibliotecas y programas para el manejo de video, audio y otros archivos.
* fdupes: analizar directorios en busca de archivos duplicados, con opciones para enumerar, eliminar o reemplazar los archivos con hardlinks que apunten al duplicado.


