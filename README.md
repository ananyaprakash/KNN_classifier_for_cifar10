# KNN_classifier_for_cifar10
An experiment to perform knn classification on cifar10 dataset

The kNN classifier consists of two stages:

During training, the classifier takes the training data and simply remembers it
During testing, kNN classifies every test image by comparing to all training images and transfering the labels of the k most similar training examples
The value of k is cross-validated

Final classifier accuracy at 28.2%
