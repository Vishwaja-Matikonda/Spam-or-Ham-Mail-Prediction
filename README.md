# Spam-or-Ham-Mail-Prediction

The project involves the detection of spam in SMS communications. We used the text classification system to identify whether or not the messages are spam and NLP methods to prepare and clean up text data (tokenization, remove stop words, stemming). In order to get more reliable predictions, we used various machine learning classification algorithms such as: Logistic Regression, Naive Bayes, Vector Machine Support Vector Machine (SVM).

Technologies used

Python 
libraries: pandas, numpy, scikit-learn, NLTK, imbalanced-learn.

Dataset

The dataset comes from SMS Spam Collection that can be find at https://www.kaggle.com/uciml/sms-spam-collection-dataset

This SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It comprises one set of SMS messages in English of 5,574 messages, which is tagged acording being ham (legitimate) or spam.

This project was aimed to text classification to determined whether the messages is spam or not. We started with the dcleaning and text mining, which cover change text into tokens, remove punctuation, stop words and normalization them by stemming. Following we used bag of words model to convert the text into numerical feature vectors. Finally we started training six different classification models and we got the best accuracy of 0.97 for Naive Bayes method.
