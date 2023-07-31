# Ejecución del Programa

## Requisitos

- Docker para Windows
- Anaconda (Jupyter Notebook)

## Paso 1

Clonar este repositorio con el siguiente comando en la **Terminal**

```bash
git clone https://github.com/JoaZ94/notas_estudiantes
```
## Paso 2

Ingrese a la carpeta del **Proyecto** desde la **Terminal** con el comando **cd**

## Paso 3

Levantar al servicio 'MySQL', para lo cual se ejecuta desde la **Terminal**, ubicada en la carpeta del proyecto el siguiente comando:

```bash
docker-compose up -d
```
## Paso 4

Abrir Jupyter Notebook desde la interfaz de Anaconda

## Paso 5

Descomentar la línea 2 de la celda 1 **pip** para instalar la librería necesaria para ejecutar el proyecto.

## Paso 6

En la celda 7, cambiar la ip, por la ip del equipo host, en Windows se obtiene con **ipconfig**, en sistemas operaivos Unix, con ifconfig.

## Paso 7

Ejecutar todas las celdas.

# Paso 8

Para ver los datos en la base de datos, se puede usar MySQL Workbench y crear una nueva conexión, para lo cual asigne los siguientes datos:

- Hostname: 127.0.0.1
- Port: 3306
- Username: root
- Password: passwordroot
