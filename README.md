# Employee-Performance-Analysis-Prediction

# 🎯Objective: 

📊 Employee Performance Analysis & Prediction🤖💡

Employee performance analysis is a process of analyzing employee data to identify patterns and trends that can help improve employee productivity, engagement, and retention.

* 🎯 The primary aim of this project is to find the important feature affecting the performance rating and to predict the performance rating of Employees.

## 🔍 Data Cleaning:

* Dataset(Source: IABAC).
* Dealt with the null values, duplicates, data type of columns.

## 📊 Exploratory Data Analysis (EDA) :

1. Univariate Analysis: In univariate analysis I get the unique labels of categorical features, as well as get the range & density plots

2. Bivariate Analysis: In bivariate analysis I checked the features relationship with target variable.

3. Multivariate Analysis: In multivariate analysis I checked the relationship between two variable with respect to the target variable.

Insights: Some features are positively correlated with performance rating they are:Emp Environment Satisfaction, Emp Last Salary Hike Percent, Emp Work Life Balance
4. Correlation
5. Checked Skewness and Kurtosis of Numerical Features

## 🔍 Data Pre-Processing:

1. Checked Missing Value
2. Used frequency encoding for Categorical Features
3. Imputed outliers with the help of IQR 
4. Used Square Root Transformation technique in the features where skewness & kurtosis are present.
5. Scaled the data with the help of Standard scalar

## ⚙️ Feature Selection: 

1. Dropped unique and constant features
2. The dataset has 27 features, reduced dimensions using PCA

## 🤖 Model Training and Evaluation:

- The data is imbalance, so balanced the data with the help of SMOTE
- Applied Support vector machine algorithm to built the model

## ⚙️ Hyperparameter Tuning:
- Used GridSearchCV to improve its performance and get the best hyperparameters for the model 

## 💡 Model Evaluation:

- Model well performed on training data with accuracy 96.61% but the test score is 94.66 after applying Hyperparameter tunning score is 98.28.

### 🚀 Conclusions: 
This project provides valuable insights for organizations aiming to improve employee productivity and performance. By understanding the key factors influencing performance ratings and leveraging predictive analytics, businesses can implement targeted interventions, training programs, and policies to foster a conducive work environment and maximize employee potential.
