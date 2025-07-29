# Loan Prediction Dataset

# Objective
The goal of this project is to predict whether a loan applicant is likely to **default on a loan**, using classification models. This is a **binary classification problem**, where the outcome is either "Yes" (likely to default) or "No" (not likely to default).


#  Dataset
Loan Prediction Dataset available on Kaggle
  - The dataset contains various features such as:
  - Gender, Married, Education
  - ApplicantIncome, CoapplicantIncome
  - LoanAmount, Loan_Amount_Term
  - Credit_History
  - Property_Area, Self_Employed
  - Target variable: Loan_Status (Y/N)



# Tools Used
  - **Power BI** for Data Cleaning and Data Visualization (EDA)
  - **Kaggle (Jupyter Notebook - Python)** for Model Training and Model Evaluation


# Data Cleaning (Power BI)
  - Handled missing values in:
  - LoanAmount and Loan_Amount_Term (imputed with median)
  - Self_Employed, Gender, and Married (filled with mode)
  - Ensured data types were consistent and ready for modeling


# Exploratory Data Analysis (Power BI)
  - Visualized key trends and relationships:
  - Distribution of **Loan Amount**
  - Impact of **Education** on loan approval
  - Relationship between **Income and Loan Status**
  - **Loan Status** by gender
  - Distribution of **Loan Amount** by property
  - **Slicer** and **Cards** for better insights
    

#  Model Training (Kaggle Notebook)
- Used **Logistic Regression** 
- Encoded categorical variables using Label Encoding
- Split dataset into training and testing sets (80/20)

# Logistic Regression Results
- Accuracy: **78.86%** 
- Confusion Matrix:
 **[[18 25]
 [ 1 79]]**


# Conclusion
- The dataset was cleaned and visualized using **Power BI**.
- ML models is trained in **Kaggle**, with Logistic Regression showing slightly better performance.
- The trained model can be used to help financial institutions assess **credit risk** of applicants and make more informed decisions.


# Skills Applied
- Data Cleaning and Preprocessing in Power BI
- Data Visualization using Power BI
- Binary Classification (Logistic Regression)
- Evaluation using Confusion Matrix & Accuracy



