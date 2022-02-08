## Customer Loan Prediction 

**Goal of the project:** 
build a machine learning model, which determines whether or not a person will be approved for a loan. 

**Data:**

  The data consist of 614 points and 13 features. 
  
  Features:
  
    Loan_ID: loan application id
    Gender: gender of the client (Male, Female)
    Married: whether the client is married (Yes, No)
    Dependents: how many dependents a client has (0, 1, 2, 3+)
    Education: graduate or non-graduate (Graduate, Not Graduate)
    Self_Employed: whether the client is self-employed (Yes, No)
    ApplicantIncome: applicant's yearly income in dollars
    CoapplicantIncome: coapplicant's yearly income in dollars
    LoanAmount: the amount of loan applied for in dollars 
    Loan_Amount_Term: term of loan in days 
    Credit_History: whether applicant has a credit history (Yes, No)
    Property_Area	Loan_Status: Urban, Rural, Semiurban
    
 **Methodology:**
 
 1. Exploratoty Data Analysis (univariate and bivariate)
 2. Data cleaning (impute missing values)
 3. Feature engineering (handle categorical variables)
 4. Perform oversampling to fix class imbalance 
 5. Model building - compare Logistic Regression and Gradient Boosting classification models using classification metrics
