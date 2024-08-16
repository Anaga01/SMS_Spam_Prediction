# SMS_Spam_Prediction
# Spam Classification with DistilBERT

This project demonstrates how to build and train a spam classification model using the DistilBERT transformer model. The model is trained to classify SMS messages as either "spam" or "ham" (not spam).

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Data Loading and Preprocessing](#Data-Loading-and-Preprocessing)
- [Model Training](#model-training)
- [Prediction](#prediction)
- [Usage](#usage)


## Overview

Explanation: This section gives a brief summary of what the project does. It outlines the main steps involved in the spam classification process:

Data loading and preprocessing: This step involves loading the SMS data and preparing it for analysis.
Tokenization of text data: Here, the text data is converted into a format that can be processed by the DistilBERT model.
Model training and evaluation: This step involves training the DistilBERT model on the data and evaluating its performance.
Predicting whether new messages are spam or not: Finally, the trained model is used to predict whether new messages are spam.

## Installation

To set up the environment, install the required libraries using pip:

```bash
pip install pandas scikit-learn transformers torch


## Data
This section explains how to load and preprocess the data. It describes the format of the data and how it is split into features and labels.
Loading the dataset: Reads the SMS data from a file and assigns column names.
Mapping labels: Converts 'ham' and 'spam' labels to numerical values (0 and 1).
Splitting data: Divides the dataset into features (messages) and labels, and then splits it into training and test sets.


## Model Training
Explanation: This section covers the steps to train the DistilBERT model. It includes tokenization, dataset preparation, model initialization, and training.


## Usage
Explanation: Provides instructions on how to run the project, including loading the data, training the model, and making predictions.

Load and preprocess the data: Ensure that the SMSSpamCollection.txt file is in the correct path or adjust the path accordingly.
Train the model: Run the provided code to train the DistilBERT model.
