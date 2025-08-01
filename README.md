<!-- PROJECT TITLE -->
<h1 align="center"> Email Spam Detection using NLP & Machine Learning</h1>

---

##  Project Overview

This project aims to build an **Email Spam Detection** system using **Natural Language Processing (NLP)** and **Machine Learning**. The system analyzes the content of emails and predicts whether a message is **spam** or **not spam (ham)** based on patterns learned from historical data.

Key technologies used:
- Python
- Scikit-learn
- NLP (tokenization, stopword removal, etc.)
- Naive Bayes Classification

---

##  Dataset Information

- **Source**: Public dataset containing email text labeled as spam or not.
- **Total Records**: ~5,728 emails
- **Label Column**: `spam`  
  - `1` → Spam  
  - `0` → Not Spam (Ham)

Each record contains an email message and its corresponding classification label.

---

##  Project Workflow

###  Section 1: Data Preparation

1. **Loading the Data** – Read the dataset into a DataFrame  
2. **Data Visualization** – Explore class distributions and word frequencies  
3. **Data Cleaning** – 
   - Remove duplicates  
   - Lowercase conversion  
   - Remove stopwords and punctuation  
4. **Text Vectorization** – Convert text into numerical format using TF-IDF  
5. **Train-Test Split** – Split dataset into 80% training and 20% testing

###  Section 2: Model Building & Evaluation

- Use **Multinomial Naive Bayes Classifier** from `scikit-learn`
- Train the model on preprocessed training data
- Evaluate using:
  -  Accuracy Score
  -  Classification Report
  -  Confusion Matrix

---

## 🔗 References & Resources

1. [Spam Detection with Machine Learning](https://bit.ly/3nwiKtA)
2. [Understanding Naive Bayes Algorithm](https://bit.ly/3zc9SLH)
3. [Evaluating Machine Learning Models](https://bit.ly/3B12VOO)

---

##  Future Improvements

- Integrate deep learning models (e.g., LSTM)
- Deploy as a web application using Flask or Streamlit
- Improve preprocessing using advanced NLP techniques like Lemmatization

---

> *"Filtering spam might seem small, but it's the first wall of defense against cyber threats. Smart filters = safer inbox."*

---
