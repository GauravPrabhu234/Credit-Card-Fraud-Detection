# Credit-Card-Fraud-Detection

**This project focuses on identifying fraudulent credit card transactions using various machine learning techniques. The dataset used contains a large number of transactions, including a small percentage of fraud cases. The main goal is to build an effective model that can distinguish between legitimate and fraudulent transactions with high accuracy. The project involves data preprocessing, exploratory data analysis, feature engineering, and the application of different classification algorithms.**

**In this project , first we differentiated the data sets into 0 and 1. 0 indicates the legit transaction and 1 indicates the fraudulent transactions  and made a new dataset named as legit sample and predicted the accuracy scores.**

**I used many different Scikit-learn Libraries** 
**1) from sklearn.model_selection import train_test_split:
This line imports the train_test_split function from the sklearn.model_selection module. The train_test_split function is used to split a dataset into two parts: a training set and a testing set. This is essential for evaluating the performance of a machine learning model by training it on one portion of the data and testing it on another.**


**2)from sklearn.linear_model import LogisticRegression:
This line imports the LogisticRegression class from the sklearn.linear_model module. Logistic Regression is a popular machine learning algorithm used for binary classification tasks. It models the probability that a given input belongs to a particular class, making it well-suited for tasks like fraud detection.**


**3)from sklearn.metrics import accuracy_score:
This line imports the accuracy_score function from the sklearn.metrics module. The accuracy_score function is used to calculate the accuracy of a classification model, which is the ratio of correctly predicted instances to the total instances in the dataset. It is a common metric for evaluating the performance of classification models.**
