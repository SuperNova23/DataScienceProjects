# DataScienceProjects

# Project 1: End-to-End Multi-Class Breed Classification
This notebook builds an end-to-end multi-class image classifier using TensorFlow 2.0 and TensorFlow Hub

### 1. Problem
Identifying the breed of a dog given an image of a dog

When I am at a friends house and take a photo of their dog, I want to know what breed of dog it is.

### 2. Data
The Data we are using is from Kaggle's dog breed identification compitition https://www.kaggle.com/c/dog-breed-identification/data?select=test

### 3. Evaluation
The evaluation is a file with a prediction probablities for each dog breed of each test image

### 4. Features
Some information about the data: *We're dealing with images(unstructured data) so it's probably beest we use deep learning/transfer learning.

There are around 10,000 + images in the training set.(these images have labels)
There are arouind 10,000 plus images in the test set.(these images have no labels because we want to predict them)

# Project 2: Predicting Heart Disease Using Machine Learning 

This notebook liiks into various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes 

We're going to take the following approach:
1. Problem Definition 
2. Data 
3. Evaluation
4. Features 
5. Modeling 
6. Experimentation 

### 1. Problem Definition 

In a statement, 
> Given clinical parameters about a patient, can we predict whether or not they have heart disease?

### 2. Data

The original data came from the Cleavland data from the UCI Machine Learning Repository.
https://archive.ics.uci.edu/ml/datasets/Heart+Disease

There is also a version of it available on Kaggle. https://www.kaggle.com/ronitf/heart-disease-uci

### 3. Evaluation 

>If we can reach 95% accuracy at predicting whether or not a patient has heart disease during the proof of concept, we'll pursue the project.

### 4. Features 

This is where you'll get different information about each of the features in your data. 

# Project 3: Predicting The Sales Price of Bulldozers Using Machine Learning

In this notebook, we are going to go through an example machine learning project with the goal of predicting the sale price of bulldozers

### 1. Problem Definition

Our goal is to use a machine learning model to predict the price of bulldozers in the future

### 2. Data
I downloaded the data from Kaggle Bluebook for a Bulldozers competition: https://www.kaggle.com/c/bluebook-for-bulldozers/data

There are three main datasets:

Train.csv is the training set, which contains data through the end of 2011.
Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 You make predictions on this set throughout the majority of the competition. Your score on this set is used to create the public leaderboard.
Test.csv is the test set, which won't be released until the last week of the competition. It contains data from May 1, 2012 - November 2012. Your score on the test set determines your final rank for the competition.

### 3. Evaluation
The evaluation metric for this competition is the RMSLE (root mean squared log error) between the actual and predicted auction prices.

For more information on the evaluation of this project check: https://www.kaggle.com/c/bluebook-for-bulldozers/overview/evaluation

The goal for most evaluation metrics is to minimize the error. For example, our goal for this project will be to build a machine learning model which minimises RMSLE

### 4. Features
You can find an online version of the data dictionary for this dataset at: https://www.kaggle.com/c/bluebook-for-bulldozers/data
