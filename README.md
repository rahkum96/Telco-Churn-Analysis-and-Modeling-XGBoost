# Telco-Churn-Analysis-and-Modeling-XGBoost
![image](https://user-images.githubusercontent.com/86415241/141137806-2d182c32-4848-4465-b8a8-0206c79957ce.png)

## Problem statement
- There are promotional charges called as Acquisition Cost and Retention Cost in a telco company. The cost of acquiring new consumers is referred to as acquisition cost. Meanwhile, the expense of retaining existing clients is known as Retention Cost.
- We are frequently inaccurate in our predictions of which customers would churn and which ones will stay due to human limitations. As a result, the allocation of money may be incorrect, resulting in a higher amount of funds being issued.
- Moreover, according to some sources, the acquisition cost is 5x greater than the retantion cost. If we are wrong in predicting a customer who will actually churn, but it turns out that we predict as a customer who will retain, then we need to spend more than it should be.

## What to do
I will try to create a Machine Learning model to predict customer churn and retantion.

## Goal
Machine Learning has a goal so that cost allocation can be done as precisely as possible.

## Value
There is no wasted cost allocation.

## Modules needed:
```
- xgboost
- Pandas
- Scikit-Learn &
- Numpy
- seaborn
- GridsearchCv
```


## Usage

- Just run `jupyter notebook` in terminal and it will run in your browser.

  Install Jupyter [here](http://jupyter.readthedocs.io/en/latest/install.html) i've you haven't.

- install xgboost by using `pip install xgb` in command line prompt/ anconda  i've you haven't.

## Model performance
- I have acheived model accuracy 78%, but the goal is predict the correctly classified who, left the comapany, means we have more focused on recall, (82%)

               precision    recall  f1-score   support

           0       0.92      0.72      0.81      1294
           1       0.52      0.82      0.64       467

## Model summary
- 77% AUC indicates model is correct on nearly 4 out of 5 customers cases
- 83% Recall means model predicts 83% of customer churn cases correctly
- 52% Precision means model predicts nearly 1 in 2 false positives 

## Dataset:
https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113

