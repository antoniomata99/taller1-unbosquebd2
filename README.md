# Workshop: Data Warehouses and ELTs

_El proposito del proyecto es desarrollar un proceso de extracción y manipulación de datos con el software Pandas_

## Comenzando 🚀

_Git Clone

_

Mira **Deployment** para conocer como desplegar el proyecto.


### Pre-requisitos 📋

* Anaconda
* Postgress
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




* [Postgress](https://www.postgresql.org/download/) - Base dedatos
* [Anaconda](https://www.anaconda.com/products/individual) - Manejador de datos
* [Cuenta en Google Cloud](https://console.cloud.google.com/) - Bodega de Datos


## Autores ✒️

_Menciona a todos aquellos que ayudaron a levantar el proyecto desde sus inicios_

* **Antonio Mata** - *Desarrollo* - [_amata@unbosque.edu.co_](https://github.com/antoniomata99)
* **Maruan Arias** - *Desarrollo* - [_meariasc@unbosque.edu.co_](https://github.com/MaruanArias)
* **John Bedoya** - *Desarrollo* - [_jabedoya@unbosque.edu.co_](https://github.com/Alejandro-prog)
* **Fabian Gonzalez** - *Desarrollo* - [_fagonzalezm@unbosque.edu.co_](https://www.youtube.com/watch?v=XFkzRNyygfk)



## Licencia 📄

Este proyecto está bajo la Licencia de wakanda - mira el archivo [LICENSE.md](LICENSE.md) para detalles

## Expresiones de Gratitud 🎁

*Ponganos 5.0 profe 

⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣤⣤⣴⣦⣶⣶⣴⣼⣴⣾⣄⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⣴⣾⣷⣿⣷⣶⣤⣤⣄⣀⣤⣆⣠⣤⣭⣿⣿
⠀⠀⠀⠀⠀⠀⠀⣀⣀⣤⣼⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⢿⠧⠀⠀⠀⠀⠀⢀⡤⢶⣿⣿⣿⣿⣿⣿⣿⢿⣿⣿⣿⣿⣿⣿⣿⡿⣿⣿⣿
⠀⢀⣀⣤⠴⠺⠻⠛⠛⢻⡟⠏⣿⠙⠉⢻⠻⣿⣿⣿⣿⣷⣦⣄⣀⣀⣀⣠⣼⣷⣿⣿⣿⣿⣿⣿⣾⣇⣿⣿⣿⣿⣿⣿⣿⣿⣋⠏⠈⠙
⠀⠈⠉⠀⠀⣀⡤⠀⠋⠁⠀⠀⠀⠐⠚⣠⣆⣿⣿⣿⣉⠹⢿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣾⣿⣿⣽⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣐⡀⠀⠀
⠀⠀⠀⠀⠨⠁⠁⢀⣠⣤⣶⣶⣶⣾⣷⣿⣿⣿⣿⡿⢽⢤⢸⣿⣿⠤⠀⠺⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣤
⠀⠀⠀⠀⠀⢀⣴⠿⠻⣿⣿⣿⣿⣿⣿⠷⠶⣥⠀⠠⠄⠆⢺⣿⠋⠀⠀⠀⠹⣿⣿⣅⣼⣶⣶⣷⡄⠙⠻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
⠀⠀⠀⢀⣔⠛⠋⠀⠘⡏⠉⠻⠿⢿⠑⠀⠀⠉⠀⠀⠀⠀⣾⠏⠀⠀⠀⠀⠀⠻⣿⣿⡫⠉⠐⢽⣿⣆⣤⣺⣿⣿⣿⣿⣿⣿⡿⠿⡿⠋
⠀⠀⠀⠈⠀⠀⠀⠰⠮⣊⣵⣿⣿⣟⣞⠁⠀⠀⠀⠀⠀⣰⡟⠀⠀⠀⠀⠀⠀⠈⣿⣿⣧⡀⠀⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣓⣯
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⠫⣟⣿⣻⣿⠗⠉⠀⠀⠀⣼⣿⠀⠀⠀⠀⠀⠀⠀⠀⠸⣿⡿⣿⣧⡹⠿⡿⢽⠯⠻⠿⣿⢿⣿⣿⣿⣿⣭⣧
⠀⠰⡀⠀⠀⠀⠀⠀⠀⠀⠀⡤⣼⠷⠉⠀⣀⣠⡔⠋⠹⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⣯⡸⣿⡿⠿⠧⣬⣤⣤⣄⣁⣨⣿⣬⣯⣽⣷⣿
⠀⠀⠈⠓⠢⢤⣤⣤⣤⣤⣤⣦⠵⠶⠞⠋⠉⠀⠀⠀⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠿⠿⡏⠉⠁⠀⠀⠉⠙⠋⠛⠻⠛⠛⠉⠟⠉⠙
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢂⣤⢸⢀⠀⠀⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣷⠀⠀⠀⢠⣤⣦⣤⠀⠀⢀⣸⣿⣿⣿⣟⣶⡆⡁⠀⠈⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⠀⣌⣿⡇⠀⠀⠈⢋⠁⠀⣀⣰⣾⣿⣿⣿⣿⣿⡟⠀⠑⠀⠀⠀⠀⠈⠀⠀⠀⠀⠀⠀⠀⠀⢀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠁⠀⠛⠁⠀⠀⠈⠟⠁⠀⠀⠸⠛⠀⠀⠀⠉⠉⠛⠀⠀⠐⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢤⣴⣶⣶⣿⣛⡠⡊⡁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠠⠀⠀⠠⠀⣨
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⣤⣤⣦⣤⣤⣯⣿⣿⣿⣽⣭⣧⣀⣀⡀⠀⠀⠀⠀⠀⡀⠀⠀⠀⢀⡈⡀⣈⣬
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡴⡿⠿⠟⠛⠛⠛⠛⠛⠛⠛⠻⢿⣿⣿⣿⣿⠄⠀⠀⠀⠀⠀⠀⠀⠈⠀⠈⠫⠿⢿
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠴⠚⠛⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⡛⡿⠛⠛⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠄⢰⣷
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⠀⣄⢨⢐⣂⠀⠀⠀⠁⠨⠀⠀⠀⠀⠀⠀⠀⠐⡇⣴⣿
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠐⠀⠋⠘⠋⠛⠓⠉⠛⠀⠀⠀⠈⠀⠀⠀⠀⠀⠈⠀⠂⠀⠁⠘⠛
