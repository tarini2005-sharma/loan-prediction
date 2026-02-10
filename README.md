# Loan Prediction Project

## 📌 Project Overview
This project predicts whether a loan application will be **approved or not** using machine learning classification techniques.

The model is trained on historical loan data containing applicant details such as income, loan amount, credit history, and property area.

---

## 🎯 Objective
To build a **classification model** that predicts:
- **Loan Approved (Y)**
- **Loan Not Approved (N)**

---

## 🧠 Machine Learning Type
- **Supervised Learning**
- **Classification**

---

## 📊 Dataset
The dataset contains information such as:
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Gender
- Married
- Education
- Self_Employed
- Property_Area
- Loan_Status (Target variable)

---

## 🛠️ Steps Performed

### 1. Data Cleaning
- Handled missing values:
  - Numerical columns → filled using **mean**
  - Categorical columns → filled using **mode**
- Checked and analyzed outliers

### 2. Feature Engineering
- Converted categorical variables using **One-Hot Encoding (get_dummies)**
- Dropped unnecessary columns

### 3. Model Building
- Split data into training and validation sets
- Trained a **Logistic Regression** classification model

### 4. Model Evaluation
- Accuracy score used for evaluation
- Predictions generated on test data

### 5. Final Output
- Predicted loan status saved in a CSV file

---

## 📈 Libraries Used
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

---

## 📂 Output
Final predictions are saved in:

