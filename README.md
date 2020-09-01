# leads
Training a logistic regression model for classification, that can be used for marketing purposes --> lead scoring

- 'lead' is a potential customer who might convert (become real customer)
- 'conversion' is the target we want to predict
- dataset available on: https://www.kaggle.com/ashydv/leads-dataset

- dataset has a lot of NaN values, so I used different imputation methods to replace these NaN values

- another challenge is, that the number of features in the training and validation sets are different after the one-hot-encoding
- here I added extra columns with values = 0 in order to get the same feature numbers for the training and validation sets
