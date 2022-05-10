# Document-classifier
Formed a Document classifier, that classifies in the format 0 or 1. 
Here the data is used by collecting real scanned invoices which we will classify as the following: 
1 - Invoice
0 - Not Invoice

## Model
One class Support Vector Machine

## Process
1. Converted .pdf files to .txt files using Tika python
2. Pre-processing of .txt files by changing the case to lower, using nltk.sent_tokenize to tokenize the words
3. Vectorize the content
4. Using the One class SVM model, train and test the data
5. Finally Predict the result
