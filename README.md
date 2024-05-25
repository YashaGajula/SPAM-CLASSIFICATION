# Spam classification model using ML, DL and LLM.
Goal:
We have a bunch of emails classified as 'spam' and a bunch of emails classified as 'ham' (not spam)
The emails are first read and stored in a dataframe. They are then parsed using CountVectorizer
This information is used to train the model and its prediction is then tested with a sample input
Python Libraries used: pandas, numpy, io, os, CountVectorizer and MultinomialNB from sklearn.
# Distribution of Spam/Ham in dataset.
![image](https://github.com/YashaGajula/SPAM-CLASSIFICATION/assets/170789442/149444d7-6758-42d6-884b-f498ed1ccb92)
# Naive Bayes Classifier (ML)
# CNN (DL Model)
# BERT (LLM)
![image](https://github.com/YashaGajula/SPAM-CLASSIFICATION/assets/170789442/0b9ccfbc-7f2c-4757-a6ba-9f2859d9109b)
ML (Naive Bayes): Achieved an accuracy of approximately 98.25%.
DL (CNN): Achieved an accuracy of approximately 98.10%.
LLM (BERT): Achieved the highest accuracy, approximately 99.00%.
The graph clearly shows that the BERT model, a large language model, outperforms both the traditional machine learning model (Naive Bayes) and the deep learning model (CNN) in terms of classification accuracy.



