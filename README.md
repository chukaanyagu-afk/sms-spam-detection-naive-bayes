# sms-spam-detection-naive-bayes
sms-spam-detection-naive-bayes
# SMS Spam Detection Using Naive Bayes

## Project Overview

This project applies a Naive Bayes classifier to the SMS Spam Collection dataset to classify text messages as spam or legitimate messages.

It demonstrates how machine learning can be applied to text classification, a common task in natural language processing.

## Problem Statement

Unwanted messages can expose users to scams, misleading content, and unnecessary communication. Automated text classification provides a way to identify messages that may be spam.

This project explores how a probabilistic machine learning model can learn patterns in labeled SMS messages and use them to classify new messages.

## Objectives

- Explore and prepare the SMS dataset.
- Process message text for machine learning.
- Convert text into a suitable numerical representation where required.
- Train a Naive Bayes classifier.
- Evaluate spam detection performance.
- Examine classification errors and limitations.

## Dataset

**Dataset:** SMS Spam Collection (`spam.csv`)

The dataset contains SMS messages labeled as spam or legitimate (ham). The exact columns and preprocessing steps are described in the notebook.

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib and Seaborn (if used)

## Algorithm: Naive Bayes

Naive Bayes is a family of probabilistic classification algorithms based on Bayes' theorem. It estimates class probabilities using features extracted from the input data.

For text classification, the model can work with numerical text representations such as bag-of-words counts or TF-IDF features. The appropriate representation depends on the implementation.

## Methodology

1. Load and inspect the SMS dataset.
2. Prepare the message text and labels.
3. Split the dataset into training and testing sets.
4. Convert the text into numerical features if required.
5. Train the selected Naive Bayes classifier.
6. Predict message classes on the test set.
7. Evaluate the model using classification metrics.

## Model Evaluation

| Metric | Result |
|---|---|
| Accuracy | [1.00] |
| Precision | [1.00] |
| Recall | [1.00] |
| F1-score | [1.00] |

*Use the actual metrics produced by your notebook.*

## Key Findings

- Text representation used: [vectorizer].
- Naive Bayes variant: [GaussianNB()].


## How to Run the Project

1. Clone or download this repository.
2. Install the dependencies.
3. Open the Jupyter Notebook.
4. Run the cells in sequence.

Install the commonly used dependencies with:

`pip install pandas numpy scikit-learn matplotlib seaborn jupyter`

## Limitations

The dataset may not represent the full range of messages encountered in current communication systems. Slang, new scam techniques, language variation, and changing spam patterns may affect performance.

False positives are important because legitimate messages incorrectly labeled as spam may be missed by users.

## Conclusion

This project demonstrates how Naive Bayes can be applied to SMS text classification. It provides practical experience in text preprocessing, feature representation, probabilistic classification, and model evaluation.

## Author

[Anyagu Chuka]

## Project Type

Supervised Machine Learning | Text Classification
