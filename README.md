#  **Customer Churn Prediction Using Logistic Regression**

##  **Project Overview**
This project focuses on building a **Customer Churn Prediction Model** using **Logistic Regression**. The goal is to predict whether a customer will churn based on factors like tenure, payment method, contract type, and monthly charges. The dataset is preprocessed, balanced using **SMOTE**, and optimized with **GridSearchCV**.

---

## **Dataset Information**
- **Source:** [Telco Customer Churn Dataset on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Target Variable:** `Churn` (`Yes` or `No`)
- **Key Features:**  
   - `tenure`: Number of months the customer has stayed with the company  
   - `Contract`: Type of contract (Month-to-month, One year, Two years)  
   - `PaymentMethod`: Method of payment  
   - `MonthlyCharges`: Amount charged monthly  
   - `TotalCharges`: Total amount charged  

---

## **Project Workflow**

### 🔹 **1. Data Preprocessing**
- Encoded categorical features using **LabelEncoder**.  
- Handled missing values.  
- Balanced dataset using **SMOTE**.  
- Standardized numerical features with **StandardScaler**.  

### 🔹 **2. Exploratory Data Analysis (EDA)**
- Visualized churn distribution.  
- Identified correlations between features using heatmaps.  
- Analyzed key features affecting churn.  

### 🔹 **3. Model Building**
- Trained a **Logistic Regression** model.  
- Tuned hyperparameters using **GridSearchCV** with cross-validation.  

### 🔹 **4. Model Evaluation**
- Used metrics like **Accuracy**, **Precision**, **Recall**, **F1-Score**, and **ROC-AUC Score**.  
- Visualized evaluation results using **Confusion Matrix** and **ROC Curve**.  
