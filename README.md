Social-Networks-Ads
Logistic Regression
Logistic regression is a classification algorithm used to assign observations to a discrete set of classes. Unlike linear regression which outputs continuous number values, logistic regression transforms its output using the logistic sigmoid function to return a probability value which can then be mapped to two or more discrete classes.

for more -https://ml-cheatsheet.readthedocs.io/en/latest/logistic_regression.html

K Nearest Neighbors
The model representation for KNN is the entire training dataset.

It is as simple as that.

KNN has no model other than storing the entire dataset, so there is no learning required.

Efficient implementations can store the data using complex data structures like k-d trees to make look-up and matching of new patterns during prediction efficient.

Because the entire training dataset is stored, you may want to think carefully about the consistency of your training data. It might be a good idea to curate it, update it often as new data becomes available and remove erroneous and outlier data.

KNN works well with a small number of input variables (p), but struggles when the number of inputs is very large.

Dataset can be downloaded from - https://www.kaggle.com/rakeshrau/social-network-ads#Social_Network_Ads.csv

Our Goal is to predict whether a person will be able to buy a car depending upon his age and his salary
Using Logistic Regression we achived an accuracy of - 0.875

Using K Nearest Neighbours we achived an accuracy of - 0.9166666666666666
