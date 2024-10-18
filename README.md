# Loan Eligibility Prediction for Home Credit

## Project Overview
This project aims to predict the loan eligibility of applicants for Home Credit based on a variety of customer data. Using machine learning models, the goal is to identify high-risk borrowers and reduce the likelihood of default. The project uses a structured pipeline for data preprocessing, feature engineering, and model evaluation, applying several algorithms to achieve the best performance in predicting loan eligibility.

## Key Features
### Data Preprocessing: Handling missing values, outliers, and categorical variables, ensuring a clean dataset for modeling.
### Feature Engineering: Creating new features such as CREDIT_INCOME_RATIO and EXT_SOURCE_MEAN to improve model accuracy.
### Modeling: Applying machine learning models such as Random Forest, K-Nearest Neighbors (KNN), and Support Vector Machine (SVM) to predict loan eligibility.
### Performance Evaluation: Using accuracy, AUC, and other metrics to evaluate model performance, with Random Forest yielding the best results.

## Dataset
The dataset was sourced from the Home Credit Default Risk competition on Kaggle and includes over 300,000 data points with 217 features. Key data includes:

Loan Amount
Applicant Income
Credit History
Employment Duration
External Credit Scores

## Project Structure
The project follows the CRISP-DM framework and is divided into several key stages:

### Exploratory Data Analysis (EDA):
Analyzing distributions and relationships between key variables.
Visualizing data trends with graphs and heatmaps.

### Feature Engineering:
Creating new features based on existing ones (e.g., CREDIT_INCOME_RATIO).
Selecting relevant features using correlation analysis and domain knowledge.

### Data Preprocessing:
Imputing missing values, handling outliers, and encoding categorical variables.
Scaling numerical features for better model performance.

### Modeling:
Training models such as Random Forest, KNN, and SVM.
Performing hyperparameter tuning to optimize model performance.

### Model Evaluation:
Evaluating models based on accuracy, AUC, and F1-score.
Random Forest achieved the best performance with an accuracy of 96.5% and an AUC of 96.4%.
