# Credit Risk Analysis

**Table of Contents**

1. [Overview](https://github.com/catsdata/Credit_Risk_Analysis#overview)
2. [Resources](https://github.com/catsdata/Credit_Risk_Analysis#resources)
3. [Results](https://github.com/catsdata/Credit_Risk_Analysis#results)
    - [Oversampling - Random](https://github.com/catsdata/Credit_Risk_Analysis#oversampling---randomoversampler)
    - [Oversampling - SMOTE](https://github.com/catsdata/Credit_Risk_Analysis#oversampling---smote)
    - [Undersampling - Cluster](https://github.com/catsdata/Credit_Risk_Analysis#undersampling---clustercentroids)
    - [Combination - SMOTEENN](https://github.com/catsdata/Credit_Risk_Analysis#combination-overunder---smoteenn)
    - [Ensemble - Balanced Forest](https://github.com/catsdata/Credit_Risk_Analysis#ensemble---balancedrandomforestclassifier)
    - [Ensemble - Easy](https://github.com/catsdata/Credit_Risk_Analysis#ensemble---easyensembleclassifier)
4. [Summary](https://github.com/catsdata/Credit_Risk_Analysis#summary)


## Overview

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill has asked us to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, we oversampled the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. We then used a combinatorial approach of over- and undersampling using the SMOTEENN algorithm.  To reduce bias, we compared two new machine learning models, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 

## Resources

- Data Sources: 
    - [Loan Stats](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Resources/LoanStats_2019Q1.csv)
- Software/Packages:  
    - Supervised Machine Learning (mlenvs)
        - Pandas
        - SKLearn
        - IMlearn
    - Jupyter Notebook

## Results

### Oversampling - RandomOverSampler

- Accuracy 64.1%
- High Risk Precision 0.01
- High Risk Recall 0.60

![acc1](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/accuracy1.PNG)

![conf1](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/confusion1.PNG)

![class1](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/classification1.PNG)

### Oversampling - SMOTE

- Accuracy 63.8%
- High Risk Precision 0.01
- High Risk Recall 0.60

![acc2](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/accuracy2.PNG)

![conf2](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/confusion2.PNG)

![class2](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/classification2.PNG)

### Undersampling - ClusterCentroids

- Accuracy 63.7%
- High Risk Precision 0.01
- High Risk Recall 0.62

![acc3](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/accuracy3.PNG)
    
![conf3](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/confusion3.PNG)
    
![class3](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/classification3.PNG)

### Combination (over/under) - SMOTEENN

- Accuracy 59.5%
- High Risk Precision 0.01
- High Risk Recall 0.70

![acc4](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/accuracy4.PNG)

![conf4](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/confusion4.PNG)

![class4](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/classification4.PNG)

### Ensemble - BalancedRandomForestClassifier

- Accuracy 78.8%
- High Risk Precision 0.04
- High Risk Recall 0.67

![acc5](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/accuracy5.PNG)

![conf5](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/confusion5.PNG)

![class5](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/classification5.PNG)

### Ensemble - EasyEnsembleClassifier

- Accuracy 92.5%
- High Risk Precision 0.07
- High Risk Recall 0.91

![acc6](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/accuracy6.PNG)

![conf6](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/confusion6.PNG)

![class6](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/classification6.PNG)

Scores to look out for are the highest Accuracy, precision and recall.  The lower the numbers, the higher chances of false results.

## Summary

![summary](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/summary.PNG)

As seen from above, the over and undersampling all stayed fairly consistent with results; however the ensemble algorithms performed substantially better, with the Easy Ensemble Classifier providing the most accurate results and should be used for this credit analysis.

