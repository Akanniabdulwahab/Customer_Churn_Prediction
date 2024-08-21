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
This involved importing the dataset, ivestigated if the features are in their correct datatypes, converting features into their correct datatypes, checked the shape of the dataset, investigated the missing values, visualizing the missing values, dropping off missing datapoint, performed statistical analysis of numerical & categorical datapoints.

## Exploratory Data Analysis (EDA)
- Univariate Analysis: Exploring each features individually.
- Bivariate Analysis: Exploring each features against the profit feature.
- Multivariate Analysis: Exploring two or more features against the profit feature.

## Data Preprocessing
Extensive data-preprocessing was performed. This included handling missing values, droppig off redundant features, adding extra features for better analysis, encoded the categorical features in the data, scaled the dataset, Handling data imbalance in the dataset. 

## Machine Learning Models
The Customer Churn prediction model is built using a supervised machine learning approach. Training and test data was split 80:20. Several algorithms were experimented
- **SGDClassifier**
- **KNeighborsClassifier**
- **Random Forest Classifier**
- **Logistics Regression**
- **XGBClassifier**
- **Support Vector Classifier (SVC)**
- **GaussianNB**
- **DecisionTreeClassifier**

After several experimentation and careful examination of each model, the best performing model which is Random Forest Classifier was selected.

## Evaluation Metrics
To assess the performance of a machine learning model, the following evaluation metrics were used:
- **Accuracy**
- **F1-Score**

## Recommendation
- Design and implement personalized retention initiatives. These strategies may include offering special incentives, enhancing customer service, or improving product offerings to address specific pain points.
- Incorporate customer feedback mechanisms to gather qualitative insights, which can be used to further refine predictive models and retention strategies.

## Conclusion
The development of a customer churn prediction system is essential to improve the company's customer retention efforts. By leveraging machine learning and advanced analytics, ConnectTel can accurately identify customers at risk of churning and proactively implement targeted interventions. This approach will not only reduce churn but also enhance customer satisfaction, thereby ensuring long-term business sustainability and growth. This project highlights the importance of data-driven decision-making in addressing critical business challenges and optimizing customer retention strategies.
