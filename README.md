# leads
Training a logistic regression model for classification, that can be used for marketing purposes --> lead scoring

- 'lead' is a potential customer who might convert (become real customer)
- 'conversion' is the target we want to predict
- dataset available on: https://www.kaggle.com/ashydv/leads-dataset

- dataset has a lot of NaN values, so I used different imputation methods to replace these NaN values

- another challenge is, that the number of features in the training and validation sets are different after the one-hot-encoding
- here I added extra columns with values = 0 in order to get the same feature numbers for the training and validation sets

- Sep 11 2020: added a ROC curve to the notebook. At low thresholds (upper right corner)), the performance is worse than in a random model. The performance improves with increasing values, as the curve moves towards the upper left corner. 
