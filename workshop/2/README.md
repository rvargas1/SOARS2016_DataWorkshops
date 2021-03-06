# WORKSHOP 2
> The supreme accomplishment is to blur the line between work and play. ~ Arnold J. Toynbee

## Goals
* quick review of [exercises](https://github.com/NCAR/SOARS2016_DataWorkshops/tree/master/workshop/1/exercises) and my proposed [solutions]((https://github.com/NCAR/SOARS2016_DataWorkshops/tree/master/workshop/1/exercises/solutions.py))
* [Pandas](https://pandas.pydata.org) at a high level
* [Jupyter Notebooks](https://jupyter.org) (how to invoke from PyCharm + how to invoke from command line)
* [Series](http://pandas.pydata.org/pandas-docs/stable/dsintro.html#series) + [Dataframes](http://pandas.pydata.org/pandas-docs/stable/dsintro.html#dataframe)
* loading data into dataframes
* [indexing, slicing and filtering](http://pandas.pydata.org/pandas-docs/stable/indexing.html#indexing-and-selecting-data) a Dataframe to get the data of interest
* basic stats operations ([describe()](http://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.describe.html#pandas.DataFrame.describe), [mean()](http://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.mean.html#pandas.DataFrame.mean), [median()](http://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.median.html#pandas.DataFrame.median), etc.)
* [matplotlib](http://matplotlib.org/) (if there is time)


## Tools
In this workshop we're going to go little deeper into Python for scientific computing.  In particular, we're going to talk about Jupyter Notebooks and Pandas.


| Tool | Purpose |
|------|---------|
|Jupyter Notebooks (NB)|Jupyter Notebooks are a compact, interactive way to allow you to do EDA (Exploratory Data Analysis).  You can create notebooks that are private, share them on Github and [nbviewer](http://nbviewer.jupyter.org/)|
|Pandas|[Pandas](http://pandas.pydata.org/) is a Python library that allows you to do data manipulations and provides basic statistical tools to operate over that data.  It will save us a lot of time, and some of the text file contortions we did in Workshop 1 will not longer be necessary. |

## Jupyter NB in 10 minutes
Jupyter Notebooks are becoming the de facto tool these days for doing exploratory data analysis.  The easiest way to describe _what_ they are, is to put them into the context they belong.  Consider the scenario that you have some data, and you want to interactively explore that data -- but you want to do it in an environment that might:

1. provide you the ability to see and interact with the entire stream of your exploration in a single tool,
2. provide you the ability to interactively execute each part of your exploration as Python code, and also edit each step of your exploration (go back), if you need to,
3. provide you the ability to visualize you data inline with your other Python code while also providing the abiliy to export those visualizations,
4. provide you the ability to save, organize, edit and share your explorations with others, and
5. provide you the ability to include documentation inline with your code and visualizations, including mathematical symbols and formulae.

Well that's pretty much what Jupyter Notebooks are and much more!


