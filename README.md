# Docker-Commands
Docker-Commands
Reference https://www.youtube.com/watch?v=SjlTY4jfQy0

#### En la terminal
Descargar la imagen en la computadora

    docker pull ubuntu:18.04
#### Listar las imagenes

    docker images
#### Crear un contenedor a partir de la imagen

    docker run -i -t ubuntu:18.04
Ingresamos al contenedor.

#### Ahora se puede usar el contenedor
Para salir del contenedor.

    exit

#### Para visualizar todos los contenedores
    
    docker ps -a
    
#### Para ejecutar de nuevo el contendor

    docker start "IDdelContenedor"
    docker attach "IDdelContenedor"
Con esto ingresas al contenedor.    
#### Puedes usar el contenedor como si fuera una nueva maquina.
    
    apt-get install python
    etc... other commands
    
#### Comando para eliminar contenedores

    docker rm "IDdelContenedor"

    
