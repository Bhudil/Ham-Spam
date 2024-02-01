# Ham-Spam Detection

**Spam Detection with Naive Bayes Classifier and Tkinter GUI**

**Introduction:**
This project implements a spam detection system using the Naive Bayes classifier. The system is built with Python and leverages the scikit-learn library for machine learning and Tkinter for creating a user-friendly graphical interface. The Naive Bayes classifier is trained on a dataset of emails to distinguish between spam and ham (non-spam) messages. Users can input a message into the Tkinter GUI, and the system classifies it as either spam or ham based on the trained model.

**Contents:**
- **Data Preparation:** The project starts by loading the email dataset from a CSV file using Pandas. It explores the dataset, analyzing spam and ham messages' distribution and statistics.
  
- **Data Visualization:** Visualizations using Seaborn and Matplotlib illustrate the distribution of spam and ham messages. The spam and ham percentages are calculated to provide insights into the dataset's composition.

- **Text Vectorization:** The emails' text data is processed using the CountVectorizer from scikit-learn. This step converts the text into numerical features that can be used by machine learning algorithms.

- **Model Training:** The Naive Bayes classifier (MultinomialNB) is trained on the vectorized text data. The dataset is split into training and testing sets for model evaluation.

- **Model Evaluation:** The trained model's performance is evaluated using metrics such as confusion matrices and classification reports. These evaluations provide an understanding of the model's accuracy and ability to classify spam and ham messages correctly.

- **Tkinter GUI:** The project includes a graphical user interface built with Tkinter. Users can input a message into the provided text entry field. When the "Classify" button is clicked, the system uses the pre-trained model to classify the message and displays the result (spam or ham) on the GUI.

**Installation:**
1. Ensure you have Python installed on your system.
2. Install the required libraries using pip:
   ```
   pip install pandas numpy seaborn matplotlib scikit-learn joblib
   ```
3. Clone the repository to your local machine:
   ```
   git clone <repository_url>
   ```
4. Run the `spam_detection_gui.py` file to launch the Tkinter application.

**Usage:**
1. Execute the `spam_detection_gui.py` file.
2. Enter a message into the provided text entry field.
3. Click the "Classify" button to see the classification result (Spam or Ham) displayed on the GUI.

**Files:**
- **emails.csv:** Dataset containing email messages for training the spam detection model.
- **spam_detection_gui.py:** Python script containing the Naive Bayes classifier and Tkinter GUI implementation.
- **count_vectorizer.pkl:** Pre-trained CountVectorizer object for text vectorization.
- **spam_classifier_model.pkl:** Pre-trained Naive Bayes classifier for spam detection.


**Contributing:**
1. Fork the repository on GitHub.
2. Create a new branch for your changes.
3. Make your modifications and commit the changes.
4. Push your changes to your fork.
5. Submit a pull request with a detailed description of your changes.

**Outcomes**
## Layout:

![Screenshot (83)](https://github.com/Bhudil/Ham-Spam/assets/99169324/c37e0fed-e4eb-42a4-a875-0cf1436c7f7f)

## Spam use-Case:

![Screenshot (84)](https://github.com/Bhudil/Ham-Spam/assets/99169324/4e1e900a-b402-4a9f-903d-8d9c327c7d4e)

## Ham Use-case:

![Screenshot (85)](https://github.com/Bhudil/Ham-Spam/assets/99169324/15590c05-1f81-42d6-942f-01ddcb701de7)


**Acknowledgments:**
- The project was inspired by the need for effective spam detection systems in email communication.
- Thanks to the open-source community for providing valuable resources and tools.
