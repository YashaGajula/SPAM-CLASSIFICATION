# Spam classification model using ML, DL and LLM.
Goal:
We have a bunch of emails classified as 'spam' and a bunch of emails classified as 'ham' (not spam)
The emails are first read and stored in a dataframe. They are then parsed using CountVectorizer
This information is used to train the model and its prediction is then tested with a sample input
Python Libraries used: pandas, numpy, io, os, CountVectorizer and MultinomialNB from sklearn.
# Distribution of Spam/Ham in dataset.
![image](https://github.com/YashaGajula/SPAM-CLASSIFICATION/assets/170789442/149444d7-6758-42d6-884b-f498ed1ccb92)
# Naive Bayes Classifier (ML)
Naive Bayes classifiers are a family of simple probabilistic classifiers based on applying Bayes' theorem with strong (naive) independence assumptions between the features. 
Simple and Fast: Easy to implement and computationally efficient.
Effective for Text Classification: Performs well with high-dimensional datasets like text.
Handles Missing Data: Can handle cases where some feature values are missing.
# CNN (DL Model)
A Convolutional Neural Network (CNN) is a deep learning model commonly used for image processing tasks, but it has also been successfully applied to text classification problems, including spam/ham email classification.
Local Feature Detection: CNNs can effectively capture local patterns (e.g., phrases or n-grams) in the text.
Hierarchical Feature Learning: Multiple convolutional and pooling layers allow CNNs to learn hierarchical representations of text.
Robust to Input Variability: Can handle variations in input text and is less affected by the position of features in the text.
# BERT (LLM)
BERT is a state-of-the-art language representation model developed by Google that has achieved significant improvements in various NLP tasks, including spam/ham classification.
Contextual Understanding: BERT captures deep contextual relationships between words, improving classification accuracy.
Pretrained Knowledge: BERT is pretrained on a large corpus, which helps in achieving high performance even with limited labeled data.
Versatility: Can be fine-tuned for various NLP tasks with minimal adjustments.
![image](https://github.com/YashaGajula/SPAM-CLASSIFICATION/assets/170789442/0b9ccfbc-7f2c-4757-a6ba-9f2859d9109b)


ML (Naive Bayes): Achieved an accuracy of approximately 98.25%.
DL (CNN): Achieved an accuracy of approximately 98.10%.
LLM (BERT): Achieved the highest accuracy, approximately 99.00%.
The graph clearly shows that the BERT model, a large language model, outperforms both the traditional machine learning model (Naive Bayes) and the deep learning model (CNN) in terms of classification accuracy.



