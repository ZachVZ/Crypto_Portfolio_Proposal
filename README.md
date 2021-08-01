# Crypto_Portfolio_Proposal
This notebook analyzes crypto investments and utilizes the KMeans to identify the clusters.
Below are the steps that will be performed in this notebook.
1. Cluster Cryptocurrencies with K-means
2. Find the Best Value for k
3. Optimize Clusters with Principal Component Analysis
4. Visualize the Results

## Technologies Require
* This project leverages python version 3.8.5
* sklearn Library
* scikit-learn 
* Project will be accomplished in JupyterLab

## Installation Guide and Running Jupyter Notebook
Installing Jupyter notebook
* On the terminal (Git Bash) under the conda dev environment, type the code below:

pip install jupyterlab

* To open the Jupyter notebook
Open a new Git Bash and type the below command into your conda dev environment:

jupyter lab

* then hit the ENTER key to run


## Required Imports
* pandas - data manipulation and analysis
* hvPlot - enables interactive plotting tools such as line and bar graphs
* KMeans -  unsupervised machine learning algorith 
* PCA - statistical technique to speed up machine learning algorithms when too many dimensions exist
* StandardScaler - removes the mean and scales each variable to unit variance 

## Install Guide
* import pandas as pd
* import hvplot.pandas
* from path import Path
* from sklearn.cluster import KMeans
* from sklearn.decomposition import PCA
* from sklearn.preprocessing import StandardScaler

## Usage
To use the JupyterLab notebook clone the repo and run git bash, open notebook crypto_investments.ipynb

### Contributors
Zach Zwiener

### Contact
Email - zachzwiener3@gmail.com

### License
MIT
