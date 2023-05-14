# Customer Churn Analytics
![](https://d35fo82fjcw0y8.cloudfront.net/2017/09/26225705/header%402x.png)
## Introduction

Churn prediction means detecting which customers are likely to leave a service or to cancel a subscription to a service. It is a critical prediction for many businesses because acquiring new clients often costs more than retaining existing ones. Once you can identify those customers that are at risk of cancelling, you should know exactly what marketing action to take for each individual customer to maximise the chances that the customer will remain.
Let's look into the dataset and explore Churn Analytics!

## About the dataset

This competition is about predicting whether a customer will change telecommunications provider, something known as "churning".

The training dataset contains 4250 samples. Each sample contains 19 features and 1 boolean variable "churn" which indicates the class of the sample. The 19 input features and 1 target variable are:

1.  "state",  _string_. 2-letter code of the US state of customer residence
2.  "account_length",  _numerical_. Number of months the customer has been with the current telco provider
3.  "area_code",  _string_="area_code_AAA" where AAA = 3 digit area code.
4.  "international_plan",  _(yes/no)_. The customer has international plan.
5.  "voice_mail_plan",  _(yes/no)_. The customer has voice mail plan.
6.  "number_vmail_messages",  _numerical_. Number of voice-mail messages.
7.  "total_day_minutes",  _numerical_. Total minutes of day calls.
8.  "total_day_calls",  _numerical_. Total minutes of day calls.
9.  "total_day_charge",  _numerical_. Total charge of day calls.
10.  "total_eve_minutes",  _numerical_. Total minutes of evening calls.
11.  "total_eve_calls",  _numerical_. Total number of evening calls.
12.  "total_eve_charge",  _numerical_. Total charge of evening calls.
13.  "total_night_minutes",  _numerical_. Total minutes of night calls.
14.  "total_night_calls",  _numerical_. Total number of night calls.
15.  "total_night_charge",  _numerical_. Total charge of night calls.
16.  "total_intl_minutes",  _numerical_. Total minutes of international calls.
17.  "total_intl_calls",  _numerical_. Total number of international calls.
18.  "total_intl_charge",  _numerical_. Total charge of international calls
19.  "number_customer_service_calls",  _numerical_. Number of calls to customer service
20.  "churn",  _(yes/no)_. Customer churn - target variable.

## Table of contents

-  Data Preprocessing
    -   Importing data
    -   Identifying NA values
    -   Descriptive Statistics
-  Exploratory Data Analysis


## Exploratory Data Analysis

I have done Exploratory Data Analysis on this dataset using various plots such as Pie plot, Countplot, Stacked bar plot, Scatterplot, Kdeplot, Box plot, Distribution plot, etc.

Following are the various insights that we draw from the dataset:

   - Amount of churned customers
   - Customer optiong for voice mail plan
   - Customers opting for International Plan
   - Account length grouped by International Plan Enrollment
   - Account length grouped by Voice Mail Plan Enrollment
   - Area-wise count of customers
   - Count of number of Customer Service Calls
   - State-wise count of customers
   - Count of International Plan differentiated by churned customers
   - Count of Voice Mail Plan differentiated by churned customers
   - Count of number of customer service calls differentiated by Churned customers
   - Relationship between Total day charge and Total night charge
   - Total night charges by churn
   - Total day charges by churn
   - Total Evening charges by churn
   - Area-wise number of Day Calls
   - Churn and Total International Charge
   - Total night calls categorized by international plan
   - Comparison of Number of customer service calls distribution vs Customer Churn
   - Account length of customers based upon Churn status
   - Total International Charge by the Account length range
   - Number of voice mail messages w.r.t Account length range
  
 Now, we did some pre-processing by seperating categorical and numerical columns in seperate variables and analyzed based upon the following plots:

- Heatmap
- Wordcloud

## Decision Tree Modelling

For the modelling part, following steps were followed:

- Encoding categorical columns into numerical columns
- Splitting the data into TRAIN and TEST
- Plotting the decision tree
- Checking the training and testing accuracy
  > **Training Accuracy: 87.66%**
  > **Testing Accuracy: 85.80%**

 - Plotting the confusion matrix for training and testing
   * Training Confusion Matrix
   * Testing Confusion Matrix
