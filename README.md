# R para aplicaciones estadísticas 

Este repositorio incluye material docente, datos y código empleados en clases de introducción a R para aplicaciones estadísticas. Este material está bajo una licencia [Creative Commons CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/ "Creative Commons CC-BY-SA 4.0 title").

## 1. Introducción a R 
### 1.1 Cómo usar esta documentación

Para trabajar con la documentación de este repositorio es recomendable obtener una copia local. Para hacerlo puedes elegir entre: 

1. Descargar el repositorio en formato ZIP
2. Hacer una copia del repositorio con git: git://github.com/BlancaGB/R.git

### 1.2 ¿Qué es R? 

R es un lenguaje de programación principalmente orientado al análisis estadístico y visualización de información cuantitativa y cualitativa y publicado como software libre con licencia GNU-GPL.

### 1.3 Instalar R y RStudio

#### 1.3.1 Paso 1: Instalar R 
* Si utilizáis Windows, se puede descargar el instalador desde: http://cran.es.r-project.org/bin/windows/base/.
* Si utilizáis Mac, desde: http://cran.es.r-project.org/bin/macosx/
* Y si utilizáis Linux, posiblemente esté disponible en el gestor de aplicaciones. En todo caso, la web para Linux es: http://cran.es.r-project.org/bin/linux/.

#### 1.3.2 Paso 2: Instalar la interfaz RStudio 

Una interfaz gráfica de R recomendable es [RStudio](https://www.rstudio.com/products/rstudio/ "RStudio title"). Podéis descargar el instalador desde [aquí](https://www.rstudio.com/products/rstudio/download/ "aquí"). Os aconsejo que leáis esta breve [introducción](https://support.rstudio.com/hc/en-us/articles/200484448-Editing-and-Executing-Code "introducción title").

#### 1.3.3. Ayuda adicional para la Instalación de R y RStudio 

Tutoriales de Youtube que explican cómo realizar los pasos 1 y 2: 

* Si utilizáis Windows,  https://www.youtube.com/watch?v=TFGYlKvQEQ4 
* Si utilizáis Mac,  https://www.youtube.com/watch?v=LanBozXJjOk 
* Si utilizáis Linux,  https://www.youtube.com/watch?v=3ni-jP2qEWg 

###  1.4 Documentación

Podéis consultar el [manual introductorio](https://cran.r-project.org/doc/manuals/R-intro.html "manual introductorio title"), los [manuales oficiales](https://cran.r-project.org/manuals.html "manuales oficiales title") y los [manuales externos](https://cran.r-project.org/other-docs.html "manuales externos title"). También es muy recomendable el agregador de blogs sobre R [R-bloggers](https://www.r-bloggers.com/ "R-bloggers") Se recomienda consultar también para practicar con ejemplos básicos en R:
* El [curso](https://github.com/oscarperpinan/R "curso title") del Prof. Oscar Perpiñán de la UPM. 
* El [curso](https://www.uv.es/vcoll/preliminares.html#primeras-ideas "curso title") del Prof. Vicente Coll de la UPV. 

### 1.5 Paquetes de R 

Una de las grandes riquezas de R es la cantidad de paquetes (más de 4000 actualmente) que amplían sus funcionalidades. La lista completa está en http://cran.es.r-project.org/web/packages/. En esta documentación emplearemos algunos de los más utilizados para representaciones gráficas y análisis de datos estadísticos. 

## 2. Objetivos y mecánica del curso

En la clase práctica de Introducción a R vamos a aplicar métodos estadísticos ue se utilizan comúnmente en el análisis de datos. En la clase: 

* El alumno/a aprenderá a utilizar R para cargar datos, modificarlos, hacer gráficos y tablas, e informes en Rmarkdown.
* Se persigue que el curso sea fundamentalmente práctico, pero se necesita un mínimo de conocimiento sobre el funcionamiento de determinados aspectos y también hay que conocer un poco la jerga que se utiliza en la comunidad R.
* En lugar de presentar todos los pormenores de R de manera lineal, se irán presentando distintos aspectos de R conforme se vayan necesitando; es decir, no vamos a presentar R como un lenguaje de programación sino como una herramienta para hacer análisis estadísticos.
* En la sección 1 de este documento tenéis todos los materiales: tutoriales, algunos datos, etc. 

Los temas de la clase incluyen:

* Importación y formato de los datos
* Gráficas de barras
* Histogramas
* Gráficas de caja
* Gráficas de dispersión
* Determinación de la potencia y el tamaño de la muestra
* Pruebas t
* Intervalos de tolerancia
* Gráficas de control de variables y atributos
* Regresión lineal por mínimos cuadrados 

## 3. Preliminares 

Ir al [curso](https://www.uv.es/vcoll/preliminares.html#primeras-ideas "curso title") del Prof. Vicente Coll de la UPV, donde se cubren los contenidos de esta sección que reviseramos brevemente, para pasar a continuación a un ejemplo práctico. 

### 3.1 Instalar R y RStudio (localmente) o usar R Studio en la nube 

### 3.2 Entorno de trabajo de RStudio.

* Consola
* Scripts
* Entorno
* Miscelánea
* Configuración del directorio de trabajo (Fijar directorio o R Project)
* Instalar y cargar paquetes 

### Script en R Studio Cloud: LMBB_01_PREMILINARES

## 4. Conceptos básicos de R 

Ir al [curso](https://www.uv.es/vcoll/preliminares.html#primeras-ideas "curso title") del Prof. Vicente Coll de la UPV, donde se cubren los contenidos de esta sección que reviseramos brevemente, para pasar a continuación a un ejemplo práctico. 

* Operaciones básicas 
* Vectores, matrices, listas, factores, data frame, funciones 
* Importar y exportar datos 
* (Procesar los datos (Tydiverse))

### Script en R Studio Cloud: LMBB_02_CONCEPTOSBASICOS

## 5. Gráficos base 

Ir a la sección 6.2 del [curso](https://www.uv.es/vcoll/preliminares.html#primeras-ideas "curso title") del Prof. Vicente Coll de la UPV, donde se cubren los contenidos de esta sección que reviseramos brevemente, para pasar a continuación a un ejemplo práctico. 

* Histograma
* Boxplot 
* Diagrama de dispersión
* Diagrama de barras 
* Guardar y exportar gráficos 

### Script en R Studio Cloud: LMBB_03_GRAFICOS

## 6. R Markdown 

Ir a la sección 7 del [curso](https://www.uv.es/vcoll/preliminares.html#primeras-ideas "curso title") del Prof. Vicente Coll de la UPV, donde se cubren los contenidos de esta sección que reviseramos brevemente, para pasar a continuación a un ejemplo práctico. 

### Script en R Studio Cloud: LMBB_04_MARKDOWN
