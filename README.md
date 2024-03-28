# Breast-Cancer-Detection

Data: [Link](https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.data)

Description: [Link](https://archive.ics.uci.edu/ml/machine-learning-databases/breast-cancer-wisconsin/wdbc.names)

In this task, I experimented with various machine learning models including decision trees, logistic regression, k-nearest neighbors, and support vector machines to predict the diagnosis result based on ten real-valued features (mean, standard error, and "worst" or largest of these features). I explored the performance of different models across several parameter values.

This approach aimed to identify instances of overfitting and underfitting to optimize predictive performance. Apart from manual hyperparameter optimization, I employed nested cross-validation with multiple hyperparameters in grid search. This strategy aimed to maximize the utilization of different sub-datasets in the training data, potentially reducing the risk of overfitting.
