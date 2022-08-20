# CLASIFICACIÓN DE CÉLULAS SANGUÍNEAS

- Luis Mateo Hincapié Martínez, CC 1038417207, Ingeniería de sistemas

## Conjunto de datos

El conjunto de datos se almacena en un repositorio de Mendeley:

- Nombre del repositorio: “A dataset for microscopic peripheral blood cell images for
development of automatic recognition systems”
- Número de identificación de datos: 10.17632/snkd93bnjr.1
- URL directa a los datos: https://data.mendeley.com/datasets/snkd93bnjr/draft?a=d9582c71-9af0-4e59-9062-df30df05a121 

El conjunto de datos se pueden hacer disponibles ejecutando desde cualquier notebook en Colab los siguientes comandos

Descargamos el dataset
```
!curl -O https://md-datasets-cache-zipfiles-prod.s3.eu-west-1.amazonaws.com/snkd93bnjr-1.zip
```
Descomprimimos el dataset
```
!unzip -q snkd93bnjr-1.zip
!unzip -q PBC_dataset_normal_DIB.zip
!rm -f snkd93bnjr-1.zip PBC_dataset_normal_DIB.zip
!ls
```
Ahora tenemos una carpeta `PBC_dataset_normal_DIB` que contiene ocho subcarpetas. Cada subcarpeta contiene archivos de imagen para cada categoría.

Para acceder a la carpeta
```
!ls PBC_dataset_normal_DIB 
```

## Videos
- [Video primera entrega](https://udeaeduco-my.sharepoint.com/:v:/g/personal/lmateo_hincapie_udea_edu_co/EXO3QCSL5oxApsKI5s9qJsMBFdDKkSLa7ZV9_YEjL4AAaQ?e=adFIWr)  