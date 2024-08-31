# CODTECH_ML_02

### Overview of the Project

**Name:** SAVITHA K <br>
**Company:** CODTECH IT SOLUTIONS <br>
**ID:** CT4ML6033 <br>
**Domain:** Machine Learning <br>
**Duration:** August 01, 2024 to September 01, 2024 <br>

### Objective

The objective of this project is to make a predictive model to detect fraudulent credit card transactions.

### Key Activities

- **Data Cleaning:** Ensuring the dataset is free from inconsistencies and missing values.
- **Data Visualization:** Creating visualizations to understand data distributions, trends, and relationships.
- **Model Building and Training:** Building a model and training it on the given data.
- **Model Evaluation:** Evaluading the performance of the model to analyze its efficiency and accuracy in making predictions.

### Technologies used

- **Python**: The primary programming labguage for data science.
- **pandas**: Used for manipulation and analysis
- **numpy**: Used for manipulating arrays
- **matplotlib**: Employed for creating static, animated, and interactive visualizations.
- **seaborn**: Utilized for making statistical graphics that are informative and attractive.
- **sklearn**: Used for the model building, training and evaluating tasks.

This project provides a comprehensive overview of model making process for anomaly detection. These models are useful for detecting fraudulent transactions.

## Credit Card Fraud Detection

![image](https://github.com/user-attachments/assets/754f9667-76f9-442e-b9d5-ba9e515240cd)

csv file link: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/data

## Observations :

- Isolation Forest detected 73 errors versus Local Outlier Factor detecting 97 errors vs. SVM detecting 8516 errors
- Isolation Forest has a 99.74% more accurate than LOF of 99.65% and SVM of 70.09
- When comparing error precision & recall for 3 models , the Isolation Forest performed much better than the LOF as we can see that the detection of fraud cases is around 27 % versus LOF detection rate of just 2 % and SVM of 0%.
- So overall Isolation Forest Method performed much better in determining the fraud cases which is around 30%.
- We can also improve on this accuracy by increasing the sample size or use deep learning algorithms however at the cost of computational expense.We can also use complex anomaly detection models to get better accuracy in determining more fraudulent cases
