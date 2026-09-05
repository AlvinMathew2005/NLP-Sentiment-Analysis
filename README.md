# NLP-Based Sentiment Analysis of Customer Reviews

## Project Overview

This project develops a simple Natural Language Processing (NLP) system to classify customer reviews into **Positive, Negative, and Neutral** sentiment categories.

The project uses **TF-IDF** for text feature extraction and **Logistic Regression** for sentiment classification.

## Objectives

* Preprocess customer review text using NLP techniques.
* Convert text into numerical features using TF-IDF.
* Build a sentiment classification model using Logistic Regression.
* Classify reviews into positive, negative, and neutral categories.
* Evaluate the model using Accuracy, Precision, Recall, F1-Score, and a Confusion Matrix.
* Demonstrate the model using a simple Gradio interface.

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn
* Gradio

## Methodology

The project follows the workflow:

**Customer Reviews → Text Preprocessing → TF-IDF → Logistic Regression → Prediction → Evaluation**

Text preprocessing includes:

* Converting text to lowercase
* Removing special characters
* Removing stopwords
* Stemming using Porter Stemmer

## Model Performance

| Metric    |  Score |
| --------- | -----: |
| Accuracy  | 89.52% |
| Precision | 84.88% |
| Recall    | 89.52% |
| F1-Score  | 86.82% |

## Dataset

The project uses a customer review dataset containing review text and sentiment labels.

The complete dataset is not included in this repository because the CSV file exceeds GitHub's standard file upload size limit.

## User Interface

A simple **Gradio interface** was developed to allow users to enter a customer review and receive the predicted sentiment.

## Repository Structure

```text
NLP-Sentiment-Analysis/
│
├── README.md
├── NLP_Sentiment_Analysis.ipynb
├── source_code.py
│
├── dataset/
│   └── README.md
│
├── screenshots/
│   └── project screenshots
│
└── report/
    └── NLP_Sentiment_Analysis_Report.pdf
```

## Conclusion

The project demonstrates how basic NLP techniques and machine learning can be used to automatically analyze customer reviews and classify their sentiment. The Logistic Regression model achieved an accuracy of 89.52% on the test data.
