# Customer Segmentation and Churn Prediction using Machine Learning

## Overview

This project focuses on analyzing customer behavior and predicting customer churn using Machine Learning techniques. The goal is to help businesses identify customers who are likely to leave their services and understand different customer groups through segmentation.

The project uses the Telco Customer Churn dataset and combines Customer Segmentation using K-Means Clustering with Churn Prediction using a Random Forest Classifier. Various data preprocessing, exploratory data analysis, model evaluation, and customer risk assessment techniques have been applied to generate meaningful business insights.

---

## Problem Statement

Customer retention is one of the most important challenges faced by subscription-based businesses. Acquiring a new customer is often more expensive than retaining an existing one. Therefore, identifying customers who are likely to churn and understanding their behavior can help organizations implement effective retention strategies.

This project aims to:

1. Segment customers based on their usage and spending patterns.
2. Predict whether a customer is likely to churn.
3. Identify high-risk customers.
4. Generate business insights to improve customer retention.

---

## Dataset Information

Dataset: Telco Customer Churn Dataset

The dataset contains customer demographic information, subscription details, service usage information, billing information, and churn status.

Key Features:

* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure Months
* Phone Service
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Streaming Services
* Contract Type
* Payment Method
* Monthly Charges
* Total Charges
* Churn Value

Target Variable:

* Churn Value

  * 1 = Customer Churned
  * 0 = Customer Retained

---

## Technologies Used

Programming Language:

* Python

Libraries:

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* OpenPyXL

Development Environment:

* VS Code
* Jupyter Notebook
* Google Colab

---

## Project Workflow

### 1. Data Collection

The Telco Customer Churn dataset is loaded from an Excel file and examined for structure, missing values, and data types.

### 2. Data Preprocessing

The following preprocessing steps were performed:

* Handling missing values
* Converting Total Charges to numeric format
* Removing unnecessary columns
* Encoding categorical variables
* Feature scaling
* Data cleaning

### 3. Exploratory Data Analysis

EDA was performed to understand customer behavior and churn patterns.

Visualizations include:

* Churn Distribution
* Gender vs Churn
* Contract Type vs Churn
* Monthly Charges Distribution
* Tenure Analysis
* Correlation Heatmap

### 4. Customer Segmentation

K-Means Clustering was applied to group customers based on:

* Tenure Months
* Monthly Charges
* Total Charges

The Elbow Method was used to determine the optimal number of clusters.

Customer segments help businesses understand different customer categories and target them more effectively.

### 5. Churn Prediction

A Random Forest Classifier was used to predict customer churn.

Steps involved:

* Train-Test Split
* Model Training
* Hyperparameter Tuning using GridSearchCV
* Prediction Generation

### 6. Model Evaluation

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* ROC Curve
* AUC Score

### 7. Risk Analysis

Churn probabilities were generated for every customer.

Customers were categorized into:

* High Risk
* Medium Risk
* Low Risk

This helps businesses prioritize customer retention efforts.

---

## Machine Learning Models Used

### K-Means Clustering

Purpose:

* Customer Segmentation

Benefits:

* Groups similar customers together
* Helps identify valuable customer segments

### Random Forest Classifier

Purpose:

* Churn Prediction

Benefits:

* Handles large datasets effectively
* Provides feature importance analysis
* Produces robust predictions

---

## Results

The project successfully:

* Segmented customers into meaningful groups.
* Predicted customer churn using machine learning.
* Identified high-risk customers.
* Generated customer risk scores.
* Produced actionable business insights.

Important observations:

* Customers with shorter tenure are more likely to churn.
* Month-to-month contract customers show higher churn rates.
* Customers with higher monthly charges tend to have a greater risk of churn.
* Long-term customers generally contribute higher lifetime value.

---

## Business Recommendations

### High Risk Customers

* Provide personalized retention offers.
* Offer contract upgrades.
* Provide loyalty rewards.

### Medium Risk Customers

* Send targeted promotional campaigns.
* Improve customer engagement.

### Low Risk Customers

* Upsell premium services.
* Cross-sell additional products.

---

## Project Structure

Customer-Segmentation-and-Churn-Prediction

├── Telco_customer_churn.xlsx

├── Customer_Segmentation_Churn_Prediction.ipynb

├── customer_churn_results.csv

├── README.md

└── requirements.txt

---

## How to Run the Project

1. Clone the repository.

2. Install required dependencies:

pip install pandas numpy matplotlib seaborn scikit-learn openpyxl

3. Place the dataset file in the project directory.

4. Run the notebook or Python script.

5. Review generated visualizations and results.

---

## Future Enhancements

* Deploy the model using Flask or FastAPI.
* Create an interactive dashboard using Streamlit.
* Use advanced algorithms such as XGBoost and LightGBM.
* Integrate real-time churn monitoring.
* Automate customer retention recommendations.

---

## Author

Somil Dholakia

B.Sc Computer Science Student

MERN Stack Developer | Machine Learning Enthusiast | Open Source Contributor

LinkedIn: linkedin.com/in/somilsomi

GitHub: github.com/somildholakia
