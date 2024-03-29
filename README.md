# credit-risk-classification

In this Challenge, we use various techniques to train and evaluate a model based on loan risk by doing the following tasks:
1. Split the Data into Training and Testing Sets
2. Create a Logistic Regression Model with the Original Data
The results from the report are mentioned the Credit Risk Analysis Report below:

## Credit Risk Analysis Report 
An overview of the analysis: The results shows the use of supervised learning to understand the loan risk based on the information provided (loan_size,	interest_rate,	borrower_income,	debt_to_income,	num_of_accounts,	derogatory_marks,	total_debt,	loan_status)

The results: The model used logistic regression to test and train the dataset in to two groups (healthy loan and high-risk). Furthermore, due to the unequal amount of data provided for both the groups, the model used random oversampler to ensure equal number of dataset is used to evaluate. 

Initial results 				
	precision    	recall 	 f1-score	support
Healthy loan 	1.00	1.00	1.00	18759
High-risk loan	0.87	0.89	0.88	625				
Results using random oversampler				
	precision    	recall 	 f1-score	support
Healthy loan	0.99	0.99	0.99	75036
High-risk loan	0.99	0.99	0.99	75036

![image](https://github.com/ManishaRezaPaul/credit-risk-classification/assets/131712506/50146636-6ea9-4dac-be44-1e4daff6d321)



A summary: Logistic regression helps to classify binary dataset, therefore it is a good model to use when classifying dataset such as this (assessing loan risk). However, there must be caution in the interpretation of scores especially when there is a high variation in the amount of data between the two clusters. While this can be resolved by using random oversampler, it can reduce the precision or recall scores and might not give precise results (as in the case of healthy loan group here).


