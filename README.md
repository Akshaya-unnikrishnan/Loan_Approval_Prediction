# Loan Approval Prediction

## Project Description
Predict loan approval using a processed loan dataset by analyzing applicant details like income, credit history, employment, and property area.  
The project demonstrates data preprocessing, exploratory analysis, Logistic Regression and Random Forest models, model evaluation, and feature importance for actionable insights.

---

## Dataset
The dataset used is a processed version of the original loan dataset, where the target variable `Loan_Status` was created for prediction purposes.  
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
   - Handled missing values
   - Encoded categorical variables using Label Encoding
   - Scaled numerical features

3. **Model Training**
   - Logistic Regression
   - Random Forest Classifier

4. **Model Evaluation**
   - Accuracy, Confusion Matrix, Classification Report
   - Random Forest feature importance

---

## Results
- Random Forest achieved higher accuracy than Logistic Regression  
- Key features affecting loan approval:
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

