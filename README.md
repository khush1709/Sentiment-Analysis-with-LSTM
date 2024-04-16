# Sentiment Analysis with LSTM

This repository contains code for performing sentiment analysis on textual data using Long Short-Term Memory (LSTM) neural networks. Sentiment analysis aims to determine the sentiment expressed in a piece of text, such as whether it is positive, negative, or neutral.

## Overview

The provided code demonstrates how to:
- Preprocess textual data for sentiment analysis.
- Train an LSTM model using TensorFlow/Keras for sentiment classification.
- Evaluate the model's performance on a test dataset.
- Implement a simple chatbot interface for real-time sentiment prediction.

## Dataset

The code uses a dataset containing text samples labeled with sentiment classes (positive, negative, neutral). You can replace this dataset with your own or use a different dataset suitable for sentiment analysis tasks.

## Files

- `Sentiment_analysis.ipynb`: Jupyter Notebook containing the Python code for data preprocessing, modeling, and evaluation.
- `test.csv`: The dataset used in the project.
- `README.md`: This file providing an overview of the project.

## Usage

1. Install Dependencies: Ensure you have all the required dependencies installed. You can install them using pip install -r requirements.txt.
2. Prepare Data: Prepare your dataset or use the provided sample dataset. Ensure it is preprocessed and split into training and testing sets.
3. Training the Model: Train the LSTM model by running the training script. Adjust hyperparameters as needed to optimize performance.
4. Evaluate Model: Evaluate the trained model's performance on the test dataset to assess its accuracy and other metrics.
5. Run Sentiment Prediction Chatbot: Use the provided chatbot interface to predict the sentiment of user-input text in real-time.
