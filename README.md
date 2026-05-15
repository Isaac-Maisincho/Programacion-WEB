# Landing Page Profesional - Isaac Maisincho

## Descripción del Proyecto

Este proyecto consiste en una Landing Page Profesional desarrollada con HTML5 y CSS, orientada a presentar mi perfil académico y profesional como estudiante de Ingeniería de Software.

La página fue diseñada aplicando:

- HTML5 semántico
- CSS moderno
- Responsive Design
- Dark/Light Mode 
- Flexbox y CSS Grid
- Diseño visual moderno

---

# Tecnologías Utilizadas

## Frontend

- HTML5
- CSS3

## Despliegue

- Docker
- Nginx

---
## Instrucciones

### Construir Imagen
 ```bash
docker build -t landingp .
```

## Ejecutar contenedor
```
docker run -d -p 8080:80 landingp
```

##  Acceso al sitio web
```
http://localhost:8080
```
##  URL de la Imagen Docker Hub
```
https://hub.docker.com/r/skrisaac/landingp
```
### Descargar imagen
```
docker pull skrisaac/landingp
```

### Ejecutar desde Docker Hub
```
docker run -d -p 8080:80 skrisaac/landingp
```


```plaintext
PROGRAMACION-WEB/
│
├── landingPage/
│   ├── index.html
│   ├── style.css
│   └── images/
│
├── Dockerfile
├── .dockerignore
└── README.md

