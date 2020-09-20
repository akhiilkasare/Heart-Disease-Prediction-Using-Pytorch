# Heart Disease prediction using Pytorch.

![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg) ![scikit-learnn](https://img.shields.io/badge/Library-Scikit_Learn-orange.svg) ![Pytorch](https://img.shields.io/badge/Library-Pytorch-yellow.svg)

![image](https://miro.medium.com/max/844/1*6nE1MADqsFutGS-MZeYXig.jpeg)

## Introduction

Heart diseases is a term covering any disorder of the heart.
Heart diseases have become a major concern to deal with as studies show that the number of deaths due to heart diseases have increased significantly over the past few decades in India, in fact it has become the leading cause of death in India.

A study shows that from 1990 to 2016 the death rate due to heart diseases have increased around 34 per cent from 155.7 to 209.1 deaths per one lakh population in India.

Thus preventing Heart diseases has become more than necessary.
Good data-driven systems for predicting heart diseases can improve the entire research and prevention process, making sure that more people can live healthy lives.
This is where Machine Learning comes into play.
Machine Learning helps in predicting the Heart diseases, and the predictions made are quite accurate.

Problem Description :

A dataset is formed by taking into consideration some of the information of 779 individuals.
The problem is : based on the given information about each individual we have to calculate that whether that individual will suffer from heart disease.

## Model Training and Prediction : 
We can train our prediction model by analyzing existing data because we already know whether each patient has heart disease. The trained model is then used to predict if users suffer from heart disease. The training and prediction process is described as follows:

## Splitting: 
First, data is divided into two parts using component splitting. In this experiment, data is split based on a ratio of 80:20 for the training set and the prediction set. The training set data is used in the logistic regression component for model training, while the prediction set data is used in the prediction component.


## Model Building:
After all the pre-processing of the data and feature selection our data is ready for model building. With the help of deep learning we will create a Neural Network with the help of Pytorch.


## Prediction:
The two inputs of the prediction component are the model and the prediction set. The prediction result shows the predicted data, actual data, and the probability of different results in each group.

## Evaluation: 
The confusion matrix, also known as the error matrix, is used to evaluate the accuracy of the model.

## Model Deployment:
After building the model our model is ready for deployment. But before deployment we need to convert our model into pickle file(.pt). After converting it to a (.pt) file we will be able to deploy our model over web sucessfully.

