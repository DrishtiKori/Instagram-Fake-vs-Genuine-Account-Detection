# Instagram Fake Account Detection using Machine Learning

## Project Overview

Fake and spam accounts are a major challenge for social media platforms. These accounts are often used for spreading misinformation, scams, and artificial engagement.

This project builds a **machine learning classification model to detect fake Instagram accounts** using account-level features such as follower counts, engagement metrics, and profile characteristics.

The goal is to develop a model that can help identify suspicious accounts and improve platform integrity.

---

## Problem Statement

Social media platforms face increasing problems due to fake or spam accounts. These accounts can manipulate engagement metrics, spread misinformation, or conduct fraudulent activities.

The objective of this project is to **develop a machine learning model that can classify Instagram accounts as fake or genuine based on account metadata.**

---

## Dataset Description

The dataset contains Instagram account features such as:

- Follower count  
- Following count  
- Engagement indicators  
- Profile characteristics  

### Target Variable

`fake`

- **1 → Fake account**
- **0 → Genuine account**

The dataset allows the model to learn patterns that differentiate fake accounts from genuine users.

---

## Project Workflow

The project follows a structured machine learning workflow:

1. Data Understanding  
2. Data Cleaning  
3. Exploratory Data Analysis (EDA)  
4. Feature Preparation  
5. Train-Test Split  
6. Model Training  
7. Model Evaluation  
8. Feature Importance Analysis  

---

## Exploratory Data Analysis (EDA)

EDA was performed to better understand the dataset and identify important patterns.

Key objectives included:

- Analyzing the distribution of fake vs genuine accounts  
- Exploring relationships between features  
- Identifying potential predictors of fake accounts  

Visualization techniques used:

- Histograms  
- Correlation heatmaps  
- Scatter plots  
- Feature distribution plots  

---

## Feature Engineering

Feature preparation steps included:

- Removing unnecessary columns  
- Handling missing values  
- Preparing data for machine learning models  

Feature scaling was applied where necessary to improve model performance.

---

## Modeling

Multiple machine learning models were trained and compared:

- **Dummy Classifier** (Baseline model)
- **Logistic Regression**
- **Random Forest Classifier**

The **Random Forest model** was selected as the final model due to its superior classification performance.

---

## Model Evaluation

The model was evaluated using the following metrics:

- **F1 Score**
- **Confusion Matrix**
- **Classification Report**

These metrics help evaluate both **precision and recall**, which are important when detecting fake accounts.

---

## Key Results

The trained model successfully distinguishes between **fake and genuine Instagram accounts** using account-level features.

Feature importance analysis revealed that certain engagement and profile metrics are strong indicators of fake accounts.

---

## Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

### Tools
- Jupyter Notebook
