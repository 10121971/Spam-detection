# Spam-detection
The project aims at detecting a spam email by the use of Natural Language Processing (NLP). 

Spam detection has become extremely important to prevent people from potential frauds.

Following steps were applied to the dataset into the project:
1. Preprocessing of the raw data
2. Feature Engineering
3. Machine Learning model

The Preprocessing of raw data included tokenization of sentences and words. Stemming and Lemmatization was done on the raw data to prepare it for further processes.
Whole preprocessing steps were done using SpaCy library of Python. Another alternative is NLTK.

Feature Enginnering involved the method of 'Bag of n words'. The words were vectorized by the help of CountVectorizer of sklearn.

Naive-Bayes model was applied for classification of the data.

The model predicted the test set with approx 99% accuracy and precision scores.
