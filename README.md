# SMS-Spam-Detection

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
## Overview
This repository contains the code for building a SMS SPAM Detection system. The project aims to classify SMS messages as either spam or ham (non-spam) using the Naive Bayes Classifier with MultinomialNB algorithm. The text preprocessing is done using both Bag-of-Words (BOG) and Term Frequency-Inverse Document Frequency (TFIDF) methods to convert the text messages into numerical features for the classifier.

## Dataset
The dataset used for training and testing the SMS SPAM Detection model is stored in the `data` directory. The dataset contains labeled SMS messages, where each message is associated with its corresponding class label (spam or ham). The dataset is split into training and testing sets for model evaluation.

## Requirements
The following libraries and tools are required to run the code in this repository:
- Python 3.x
- NumPy
- Pandas
- Scikit-learn

## Usage
- The script will preprocess the SMS messages using both BOG and TFIDF methods, train the MultinomialNB classifier, and evaluate the model's performance on the test set. The accuracy, precision, recall, and F1-score metrics will be displayed.

## Results
The trained MultinomialNB model achieved good performance in detecting SMS spam messages. The final model's accuracy, precision, recall, and F1-score are reported in the output after running the file.
## Acknowledgments
Special thanks to Krish Naik Sir for concept clearing and AlmaBetter for providing the dataset and the guidance for this project.
