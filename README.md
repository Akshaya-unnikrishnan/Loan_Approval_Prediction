# Loan Approval Prediction

## Project Overview
This project predicts whether a loan will be approved based on applicant information using **Machine Learning**.  
It demonstrates **data preprocessing, exploratory data analysis, model training, and evaluation** using Logistic Regression and Random Forest.

---

## Dataset
The dataset is taken from Kaggle:  
[Loan Prediction Dataset](https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset)  

**Features include:**
- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area
- Loan_Status (target)

---

## Steps Performed

1. **Data Loading & Exploration**
   - Loaded dataset using Pandas
   - Checked for missing values and basic statistics

2. **Data Preprocessing**
   - Filled missing values with mode/median
   - Encoded categorical features using Label Encoding
   - Scaled numerical features (optional but recommended)

3. **Model Training**
   - Trained **Logistic Regression** and **Random Forest Classifier**
   - Split dataset into 80% training and 20% testing

4. **Model Evaluation**
   - Evaluated models using:
     - Accuracy
     - Confusion Matrix
     - Classification Report
   - Random Forest feature importance analysis

---

## Results
- Random Forest achieved higher accuracy than Logistic Regression  
- Important features affecting loan approval:
  - Credit History
  - Applicant Income
  - Loan Amount
  - Coapplicant Income  

---

## Tech Stack
- Python
- Pandas, NumPy
- Scikit-Learn
- Matplotlib, Seaborn

---

## How to Run
1. Clone the repository:
```bash
git clone https://github.com/Akshaya-unnikrishnan/Loan_Approval_Prediction.git
