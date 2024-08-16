# SMS_Spam_Prediction
# Spam Classification with DistilBERT

This project demonstrates how to build and train a spam classification model using the DistilBERT transformer model. The model is trained to classify SMS messages as either "spam" or "ham" (not spam).

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Data](#data)
- [Model Training](#model-training)
- [Prediction](#prediction)
- [Usage](#usage)
- [License](#license)

## Overview

This project uses the DistilBERT model from the Hugging Face `transformers` library for spam detection. The pipeline includes:
1. Data loading and preprocessing
2. Tokenization of text data
3. Model training and evaluation
4. Predicting whether new messages are spam or not

## Installation

To set up the environment, install the required libraries using pip:

```bash
pip install pandas scikit-learn transformers torch
