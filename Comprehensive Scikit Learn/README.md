# Comprehensive Scikit Learn Notebook Summary

### Overview
In this notebook, various sklearn algorithms are fitted to various datasets in an attempt to create basic classification and regression models.

### Some of the procedures implemented include:
* **Model:** Random Forest Regressor

**Model Fit 1**
* The data is imported
* Non-numerical features are converted to numbers using the One Hot Encoder
* The model is then fitted   

**Model Fit 2**
* Scikit learn's simple imputer is used to handle missing data before fitting the model
* Various algorithms are fitted to the data for practice purposes, such as:
    * Linear SVC
    * K-Neighbors classifier
    * Random Forest classifier

**Classification Evaluation Metrics**
Below are some of the evaluation metrics used to measure the classification algorithm's performance:
* Accuracy
* Area under ROC (Receiver Operating Characteristic) curve
* Confusion matrix
* Classification report (Precision, Recall & F-1 score)

**Regression Evaluation Metrics**
For the regression algorithm, here are some of the metrics used:
* R^2 score (Coefficient of determination)
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)

**A data pipeline is then used at the end of the notebook in an attempt to streamline the algorithm's implementation.**

**Environment:** Developed in a Conda environment using Python.

[Open Notebook](./Comprehensive%20Scikit%20Learn.ipynb)
