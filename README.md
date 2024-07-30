#  Checkout my application for the detection of SMS spam

https://zeel0909-6ya5sjs2nox2uxrg4ljhel.streamlit.app/

# SMS Spam Detection

Designing a machine-learning model to identify spam messages in SMS text data is the purpose of this research. To categorize SMS messages as spam or non-spam (ham), it makes use of supervised learning algorithms and natural language processing (NLP) techniques.

# Dataset

The dataset used for this project is the "SMS Spam Collection" from the UCI Machine Learning Repository. It contains a collection of 5,574 SMS messages, labeled as spam or ham. The dataset can be downloaded from [link to dataset] (https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection).

The dataset file (sms_spam_dataset.csv) contains two columns:
 * label: Indicates whether the message is spam (1) or ham (0).
 * text: The actual text content of the SMS message

# Requirements

To run the project, you need the following dependencies:
 * Python 3.x
 * pandas
 * numpy
 * scikit-learn
 * nltk (Natural Language Toolkit)
 * matplotlib

# Usage

 1. Clone the repository or download the project files.
 2. Run the sms_spam_detection.py script to train and evaluate the spam detection model.
 3. The script will load the dataset, preprocess the text data, and train a machine learning model using the TF-IDF (Term Frequency-Inverse Document Frequency) technique.
 4. After training, the model will be evaluated on a holdout set and the performance metrics (such as accuracy, precision, recall, and F1-score) will be displayed.
 5. Finally, you can use the trained model to predict the label (spam/ham) of new SMS messages by modifying the predict function in the script.

 
 * 


