# Docker Node.Js MySql

## 1. Instalación

Para descargar la aplicación del repo, se debe escribir el siguiente comando:

```
$ git clone https://github.com/FragmentosTemporales/docker-node-mysql.git
```

### Variables de entorno

Al interior de la carpeta raiz ./ debes crear un documento .env el cual debe contener las siguiente variables:

```
MYSQLDB_HOST=
MYSQLDB_ROOT_PASSWORD=
MYSQLDB_DATABASE=
MYSQLDB_PORT=

MYSQLDB_LOCAL_PORT=
MYSQLDB_DOCKER_PORT=

NODE_LOCAL_PORT=
NODE_DOCKER_PORT=
```

### Instalación de Docker Compose

Para instalar la aplicación debes ejecutar el siguiente código:

```
$ docker compose build
```

## 2. Ejecución

Para ejecutar la aplicación debes ingresar el siguiente comando:

```
$ docker compose up
```

## 3. Bibliografía

A continuación te dejo la documentación de MySql en Docker
```
https://hub.docker.com/_/mysql/
```