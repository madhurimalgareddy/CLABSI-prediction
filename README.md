# CLABSI-prediction
## Table of Contents
- [Introduction](#introduction)
- [Technologies](#technologies)
- [Algorithms](#algorithms)
- [Approach](#approach)
- [Insights](#insights)

## Introduction
Central Line-Associated Bloodstream Infections (CLABSIs) are serious infections that occur when germs (bacteria or fungi) enter the bloodstream through a central line, which is a catheter placed in a large vein. Central lines are often used in hospitals to deliver medications, fluids, or nutrition, or to draw blood over an extended period. We had an opportunity to perform EDA on the patients data provided by Texas Children Hospital and further create a plan for modeling and evaluation of metrics. 

## Technologies
Project created using Python
* Python 3.9.12

## Algorithms
* KNN
* MLP(Multi-Layer Perceptron)
* Random Forest
* Adaline model

## Approach
* Started with Data cleaning and preprocessing. TCH dataset has large number of missing values and outliers which are handled using impute methods and robust scaler
* Imbalanced data is handled using SMOTE which increased accuracy 
* Once the data is cleaned up we have built four models and run to evaluate the results based on evaluation metrics
* Understanding the nature of Type I and Type II errors in this case.

## Insights
* Of all the models Random Forest seem to have better results 
