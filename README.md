# 📧 Spam Text Classifier (ML + DL)

A spam message detection system built using **both traditional machine learning** (Naïve Bayes with TF-IDF) and **deep learning** (LSTM & GRU) models.  
The project cleans and preprocesses SMS data, extracts features, trains multiple models, tunes hyperparameters, and evaluates their performance.

---

## 📌 Features
- **Data Preprocessing**
  - Remove HTML tags, punctuation, numbers, and stopwords
  - Convert text to lowercase
- **Feature Extraction**
  - TF-IDF vectorization for Naïve Bayes
  - Tokenization & padding for deep learning models
- **Models Implemented**
  - Multinomial Naïve Bayes
  - LSTM (Long Short-Term Memory)
  - GRU (Gated Recurrent Unit)
- **Hyperparameter Tuning**
  - GridSearchCV for Naïve Bayes
- **Performance Metrics**
  - Accuracy
  - Classification Report (Precision, Recall, F1-score)

---

## 🛠 Tech Stack
- **Languages:** Python
- **Libraries:**
  - pandas, numpy
  - scikit-learn
  - nltk
  - tensorflow / keras
  - re, string

---

## 📂 Dataset
- **Source:** [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)  
- **Columns:**
  - `label` → ham (0) or spam (1)
  - `text` → original message

---

## 🚀 How to Run

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/spam-text-classifier-ml-dl.git
cd spam-text-classifier-ml-dl
