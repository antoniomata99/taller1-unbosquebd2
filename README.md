# Workshop: Data Warehouses and ELTs

_El proposito del proyecto es desarrollar un proceso de extracci贸n y manipulaci贸n de datos con el software Pandas_

### Pre-requisitos 馃搵

* Anaconda
* Postgres
* Cuenta en Google Cloud

```
https://www.postgresql.org/download/
https://www.anaconda.com/products/individual
https://console.cloud.google.com/
```

### Instalaci贸n 馃敡

_Para la intalaci贸n de Anaconda ver la siguiente pagina_


```
https://docs.anaconda.com/anaconda/install/windows/
```




* [Postgres](https://www.postgresql.org/download/) - Base de datos
* [Anaconda](https://www.anaconda.com/products/individual) - Manejador de datos
* [Cuenta en Google Cloud](https://console.cloud.google.com/) - Bodega de Datos
* [AdventureWorks](https://github.com/lorint/AdventureWorks-for-Postgres/) - Base de datos a cargar en Postgres


## Autores 鉁掞笍

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

Variable | Tipo | Descripci贸n |
---------|------|-------------|
specialofferid_x  | int64 | ID de la oferta especial del producto
type_specialofferid |  object | Tipo de la oferta especial del ID
productid_x | int64 | ID del producto en x
productid_specialofferid | object | ID del producto del ID de la oferta especial
productid_y |  int64 | ID del producto en y
specialofferid_y | int64 | ID de la oferta especial en y
orderqty | int64 | N煤mero de orden

<img src="/img/bigquery3.png" alt="My cool logo"/>

Variable | Tipo | Descripci贸n |
---------|------|-------------|
locationid | int64 | ID de la locaci贸n
name_location |  object | Nombre de la locaci贸n
workorderid | int64 | ID de la orden de trabajo
productid | int64 | ID del producto
orderqty | int64 | N煤mero de orden
productsubcategoryid | float64 | ID del producto de la subcategor铆a
name_productsubcategory | object | Nombre del producto de la subcategor铆a

<img src="/img/bigquery4.png" alt="My cool logo"/>

Variable | Tipo | Descripci贸n |
---------|------|-------------|
businessentityid | int64 | ID de la entidad del negocio
name_vendor | object | Nombre del vendedor
productid | int64 | ID del producto
productsubcategoryid | float64 | ID de la subcategor铆a del producto
productcategoryid | int64 | ID de la categor铆a del producto
name_productsubcategory | object | Nombre del producto de la subcategor铆a
name_productcategory | object | Nombre del producto de la categor铆a

<img src="/img/bigquery5.png" alt="My cool logo"/>

Variable | Tipo | Descripci贸n |
---------|------|-------------|
cultureid | object | ID de cultura
name_culture | object | Nombre de la cultura
productmodelid | int64 | ID del modelo del producto
name_productmodel | object | Nombre del modelo del producto
productid | int64 | ID del producto
orderqty | int64 | N煤mero de orden





