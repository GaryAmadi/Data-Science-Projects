# Wine Classification Notebook Summary

For this project, i explore some of the ways in which one can improve a model's performance.

I implement sklearn's logistic regression algorithm on its wine data set to predict origin based on chemical constituents by:

* **Scaling data** – Using the Standard Scaler, applying the z-score method, to avoid feature domination which could lead to biased classification.
* **Recursive Feature Elimination** – Applying RFE to identify and select the most important features in the dataset.
* **Wrapping the base model (logistic regressor) in the OneVsRestClassifier algorithm** – This allows use of the liblinear solver and also multi-class classification since the base model is a binary classifier.
* **Hyperparameter optimization** – Using Grid Search Cross-validation to identify the best possible parameters for the model's implementation.
* **Predictions** are made from the test data set, and various evaluation metrics used to evaluate the performance.


### Notebook Link
[Open Notebook](./Wine%20Classification.ipynb)
