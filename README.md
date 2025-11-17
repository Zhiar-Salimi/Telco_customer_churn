A Special Project by Zhiar Salimi

Predicting Customer Churn Using Statistical Analysis & Logistic Regression
===========================================================================
The goal of this project is to analyze the Telco Customer Churn dataset to identify which customer factors such as tenure, monthly charges, 
and contract type, most strongly predict whether a customer will churn. 
The project uses Python (Pandas, Matplotlib, Sea Born) to clean data and visualize patterns.=> (To be Updated)
---------------------------------------------------------------------------

Question:

Which customer factors have the strongest statistical relationship with churn?

Key variables examined:
	•	Tenure
	•	Monthly Charges
	•	Contract Type
	•	Churn (Target variable)
---------------------------------------------------------------------------

Dataset: Telco Customer Churn (IBM Sample)
Source: https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset

Columns used:
	•	tenure
	•	MonthlyCharges
	•	Contract
	•	Churn
	•	TotalCharges (converted to numeric)
  
---------------------------------------------------------------------------
   Data Cleaning Steps

Performed using Pandas:

	•	Converted "Churn" from Yes/No → 1/0
	•	Converted "Contract" to categories (Month-to-month, 1-year, 2-year)
	•	Converted "TotalCharges" to numeric
	•	Removed missing values
	•	Checked column types + summary statistics
---------------------------------------------------------------------------
  I created two visualizations to understand churn behavior:
	
A. Tenure Distribution by Churn Status

Finding 1: Customers with short tenure churn the most

Most churned customers (red) have very short tenure, usually less than 10 months.
Retained customers are spread across longer tenures, with a high concentration at 60–72 months.

Interpretation:
The longer a customer stays, the less likely they are to churn.
Tenure is one of the strongest predictors of churn.

 B. Monthly Charges by Churn Status (Boxplot)

Finding 2: Customers who churn pay higher monthly charges

	•	Churned customers have a higher median monthly charge
	•	Their price range is more concentrated
	•	Retained customers show a wider spread, including many low-cost plans

Interpretation:

Higher pricing → Higher customer dissatisfaction → Higher churn probability.

Monthly Charges is another critical predictor.

To Be Continued..............

  
