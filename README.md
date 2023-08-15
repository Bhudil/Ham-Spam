# Ham-Spam Detection

The following model takes in a dataset of over 5000 SMS entries and categorises then into HAM(desired) or SPAM(not desired). This is used to make it easier for the user to segregate their SMS recieved. The dataset is stopwords is downloaded forused to clean and Vectorize the SMS entries so that the classification model an accept the features. Then the context is outputted in  the form of a sparse matrix. TF-IDF is used to assign weights to the words. And lastly, we use Naive Bayes Classifier to train the model with the help of a Pipeline (all from sklearn)

STEPS-

1)
