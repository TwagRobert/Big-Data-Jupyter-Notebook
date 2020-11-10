# Installation

Base requirements:
- [Python 3](https://www.python.org/downloads/).8 or newer
- Required Python packages
  - pandas
  - textmining3
  - wordcloud
  - matplotlib
  - mlxtend
  - graphviz
  - scikit-learn
- [Jupyter](https://jupyter.org/)
- [graphviz](http://graphviz.org/)

## For Windows

### Set up using Anaconda

The most straightforward way to install the requirements if you do not already have Python 3 installed is to download and install [Anaconda for Python 3](https://www.anaconda.com/download/). 

Download and install [graphviz](http://graphviz.org/download/) for Windows.

## For Mac OSX

### Set up using Anaconda

The most straightforward way to install the requirements if you do not already have Python 3 installed is to download and install [Anaconda for Python 3](https://www.anaconda.com/download/). 

Download and install [graphviz](http://graphviz.org/download/) for Mac OSX.

## For all

Download or `git clone` this repository to your computer.

Create a new Conda environment from the provided `environment.yml` file. From the command-line, type:

    conda env create -f environment.yml

Activate the newly created Conda environment:

    conda activate lab1
    
You can then launch Jupyter from the Anaconda Navigator application.