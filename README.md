# Restaurant-price-predictor

### Aim - To determine average dining cost for two people in a restaurant using machine learning algorithms 

### Zomato Bangalore Dataset

Kaggle link: https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants


## About the dataset
This dataset contains information about the restaurants in multiple locations across Bangalore. The information includes the restaurant types, the variety of food choices available, the approximate cost for two people in a particular restaurant, etc. Also, the key factors that indicate the success quotient of a restaurant like rating, number of people who've caused the rating have also been listed in the dataset. Details about facilities like online order, advanced booking of tables has also been provided.

## Machine Learning algorithms

- ### Linear Regression
Since this is a regression problem, linear regression is an automatic choice although there are certain variables that do not have a linear relationship with the independent variable. 

- ### XGBoost 
 XGBoost is a type of boosting algorithm which can be used for this regression problem. This is a tree-based algorithm and it is an ensemble-based method. An ensemble-based model consists of several learners [models] and the prediction comes from a combination of all these learners. The main idea behind XGBoost is to boost the weak learners using gradient descent. And generally tree-based regression models run well on non-linear data and thus, we choose to go with this algorithm. Also, this has high speed and performance due to its optimization techniques for both software and hardware.

- ### Random Forests 
 This algorithm is also based on trees and an ensemble-based method. The key difference between Random Forests and XGBoost is Random Forests algorithm depends on Bagging. Bagging is a type of technique where a selected number of features are taken at random while predicting the outcome. Random Forest Regressors are widely used for regression problems as they handle non-linear data pretty well.

- ### Multi Layer Perceptrons 
This is a neural network based algorithm which generally performs well on both type of problems - classification and regression. The reason we are using this is because certain attributes seem to be non-linear with the target and MLPs generally tend to work well on non-linear data. 

- ### Support Vector Regression 
 This can be a good model for regression because this model tries to take into account only the data points that produce the least error rate. Thus, the possibilities of achieving a better learning fit using this model is high.
