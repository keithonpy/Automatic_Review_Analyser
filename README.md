# Automatic Review Analyser

The goal of the project is to design a classifer to use for sentiment analysis of product reviews. The training set consists of reviews written by Amazon customers for various food products. The reviews, which is originally given on a 5 point scale, have been adjusted to be +1 or -1 scale representing a positive or negative review respectively.


`classifier.py`: algorithm for linear classifiers - perceptron algorithm, average perceptron algorithm and Pegasos algorithm.

`utils.py`: functions for loading data, plotting results and hyperparameters tuning.

`test.py`: test cases to test the classifiers

`stopword.txt`: a list of stop words.
