# Cat-Classifier
This repository contains code and datasets for simple cat image classification.<br/>
The code is written in python and uses numpy package. Python notebook (.ipynb) file contains the code.<br/>

# Logistic Regression
To classify cats from images, simple logistic regression classifier is used. The accuracy achieved on test set is approximately  70% and that on training set is 99.04%. This is the case of overfitting as the classifier ovrfits the training set.<br/>
Though the accuracy on test set is very low, it's ok as dataset is small and very simple classifier is used.

# 2 Layer Neural Network
Extending the above model to a 2 layered Neural Network having a hidden layer of size 7 units(RELU Activated) and a sigmoid output unit.<br>
This Model gives an accuracy of 100% on the training set but only 72% on the test set. This is clearly the case of overfitting on the training set.<br>

# 5 Layer Neural Network
Extending the 2 Layered Neural Network to a 5 Layered Network to decrease variance and improve test accuracy.<br>
The network consists of 4 hidden units all RELU Activated and a sigmoid output unit.<br>
This model gives an accuracy of 98.5% on training set and 80% on the test set.
