# clustertree_resourcemodelling

# Lithological Classification and Uncertainty Analysis with Unsupervised Machine Learning

This is a project for lithological classification and uncertainty analysis in diamond drilling data using unsupervised machine learning techniques. The goal of this project is to create a classification model that can predict lithology from chemical variables, and evaluate the uncertainty associated with the model's predictions.

The dataset used in this project consists of diamond drilling data with chemical variables, such as fe_gl, sio2_gl, mn_gl, mgo_gl, cao_gl, p2o5_gl, ppc_gl, and tio2_gl. 

The target lithologies are hematites and itabirites of different types in an iron deposit. Clustering techniques like k-means clustering, agglomerative hierarchical clustering, and dual spatial clustering (Martin and Boisvert, 2018) were used to compute the uncertainty by comparing the classifications of the algorithms with the original classification. The lithological classification was done in a nested way, classifying each lithology separately. 

The source code for this project is named clustertree.ipynb, which includes data preprocessing, clustering and visualization of the results. Along with this file, other codes for validation plots and exploratory data analysis are also included.


# Requirements

To run the project, you need to have the following libraries installed:

NumPy
Pandas
Scikit-learn
Matplotlib
Seaborn
Spatial Cluster


# How to run the project

Clone this repository on your local machine.
Open the Jupyter Notebook file named clustertree.ipynb.
Run each cell of the notebook in the order presented.
Visualize the results in the results visualization section.

# Author

This project was created by joaolague as part of your final project for your course.
