Mini proyecto para aprender Docker

Despues de crear la Dockerfile 


$ sudo docker build -t hello-world .

$ sudo docker run -p 80:80 hello-world

Le decimos que escuche el puerto 80 tanto en el localhost como en el contendor 

$ sudo docker run -p 80:80 /home/jose/proyectos/DOCKER/src/:/var/www/html hello-world

Por ultimo este cambio es para ver cambios en vivo en el contenedor 

