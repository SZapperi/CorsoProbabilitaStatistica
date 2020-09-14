# CorsoProbabilitaStatistica
In questa repository si trovano i notebook python relativi alle esercitazioni del corso di Probabilità e Statistica, parte del corso di Laurea in Fisica all'Università degli Studi di Milano.
(c) Stefano Zapperi


I notebook sono stati in parte adattati dai seguenti testi:

*Practical Statistics for Data Scientists:*  
50+ Essential Concepts Using R and Python
Peter Bruce, Andrew Bruce, and Peter Gedeck
O'Reilly Media; 2 edition (June 9, 2020)
ISBN-13: 978-1492072942


*Introduction to Statistics With Python*
by Thomas Haslwanter 
Springer (2020)
ISBN-13: 978-3319283159 


## Installare jupyter sul vostro computer

Per seguire queste lezioni, è necessaria una moderna installazione di python, oltre a jupyter, numpy, matplotlib e alcune altre librerie  standard di python. Il modo più semplice per installare tutti questi pacchetti senza interferire con l'attuale installazione di python è la distribuzione Anaconda. Scegliete python 3.x e il vostro sistema operativo, scaricate, installate e dovreste essere a posto.

## Usare un ambiente online

In alternativa, se non è possibile installare jupyter sul proprio computer, è possibile utilizzare l'ambiente online mybinder, che è fondamentalmente una versione online della repository. Notate che il codice non verrà eseguito sul vostro computer, e che perderete il vostro lavoro se chiudete la finestra del browser. Per lanciare la pagina mybinder per il corso, cliccate qui! 

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fontclos/stat-mech-python-course/master?urlpath=lab)

Dopo aver completato un notebook, ricordatevi di scaricarlo sul vostro computer locale!

Di seguito alcune informazioni utili (in inglese):

## Getting started
Open a terminal and `cd` to a directory of your choice
```bash
$ cd Documents
```
Check that you have correctly installed Anaconda's python. 
```bash
$ which python
/home/username/anaconda3/bin/python
```
Clone this repository
```bash
$ git clone https://github.com/fontclos/stat-mech-python-course.git
```
A new folder called `stat-mech-python-course` will be created. Enter it and start jupyter by typing `jupyter lab`
```bash
$ cd stat-mech-python-course
$ jupyter lab
```
A browser window/tab pointing to `localhost:8888` will open automatically. Open the `notebooks` folder, then open the first notebook by double-clicking `1-Generating-Random-Numbers.ipynb`. You are ready to go!


## Searching for help online
Being able to **re-use someone else's code** is as important as being able to write your own. You are *not* supposed to figure out everything by yourself, so googling *how to X in python* is just fine. In addition, some useful resources are:

+ Ask questions
  + [Stackoverflow](https://stackoverflow.com/)

+ Official documentation sites
  + [Numpy documentation](https://docs.scipy.org/doc/numpy/reference/routines.html)
  + [Scipy documentation](https://docs.scipy.org/doc/scipy/reference/)
  + [Jupyter Lab documentation](https://jupyterlab.readthedocs.io/en/stable/)

+ Tutorials
  + [Data Flair Python Tutorials](https://data-flair.training/blogs/python-tutorials-home/)
  
+ Windows users
  + [Pre-compiled binaries](https://www.lfd.uci.edu/~gohlke/pythonlibs/)

