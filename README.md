# loan-prediction-comparative-study
"Comparative study of multiple machine learning models for predicting loan approval, including data preprocessing, model evaluation, visualization, and interactive applicant prediction."

## Project Overview

The project compares **five ML algorithms**:
- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree (ID3)
- K-Nearest Neighbors (KNN)
- Random Forest

The best model is automatically identified based on accuracy, and users can predict loan eligibility for new applicants.

---

## Dataset
- **File:** `loan_data.csv`
- **Description:** Contains loan applicant information, including:
  - Gender, Married, Dependents, Education, Self_Employed
  - ApplicantIncome, CoapplicantIncome, LoanAmount, Loan_Amount_Term
  - Credit_History, Property_Area, Loan_Status (target)

**Source:** Kaggle

---

## Features
1. **Data Preprocessing**
   - Dropping duplicates
   - Handling missing values
   - Encoding categorical features
   - Feature scaling (StandardScaler)
2. **Comparative Study**
   - Train-test split
   - Model training and evaluation
   - Metrics: Accuracy, Precision, Recall
   - Confusion matrices
3. **Best Model Identification**
   - Automatically selects the model with the highest accuracy
4. **Visualization**
   - Bar charts comparing Accuracy, Precision, Recall of all models
   - Best model highlighted
5. **Interactive Prediction**
   - Input new applicant details
   - Get loan approval prediction
   - Probability of approval (confidence)

---

