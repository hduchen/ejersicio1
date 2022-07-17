# Pasos para Ejerscio 1

* Bajar imagen nginx

    docker pull nginx

* Se creo una web statica y agrego un  dockerfile en la raiz del proyecto

* Compilamos la imagen

    docker build -t ejersicio1 .

* validamos la imagen

    docker image ls

* Exponemos el puerto y visualizmos en localhost

    docker run --name nginx2 -d -p 8080:80  ejersicio1
