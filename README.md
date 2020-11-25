# Credit_Risk_Analysis

## Overview of Project

In this module, we are given a data set of credit card information and our goal is to apply machine learning models to solve the problem: find the best model to predict credit card risk

The challenge for this assignment is that: the number of good loan and the number risk loan is imbalanced. This will cause standard machine learning model does not perform well, as they will learn that the minority class ( risky loan) is not as important as the majority class ( good loan) and put more attention and perform better on the good loan.Thus we will pay attention to resample the dataset, either oversampling or under-sampling it. In this assignment, we used 6 different strategy to resolve this problem.

## Results
To better compare the performance of each models, we have listed the below result from each model:

### Naive random oversampling algorithm
![](screenhot/1.png)

### SMOTE algorithm
![](screenhot/2.png)

### Cluster Centroids algorithm
![](screenhot/3.png)

### Combination (Over and Under) Sampling
![](screenhot/4.png)

### Balanced Random Forest Classifier
![](screenhot/5.png)

### Easy Ensemble AdaBoost classifier
![](screenhot/6.png)

## Summary

Based on the above screenshot,Balanced Random Forest Classifier and Easy Ensemble AdaBoost classifier obviously outperformed than the others. The improvement on the accuracy and robustness, as well as decrease variance of the model, and therefore increase the overall performance of the model, is due to the concept of ensemble learning: the process of combining multiple models, like decision tree algorithms. In addition to that, using random forest algorithm is beneficial because it works against overfitting as all of those weak learners are trained on different pieces of the data and it is robust to outliers and nonlinear data. And it run efficiently on large datasets.
