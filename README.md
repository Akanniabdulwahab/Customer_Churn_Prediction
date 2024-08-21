# Customer_Churn_Prediction

![image](https://github.com/user-attachments/assets/3ff73a4f-d5c4-47ee-95a6-8fcda7891687)

## Table of Cotents
- [Project Overview](#project-overview)
- [Project Objective](#project-objective)
- [Data Overview](#data-overview)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-EDA)
- [Data Preprocessing](#data-preprocessing)
- [Machine Learning Models](#machine-learning-models)
- [Evaluation Metrics](#evaluation-metrics)
- [Recommendation](#recommendation)
- [Conclusion](#conclusion)

## Project Overview
This Telecom Company is facing a critical challenge in retaining its customers, which directly impacts its business sustainability and growth. The existing customer retention strategies are not sufficiently precise, leading to the loss of valuable customers to competitors.

## Project Objective
To develop a robust customer churn prediction system by leveraging advanced analytics and machine learning techniques on available customer data, the company seeks to accurately forecast customer churn and implement targeted retention initiatives. This proactive approach will enable the company to reduce customer attrition, enhance customer loyalty, and maintain a competitive edge in the highly dynamic and competitive telecommunications industry

## Data Overview
This involved importing the dataset, ivestigated if the features are in their correct datatypes, converting features into their correct datatypes, checked the shape of the dataset, investigated the missing values, visualizing the missing values, performed statistical analysis of numerical & categorical datapoints.

## Exploratory Data Analysis (EDA)
- Univariate Analysis: Exploring each features individually.
- Bivariate Analysis: Exploring each features against the profit feature.
- Multivariate Analysis: Exploring two or more features against the profit feature.

## Data Preprocessing
Extensive data-preprocessing was performed. This included handling missing values, droppig off redundant features, adding extra features for better analysis, encoded the categorical features in the data, scaled the dataset. 

## Machine Learning Models
The employee salary prediction model is built using a supervised machine learning approach. Training and test data was split 80:20. Several algorithms were experimented
- **Linear Regression**
- **DecisionTree Regressor**
- **Support Vector Regression (SVR)**
- **GradientBoosting Regressor**

After several experimentation and hyperparameter tuning, the best performing model was selected.

## Evaluation Metrics
To assess the performance of a machine learning model, the following evaluation metrics were used:
- **R-Squared score**
- **Mean square score**
- **RMSE score**

## Recommendation
Continuous Improvement of model: Implement a feedback loop where the model can be continuously improved and updated with new data. This will ensure that the salary prediction system remains relevant and accurate over time.

## Conclusion
This project aims to provide a robust predictive model that accurately estimates employee salaries based on various factors, including education level, attributions, and other relevant features. By identifying and analyzing the key determinants of salary, the project will offer valuable insights into the relationship between employee characteristics and compensation. These insights can aid HR professionals in making data-driven decisions related to compensation strategies, employee retention, and talent management, ultimately contributing to a more informed and equitable workplace.
