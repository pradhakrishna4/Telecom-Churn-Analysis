# Telecom-Churn-Analysis
# Project Summary :

## Requirement:
No-Churn Telecom is an established Telecom operator in America with more than a decade in business. Due to new players in the Market, Telecom industry has become very competitive and retaining customers is becoming a challenge. In spite of No-Churn initiative for reducing tariffs and promoting more offers, the churn rate(percentage of customers migrating to competitors) is well above 10%. No-Churn wants to explore possibility of Machine Learning to help retain competitive edge in the industry.

Help No-Churn with their cases with Machine Learning

1. Understanding the variables that influence the customers to migrate.

2. Creating Churn risk scores that can be indicative to drive retention campaigns.

3. Introduce new predictor variable “CHURN-FLAG” with values YES(1) or NO(0) so that email campaigns with lucrative offers can be targets to Churn YES customers.

4. Exporting the trained model with prediction capability for CHURN-FLAG along with input variables.

Help to identify possible CHURN-FLAG YES customers and provide more attention in customer touch point areas, such as customer care support, request fulfillment, auto categorizing tickets as high priority for quicker resolutions of any questions customers may have etc.

## Analysis :
* The data is supervised and categorical. The predictor variables are ordinal and a few among them are nominal. The target variable 'Churn' is nominal.
* To analyze the data, various data processing techniques like Label Encoding and Standardization is used. Correlation Coeffecient is used to interpret the relationship between variables and feature selection. The most important features affecting the Churn are International Plan,Day Charge,Cust Service Calls, Voice Mail Message, Evening Charge and International Charge.
* For training the data and predicting the target, algorithms used are Logistic Regression, Support Vector Machine, Decision Tree, Random Forest, Naive Bayes, XGBoost Classifier and Artificial Neural Network.
* A separate analysis for creating the Churn Risk Scores is carried out.
# Results
The most important features affecting the Churn are International Plan,Day Charge,Cust Service Calls, Voice Mail Message, Evening Charge and International Charge. 
# Recommendation
From the models we can clearly find out the Churn YES Customers. We can undergo retention campaigns for them with lucrative offers, provide more attention in customer touch point areas, including customer care support, request fulfilment, auto categorizing tickets as high priority for quick resolutions any questions they may have etc.
