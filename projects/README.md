# Project: Classify wine as 'good' 'bad'

## Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [seaborn](https://seaborn.pydata.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)


## Code

The code is provided in the `Wine.ipynb` notebook file. The dataset file `winequality-red.csv` is also provided. 

## Run

In a terminal or command window, navigate to the top-level project directory `machine_learning/` (that contains this README) and run one of the following commands:

```bash
ipython notebook Wine.ipynb
```  
or
```bash
jupyter notebook Wine.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

## Data

The Red wine quality dataset consists of 1599 data points, with each datapoint having 11 features. This dataset can be found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/wine+quality).

**Features**
<br/>Input variables (based on physicochemical tests):
<br/>1 - fixed acidity
<br/>2 - volatile acidity
<br/>3 - citric acid
<br/>4 - residual sugar
<br/>5 - chlorides
<br/>6 - free sulfur dioxide
<br/>7 - total sulfur dioxide
<br/>8 - density
<br/>9 - pH
<br/>10 - sulphates
<br/>11 - alcohol




**Target Variable**
<br/>Output variable:
<br/>12 - quality (classified as 0/bad or 1/good)
