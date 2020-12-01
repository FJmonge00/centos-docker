<img src="../imagenes/MI-LICENCIA88x31.png" style="float: left; margin-right: 10px;" />

# Instalación de docker-compose en Centos

## Instamos paquete curl
`dnf install curl -y`

## Realizamos el curl

`curl -L https://github.com/docker/compose/releases/download/1.25.0/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose`

![servicio](../imagenes/compose1.png)

## Damos permisos de ejecución

`chmod +x /usr/local/bin/docker-compose`

![servicio](../imagenes/compose2.png)

# Comprobamos que esta instalado viendo la versión

`docker-compose --version`

![servicio](../imagenes/compose3.png)
________________________________________
*[Volver al indice...](../README.md)*