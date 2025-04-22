**Financial Risk Prdiction for Loan Aproval**

**Presented By:** Jasly Sagith
**Organization:** Entri Elevate

**Overview**
In the banking and financial sector, accurately evaluating an applicant’s financial risk is crucial for making informed loan approval decisions. This project focuses on building a regression-based machine learning model to predict the financial risk score of loan applicants based on their demographic, employment, credit, and financial information.

By using various regression models — such as Linear Regression, Decision Tree, Random Forest, Gradient Boosting, and others — we aim to identify the most reliable method for estimating financial risk. The predicted risk score can help institutions minimize defaults, optimize credit decisions, and streamline the loan approval process.

**Objectives:**
* To preprocess and analyze loan applicant data

* To engineer and select the most impactful features

* To train and evaluate multiple regression models

* To select the best-performing model based on metrics like R² Score and Mean Squared Error (MSE)

* To predict financial risk scores that assist in loan decision-making


**About Data Set**

**Dataset Link : ** https://www.kaggle.com/datasets/lorenzozoppelletto/financial-risk-for-loan-approval?select=Loan.csv

The dataset includes the following columns:

**1. ApplicationDate:** Loan application date
**2. Age:** Applicant's age
**3. AnnualIncome:** Yearly income
**4. CreditScore:** Creditworthiness score
**5. EmploymentStatus:** Job situation
**6. EducationLevel:** Highest education attained
**7. Experience:** Work experience
**8. LoanAmount:** Requested loan size
**9. LoanDuration:** Loan repayment period
**10. MaritalStatus:** Applicant's marital state
**11. NumberOfDependents:** Number of dependents
**12. HomeOwnershipStatus:** Homeownership type
**13. MonthlyDebtPayments:** Monthly debt obligations
**14. CreditCardUtilizationRate:** Credit card usage percentage
**15. NumberOfOpenCreditLines:** Active credit lines
**16. NumberOfCreditInquiries:** Credit checks count
**17. DebtToIncomeRatio:** Debt to income proportion
**18. BankruptcyHistory:** Bankruptcy records
**19. LoanPurpose:** Reason for loan
**20. PreviousLoanDefaults:** Prior loan defaults
**21. PaymentHistory:** Past payment behavior
**22. LengthOfCreditHistory:** Credit history duration
**23. SavingsAccountBalance:** Savings account amount
**24. CheckingAccountBalance:** Checking account funds
**25. TotalAssets:** Total owned assets
**26. TotalLiabilities:** Total owed debts
**27. MonthlyIncome:** Income per month
**28. UtilityBillsPaymentHistory:** Utility payment record
**29. JobTenure:** Job duration
**30. NetWorth:** Total financial worth
**31. BaseInterestRate:** Starting interest rate
**32. InterestRate:** Applied interest rate
**33. MonthlyLoanPayment:** Monthly loan payment
**34. TotalDebtToIncomeRatio:** Total debt against income
**35. LoanApproved:** Loan approval status
**36. RiskScore:** Risk assessment score


**Data Preprocessing**
**Loading and Cleaning Data:**
* Loaded the dataset using pandas.
* Examined missing values and duplicates.
* Removed irrelevant features and duplicate entries.
* Outlier Detection and removal
  
**Exploratory Data Analysis (EDA):**
* Univariate anlaysis using Boxplot and Histogram for numerical variables
* Univariate analysis using Countplots for Categorical variables
* Bivariate analysis using Heatmap and Boxplot

**Data Engineering**
* Feature Encoding
* Feature Selection
* Feature Importance Analysis using Random Forest method
* Data Splitting
* Feature Scaling

**Model Building**
* Model Selection – Choose different machine learning algorithms to compare performance.
* Training the Models – Fit models to the training data.
* Evaluation Metrics – Assess models using Mean Squared Error and R2Score
  
**Regression Algorithms applied:**
1. Linear Regression
2. SVM
3. Decision Tree
4. Random Forest
5. Gradient Boost.
   
**Hyperparameter Tuning**

**Selecting the best model**

**Pipeline for Machine Learning**

**Testing with unseen data**
