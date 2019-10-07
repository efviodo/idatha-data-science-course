![IdathaLogo](notebooks/figures/idatha-logo.jpeg)

# idatha-data-science-course

Un taller que brinda al estudiante conocimientos básicos sobre Ciencia de Datos y a la vez le permite ganar experiencia con herramientas de Ciencia de Datos como Jupyter Notebooks, Python, R, entre otras, en el desarrollo de un proyecto de investigación en Ciencia de Datos.

## Organización

El taller se compone de material convencional en formato slides, a través del cual el estudiante puede aprender los principales conceptos acerca de Ciencia de Datos. La lista completa de slides está disponible en el directorio [slides/](slides). A modo de gúia, se suguiere el siguiente orden de lectura:

1. [01 - IDATHA - UM - Data Science - Presentacion.pdf](slides/01%20-%20IDATHA%20-%20UM%20-%20Data%20Science%20-%20Presentacion.pdf)
2. [02 - IDATHA - UM - Data Science - Teorico Parte 1.pdf](slides/02%20-%20IDATHA%20-%20UM%20-%20Data%20Science%20-%20Teorico%20Parte%201.pdf)
3. [03 - IDATHA - UM - Data Science - Teorico Parte 2.pdf](slides/03%20-%20IDATHA%20-%20UM%20-%20Data%20Science%20-%20Teorico%20Parte%202.pdf)

De forma complementaria, el taller cuenta con material en formato Jupyter Notebooks, mediante el cual el estudiante puede ver en acción, utilizando datos de verdad, los conceptos que previamente fueron presentados a través de las slides. 

Con el espíritu de simplificar el proceso de aprendizaje, minimizando la curva de aprendizaje, se proveen Notebooks con ejemplos para los lenguajes **R** y **Python**. Estos son los dos lenguajes de programación más utilizados actualmente por la comunidad de data scientist. 

Vale la pena aclarar, si bien cada notebook responde a un grupo de conceptos en particular, como _Data Preparation_, _Data Visualization_, etc., el lector puede encontrar pequeñas diferencias entre la versión de un mismo Notebook escrito en **R** o escrito en **Python**. Esto se debe principalmente a que cada lenguaje cuenta con sus propias particularidades y librerías, lo cual imposibilita en algunos casos, que un mismo notebook, en **R** sea una fiel espejo del mismo en **Python**. 

Por otro lado, el conjunto de Notebooks en **R** se desarrolló primero, siguiéndole el conjunto de notebooks portados a **Python**. Por esta razón, puede que los notebooks en **Python** contengan algun BUG Fix o mejora, introducido como parte del proceso de "portado" que aún no haya sido trasladado a la versión original en **R**. 

La lista completa de notebooks está disponible en el directorio [notebooks/](notebooks). A modo de guía, se suguiere el siguiente orden de lectura:

**R**

1. [01 - DS - Conceptos Basicos Jupyter Notebooks - R.ipynb](notebooks/01%20-%20DS%20-%20Conceptos%20Basicos%20Jupyter%20Notebooks%20-%20R.ipynb)
2. [02 - DS - Introduccion a Data Science - R.ipynb](notebooks/02%20-%20DS%20-%20Introduccion%20a%20Data%20Science%20-%20R.ipynb)
3. [03 - DS - Adquisicion de Datos - R.ipynb](notebooks/03%20-%20DS%20%20Adquisicion%20de%20Datos%20-%20R.ipynb)
4. [04 - DS - Comprension de los Datos - R](notebooks/04%20-%20DS%20-%20Comprension%20de%20los%20Datos%20-%20R.ipynb)
5. [05 - DS - Visualizacion de Datos - R.ipynb](notebooks/05%20-%20DS%20-%20Visualizacion%20de%20Datos%20-%20R.ipynb)
6. [06 - DS - Preparacion de Datos y Visualizacion - R.ipynb](notebooks/06%20-%20DS%20-%20Preparacion%20de%20Datos%20y%20Visualizacion%20-%20R.ipynb)


**Python**

1. [01 - DS - Conceptos Basicos Jupyter Notebooks - Python.ipynb](notebooks/01%20-%20DS%20-%20Conceptos%20Basicos%20Jupyter%20Notebooks%20-%20Python.ipynb)
2. [02 - DS - Introduccion a Data Science - Python.ipynb](notebooks/02%20-%20DS%20-%20Introduccion%20a%20Data%20Science%20-%20Python.ipynb)
3. [03 - DS - Adquisicion de Datos - Python.ipynb](notebooks/03%20-%20DS%20-%20Adquisicion%20de%20Datos%20%20Python.ipynb)
4. [04 - DS - Comprension de los Datos - Python](notebooks/04%20-%20DS%20-%20Comprension%20de%20los%20Datos%20-%20Python.ipynb)
5. [05 - DS - Visualizacion de Datos - Python.ipynb](notebooks/05%20-%20DS%20-%20Visualizacion%20de%20Datos%20%20Python.ipynb)
6. [06 - DS - Preparacion de Datos y Visualizacion - Python.ipynb](notebooks/06%20-%20DS%20-%20Preparacion%20de%20Datos%20y%20Visualizacion%20-%20Python.ipynb)

## Ambiente de ejecución

### Jupyter Notebook
Es una aplicación Web interactiva, open-source, en la cual podemos combinar código (junto con su ejecución y resultados), texto enriquecido, tablas, entre otros. De esta forma, podemos crear como data scientitst, informes y análisis de datos combinando código con conclusiones en un mismo lugar.

Más información acerca de Jupyter Notebook en [https://jupyter.org/](https://jupyter.org/)

### Anaconda

Esencialmente es una distribución libre y abierta de los lenguajes Python y R, junto con herramientas que facilitan la configuración y despliegue de un ambiente virtual con todas sus dependencias (librerías, etc.).

Es ampliamente utilizado en el área de la ciencia de datos y además es compatible con Linux y Windows. 

Podemos utilizarlo como gestor para la instalación de Python/R, Jupyter Notebooks y todas las librerías que vayamos a necesitar.

Más información acerca de Anaconda en [https://www.anaconda.com/distribution/](https://www.anaconda.com/distribution/)

### Google Colab

Colaboratory es un entorno de notebook de Jupyter gratuito que no requiere configuración y se ejecuta completamente en la nube.

Tiene la ventaja de permitir las mismas funcionalidades de Jupyter Notebooks en un ambiente en la nube, sin instalación y de forma gratuita, necesitando solamente de un navegador Web. Como contra-parte, de forma gratuita, está limitada la utilización de Memoria RAM y CPU ya que utiliza hardware compartido en la nube.

Más información acerca de Google Colab en [https://colab.research.google.com/notebooks/welcome.ipynb](https://colab.research.google.com/notebooks/welcome.ipynb)

## Contribuidores

* Emiliano Viotti
* Manu Reynaert
