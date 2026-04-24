Este proyecto consiste en una landing page de hoja de vida desarrollada en HTML y desplegada usando Docker con Nginx.


## ⚙️ Construir imagen

```bash
docker build -t cv-isaac .
```

## ▶️ Ejecutar contenedor

```bash
docker run -d -p 8080:80 cv-isaac
```

## 🌐 Acceso

http://localhost:8080

## 🐳 Docker Hub

https://hub.docker.com/r/tuusuario/cv-isaac

### Descargar imagen

```bash
docker pull tuusuario/cv-isaac
```

### Ejecutar desde Docker Hub

```bash
docker run -d -p 8080:80 tuusuario/cv-isaac
```
