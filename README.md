# Predictive Analytics for Transport Success

Implementing various machine learning algorithms for binary classification

## Table of Contents
- [Project Description](#project-description)
- [Dataset Overview](#dataset-overview)
- [Implemented Models](#implemented-models)
- [Result](#result)
- [Contributors](#contributors)

 
## Project Description

Welcome to this comprehensive guide on binary classification with the Spaceship Titanic dataset. The objective is to predict whether a passenger was transported to an alternate dimension during the Spaceship Titanic's collision with a spacetime anomaly.

## [Dataset Overview](https://www.kaggle.com/competitions/spaceship-titanic/data)

- PassengerId - A unique Id for each passenger. Each Id takes the form gggg_pp where gggg indicates a group the passenger is travelling with and pp is their number within the group. People in a group are often family members, but not always.

- HomePlanet - The planet the passenger departed from, typically their planet of permanent residence.

- CryoSleep - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to their cabins.

- Cabin - The cabin number where the passenger is staying. Takes the form deck/num/side, where side can be either P for Port or S for Starboard.

- Destination - The planet the passenger will be debarking to.

- Age - The age of the passenger.

- VIP - Whether the passenger has paid for special VIP service during the voyage.
RoomService, FoodCourt, ShoppingMall, Spa, VRDeck - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.

- Name - The first and last names of the passenger.
Transported - Whether the passenger was transported to another dimension. This is the target, the column you are trying to predict.

## Implemented Models

1. Logistic Regression
- Logistic Regression is one of the most basic statistical methods used for binary classification, where it models the probability that a given input belongs to one of two possible classes, employing a logistic function to map inputs to outputs.
2. Support Vector Classifier (SVC)
- SVC is a supervised machine learning algorithm that finds the optimal hyperplane in a high-dimensional space to classify data points into different classes, aiming to maximize the margin between them.
3. Decision Tree and Random Forest
- A Decision Tree is a hierarchical model that splits the dataset into subsets based on the value of input features, aiming to classify or predict the target variable. Random Forest, on the other hand, is an ensemble learning method that constructs multiple decision trees and combines their predictions to improve accuracy and reduce overfitting.
4. Neural Network
- A neural network (NN) is a computational model inspired by the structure and function of the human brain, composed of interconnected nodes arranged in layers. It's trained using algorithms to learn complex patterns in data and make predictions or decisions.
5. LGBMclassifier
- LGBMClassifier stands for LightGBM Classifier. LightGBM is a gradient boosting framework that uses tree-based learning algorithms. It is designed for distributed and efficient training, particularly suited for large datasets.
6. XGBoost
- XGBoost, which stands for eXtreme Gradient Boosting, is a popular open-source machine learning library known for its high performance and effectiveness in handling structured data. It is an implementation of gradient boosted decision trees designed for speed and performance.

## Result

Among all the models, the LGBMclassifier shows the highest accuracy and AUC score, with a relatively quick training process.

![image](https://github.com/yzhang1999/Predictive-Analytics-for-Transport-Success/assets/145066585/17c5844b-3794-4997-b0fc-3e3c21918c53)

## Contributors
- Yumin Zhang
- Xinran Wang
- Kevin Li
- Siyan Li

