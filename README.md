# 🍽 Sentiment Analysis of Restaurant Reviews

## 📌 Project Overview
This project performs **Sentiment Analysis on Restaurant Reviews** using Natural Language Processing (NLP) techniques.  
The model classifies customer reviews as **positive or negative**, helping businesses understand customer feedback and improve service quality.

The project uses **text preprocessing, Bag of Words feature extraction, and a Naive Bayes classifier** to predict review sentiment.

---

## 📊 Dataset
The dataset contains **1000 restaurant reviews** labeled as:

- **1 → Positive Review**
- **0 → Negative Review**

Each review represents customer feedback about restaurant experience.

---

## ⚙️ Project Workflow

1. **Data Loading**
   - Import dataset using Pandas.

2. **Text Preprocessing**
   - Remove special characters
   - Convert text to lowercase
   - Remove stopwords
   - Apply stemming using PorterStemmer

3. **Feature Extraction**
   - Convert text to numerical format using **Bag of Words (CountVectorizer)**.

4. **Model Training**
   - Train a **Multinomial Naive Bayes classifier**.

5. **Model Evaluation**
   - Accuracy Score
   - Precision Score
   - Recall Score
   - Confusion Matrix visualization

---

## 🧠 Machine Learning Model
- **Algorithm:** Multinomial Naive Bayes
- **Feature Extraction:** Bag of Words (CountVectorizer)
- **Training/Test Split:** 80% / 20%

---

## 📈 Evaluation Metrics
The model performance is evaluated using:

- Accuracy
- Precision
- Recall
- Confusion Matrix

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

---

## 📂 Project Structure
