# guia de docker 

## Introducción

Docker es una plataforma de código abierto que permite a los desarrolladores empaquetar, enviar y ejecutar aplicaciones en contenedores. Los contenedores son entornos aislados y ligeros que se pueden ejecutar en cualquier sistema operativo que tenga instalado Docker.


## Instalación
usa docker -facil  para ionstarlo en linux

github.com/alfcl/docker-facil

## Comandos básicos

### Correr un contenedor
```bash
docker run -d -p 80:80 nginx
```

### Listar contenedores
```bash
docker ps
```

### Detener un contenedor
```bash

docker stop <container_id>
```

### Eliminar un contenedor
```bash
docker rm <container_id>
```

### Ver logs de un contenedor
```bash
docker logs <container_id>
```

### Ver información de un contenedor
```bash
docker inspect <container_id>
```

### Ver información de un contenedor
```bash
docker inspect <container_id>
```

### Ver información de un contenedor
```bash

docker inspect <container_id>
```


## Dockerfile

Un Dockerfile es un archivo de texto que contiene una serie de instrucciones necesarias para crear una imagen de Docker. Aquí tienes un ejemplo de un Dockerfile para crear una imagen de Nginx:

```Dockerfile
# Use an official Nginx image
FROM nginx

# Copy a custom configuration file from the current directory
COPY nginx.conf /etc/nginx/nginx.conf

# Expose port 80
EXPOSE 80

# Define the default command to run when the container starts
CMD ["nginx", "-g", "daemon off;"]
```

Para construir una imagen de Docker a partir de un Dockerfile, puedes usar el comando `docker build`. Por ejemplo:

```bash
docker build -t my-nginx .
```

## Docker Compose

Docker Compose es una herramienta que te permite definir y ejecutar aplicaciones Docker multi-contenedor. Puedes usar un archivo YAML para configurar tus servicios, volúmenes y redes. Aquí tienes un ejemplo de un archivo `docker-compose.yml` para ejecutar un contenedor de Nginx y otro de MySQL:

```yaml
version: '3'

services:
  web:
    image: nginx
    ports:
      - "80:80"
  db:
    image: mysql
    environment:
      MYSQL_ROOT_PASSWORD: example
```

Para ejecutar tus servicios con Docker Compose, puedes usar el comando `docker-compose up`. Por ejemplo:

```bash
docker-compose up
```

## Conclusiones

Docker es una herramienta poderosa que te permite empaquetar, enviar y ejecutar aplicaciones en contenedores. Con Docker, puedes crear entornos aislados y ligeros que se pueden ejecutar en cualquier sistema operativo. Además, Docker Compose te permite definir y ejecutar aplicaciones Docker multi-contenedor de forma sencilla. ¡Espero que esta guía te haya sido útil para empezar a trabajar con Docker!

