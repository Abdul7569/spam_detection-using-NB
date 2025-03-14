# spam_detection-using-NB
# Spam Detection Using Naïve Bayes 📧🔍

![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Abdul7569/spam_detection-using-NB/blob/main/spam_detection.ipynb)

## 📌 Project Overview
This project implements a **Spam Detection** system using **Naïve Bayes** classifier. The model is trained on SMS messages to classify them as **Spam** or **Not Spam**.

## 🚀 Features
- **Text Preprocessing**: Cleaning, stopword removal, and tokenization.
- **Feature Extraction**: TF-IDF vectorization for text representation.
- **Model Training**: Using **Multinomial Naïve Bayes**.
- **Performance Evaluation**: Accuracy, Precision, Recall, and F1-score.
- **Live Prediction**: A function to predict whether a given message is spam.

## 📂 Dataset
- The dataset used is a collection of SMS messages labeled as `spam` or `ham`.
- Preprocessed to remove unnecessary characters and stopwords.

## ⚙️ Installation
To run this project, follow these steps:

```bash
# Clone the repository
git clone https://github.com/Abdul7569/spam_detection-using-NB.git

# Change directory
cd spam_detection-using-NB

# Install dependencies
pip install -r requirements.txt
