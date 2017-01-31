React con Docker 

Este proyecto usa React sobre Docker, Usando Docker Containter mediante el cual permite hacer una prueba de React.

http://facebook.github.io/react/docs/tutorial.html

Requerimientos

Docker 
Docker Container
Web Browser


Crear una Imagen

docker build -t bravewood/react .


Correr el Contenedor

bash run_docker.sh

Usar la aplicación

http://localhost:3000/

Problemas encontrados.

1.- Poca Documentación o ejemplos de como integrar React Angular sobre una imagen de Docker.
2.- El Host en algunos casos no se logra crear correctamente
3.-  Las librerías de NPM muchas veces causan error por la version de NPM o NodeJS que se esta ejecutando.
4.- El puerto con el que se crea marca error al conectarse con Docker
