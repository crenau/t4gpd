# t4gpd
Set of tools based on Python, GeoPandas and Shapely to achieve urban geoprocessing

## Pre-requisites
To be able to use the **t4gpd** plugin, perform geoprocessing and display your own maps, you need a Python3 interpreter and recent versions of the geopandas, matplotlib, numpy, and shapely libraries. One possibility is to install a [Miniconda3](https://docs.conda.io/en/latest/miniconda.html) environment, in which you will first create and then configure a new environment (we will call it gpd):
> conda create -n gpd

> conda activate gpd

> conda config --env --add channels conda-forge

> conda config --env --set channel_priority strict

> conda install descartes geopandas matplotlib networkx 

> conda install notebook numpy scikit-learn PyWavelets pysolar

## Installation instructions
Start by downloading the **t4gpd** latest version available from the [SourceSup website](https://sourcesup.renater.fr/projects/t4gs). Then, install the Python3 plugin you downloaded:
> pip install t4gpd-0.1.0.tar.gz

## Read the documentation
Go to [https://t4gpd-docs.readthedocs.io](https://t4gpd-docs.readthedocs.io) to consult the documentation.

