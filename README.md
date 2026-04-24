##Descripcion del Proyecto

Este proyecto consiste en una landing page sobre hoja de vida personal desarrollada en HTML y desplegada usando Docker con Nginx.

## Estructuras de Carpetas 
Actividad_1/ 
│── index.html 
│── images/ 
│── Dockerfile 
│── .dockerignore 
│── README.md

## Instrucciones:

## Construir imagen
docker build -t landingp .

## Ejecutar contenedor
docker run -d -p 8080:80 landingp


##  Acceso al sitio web
http://localhost:8080

##  URL de la Imagen Docker Hub
https://hub.docker.com/r/skrisaac/landingp

### Descargar imagen
docker pull skrisaac/landingp

### Ejecutar desde Docker Hub
docker run -d -p 8080:80 skrisaac/landingp

