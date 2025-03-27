# Machine_learning
Description:

This project explores how different kernel functions influence the performance of a Support Vector Machine (SVM) classifier using the Breast Cancer dataset from scikit-learn. The tutorial provides insights into hyperparameter tuning, feature scaling, and model evaluation.

Dataset:

Breast Cancer Dataset (569 samples, 30 features, 2 target classes: malignant & benign)
Source: scikit-learn’s load_breast_cancer
Key Components:

Data preprocessing using StandardScaler
Kernel experiments:
linear
poly (degree=3)
rbf (Radial Basis Function)
sigmoid
Performance evaluation:
Accuracy
Confusion matrix
Classification report
Visualization of results:
Decision boundaries
Accuracy vs. kernel function
Learning curves
GridSearchCV for advanced hyperparameter tuning
Best Model Configuration:

Kernel: rbf
C: 1.0
Gamma: scale
Accuracy: Achieved over 98% accuracy on the test set
Tools Used:

Python 3.x
scikit-learn
matplotlib
seaborn
pandas, numpy
How to Run:

Open the notebook (.ipynb file) in Jupyter Notebook or Google Colab and execute the cells sequentially.

Author:

Rahul yadav suresh

References:

UCI Machine Learning Repository
Scikit-learn Documentation
Vapnik, V. (1998). Statistical Learning Theory
