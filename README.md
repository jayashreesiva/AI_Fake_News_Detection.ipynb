# 📰 AI-Based Fake News Detection Using Machine Learning

An **AI-Based Fake News Detection System** developed using **Python and Machine Learning** in Google Colab.

The system analyzes a news article and predicts whether it is **Real** or **Fake** using **TF-IDF Vectorization** and **Logistic Regression**.

---

## 📌 Project Overview

Fake news can spread misleading or false information through online platforms.

This project demonstrates a simple Machine Learning approach for classifying news articles into two categories:

* ✅ Real
* ❌ Fake

The system converts news text into numerical features using **TF-IDF** and then uses **Logistic Regression** to predict the news category.

---

## 🎯 Objectives

* Detect whether a news article is Real or Fake.
* Apply Natural Language Processing techniques.
* Convert text into numerical features using TF-IDF.
* Train a Machine Learning classification model.
* Evaluate the model using standard metrics.
* Provide an interactive news prediction system.
* Save the trained model and vectorizer for future use.

---

## 🛠️ Technologies Used

| Technology          | Purpose                        |
| ------------------- | ------------------------------ |
| Python              | Programming language           |
| Google Colab        | Development environment        |
| Pandas              | Dataset handling               |
| NumPy               | Numerical operations           |
| Scikit-learn        | Machine Learning               |
| TF-IDF              | Text feature extraction        |
| Logistic Regression | Classification                 |
| Matplotlib          | Visualization                  |
| Seaborn             | Confusion matrix visualization |
| Joblib              | Model saving                   |

---

## 📚 Dataset

For this educational project, a small **synthetic/demo dataset** was created.

The dataset contains:

* **20 news articles**
* **10 Real news articles**
* **10 Fake news articles**

The dataset contains two columns:

```text
news
label
```

Example:

```text
News:
The government announced a new public transportation project.

Label:
Real
```

Another example:

```text
News:
A secret machine can make unlimited money from ordinary paper.

Label:
Fake
```

> ⚠️ This dataset is created for demonstration and learning purposes. It is not a real-world fact-checking dataset.

---

## 🧠 Machine Learning Approach

The project follows this workflow:

```text
News Article
     ↓
Text Preprocessing
     ↓
TF-IDF Vectorization
     ↓
Logistic Regression
     ↓
Prediction
     ↓
Real / Fake
```

### 1. TF-IDF Vectorization

TF-IDF stands for:

**Term Frequency – Inverse Document Frequency**

It converts text into numerical values that the Machine Learning model can understand.

The project also uses:

```python
ngram_range=(1, 2)
```

This allows the model to consider both individual words and two-word combinations.

---

### 2. Logistic Regression

Logistic Regression is used as the classification algorithm.

It learns patterns from the training news articles and predicts whether a new article belongs to the **Real** or **Fake** class.

---

## 📊 Model Evaluation

The model is evaluated using:

### Accuracy

Measures the percentage of correctly classified news articles.

### Classification Report

Provides:

* Precision
* Recall
* F1-score
* Support

### Confusion Matrix

Shows the number of:

* Correct Real predictions
* Incorrect Real predictions
* Correct Fake predictions
* Incorrect Fake predictions

---

## 💬 Example Predictions

The system can analyze news such as:

```text
Scientists published a new study about renewable energy t
```
