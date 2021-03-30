# Predicting-the-Churn-of-Telecom-Users

Definition of Problem: This is a binary classification problem which predicts churn of a Telocom users in order to react in time to keep those who want to leave.

Dataset: The original dataset has 5986 examples with 22 columes. Only four (4) of the features are numeric, and the Target class is unbalanced. Please find the Metadata for the dataset at the bottom.

Data Cleansing & Exploratory Data Analysis: Although no 'missing values' in the dataset, several examples with empty string values in a feature had to be filtered out and dropped. The Exploratory Data Analysis and visualization revealed four (4) categorical features, each with a class that accounted for a greater proportion of churn within the feature's classes.

![pic1](https://user-images.githubusercontent.com/73043768/113038833-98b5c480-915c-11eb-9dec-556cb1882ef0.png)
![pic2](https://user-images.githubusercontent.com/73043768/113038844-9bb0b500-915c-11eb-9e17-10f958b96eb9.png)


Model Building: A Total of four (4) models using KNN, Random Forest, XGBoost, and Tensorflow's Keras Neural Network were used for the classification problem. The first 3 sets involved the use of GridSearch with Cross Vadilidation to search for the model's optimal hyperparameters. The neural network model was built with 2 hidden layers and a callback for early stopping to prevent overfitting.

Summary of Results: The XGBoost Model was chosen because it has the highest testing accuracy as shown below:

<img width="872" alt="Screen Shot 2021-03-30 at 2 02 25 PM" src="https://user-images.githubusercontent.com/73043768/113042367-b8e78280-9160-11eb-9363-6e42821ee41b.png">


Metadata:


<img width="838" alt="12B3593B-3B7C-454B-B064-F7DAFD03437B" src="https://user-images.githubusercontent.com/73043768/113038688-66a46280-915c-11eb-8781-cfe179993f4d.png">



















