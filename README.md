# Pyforest-for-Classification-Tasks
This repository contains examples of using Pyforest, a lazy-import Python library, for classification tasks. The repository demonstrates how to leverage Pyforest to reduce manual import overhead while working on popular classification problems using datasets such as Breast Cancer and Iris.

Project Overview

The main goal of this project is to show how Pyforest simplifies the import process when working on machine learning tasks. By using lazy loading of libraries, we reduce the need for multiple import statements, which results in cleaner and more readable code.
Included Files:

Introduction to Pyforest.ipynb
A simple introduction to Pyforest, demonstrating how it can be used to lazily load popular Python libraries such as pandas, numpy, matplotlib, and scikit-learn.
This notebook covers basic usage examples, such as data analysis and visualization, showing how Pyforest automatically imports libraries on demand.

Classifcation using Iris Dataset.ipynb
This notebook demonstrates how to perform a classification task using the famous Iris dataset.
The model used for classification is Support Vector Machine (SVM), and the task focuses on predicting the species of iris flowers based on petal and sepal measurements.
Pyforest is used to handle lazy imports of common libraries like pandas, matplotlib, seaborn, and scikit-learn.

Breast Cancer Classification.ipynb
This notebook tackles the problem of classifying breast tumors as either malignant or benign using the Breast Cancer dataset from sklearn.datasets.
The SVM algorithm with a linear kernel is used to classify the tumors.
The notebook demonstrates how Pyforest allows us to use libraries such as pandas, numpy, and sklearn without needing to manually import them.

Requirements
Python 3.6 or later
pyforest library for lazy imports
scikit-learn for machine learning algorithms
Jupyter Notebook or Jupyter Lab to run the .ipynb files
