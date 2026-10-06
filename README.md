# 📊 Predictive Analytics Using Historical Data

## 📌 Project Overview

This project focuses on using historical customer data to analyze customer behavior and predict **customer churn** using Machine Learning.

The **Telco Customer Churn dataset** is analyzed through data preprocessing, exploratory data analysis, feature engineering, and machine learning. A **K-Nearest Neighbors (KNN)** classification model is used to predict whether a customer is likely to **stay or churn**.

## 🎯 Objectives

* Analyze historical customer data
* Identify factors associated with customer churn
* Clean and preprocess the dataset
* Perform exploratory data analysis
* Transform categorical data into numerical features
* Scale features for machine learning
* Build a KNN classification model
* Evaluate model performance using classification metrics

## 🗂️ Dataset

**Dataset:** Telco Customer Churn

* Rows: 7,043
* Columns: 21
* Target variable: `Churn`
* `Yes` → Customer churned
* `No` → Customer stayed

### Important Features

* Customer tenure
* Monthly charges
* Total charges
* Contract type
* Payment method
* Internet service
* Online security
* Tech support
* Senior citizen status
* Partner and dependents

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## 🔄 Project Workflow

```text
Historical Customer Data
          ↓
Data Loading
          ↓
Data Cleaning
          ↓
Exploratory Data Analysis
          ↓
Feature Engineering
          ↓
Categorical Encoding
          ↓
Feature Scaling
          ↓
Train-Test Split
          ↓
KNN Model
          ↓
Prediction
          ↓
Model Evaluation
```

## 🤖 Machine Learning Model

### K-Nearest Neighbors (KNN)

KNN is a supervised machine learning classification algorithm. It predicts the class of a customer by comparing the customer with nearby data points based on feature similarity.

The model is trained using the prepared customer data and predicts whether a customer will:

* **Churn**
* **Not Churn**

## 📈 Model Evaluation

The model is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics help understand how effectively the model predicts customer churn.

## 📁 Project Structure

```text
Predictive-Analytics-Using-Historical-Data/
│
├── WA_Fn-UseC_-Telco-Customer-Churn.csv
├── Predictive_Analytics.ipynb
├── README.md
└── requirements.txt
```

## 💡 Key Insights

The analysis helps identify customer characteristics and service-related factors that are associated with a higher likelihood of churn.

Predictive analytics can help businesses identify customers who may leave and take preventive actions such as improving services, providing personalized offers, or addressing customer concerns.

## 🚀 Future Improvements

* Compare KNN with Logistic Regression, Decision Tree, Random Forest, and XGBoost
* Perform hyperparameter tuning
* Handle class imbalance
* Improve model accuracy
* Create an interactive Power BI or Streamlit dashboard
* Deploy the prediction model as a web application

## 👩‍💻 Author

**Sujitha Suresh**

B.Tech Artificial Intelligence and Data Science

GitHub: [sujitha-data](https://github.com/sujitha-data)
