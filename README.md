# SO2022
Repositorio Sistemas Operativos 2022

Sebastian Montero

Universidad Latinoamericana de Ciencia y Tecnología

ULACIT

2022

Ip addr para saber la ip
![image](https://user-images.githubusercontent.com/106941865/185649082-79ee6ae5-6fdd-4d67-9c15-0b35960db8d2.png)


Ls lista los directorios

Ls /bin    lo que hay en la carpete




Ps -aux | grep "firefox"    para buscar lo que esta en las comillas



Mkdir nombre   para crear carpeta


Sudo adduser nombre   crear usuarios


Sudo passwd user   cambiar contraseña user

Sudo userdel borra el usuario

Su user   es para pasarse del usuario adentro de la terminal



Whoami   muestra el usuario loggeado


Nano para ver ficheros

Nano nombre abre el archivo


Cat nombre    es para ver el contenido 


Head ver las primeras lines de un archivo

Tail el final del archivo


Cp archivo direccion       copiar

Mv archivo direccion       mover



rm archivo borrar

Dpkg -i xxx.deb       eso instala los .deb




Alias apodo="ls -l"      

Reiniciar = sudo reboot


Ps -aux     para ver los procesos del sistema
Top       para ver mas info



Cntrl c    cancela algun comando en ejecucion 



Para instalar     sudo install apt XXXXX


Htop   es como un task manager


Pstree    para ver jerarquias d eprocesoo



Kill -9 XXXXX   para matar el proceso en las x va el id del proceso


Docker
# mostrar la versión de Docker
docker –version


# mostrar la ayuda de Docker
docker --help

# mostrar información de Docker
docker info

# mostrar imágenes de Docker en el host
docker images


docker --help	Muestra la ayuda para la CLI de Docker
docker --version	Muestra la versión de la instalación de Docker
docker info	Muestra información de todo el sistema sobre la instalación de Docker
docker login	Accede a un registro de contenedores o a un backend de la nube
docker logout	Sale del registro de contenedores o del backend de la nube


docker container ls	Muestra los contenedores que se ejecutan en el host

docker container stats	Muestra información sobre el estado de los contenedores en funcionamiento

docker container run <image>	Inicia un nuevo contenedor desde la imagen especificada o ejecuta un comando en un nuevo contenedor
  
docker container commit <container>	Crea una nueva imagen a partir de los cambios de un contenedor en funcionamiento
  
docker container attach <container>	Proporciona un contenedor en ejecución con flujos locales de entrada, salida y error estándar
  
docker container logs <container>	Muestra la información de registro de un contenedor
  
docker container inspect <container>	Muestra información detallada de un contenedor
  
docker container update <container>	Renueva la configuración de un contenedor
  
docker container rename <container> <new-name>	Da un nuevo nombre a un contenedor
  
docker container port <container>	Muestra la asignación de puertos de un contenedor
  
docker container pause <container>	Pone en pausa los procesos que se ejecutan en un contenedor
  
docker container unpause <container>	Reanuda la ejecución de los procesos pausados en un contenedor
  
docker container exec <container> <command>	Ejecuta un comando dentro de un contenedor en funcionamiento
  
docker container stop <container>	Detiene la ejecución de un contenedor
  
docker container start <container>	Reanuda la ejecución de un contenedor detenido
  
docker container restart <container>	Reinicia un contenedor; se comporta como “docker container stop <container>; docker container start <container>”
  
docker container top <container>	Lista de los procesos que se ejecutan dentro de un contenedor
  
docker container kill <container>	Detiene un contenedor en marcha
  
docker container rm <container>	Elimina un contenedor del sistema
  
docker container prune	Elimina todos los contenedores detenidos del sistema
  
docker container cp <container>:<source-path> <dest-path>	Copia archivos y carpetas entre un contenedor y el sistema de archivos local
  
docker container diff <container>	Muestra los cambios en el sistema de archivos de un contenedor
  
docker container export <container>	Exporta el sistema de archivos de un contenedor a un archivo tarball; todas las capas se reducen a una
  
  
  
docker image build	Crea una imagen de Docker a partir de un fichero de Docker
docker image history <image>	Muestra los pasos para crear una imagen de Docker
docker image import <tarball>	Crea una imagen de Docker a partir de un archivo “tarball”
docker image inspect <image>	Muestra información detallada de una imagen de Docker
docker image load	Carga un archivo de imagen creado con “docker image save”
docker image ls	Lista de imágenes disponibles en el host Docker
docker image prune	Elimina las imágenes de Docker no utilizadas del host Docker
docker image pull <image>	Obtiene la imagen de Docker del registro
docker image push <image>	Envía una imagen a un registro
docker image rm <image>	Elimina una imagen del host local
docker image save <image>	Crea un archivo de imágenes con todas las capas de una imagen
docker image tag <source-image> <target-image>	Etiqueta una imagen
