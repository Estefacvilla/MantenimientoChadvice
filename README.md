# Paso a paso

## Instalar docker desktop
Verificar que esta instalado docker con "docker --version", si no lo está descargarlo del siguiente enlace: https://www.docker.com/products/docker-desktop/ 

## Archivo .env
En la raíz del proyecto crear el archivo .env y agregarle la siguiente información:
```js
    NAME_DB=postgres
    USER_DB=postgres
    PASSWORD_DB='Solicitar al Admin'
    HOST_DB='Solicitar al Admin'
    DIALECT_DB=postgres
```

##  Run docker
### Abrir el Docker.
### Escribir el siguiente comando en el terminal.
```bash
docker-compose up --build
```

## Leer el QR
Al ejecutarse el proyecto se genera un QR que debe ser leido con la funcionalidad *Linked devices* de Whatsapp

<img src="https://github.com/Estefacvilla/MantenimientoChadvice/assets/67327495/e1679f6e-df7c-42e7-9b2c-8a5125fae99d" height="400">

##  Interactuar con el aplicativo por medio de *Mi chat* en Whatsapp Web
Para acceder al aplicativo se usa el chat que Whatsapp habilita para escribirle a nuestro propio número, basta con saludar para que funcione.

<img src="https://github.com/Estefacvilla/MantenimientoChadvice/assets/67327495/876bd0ff-cba8-4615-99ef-4bd1747d36f4" height="200">
