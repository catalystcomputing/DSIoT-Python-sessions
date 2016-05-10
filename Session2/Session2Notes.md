# IPython - Session 2 scikit learn

- IPython Interactive interpreter
- Anaconda installation give 300+ libraries and a package installation and maintenance
- [scikit-learn](http://scikit-learn.org/stable/index.html "scikit-learn web site") - Machine Learning in Pythonm
  - Simple and efficient tools for data mining and data analysis
  - Accessible to everybody, and reusable in various contexts
  - Built on NumPy, SciPy, and matplotlib
  - Open source, commercially usable - BSD license

## scikit learnm

### Install Anaconda

[http://docs.continuum.io/anaconda/install](http://docs.continuum.io/anaconda/install "anaconda installation")

- Install Anaconda from USB stick if you don't have it installed. There are version for Windows, MacOSX and Linux.
- Copy Session2 folder to your machine.

### Update Anaconda to latest version and start ipython

`conda update conda`

`conda update ipython ipython-notebook ipython-qtconsole`

`conda install scikit-learn`m

**Start ipython notebook**


`cd <Session2 folder>/code` 

`ipython.exe notebook`

When running your default browser will start `http://localhost:8888/tree` running jupyter

### 00 Download data

Open `00 Download data` notebook.

Run command in notebook to start data downloading.
```
from sklearn.datasets import fetch_20newsgroups
twenty_train = fetch_20newsgroups(subset='train', shuffle=True, random_state=42)
```

This will download the ~15MB dataset locally for use later into:

`C:\Users\<User name>\scikit_learn_data`

or

`~/scikit_learn_data`

### 01 Working with text

Sample from [http://scikit-learn.org/stable/tutorial/text_analytics/working_with_text_data.html](http://scikit-learn.org/stable/tutorial/text_analytics/working_with_text_data.htm)

The data set is '20 newsgroups dataset' a dataset used for testing machine learning accuracy described at:
[20 newsgroups dataset website](http://people.csail.mit.edu/jrennie/20Newsgroups/)

We will be running through the items in the notebook.

## Extracting features from text files

1. What is a feature vector?
2. What is a spare matrix?
3. What are two problems with using a word count in a document?

## Training a classifier

[http://scikit-learn.org/stable/modules/naive_bayes.html#naive-bayes](http://scikit-learn.org/stable/modules/naive_bayes.html#naive-bayes 'naïve Bayes')

## Building a pipeline

## Using metrics

## Parameter tuning

1. Why has this only give a .93 instead of .97?

We see comp.graphics is the only category to see a drop in prediction the other have improved.

## Conclusion

We can see that scikit learn can do a good job in classification with the amount of training and test data in this simple example.

1. Can you see a use in your project?
2. What issues can you see with the training and test data?  

## Links

### scikit-learn Tutorials

[http://scikit-learn.org/stable/tutorial/index.html](http://scikit-learn.org/stable/tutorial/index.html "sciket-learn Tutorials") 

### iPython site

[http://ipython.readthedocs.org/en/stable/](http://ipython.readthedocs.org/en/stable/ "IPython documentation")

### iPython keyboard shortcuts

[https://ipython.org/ipython-doc/1/interactive/notebook.html#keyboard-shortcuts](https://ipython.org/ipython-doc/1/interactive/notebook.html#keyboard-shortcuts "keyboard shortcuts")

### Others

[http://scipy.org](http://scipy.org)

[http://www.numpy.org](http://www.numpy.org)

[https://plot.ly/python/ipython-notebook-tutorial/](https://plot.ly/python/ipython-notebook-tutorial/)

[http://pandas.pydata.org/pandas-docs/stable/index.html](http://pandas.pydata.org/pandas-docs/stable/index.html)

[http://www.labri.fr/perso/nrougier/teaching/matplotlib/#simple-plot](http://www.labri.fr/perso/nrougier/teaching/matplotlib/#simple-plot)

[http://nbviewer.ipython.org/github/ipython/ipython/blob/1.x/examples/notebooks/Cell%20Magics.ipynb](http://nbviewer.ipython.org/github/ipython/ipython/blob/1.x/examples/notebooks/Cell%20Magics.ipynb "Magic functions")

[http://www.scipy.org/scipylib/index.html](http://www.scipy.org/scipylib/index.html)

[http://matplotlib.org/resources/index.html#books-chapters-and-articles](http://matplotlib.org/resources/index.html#books-chapters-and-articles)

### Useful commands

- ? - IPython’s features
- %quickref - Quick reference Card
- help - Python help
- object? - details about an object 
