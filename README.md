## 📌 Project Overview

The SMS Spam Checker is a machine learning–based application that classifies SMS messages as Spam or Not Spam.
The project combines Natural Language Processing (NLP) with a Python-based GUI, allowing users to enter SMS content interactively and receive instant classification results.

This application demonstrates the end-to-end ML workflow: text preprocessing, feature extraction, model training, and deployment via a graphical user interface.

## 🚀 Features

📥 User-friendly GUI to input SMS text

🧠 Machine Learning–based spam detection

🔍 Text preprocessing using NLP techniques

📊 TF-IDF feature extraction

⚡ Real-time prediction results

🐍 Built entirely using Python

🛠️ Tech Stack

Programming Language: Python

GUI Framework: Tkinter

Machine Learning: Scikit-learn

NLP Techniques: Tokenization, Stopword Removal

Feature Engineering: TF-IDF Vectorization

Model Used: Naive Bayes / Logistic Regression (configurable)

## 📂 Project Structure
sms-spam-checker/
│
├── model/
│   ├── spam_model.pkl
│   └── tfidf_vectorizer.pkl
│
├── main.py              # GUI application
├── train_model.py       # Model training script
├── requirements.txt     # Project dependencies
├── dataset.csv          # SMS spam dataset
└── README.md

## 🧠 Machine Learning Workflow

Dataset Loading – SMS dataset with labeled spam/ham messages

Text Preprocessing – Lowercasing, punctuation removal, stopwords removal

Feature Extraction – TF-IDF Vectorization

Model Training – Supervised classification model

Model Serialization – Saved using pickle

GUI Integration – Model loaded into a Tkinter-based interface

🖥️ GUI Preview

Text input field for SMS content

“Check Spam” button

Output label displaying Spam or Not Spam

## 📊 Dataset

Publicly available SMS Spam Collection dataset

Contains labeled SMS messages (spam / ham)

Used for supervised learning and evaluation

## 🎯 Use Cases

Learning NLP and text classification

Demonstrating ML model deployment with GUI

Academic projects and portfolio showcase

Understanding end-to-end ML pipelines

## 📈 Future Enhancements

Add deep learning models (LSTM, BERT)

Improve preprocessing with lemmatization

Add confidence scores for predictions

Convert GUI to a web application using Flask or Streamlit

## 👨‍💻 Author

Anant Singh
Machine Learning & Data Analytics Enthusiast

## ⭐ Acknowledgements

Scikit-learn documentation

SMS Spam Collection Dataset

Python Tkinter community
