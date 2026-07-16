# Spam Email Classifier

A machine learning pipeline designed to automatically detect and filter spam emails based on text content. This project implements and compares two text classification algorithms—Multinomial Naive Bayes and  Support Vector Machines (SVM)—using Term Frequency-Inverse Document Frequency (TF-IDF) for text feature extraction.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Installation](#installation)
- [Complete Implementation Code](#complete-implementation-code)
- [Usage](#usage)
- [Performance Comparison](#performance-comparison)
- [License](#license)

---

## Project Overview
Email classification is a core application of Natural Language Processing (NLP). This repository provides a complete pipeline to clean raw email data, transform textual features into normalized numerical matrices, train predictive models, evaluate generalization metrics, and handle custom raw string inference.

## Features
- **Dual Architecture:** Compares Multinomial Naive Bayes against Linear Support Vector Classification (LinearSVC).
- **Text Vectorization:** Implements Scikit-Learn's `TfidfVectorizer` to handle stop-word filtering and vocabulary tokenization.
- **Pure Validation:** Shuffles and partitions the dataset using an 80/20 train-test split to guarantee clean evaluation metrics.
- **Real-Time Testing:** Includes a integrated framework to run custom text strings through the pre-fit processing pipeline.

## Project Structure
```text
├── classifier.py      # Main Python script for pipeline execution
├── emails.csv         # Labeled email dataset
└── README.md          # Project documentation


## 🛠️ Tech Stack

- Python
- Pandas
- Scikit-learn
- NLTK

## 📂 Project Structure

```
Spam-Email-Classifier/
│── main.ipynb
│── emails.csv
└── README.md
```

## 📊 Dataset

The model is trained on a labeled spam email dataset containing two classes:

- **Spam** – Unwanted or fraudulent emails
- **Ham** – Legitimate emails

## ⚙️ Workflow

1. Input email text
2. Preprocess the text
3. Convert text into TF-IDF vectors
4. Predict using the trained model
5. Display Spam or Ham


## 📈 Model

The project uses:

- TF-IDF Vectorizer
- Multinomial Naive Bayes 
- Support Vector Machines

Evaluation metrics may include:

- Accuracy
- Precision
- Recall
- F1 Score

## 🔮 Future Improvements

- Deep Learning (LSTM/BERT)
- Phishing URL detection
- Multi-language support
- Email attachment scanning
- FastAPI deployment
