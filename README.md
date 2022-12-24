# Welcome to my Machine Learning Projects!
These projects are a collection of fundamental ML algorithms that serve as an introduction to various ML applications. This repo is meant to serve as a 
home for ML algorithms as I come across them in my learning process. Hopefully, it will be a good way for myself and others to view my progress. 
Previously, this code was hosted locally, but it has since migrated to this Git repository.

## Summary of projects

### (1) Housing.ipynb: Predicting California housing prices
- Pipeline, clean, and split data into training, validation, and test sets
- Make predictions using Linear Regressors, Decision Tree Regressors, and Random Forest
- Evaluate algorithms with root mean squared error (RMSE)
- Evaluate using k-Fold Cross Validation
- Use GridSearchCV to determine best hyperparameters

### (2) TrainingModelsLinReg.ipynb: Stone Laying Problem + Linear and Logistic Regression
- Given a variety of different stones and an area to cover, determine the best arrangement of stones in order to cover the most area
- This program was developed to advise a contractor on how to lay various stones in a backyard

- Explore various ways to fit equations to linear and polynomial data, including:
- (1) Normal Equation
- (2) Gradient Descent (Stochastic, Mini-Batch, Standard)
- (3) Gradient Descent w/ Regularization (Ridge, Lasso)

- use Early Stopping to prevent overtraining
- Logistic and Softmax Regression for classification tasks

### (3) Classification.ipynb: MNIST
- Understanding precision vs. recall
- Uses Multiclass Classifiers 
- Achieves better than 97% accuracy on the MNIST dataset
- Uses data augmentation to generate data (shifting digit images in MNIST)
- Predicts survivorship on the Titanic

### (4) SupportVectorMachines.ipynb: Half-Moons Dataset Classifier
- Uses a Support Vector Machine Classifier to perform classification on the half-moons dataset

### (5) DecisionTrees.ipynb: 
- Uses decision tree classifiers to classify for a multiclass classification task
- Uses an ensemble of DecisionTrees to create a Random Forest classifier

### (6) Ensemble Learning and Random Forests.ipynb: 
- Combines individual ML algorithms into an ensemble to improve performance
- uses scikit-learn's BaggingClassifier

## Extras: Just for Fun
- unival_tree.py: Function to recursively count the number of unival trees within a binary tree
- xor_ll.py: Implementation of an XOR Linked List, a more memory efficient data structure compared to the standard linked list

























