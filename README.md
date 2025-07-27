# 🛍️ Sentiment Analysis on Amazon Product Reviews

This project aims to analyze customer sentiments on Amazon product reviews using both classical machine learning models and pretrained sentiment analysis tools.

## 📂 Dataset

- Source: [Kaggle - Amazon Product Reviews](https://www.kaggle.com/datasets)
- Contains textual reviews categorized as **positive** or **negative**

## 🧹 Data Preprocessing

The raw reviews were cleaned using the following steps:
- Lowercasing
- Removing punctuation and special characters
- Tokenization
- Stopword removal
- Lemmatization

## 🧠 Models Used

### 🔸 Classical Models
- **Logistic Regression**
- **Naive Bayes (MultinomialNB)**

### 🔹 Pretrained Model
- **TextBlob**: Polarity-based sentiment scoring

## 🧪 Evaluation

- Accuracy, Precision, Recall, F1-Score
- Confusion Matrix for model comparison

## ☁️ WordCloud Visualization

- **Positive WordCloud**: Words most frequently appearing in positive reviews
- **Negative WordCloud**: Words most commonly used in negative reviews

## 📊 Project Structure

