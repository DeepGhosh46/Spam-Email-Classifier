# 📧 Spam Email Classifier

A machine learning pipeline designed to automatically detect and filter spam emails based on text content. This project implements and compares two text classification algorithms—**Multinomial Naive Bayes** and **Support Vector Machines (SVM)**—using **Term Frequency-Inverse Document Frequency (TF-IDF)** for text feature extraction.

---

## 📌 Project Overview

Email classification is a core application of Natural Language Processing (NLP). This project provides a complete pipeline to preprocess email data, transform text into numerical features using TF-IDF, train machine learning models, evaluate performance, and classify custom email messages as **Spam** or **Ham**.

---

## 🚀 Features

- **Dual Model Architecture:** Compares Multinomial Naive Bayes and Support Vector Machines (SVM).
- **TF-IDF Vectorization:** Converts text into numerical feature vectors.
- **Text Preprocessing:** Cleans and prepares email text for classification.
- **Train-Test Split:** Uses an 80/20 split for unbiased model evaluation.
- **Performance Evaluation:** Measures Accuracy, Precision, Recall, and F1 Score.
- **Custom Predictions:** Test your own email messages using the trained model.

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK

---

## 📂 Project Structure

```text
Spam-Email-Classifier/
│── main.ipynb          # Model training and evaluation
│── emails.csv          # Email dataset
│── README.md           # Project documentation
```

---

## 📊 Dataset

The model is trained on a labeled email dataset containing two classes:

- **Spam** – Unwanted or malicious emails
- **Ham** – Legitimate emails

---

## ⚙️ Workflow

1. Load the email dataset.
2. Preprocess the text data.
3. Convert text into TF-IDF feature vectors.
4. Train the Machine Learning models.
5. Evaluate model performance.
6. Predict whether a custom email is Spam or Ham.

---

## 🤖 Models Used

- TF-IDF Vectorizer
- Multinomial Naive Bayes
- Support Vector Machines (SVM)

---

## 📈 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score

---

## 🔮 Future Improvements

- Deep Learning (LSTM/BERT)
- Phishing URL detection
- Multi-language spam detection
- Email attachment analysis
- FastAPI or Streamlit deployment

---