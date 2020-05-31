# Practicas de estadistica y análisis de datos con Python

El siguiente repo contiene Jupyter Notebooks con ejemplos de Estadística sobre distintos temas aplicados con librerias para de análisis en Python como:

## Temario de los ejercicios

### Distribuciones de probabilidad

* [Distribuciones de probabilidad](/Distribuciones/Distribuciones.ipynb)

**Discretas**

* [Distribucion de Poisson](/Distribuciones/Distribución%20continua%20de%20Poisson.ipynb)
* [Distribucion de Bernouli](/Distribuciones/Distribución%20discreta%20de%20Bernoulli.ipynb)
* [Distribucion de Binomial](/Distribuciones/Distribución%20discreta%20Binomial.ipynb)
* [Distribucion de Hipergeometrica](/Distribuciones/Distribución%20hipergeométrica.ipynb)

**Continuas**

* [Distribucion normal o de Gauss](/Distribuciones/Distribución%20normal.ipynb)
* [Distribucion exponencial](/Distribuciones/Distribución%20exponencial.ipynb)

### Modelos de predicción

* [Regresión líneal con sklearn](/Regresiones/Regresión%20líneal%20sklean.ipynb)
* [Regresión líneal con statsmodels](/Regresiones/Regresión%20líneal%20con%20statsmodels.ipynb)
* [Regresión líneal con statsmodels 2](/Regresiones/Regresión%20líneal%20con%20statsmodel%202.ipynb)
* [Regresión líneal con statsmodels 3](/Regresiones/Regresión%20líneal%20con%20statsmodel%203.ipynb)
* [Regresión logistica](/Regresiones/Regresión%20logística.ipynb)


### Modelos de decisión

* [Árboles de decisión](/Arboles%20de%20decisión/Árboles%20de%20decisión.ipynb)

<div align="center">
  <img src="img/stats.png">
</div>

## Librerías de análisis estadístico

* **Scipy:** Computo científico
  * https://www.scipy.org/
* **Pandas:** Estructuras de datos y análisis
  * https://pandas.pydata.org/
* **Numpy:** Estructuras de N dimensiones 
  * https://numpy.org/
* **SKlearn:** Aprendizaje automático   
  * https://scikit-learn.org/stable/
* **SymPy:** Matemáticas simbolicas
  * https://www.sympy.org/en/index.html
* **Statsmodels** Modelos estadísticos, hypothesis tests, and data exploration

## Librerías de visualización
* **Seaborn**: Visualización de datos basada en Matplotlib. Capa adicional de abstracción
  * https://seaborn.pydata.org/
* **Matplotlib:** Gráficado en 2D
    * https://matplotlib.org/


## Librerías complementarias
* **Pyreadstat** A python package to read and write sas (sas7bdat, sas7bcat, xport), spps (sav, zsav, por) and stata (dta) data files into/from pandas dataframes.
  * https://github.com/Roche/pyreadstat
* **Graphviz** Requerido para trabajar con gráficos y arboles de decisión
  * https://pypi.org/project/graphviz/
  * https://graphviz.gitlab.io/_pages/Download/Download_windows.html

## Contenido complementario

* [Teoría sobre probabilidad y estadística](https://github.com/eocode/Love-Data-with-Python-SQL-R-Scala/tree/master/learn/Matematicas/pye)
* [Estadística con Python](https://github.com/eocode/Love-Data-with-Python-SQL-R-Scala/tree/master/learn/DataScience/StatsAndDataAnalysis)
* [Pensamiento probabilistico y matemáticas aplicadas](https://github.com/eocode/Love-Data-with-Python-SQL-R-Scala/tree/master/learn/DataScience/Matematicas%20Aplicadas)

## Guía de Aplicaciones

### Uso de las distribuciones

Algunos consejos:

> Comenzar con los datos sin procesar y responder a cuatro preguntas básicas acerca de los mismos, que nos pueden ayudar a caracterizarlos.

* La primer pregunta se refiere a si los datos pueden tomar valores discretos o continuos.
* La segunda pregunta que nos debemos hacer, hace referencia a la simetría de los datos y si hay asimetría, en qué dirección se encuentra; en otras palabras, son los valores atípicos positivos y negativos igualmente probables o es uno más probable que el otro.
* La tercer pregunta abarca los límites superiores e inferiores en los datos; hay algunos datos, como los ingresos, que no pueden ser inferiores a cero, mientras que hay otros, como los márgenes de operación que no puede exceder de un valor (100%).
* La última pregunta se refiere a la posibilidad de observar valores extremos en la distribución; en algunos casos, los valores extremos ocurren con muy poca frecuencia, mientras que en otros, se producen con mayor frecuencia.

<div align="center">
  <img src="img/distributions_choice.png">
</div>

## Modelos de ML

<div align="center">
  <img src="img/machinelearning.png">
</div>

## Fuentes

* https://platzi.com/datos/
* https://relopezbriega.github.io
* https://blog.adrianistan.eu
* https://aprendeconeli.com

## Contribuye con ejemplos

Enviame un pullrequest con un nuevo notebook con ejemplos detallados sobre algún tema de interés

## Licencia

MIT License

Copyright (c) 2020 Elias Ojeda Medina

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
