![](./images/egytp_logo.png)

Diciembre 2021

M. Sc. Liliana Millán Núñez liliana.millan@tec.mx

## Herramientas de análisis de datos

### Contenido

+ Datos `tidy`
+ R
+ Python

***

Sin importar la herramienta que utilices para el análisis de los datos y el modelado, necesitarás tener tus datos en formato `tidy`.

Filosofía de datos `tidy`:

* Cada fila es una observación
* Cada columna es una variable/característica de cada observación
* Se tiene una matriz de observaciones

La estructura de datos que se ocupa tanto en R como en Python/Pandas es el *Data Frame* que asimila una tabla -matriz- que sigue la filosofía de datos `tidy`.

### R

+ OpenSource
+ R base
  + Instalación para [Windows](https://cran.itam.mx/) Selecciona la opción *Download R for Windows*
  + Instalación para [Mac](https://cran.itam.mx/) Selecciona la opción *Download R for macOS*
  + Instalación para [Linux](https://cran.itam.mx/) Selecciona la opción *Download R for Linux*
+ RStudio
  + Instlaación para [Windows](https://www.rstudio.com/products/rstudio/download/#download) Selecciona la opción para Windows.
  + Instlaación para [Mac](https://www.rstudio.com/products/rstudio/download/#download) Selecciona la opción para macOS.
  + Instalación para [Linux](https://www.rstudio.com/products/rstudio/download/#download)

+ Tidyverse: La primera vez: `install.packages("tidyverse")`, una vez instalado, cargar la librería con `library(tidyverse)`
+ Dplyr: La primera vez: `install.packages("dplyr")`, una instalado, cargar la librería con `library(dplyr)`.
+ Librerias de ML: Depende del algoritmo, modelo que quieres utilizar.

Si por algún motivo no puedes instalar R y RStudio en tu máquina, puedes ocupar `rdrr.io` para correr código de R en tu *browser* [rdrr.io](https://rdrr.io/snippets/).

### Python

+ Pandas
+ Seaborn
+ Scikit-learn
+ Spark

Si no quieres/puedes instalar python y demás paquetes en tu máquina, puedes ocupar `google colab` para generar y correr notebooks de python que te permiten analizar tus datos. Se guardan como scripts en Drive.



[Inicio](./index.md)
