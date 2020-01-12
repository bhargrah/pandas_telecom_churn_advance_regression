# Problem Statement 

## Business Problem Overview
In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

For many incumbent operators, retaining high profitable customers is the number one business goal.

To reduce customer churn, telecom companies need to predict which customers are at high risk of churn.

In this project, you will analyse customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn and identify the main indicators of churn.

## Model Comparisions 
|Sr. No.| Model	| Accuracy |	Precision |	Recall |	AUC |	F1 |
| 0 |	SVM (Default)-linear |	0.83 | 0.80 |	0.30 |	0.82 | 0.44 |
| 1 |	SVM (Default)-rbf |	0.87	| 0.74 |	0.37 |	0.81	| 0.49 |
| 2 |	SVM( rfb ) [Hyper] |	0.92	| 0.48 | 0.49	| 0.72 | 0.48 |
| 3 |	RandomForest (Default) |	0.91	| 0.49	| 0.44 |	0.72 |	0.46 |
| 4 |	RandomForest (Hyper) |	0.90	| 0.67	| 0.41	| 0.79	| 0.51 |
| 5 | XGBoost (Default) |	0.86 |	0.75	| 0.33 |	0.81 |	0.46 |
| 6 |	XGBoost (Hyper Tuned )|	0.85 |	0.75 |	0.32 |	0.81 |	0.45 |
