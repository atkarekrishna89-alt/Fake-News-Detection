# 📰 Fake News Detection using Machine Learning

## 📌 Overview

This project demonstrates how Machine Learning and Natural Language Processing (NLP) can be used to classify news articles as **Fake** or **Real**.

The notebook performs data preprocessing, feature extraction using **TF-IDF**, trains multiple machine learning models, compares their performance, and saves the best-performing model.

---

## 🚀 Features

- Load Fake & Real News datasets
- Data preprocessing using NLP
- Stopword removal
- TF-IDF Vectorization
- Train Naïve Bayes model
- Train Logistic Regression model
- Compare model performance
- Display Confusion Matrix
- Generate Classification Report
- Save the best model using Pickle
- Predict whether news is Fake or Real

---

## 🛠 Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- Pickle

---

## 📂 Dataset

Dataset used:

**Fake and Real News Dataset**

🔗 https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset

Required files:

- Fake.csv
- True.csv

---

## 📋 Workflow

1. Import required libraries
2. Load the dataset
3. Merge and shuffle the data
4. Clean and preprocess text
5. Convert text into TF-IDF vectors
6. Split data into training and testing sets
7. Train Naïve Bayes and Logistic Regression models
8. Evaluate model performance
9. Compare model accuracy
10. Save the best model (`model.pkl`) and vectorizer (`tfidf.pkl`)
11. Predict Fake or Real news

---

## 📊 Machine Learning Models

- Multinomial Naïve Bayes
- Logistic Regression

---

## 📈 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## ▶️ How to Run

1. Open the notebook in **Google Colab**.
2. Upload `Fake.csv` and `True.csv` when prompted.
3. Run all cells sequentially.
4. The notebook will train the models, evaluate them, and save:
   - `model.pkl`
   - `tfidf.pkl`

---

## 📌 Output

The notebook:

- Predicts whether a news article is **Fake** or **Real**
- Displays model accuracy and performance metrics
- Saves the best-performing model for future use

---

## 👨‍💻 Author

**Krishna Atkare**

B.E. Artificial Intelligence & Data Science

---

⭐ If you found this project useful, consider starring the repository.
