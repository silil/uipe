![](./images/egytp_logo.png)

Diciembre 2021

M. Sc. Liliana Millán Núñez liliana.millan@tec.mx

## Herramientas de análisis de datos

### Contenido

+ R
+ Python
+ Análisis exploratorio de datos

***

Sin importar la herramienta que utilices para el análisis de los datos y el modelado, necesitarás tener tus datos en formato `tidy`.

Recordemos que el formato `tidy` implica que:

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

+ Pandas: Paquete que habilita a Python para análisis de datos (simil de R).
+ Seaborn: Paquete que habilita a Python para realizar gráficas.
+ Scikit-learn: Paquete que habilita a Python la parte de *machine learning*.
+ Spark: Paquete que habilita a Python al análisis de datos y *machine learning* en cluster.

Si no quieres/puedes instalar python y demás paquetes en tu máquina, puedes ocupar `google colab` para generar y correr *notebooks* de Python que te permiten analizar tus datos. Se guardan como scripts en Drive. [Google Colab](https://colab.research.google.com)


## Análisis exploratorio de datos (EDA)

Objetivos de un EDA:

* Conocer los datos -nivelar conocimiento con el cliente/socio-
* Identificar errores en los datos
* Responder preguntas de hipótesis que se tienen sobre los datos
* Identificar variables que aportan información para responder una pregunta analítica -generalmente predictiva-

### Ejercicio

Ocuparemos los datos de Covid 19 de México para realizar un análisis exploratorio de datos.

Queremos contestar las siguientes preguntas:

1. ¿Con qué variables contamos?
2. ¿Los datos están en formato `tidy`?
3. ¿Desde cuándo hasta cuándo tenemos datos de casos de Covid 19?
4. ¿Tenemos datos de todas las entidades federativas?
5. ¿Existen casos en donde la fecha de defunción suceda antes de la fecha de ingreso?
6. Hay más casos en 2021 que en 2020

**Hipótesis**

6. Personas mayores de 60 años tienen mayor defunción que otros grupos de edad
7. Los hombes son más suceptibles a morir por COVID-19
8. Una vez que eres intubado es poco probable que sobrevivas
9. Personas con comorbilidades tienen mayor probabilidad de morir por COVID-19
10. Estados "turísticos" tienen más casos
11. Un par de semanas después de fechas "feriadas" -día de las madres, semana santa, navidad, año nuevo- hay más contagios



[Inicio](./index.md)
