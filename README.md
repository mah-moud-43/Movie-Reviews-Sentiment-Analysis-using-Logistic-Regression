# 🎬 Movie Reviews Sentiment Analysis

This project is a complete pipeline for analyzing and classifying movie review sentiments using Natural Language Processing (NLP) and Logistic Regression.

---

## 🔍 Overview

We collected and cleaned real movie reviews from various genres, processed the text, visualized the sentiment distribution, and built a predictive model using logistic regression.

---

## 📌 Project Steps

### 1. 📥 Data Collection
- Used **TMDb API** and **Web Scraping** to gather movie reviews from genres:  
  `Action`, `Drama`, `Comedy`, `Romance`, `Horror`.

### 2. 🧹 NLP Preprocessing
- Lowercased text
- Removed punctuation and non-alphabetic characters
- Removed English stopwords
- Applied **negation handling**: flipped sentiment when negation words (not, never...) preceded positive or negative expressions.

### 3. 📊 Exploratory Data Analysis (EDA)
- Pie chart showing sentiment distribution.
- Heatmap for model performance visualization using confusion matrix.
- Used `plt.figure()` to size plots accurately.

### 4. 🧠 Text Vectorization
- Applied `TfidfVectorizer` (top 5000 features) to convert reviews into numerical format.

### 5. 🏗️ Model Building
- Used **Logistic Regression** for its simplicity and speed.
- Data split: 80% training / 20% testing.
- Balanced the dataset for better performance.

### 6. 📈 Model Evaluation
- Confusion Matrix with heatmap.
- Accuracy score for overall performance.
- Observed accuracy improvement with negation handling logic.

### 7. 🧪 Testing on New Texts
- Classified new English movie review samples with high accuracy.

---

## ⚙️ Technologies Used
- Python
- Google Colab
- `nltk`, `scikit-learn`, `matplotlib`, `seaborn`
- TMDb API

---

## ✅ Results
- Model achieved satisfying performance.
- Custom negation handling significantly improved sentiment accuracy.

---

## 📁 Structure
