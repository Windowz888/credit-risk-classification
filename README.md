# credit-risk-classification
A Summary of the Analysis
The goal of this analysis is to assess borrowers' creditworthiness using previous lending activity data from a peer-to-peer lending services organization. We hope to anticipate the risk associated with each loan by constructing and analyzing machine learning models, specifically whether a loan is healthy or at high risk of defaulting.

Score for Accuracy of Results:

99.38% for the original model
Oversampled Data Model: 99.37%
The accuracy score is the model's percentage of correct predictions out of all forecasts. Both models had an accuracy of around 99.37%, indicating that they are quite good at forecasting loan conditions.

Precision Rating:

Healthy Loans (0) - 100%, High-Risk Loans (1) - 85%, Original Model
Oversampled Data Model: Healthy Loans (0) - 100%, High-Risk Loans (1) - 84%
Precision is calculated by dividing the number of true positive predictions by the sum of true positives and false positives. A high precision for healthy loans implies that the model predicts healthy loans accurately. Although the precision for high-risk loans is lower, it is still commendable.

Score for Recall:

Healthy Loans (0) - 99%, High-Risk Loans (1) - 91%, Original Model
Oversampled Data Model: Healthy Loans (0) - 99%, High-Risk Loans (1) - 99%
The proportion of true positives that were correctly identified is indicated by recall (or sensitivity). According to the recall scores, both models are capable of identifying high-risk loans, with the oversampled model doing somewhat better.

Summary
Both the initial logistic regression model and the model trained with oversampled data predicted loan statuses very well. The models performed well in terms of accuracy, precision, and recall, suggesting their dependability and efficacy.

Based on the findings, I recommend that the logistic regression model trained with oversampled data be used for the company's operations. As indicated by the high recall value for label 1, the oversampling strategy improved the model's ability to predict high-risk loans. This approach will allow the organization to make more informed loan decisions, lowering the risk of default and increasing profitability.


