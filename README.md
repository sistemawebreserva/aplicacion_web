# Sistema WEB de reservas para arriendo de cabañas

## Descripción de carpetas 

|Carpeta|Descripción|
|:----:|:---------:|
|src| Código fuente del proyecto|
|informes| Informes del proyecto|
|docker| Archivo Dockerfile que permite correr el proyecto|

## Ejecutar docker

```bash
docker build -t srcdocker -f docker/Dockerfile .
docker run -p 80:8080 srcdocker
```
