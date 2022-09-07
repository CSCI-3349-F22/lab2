# Lab 2: nltk and spaCy

In this lab, you'll be learning how to use the nltk library to carry out text normalization and do some basic text analysis. At the very end, you'll use a different library, spaCy, which will allow you to do much of this normalization in a more streamlined but less transparent way. 

The lab will be entirely contained within a Jupyter notebook. If you have never used one before, don't worry! This lab will walk you through using Jupyter.

Depending on how you installed Python 3.9 and what you have done before, it's possible that you are going to need to install some stuff. Please review the material below.

### Part 1: Install nltk and spaCy for your Python 3.9

* With Anaconda: Anaconda has a library manager within the Anaconda navigator that you can use to install these libraries. Alternatively, you can install them with the conda package manager from the command line, like so:

```conda install -c anaconda nltk```
```conda install -c conda-forge spacy```

* Without Anaconda: You can just use pip, like so

```python3.9 -m pip install nltk```
```python3.9 -m pip install spacy```

### Part 2: Make sure you can launch jupyter notebook *within Python 3.9*.

* With Anaconda: If you have Anaconda with Python 3.9, then you most likely have jupyter already. You can launch jupyter notebook in one of two ways. (1) Launch Anaconda Navigator, then click the Jupyter Notebook launch button. ~OR~ (2) If you installed Anaconda recently, its version of jupyter should be the one you can launch from a command line. Open a terminal, and type ``which jupyter``. If the path it prints out includes the word "Anaconda" and "3.9" it in somewhere, you should also be able to launch jupyter notebook with Python 3.9 just by typing ```jupyter notebook``` at the command line.

* With pip: If you installed Python 3.9 not using Anaconda, you might not have jupyter already, unless you installed yourself for something else. Open a terminal and type

```which jupyter```

If it gives you a path back that's the same as you get if you typed ```which python3```, you are good to go!  Type ``jupyter notebook`` to launch.

If it doesn't give you back anything or if it gives you back a path that's not the same as ```which python3```, then you'll need to (re)install it, like so. (You can also just use pip3, but make sure that pip3 is also 3.9!)

```python3 -m pip install jupyter```


