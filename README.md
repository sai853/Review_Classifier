# Review_Classifier

This project aim to classify reviews from yelp dataset as positive/negative based on the text analysis.

The project was built using python language with the help of Jupyter Notebook, the project uses pandas, numpy, nltk, matplot and seaborn.

In this project, first the dataset will be pre-processed with some techniques to clean the data or preparing the data to bulit a model.

Next some Natural Language Processing(NLP) methods are applied like implementing tokenization, removing stop words, Count Vectorizer.

Count Vectorizer : The model can't usderstand the text so count vectorizer is used to transform a given text into a vector on the basis of the frequency (count) of each word that occurs in the entire text.

Two ML Classification methods are used to break dwon the patterns and get the accuracy of a model.

K-Nearest Neighbor Classifier(KNN) : KNN algorithm assumes that similar things exist in close proximity, for instance It compares the good review with the bad review
and classified according to the label. It had training and testing sets which builts confusion matrix , recall, precision, f1-score, support and accuracy, These scores are calculated with true positive, true negative, false positive and false negative. 

MultiNomial NB : Multinomial Naive Bayes algorithm is a probabilistic learning method that is mostly used in Natural Language Processing (NLP). The algorithm is based on the Bayes theorem and predicts the tag of a text such as a piece of email or newspaper article. It calculates the probability of each tag for a given sample and then gives the tag with the highest probability as output. It had training and testing sets which builts confusion matrix , recall, precision, f1-score, support and accuracy, These scores are calculated with true positive, true negative, false positive and false negative. 

These two classification models are compared their accuracy using matplot and pyplot, Multinomial NB gives best accuracy than K-Nearest neighbor.
