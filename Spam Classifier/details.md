# Spam Classifier using Streamlit

This application uses a pre-trained model to classify messages as spam or not spam.

## Overview

This Streamlit app predicts the probability of a message being spam using a pre-trained model and a TF-IDF Vectorizer. The model leverages a Multinomial Naive Bayes classifier for prediction.

## Prerequisites

- Python 3.6+
- Libraries: `streamlit`, `nltk`, `scikit-learn`


## Usage

- Enter the text message in the provided text area.
- Click on the "Predict" button to classify the message as spam or not spam.

## Files

- `app.py`: The main Streamlit application code.
- `model2.pkl`: Pre-trained model file.
- `vectorizer2.pkl`: Pre-trained TF-IDF Vectorizer file.
- `requirements.txt`: List of required Python packages.

## Data and Model

The model used in this application has been pre-trained using a dataset of labeled messages for spam classification.


