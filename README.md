# Título del Proyecto

flask-docker-example

## Descripción

Proyecto Python usando Flask y Docker

### Instalación

Una vez instalado, para ejecutar el proyecto por primera vez, se debe usar el siguiente comando

```
docker-compose up -d --build
```

## Apagar el contenedor

Para apagar el contenedor y no ejecutar memoria usar el siguiente comando

```
docker-compose down
```

## Iniciar el contenedor cuando ya esta construido la imagen

Para iniciar el contenedor cuando la imagen ya esta construida por build usar el siguiente comando

```
docker-compose up -d
```
