Pasos:
------

- Crear el Dockerfile, basado en la imagen oficial de NGINX
- Crear un fichero index.html con un texto simple de prueba
- Copiar el fichero index.html a la ruta que utiliza NGINX para servir las páginas estáticas.
- Crear el fichero docker-compose.yml donde se define el volumen que utilizara el contenedor y el dockerfile con que se
  va a crear. Además, se define el puerto que se va a mapear con el host.
- Levantar el contenedor utilizando docker-compose