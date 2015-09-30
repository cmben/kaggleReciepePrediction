# Kaggle Reciepe Prediction Challenge

This project contains code for implementing classifier in the Kaggle Challenge https://www.kaggle.com/c/whats-cooking

The train and test data is available in JSON format.

The complete python code is in notebooks directory as Ipython notebook. 

Steps followed in classifying the reciepe - 
1. Load training data
2. Clean training data (ingredients). Remove special characters, numbers, puncuation marks and stopwords.
3. Tokenize the data
4. Build Document by Words matrix. We can also substitute this with  TF-IDF matrix.
5. Try different classifiers such as SGDClassifier, Multinomial Naive Bayes, Random Forest.
6. Measure accuracy. 
