# Credit-Risk-Analysis
Module 17 - Supervised Machine Learning

## Overview of the loan prediction risk analysis:

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Different techniques were used to train and evaluate models with unbalanced classes. Following are the libraries and algorithms that were used to build and evaluate models using resampling:

1. imbalanced-learn
2. scikit-learn
3. RandomOverSampler
4. SMOTE algorithms
5. ClusterCentroids algorithm
6. SMOTEENN algorithm
7. BalancedRandomForestClassifier (bias reduction model)
8. EasyEnsembleClassifier (bias reduction model)

## Purpose:

1. To determine how a machine learning algorithm is used in data analytics.
2. To create training and test groups from a given data set.
3. Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
4. Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
5. To determine which supervised learning algorithm is best used for a given data set or scenario.
6. To use ensemble and resampling techniques to improve model performance.

## Results:
The results for the six machine learning models including their respective balanced accuracy, precision, and recall scores are as follows:

## Naive Random Oversampling

<img width="701" alt="Screen Shot 2022-02-13 at 12 14 18 PM" src="https://user-images.githubusercontent.com/91294352/153766452-6512e082-b5e1-489c-b2b9-59ab66fd76f3.png">

## SMOTE Oversampling

## Undersampling

## Combination Under-Over Sampling

## Balanced Random Forest Classifier

## Easy Ensemble AdaBoost Classifier

## Summary:

The Easy Ensemble AdaBoost Classifier had the highest recall score, making it the final best machine learning model to choose for further credit card analysis.

1. When working with balanced accuracy, the highest compared accuracy between 0 and 1 and is closest to 1 is the best machine learning model.
2. For the credit card data set, the Easy Ensemble AdaBoost Classifier is the best model to choose with its .93 balanced accuracy. The other models were below .80 balanced accuracy. 
3. The precision for all models were similar and within an appropriate range. 
4. The recall score also needs to fall within 0 and 1, with numbers closer to 1 being the better model. 
