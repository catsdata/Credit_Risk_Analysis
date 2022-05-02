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

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Resources

- Data Sources: 
    - [Loan Stats](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Resources/LoanStats_2019Q1.csv)
- Software:  
    - Supervised Machine Learning (mlenvs)
    - Pandas
    - SKLearn
    - IMlearn
    - Jupyter Notebook

## Results

### Oversampling - RandomOverSampler

<p>![acc1](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/accuracy1.PNG)</p>
<p>![conf1](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/confusion1.PNG)</p>
<p>![class1](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/classification1.PNG)</p>

### Oversampling - SMOTE

<p>![acc2](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/accuracy2.PNG)</p>
<p>![conf2](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/confusion2.PNG)</p>
<p>![class2](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/classification2.PNG)</p>

### Undersampling - ClusterCentroids

<p>![acc3](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/accuracy3.PNG)</p>
<p>![conf3](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/confusion3.PNG)</p>
<p>![class3](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/classification3.PNG)</p>

### Combination (over/under) - SMOTEENN

<p>![acc4](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/accuracy4.PNG)</p>
<p>![conf4](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/confusion4.PNG)</p>
<p>![class4](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/classification4.PNG)</p>

### Ensemble - BalancedRandomForestClassifier

<p>![acc5](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/accuracy5.PNG)</p>
<p>![conf5](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/confusion5.PNG)</p>
<p>![class5](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/classification5.PNG)</p>

### Ensemble - EasyEnsembleClassifier

<p>![acc6](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/accuracy6.PNG)</p>
<p>![conf6](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/confusion6.PNG)</p>
<p>![class6](https://github.com/catsdata/Credit_Risk_Analysis/blob/main/Images/classification6.PNG)</p>

Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

## Summary

Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
