# Credit_Risk_Analysis

## Overview

The purpose of this excercise was to gain familiarity with supervised machine learning. In this particular example, we used various models to determine the credit risk of loans.

## Results

Overview of results
- Highest accuracy score: Easy Ensemble Classifier
- Lowest accuracy score: SMOTE Oversampling
- Highest precision score: Easy Ensemble Classifier

**Naive Random Oversampling:**

![Naive Random Oversampling](https://github.com/niklasax/Credit_Risk_Analysis/blob/main/Screen%20Shot%202021-02-14%20at%206.48.05%20PM.png "Naive Random Oversampling")

**SMOTE oversampling:**

![SMOTE oversampling](https://github.com/niklasax/Credit_Risk_Analysis/blob/main/Screen%20Shot%202021-02-14%20at%206.57.03%20PM.png "SMOTE Oversampling")


**Undersampling using ClusterCentroids**

![Undersampling using ClusterCentroids](https://github.com/niklasax/Credit_Risk_Analysis/blob/main/Screen%20Shot%202021-02-14%20at%207.03.08%20PM.png "Undersampling using ClusterCentroids")


**Combination sampling using SMOTEENN**

![Combination sampling using SMOTEENN](https://github.com/niklasax/Credit_Risk_Analysis/blob/main/Screen%20Shot%202021-02-14%20at%207.03.46%20PM.png "Combination sampling using SMOTEENN")

**Balanced Random Forest Classifier using Balanced Random Forest**

![Balanced Random Forest Classifier using Balanced Random Forest](https://github.com/niklasax/Credit_Risk_Analysis/blob/main/Screen%20Shot%202021-02-14%20at%207.38.37%20PM.png "Balanced Random Forest Classifier using Balanced Random Forest")

**EasyEnsembleClassifier**

![EasyEnsembleClassifier](https://github.com/niklasax/Credit_Risk_Analysis/blob/main/Screen%20Shot%202021-02-14%20at%207.45.52%20PM.png "EasyEnsembleClassifier")

## Summary

In this particular exercise, Easy Ensemble Classifier was the best overall model to predict loan status. It had an accuracy score of 94% and a precision score of 99%. Out of 17000+ observations in the data set there were only 8 false negative predictions and less than 1000 false positive predictions, which, in the context of insurance risk profiling seems to accetpable.
