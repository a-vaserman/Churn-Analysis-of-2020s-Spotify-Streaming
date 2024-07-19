# Churn Analysis for Spotify 2020s Streaming

## Project Overview

This project focuses on performing a churn analysis for Spotify, a leading music streaming service. Churn, also known as customer attrition rate, is the percentage of customers who stop using/purchasing a company's product/service over a period of time. The objective is to identify factors contributing to user churn, predict which users are likely to churn, and provide actionable insights to reduce churn rates. By analyzing user activity, subscription details, and engagement metrics, I aim to develop a predictive model that helps Spotify retain its customer base.

**Objectives**
1. **Understand Churn Dynamics**: Identify key factors that influence user churn in the context of Spotify's streaming service.
2. **Predict Churn**: Develop a predictive model to classify users as likely to churn or not
3. **Provide Recommendations**: Offer actionable insights and strategies to reduce churn based on the analysis.

## Data Collection
**Spotify API**: Collect data on user activity, tracks, and other relevant information using the Spotify Web API
**Kaggle Datasets**: Utilize publicly available datasets from platforms like Kaggle to supplement the analysis.
**Simulated Data**: Create synthetic datasets mirroring Spotify's data structure if necessary.

## Data Preparation
1. **Loading Data**: Load the collected datasets into Pandas DataFrames for analysis.
2. **Data Cleaning**: Handle missing values, remove duplicates, and standardize data formats.
3. **Feature Engineering**: Create new features such as subscription duration, total listening time, and average daily listening time.

## Exploratory Data Analysis (EDA)
**Descriptive Statistics**: Calculate basic statistics to understand the data distribution.
**Visualizations**: Use histograms, bar charts, and heatmaps to identify patterns and correlations.
**Churn Definition**: Define churn as users who did not renew their subscription and create a binary churn variable.

## Model Building
1. **Feature Selection**: Identify and select relevant features for the churn prediction model.
2. **Data Splitting**: Split the data into training and testing sets.
3. **Model Training**: Train a logistic regression model to predict churn.
4. **Model Evaluation**: Evaluate the model's performance using accuracy, precision, recall, F1 score, and confusion matrix.

## Evaluation and Reporting

**Confusion Matrix**: Visualize the confusion matrix to understand model performance
**Feature Importance**: Identify and plot feature importances to understand which factors contribute most to churn.
**Recommendations**: Provide insights and strategies to reduce churn based on the model's findings.

## Tools and Technologies

**Programming Languages**: Python
**Libraries**: NumPy, Matplotlib, Seaborn, Scikit-learn, Spotipy
**Data Visualization**: Power BI, Tableau
**Documentation**: Jupyter Notebooks, GitHub

## Expected Outcomes

**Predictive Model**: A trained and validated model that accurately predicts user churn.
**Insights**: Identification of key factors that influence user churn.
**Actionable Strategies**: Recommendations to reduce churn and improve user retention


