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

![acc1](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/accuracy1.PNG)

![conf1](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/confusion1.PNG)

![class1](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/classification1.PNG)

### Oversampling - SMOTE

![acc2](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/accuracy2.PNG)

![conf2](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/confusion2.PNG)

![class2](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/classification2.PNG)

### Undersampling - ClusterCentroids

![acc3](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/accuracy3.PNG)
    
![conf3](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/confusion3.PNG)
    
![class3](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/classification3.PNG)

### Combination (over/under) - SMOTEENN

![acc4](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/accuracy4.PNG)

![conf4](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/confusion4.PNG)

![class4](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/classification4.PNG)

### Ensemble - BalancedRandomForestClassifier

![acc5](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/accuracy5.PNG)

![conf5](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/confusion5.PNG)

![class5](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/classification5.PNG)

### Ensemble - EasyEnsembleClassifier

![acc6](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/accuracy6.PNG)

![conf6](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/confusion6.PNG)

![class6](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/classification6.PNG)

Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

## Summary

Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
