<img src="../imagenes/MI-LICENCIA88x31.png" style="float: left; margin-right: 10px;" />

# Instalación de docker en CentOs
## Añadimos repositorios
`dnf config-manager --add-repo=https://download.docker.com/linux/centos/docker-ce.repo`

## Instalamos los paquetes de docker
`dnf install docker-ce --nobest -y`

## Iniciamos y activamos el servicio de docker
`systemctl start docker`
`systemctl enable docker`
![servicio](../imagenes/1.png)

## Vemos la versión
`docker --version`
![version](../imagenes/2.png)
