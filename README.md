# Email Spam Classifier

## Overview

This project is a Machine Learning-based Email Spam Classifier that classifies messages as either **Spam** or **Ham (Not Spam)**.

The project uses the SMS Spam Collection dataset containing 5,572 messages. The text data is converted into numerical features using **TF-IDF (Term Frequency-Inverse Document Frequency)**, and **Logistic Regression** is used as the classification algorithm.

## Technologies Used

* Python
* NumPy
* Pandas
* Scikit-learn
* TF-IDF Vectorization
* Logistic Regression
* Jupyter Notebook

## Project Workflow

1. Load the email/SMS dataset using Pandas.
2. Handle missing values.
3. Convert the `spam` and `ham` categories into numerical labels.
4. Split the dataset into training and testing sets.
5. Convert text messages into TF-IDF features.
6. Train a Logistic Regression model.
7. Evaluate the model using accuracy.
8. Predict whether a message is Spam or Ham.

## Dataset

The dataset contains two columns:

* `Category` – Spam or Ham
* `Message` – The actual text message

The dataset contains **5,572 records**.

## Machine Learning Model

### Logistic Regression

Logistic Regression is used to classify messages into two categories:

* `0` → Spam
* `1` → Ham

The dataset is divided into training and testing sets using an 80:20 split.

## Feature Extraction

TF-IDF Vectorization is used to convert text messages into numerical features. The project uses lowercase conversion and English stop-word removal.

## Results

The trained Logistic Regression model is evaluated on the test dataset using accuracy.

## Future Improvements

* Add precision, recall and F1-score.
* Add a confusion matrix.
* Compare Logistic Regression with other classification algorithms.
* Build a simple web interface for real-time spam detection.
* Improve text preprocessing and model performance.
