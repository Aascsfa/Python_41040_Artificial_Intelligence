# 41040 Artificial Intelligence

## Problem and Context
This project focuses on evaluating the effectiveness of a direct marketing campaign for a Portuguese bank using machine learning. The goal is to predict whether a customer subscribed to a term deposit after the campaign. The dataset, available on Kaggle, includes over 45,000 rows and 17 attributes.

## Importance of Customer Term Deposits
In the aftermath of the 2008 Global Financial Crisis, customer confidence in banks was low, impacting the bank's liquidity. Sufficient customer term deposits are crucial for the bank to maintain operations, comply with regulations, and lend money. The bank seeks to identify factors influencing customers' decisions to subscribe to term deposits.

## Project Necessity
Manual analysis of such a large dataset would be resource-intensive and time-consuming. Machine learning offers an efficient alternative by identifying patterns and predicting customer behavior based on their attributes. The model developed can also be adapted for similar future scenarios.

## Solution Approach
The solution involves using a random forest classifier to predict customer subscriptions. Although this approach is a "black-box" model, it effectively minimizes prediction errors by computing multiple decision trees. The steps taken include importing and exploring the dataset, preprocessing and cleaning the data, splitting the data into training, testing, and validation sets, constructing and training the model, and finally, evaluating and fine-tuning the model to improve performance.
