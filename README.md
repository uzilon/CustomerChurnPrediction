# CustomerChurnPrediction

![image](https://github.com/uzilon/CustomerChurnPrediction/assets/111258660/e3c0bb5e-0a36-4494-b0b5-2f39685558f9)


## Table of contents
- [Project Overview](#project-overview)
- [Project Objective](#project-objective)
- [Data Sources](#data-sources)
- [Data Cleaning and Explorative Data Analysis](#data-cleaning-and-explorative-data-analysis)
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning](#machine-learning)
- [Evaluation Metrics](#evaluation-metrics)
- [Conclusion and Recommendation](#conclusion-and-recommendation)


## Project Overview

ConnectTel Telecom Company faces the pressing need to address customer churn, which poses a significant threat to its business sustainability and growth. 

## Project Objective

This project aims aims to develop a robust customer churn prediction system for which will enable ConnectTel to reduce customer attrition, enhance customer loyalty, and maintain a competitive edge

## Data Sources 

The dataset used in this project was provided by 10alytics. The Dataset contains a collection of 20 features obtained form ConnectTel including a unique customer ID, 18 Independent features and the predictive feature (Churn)

## Data Cleaning and Explorative Data Analysis

Dataset was investigated and it was discovered that the feature Total Charges had an object datatype instead of float. It was converted to float

Univariate, Bivariate and Multivariate Data Analysis was carried out and Key Insights were recorded.

### Univariate Analysis
- Total number of records was 7043, out of which they recorded a 26% (1864) churning
- Most of the Customers (83%) were not Senior Citizens
- Most of the Customers (70%) had no Dependents
- Most of the Customers (90%) had Phone Service
- Most of the Customers (43%) use fibre optics for internet service
- 49% for the most of the customers had no online security
- 44% for the most of the customers had no online backup
- 44% for the most of the customers had no Device Protection
- 49% for the most of the customers had no tech support
- 55% for the most of the customers were on a month to month contract
- 34% for the most of the customers used electronic check

### Univariate Analysis
Most of the customer that churned

- Used fibre optics
- had no online security
- had no device protection
- had no online backup
- had no tech support
- were on a month to month contract
- used electronic check

### Multivariate Analysis

- Total Charges and Tenure had a strong positive correlation of 0.85 i.e Tenure increases with Total Charges
- Total Charges and Monthly had a positive correlation as well of 0.65

## Data Preprocessing

Label Encoding was carried out on all Categorical Variable while the Min Max Scaler was used on numeric variable to deal with outliers

## Machine Learning 

Dataset was trained on the following six models 
- Random Forest
- K-Nearest Neighbour
- SGD  
- SVC
- Decision Tree
- Logistic Regression

## Evaluation Metrics

Among the six models trained for this project, the Logistic Regression model produced the highest accuracy of 81.55%. In computing the confusion matrix, it also gave the lowest error in predicting customers that have churned.

## Conclusion and Recommendation

To reduce percentage Customer Churn, we recommend ConnectTel Telecom look into the following areas;

- Optimize their internet fibre optic service .
- Encourage customers who have internet service to equally have an online security, online backup and device protection.
- Provide tech support.
- Regular Promotions to encourage customers to move from  month to month contract to one or two years plan.
