# Ham-Spam Detection

The following model takes in a dataset of over 5000 SMS entries and categorises then into HAM(desired) or SPAM(not desired). This is used to make it easier for the user to segregate their SMS recieved. The dataset is stopwords is downloaded forused to clean and Vectorize the SMS entries so that the classification model an accept the features(using nltk library). Then the context is outputted in  the form of a sparse matrix. TF-IDF is used to assign weights to the words. And lastly, we use Naive Bayes Classifier to train the model with the help of a Pipeline (all from sklearn)

STEPS-

1) Use rstrip to extract the useful information from the dataset.

2) enumerate it and load it into a DataFrame.

3) Visualize it in graphs to get an overview of the two categories. We deduced that SPAM messages have more characters.

4) Text Preprocessing: bag of words is used to convert each word to a numeric value so that the classifier can take in the values.

5) For nltk import the stopwords corpus to clean the dataframe. Further use Vectorization to normalize the data.

6) Use Sparse matrix to display the new bag of words.

7) TF-IDF is used for data mining from the dataframe and evaluating weight of each words in the corpus.

8) Finally a model is trained and evaluated using the Naive Bayes Classifier form Sci-Kit Library

9) A confusion matrix an classification report is generated it display various metrics of the model(like presicion and accuracy)
