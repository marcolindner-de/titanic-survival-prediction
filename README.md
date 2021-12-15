# Readme

## About

This repository holds a Jupyter Notebook you can read [here](https://github.com/marcolindner-de/titanic-survival-prediction/blob/main/titanic-survival-prediction.ipynb).

It is based on the [Data Science Tutorial](https://code.visualstudio.com/docs/datascience/data-science-tutorial) from the [Visual Studio Code documentation](https://code.visualstudio.com/docs). It uses the [Titanic dataset](https://hbiostat.org/data/repo/titanic.html) available on [OpenML.org](https://www.openml.org/d/40945), which is obtained from [Vanderbilt University's Department of Biostatistics](https://hbiostat.org/data/). The Titanic data provides information about the survival of passengers on the Titanic, as well as characteristics about the passengers such as age and ticket class. Using this data, the goal is to establish a model (using a neural network) for predicting whether a given passenger would have survived the sinking of the Titanic. It will use scikit-learn, Keras and TensorFlow.

## Prerequisites

The notebook was build using Python 3.9.2. If you want to rebuild it, you can set up a virtual Python environment using the requirements.txt filethat contains the output of `pip freeze` from the virtual environment. In particular, you will need to install the following packages: jupyter, pandas, seaborn, scikit-learn, keras, and tensorflow.