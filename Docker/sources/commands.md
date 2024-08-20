// Crea la imagen de acuerdo al Dockerfile
docker build -t <nombre_imagen> .

// Lista las imagenes creadas
docker images

// Remueve la imagen
docker rmi <name_image>
 
// Ejecuta un contenedor para la imagen y crea un puerto para vidualizarlo   
docker run -p 3000:80 <nombre_imagen>

// Muestra de forma interactiva el contenedor por medio de una consola Bash
docker exec -it <nombre_contenedor> bash

// Lista los contenedores
docker ps

// Construye la red completa 
docker-compose up

// Elimina la red completa
docker-compose down