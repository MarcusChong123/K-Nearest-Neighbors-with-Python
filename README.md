# K-Nearest-Neighbors-with-Python
We are going to learn step by step how to use K-Nearest Neighbors with Python to make prediction. For full article, https://learndatascienceskill.com/index.php/2020/08/06/k-nearest-neighbors-with-python/

Today, I want to demonstrate an K-Nearest Neighbors example with using Python. K-Nearest Neighbors (KNN) is a supervised machine learning which can be used for regression and classification. Basically, KNN learns from labelled data sets and classifies new data points based on similarity or so called nearest neighbors.

In order to identify the nearest neighbors, KNN calculates the Euclidean Distance of an unknown data point to its neighbors. Depending on the number of neighbors (K) that is being specified, the unknown point will be classified to a category based on the majority in the neighbors. Normally, K has to be odd number in order to avoid confusion to the machine. As a rule of thumb, we can use square root of n to set the first value of K, where n is the total number of data points.

If you have a large data set with vast variety of variables, it is not advisable to use KNN as the computation will be very slow. One thing to also take note is that KNN is a lazy learner and it does not actually learn from the train data set. Instead, it uses for the training data itself for the purpose of classification of the unknown data.

In this tutorial, I will show you how to perform Machine learning with Python using K-Nearest Neighbors (KNN), with the example of predicting the possibility of getting heart attack based on some features such as maximum heart rate achieved, resting blood pressure, etc. I will show you step by step of:

1. How to load the data into Google Colab notebook
2. How to explore the data
3. How to pre-process the data
4. How to split the data into train and test data
5. How to train the model and evaluate the model
6. How to do prediction with using test data

You can also download the dataset at:
https://www.kaggle.com/nareshbhat/health-care-data-set-on-heart-attack-possibility
