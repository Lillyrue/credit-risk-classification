# credit-risk-classification
#### Overview: 
In this analysis, we are looking at the credit worthiness of borrowers based on the analysis of healthy loans and high-risk loans.  A logistic regression model was used to train and predict the data of credit risk by using the original lending data and RandomOverSampler data.  The models were evaluated by the accuracy balance score, the confusion matrix, and the classification report.

#### Results: 
Looking at the balanced accuracy score in the original data, it came out to 95%.  The balanced accuracy score using the resampled data, scored much higher at 99%.

From the classification report, we can see the results for both of the logistic regression models with the original data and with the resampled data.
*  The accuracy score for the original data is 99%, as well as for the resampled data.  
*  The precision score for the healthy loans in the original data and resampled data was 100%. However, for the high-risk loans in the original data, the precision score was 85%.  The precision score for the high-risk loans in the resampled data was 84%.
*  The recall score for the healthy loans in the original data was 99%. However, for the high-risk loans in the original data, the recall score was 91%. The recall score for both the healthy loans and high-risk loans in the resampled data was 99%.

#### Summary: 
Observing both the original dataset and the resampled dataset, the model is more accurate with the resampled data.  However, even with the model being more accurate at 99% with the resampled data than the model with the original data, I would not recommend the company to use either models for predicting which borrowers are credit worthy.  There is room for error and bias based on the data, and some borrowers may be denied loans unfairly if they are inaccurately considered to have high-risk loans. Some things to consider are what the loans are for, which is not included in the data, for example, small businesses, real estate, school, etc.  I would only feel comfortable recommending a model that predicted 100% accuracy, especially when it comes to dealing with customers and loans.
