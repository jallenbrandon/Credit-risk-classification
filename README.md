# Module 12 Report Template


## Credit Risk Classification Analysis Overview:

This analysis aims to develop and assess machine learning models for credit risk classification, utilizing a dataset of historical lending activity from a peer-to-peer lending services company. The objective is to build models capable of discerning the creditworthiness of borrowers and categorizing the risk associated with loans.

The target variable for prediction is the loan status, while features such as loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, and total debt are utilized to predict this status.

The dataset contains two categories of loan_status: '0' representing healthy loans (with a count of 75,036) and '1' representing high-risk loans (with a count of 2,500).

# The machine learning process consists of the following stages:

Creation of label sets and feature DataFrame.
Splitting the data into training and testing datasets.
Utilizing logistic regression models for prediction.
Evaluation of model performance through accuracy scores, confusion matrices, and classification reports.
Two methods are employed:

Logistic Regression on the original data, with oversampling using RandomOverSampler to address imbalance.
Logistic Regression on data oversampled with RandomOverSampler.
Results:

# Machine Learning Model 1 - Logistic Regression:

Achieves high accuracy (99.18%) and balanced accuracy (95.20%) scores.
Precision is 100% for healthy loans and 85% for high-risk loans.
Recall is 99% for healthy loans and 91% for high-risk loans.
Machine Learning Model 2 - RandomOverSampler:

Shows improved accuracy (99.38%) and balanced accuracy (99.37%).
Precision is 100% for healthy loans and 84% for high-risk loans.
Recall is 99% for both healthy and high-risk loans.
# Summary:

RandomOverSampler method enhances model performance, especially in recall scores for high-risk loans.
Correct identification of high-risk loans is crucial for reducing default risks and ensuring profitability.
Recommending the use of RandomOverSampler for data resampling before logistic regression for improved accuracy and recall scores, vital for lending service companies' decision-making processes
