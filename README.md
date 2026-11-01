# sms-spam-classifier
SMS spam detection using TF-IDF and Logistic Regression.

## Dataset

SMS Spam Collection (Almeida and Hidalgo, UCI), downloaded from Kaggle. 
After removing duplicates: 5168 SMS (4516 ham, 652 spam).

## What I did

Cleaned the data and removed duplicates
Split into train and test (80/20)
Converted text to numbers with TF-IDF
Trained Logistic Regression

## Results

Accuracy: 97%, spam precision: 0.99, spam recall: 0.77

## Note

Only about 13% of messages are spam, so accuracy alone is not enough. Results are from one train/test split.
