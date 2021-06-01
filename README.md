# Workshop: Data Warehouses and ELTs

_El proposito del proyecto es desarrollar un proceso de extracción y manipulación de datos con el software Pandas_

## Comenzando 🚀

_Git Clone

_

Mira **Deployment** para conocer como desplegar el proyecto.


### Pre-requisitos 📋

* Anaconda
* Postgres
* Cuenta en Google Cloud

```
https://www.postgresql.org/download/
https://www.anaconda.com/products/individual
https://console.cloud.google.com/
```

### Instalación 🔧

_Para la intalación de Anaconda ver la siguiente pagina_


```
https://docs.anaconda.com/anaconda/install/windows/
```




* [Postgres](https://www.postgresql.org/download/) - Base de datos
* [Anaconda](https://www.anaconda.com/products/individual) - Manejador de datos
* [Cuenta en Google Cloud](https://console.cloud.google.com/) - Bodega de Datos
* [AdventureWorks] (https://github.com/lorint/AdventureWorks-for-Postgres/) - Base de datos a cargar en Postgres 


## Autores ✒️

* **Antonio Mata**  - [_amata@unbosque.edu.co_](https://github.com/antoniomata99)
* **Maruan Arias** - [_meariasc@unbosque.edu.co_](https://github.com/MaruanArias)
* **John Bedoya** - [_jabedoya@unbosque.edu.co_](https://github.com/Alejandro-prog)
* **Fabian Gonzalez** - [_fagonzalezm@unbosque.edu.co_](https://www.youtube.com/watch?v=XFkzRNyygfk)

# 
# Evidencias

## Carga a Postgres
<img src="/img/postgres.png" alt="My cool logo"/>

## Carga a BigQuery Google Cloud
<img src="/img/bigquery1.png" alt="My cool logo"/>

## Diccionario de datos
<img src="/img/bigquery2.png" alt="My cool logo"/>

Variable | Tipo | Descripción |
---------|------|-------------|
specialofferid_x  | int64 | ID de la oferta especial del producto
type_specialofferid |  object | Tipo de la oferta especial del ID
productid_x | int64 | ID del producto en x
productid_specialofferid | object | ID del producto del ID de la oferta especial
productid_y |  int64 | ID del producto en y
specialofferid_y | int64 | ID de la oferta especial en y
orderqty | int64 | Número de orden

<img src="/img/bigquery3.png" alt="My cool logo"/>

Variable | Tipo | Descripción |
---------|------|-------------|
locationid | int64 | ID de la locación
name_location |  object | Nombre de la locación
workorderid | int64 | ID de la orden de trabajo
productid | int64 | ID del producto
orderqty | int64 | Número de orden
productsubcategoryid | float64 | ID del producto de la subcategoría
name_productsubcategory | object | Nombre del producto de la subcategoría

<img src="/img/bigquery4.png" alt="My cool logo"/>

Variable | Tipo | Descripción |
---------|------|-------------|
businessentityid | int64 | ID de la entidad del negocio
name_vendor | object | Nombre del vendedor
productid | int64 | ID del producto
productsubcategoryid | float64 | ID de la subcategoría del producto
productcategoryid | int64 | ID de la categoría del producto
name_productsubcategory | object | Nombre del producto de la subcategoría
name_productcategory | object | Nombre del producto de la categoría

<img src="/img/bigquery5.png" alt="My cool logo"/>

Variable | Tipo | Descripción |
---------|------|-------------|
cultureid | object | ID de 
name_culture | object | Nombre del vendedor
productmodelid | int64 | ID del modelo del producto
name_productmodel | object | Nombre del modelo del producto
productid | int64 | ID del producto
orderqty | int64 | Número de orden





