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

```

