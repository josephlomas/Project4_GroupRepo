# Credit Classification Predictive Modeling

**Overview**

For this project, we utilized a credit score dataset from Kaggle.com to run a supervised learning model in an attempt at predicting an individual's credit score classification. The dataset included a variety of features that were eventually whittled down to Age, Annual Income, Number of Bank Accounts, Number of Credit Cards, Interest Rate, Delay from Due Date, Number of Delayed Payments, Changed Credit Limit, Number of Credit Inquiries, Outstanding Debt & Monthly Balance.  The dataset was cleaned and transformed with Python/Pandas to prepare for machine learning modeling.

**K Nearest Neighbors Modeling**

We used a K-Nearest Neighbors model to train and test our data.  We set the test sample size to 7.5%, which allowed for >2500 rows of data for testing.  Our model acheived 76% accuracy and 10/11 features showed statistical significance towards our target variable (credit score classification).  Good and Poor classifications were well predicted, while Standard classifications were poorly forecasted.  The small k-value (2) and/or our less-than-standard test size left open the possibility for overfitting, but otherwise the model showed relatively high predictive power.

Lastly, a second accompanying dataset (without pre-assigned credit classification) was tested post-hoc with our model.  Credit score classification distributions for the new dataset were very similar to the original, thus potentially reinforcing the strength/accuracy of our initial model.



**Resources**

https://www.kaggle.com/datasets/parisrohan/credit-score-classification?select=train.csv 
https://www.scikit-yb.org/en/latest/index.html 
https://medium.datadriveninvestor.com/increase-10-accuracy-with-re-scaling-features-in-k-nearest-neighbors-python-code-677d28032a45 
https://towardsdatascience.com/feature-selection-with-pandas-e3690ad8504b 
https://www.analyticsvidhya.com/blog/2021/06/confusion-matrix-for-multi-class-classification/ 

