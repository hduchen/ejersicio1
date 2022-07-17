# Pasos para Ejerscio 1

* Bajar imagen nginx

    docker pull nginx

* Se creo una web statica y agrego un  dockerfile en la raiz del proyecto

* levantamos el contenedor del sitio

    docker run --name ej-01 -v /Balanz/Capacitaciones/Docker/Ej1/divididos:/usr/share/nginx/html:ro -d -p 127.0.0.2:80:89  nginx
