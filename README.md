# SMS Spam Detection with Machine Learning (Google Colab)

## 📥 Dataset
Download the dataset from Kaggle:  
**SMS Spam Collection Dataset** — https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset  
➡️ **Download and upload the CSV/TSV file directly into Google Colab** to start the project.  

## 🧠 Project Overview
This project detects whether an SMS message is **spam** or **not spam (ham)** using machine learning in **Google Colab**.

## 🔍 Steps We Completed

### 1. Data Loading & Inspection
- Loaded the dataset into Colab.
- Checked structure: `v1` (label) and `v2` (message).

### 2. Data Cleaning
- Handled missing values or duplicates.
- Standardized labels (`spam`/`ham`).

### 3. Text Preprocessing
- Converted text to lowercase.
- Removed punctuation and special characters.
- Tokenized and removed stopwords.
- Applied stemming/lemmatization.

### 4. Feature Extraction
- Used **CountVectorizer** and **TF‑IDF Vectorizer** to convert text into numeric features for model training.

### 5. Model Training
- Trained models like **Naive Bayes** and **Logistic Regression** directly in Colab.
- Optional: tested additional models (SVM, Random Forest).

### 6. Model Evaluation
- Split dataset into training and testing sets.
- Evaluated with:
  - Accuracy
  - Confusion Matrix
  - Precision, Recall, F1‑Score

## 🧪 Results
- The models successfully classified spam vs ham SMS messages.
- Evaluation metrics showed strong performance.


