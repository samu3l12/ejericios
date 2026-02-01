# Guía de Inicio para el Entorno Jupyter con Docker

Este proyecto porporciona un entorno preconfigurado de Jupyter Lab con soporte para **Pandas** y **Polars**.

## Requisitos Previos

Antes de comenzar, asegúrate de tener instalado en tu sistema:

*   **Docker Desktop**: Puedes descargarlo desde [https://www.docker.com/products/docker-desktop/](https://www.docker.com/products/docker-desktop/)

## Instrucciones Paso a Paso

Sigue estos pasos para arrancar el entorno:

### 1. Iniciar Docker
Abre la aplicación **Docker Desktop** y espera a que el icono de la ballena en la barra de tareas indique que está corriendo (Docker Engine running).

### 2. Arrancar el Proyecto
Abre una terminal (PowerShell o CMD) en la carpeta donde has descargado estos archivos y ejecuta el siguiente comando:

```bash
docker compose up -d --build
```

> **Nota**: La primera vez que ejecutes este comando puede tardar unos minutos en descargar las imágenes y construir el entorno.

### 3. Acceder a Jupyter Lab
Una vez que el comando anterior haya terminado, abre tu navegador web favorito e ingresa a la siguiente dirección:

[http://localhost:8888](http://localhost:8888)

### 4. Trabajar con los Notebooks
Dentro de Jupyter Lab, verás la carpeta `notebook` (o `work`) en el panel izquierdo. Ahí encontrarás la carpeta `01_Pandas_Polar` con los ejercicios.

## Detener el Entorno

Cuando termines de trabajar, puedes apagar los contenedores desde la terminal con el comando:

```bash
docker compose down
```

---
¡Listo! Ya tienes tu entorno de Big Data preparado.
