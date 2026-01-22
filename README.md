# sentiment-analysis-nlp
# 📝 Sentiment Analysis using NLP and Machine Learning

## 📌 Overview
This project focuses on analyzing sentiment in movie reviews using Natural Language Processing (NLP) techniques.  
The goal is to classify reviews as positive or negative based on the text content.

A machine learning approach was used to convert text data into numerical features and train a classification model.

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- NLP (TF-IDF)
- Logistic Regression

---

## 📊 Dataset
IMDb Movie Reviews Dataset

- review: text of the movie review  
- sentiment: positive or negative  

---

## ⚙️ Project Workflow
1. Load and explore the dataset
2. Clean and preprocess text data
3. Convert text into numerical vectors using TF-IDF
4. Split data into training and testing sets
5. Train Logistic Regression model
6. Evaluate model using precision, recall, and F1-score
7. Test the model on custom input reviews

---

## 📈 Model Evaluation
The model was evaluated using:
- Precision
- Recall
- F1-score
- Confusion Matrix

The trained model achieved around 88% accuracy on the test dataset.

---

## ▶️ Example Usage
```python
predict_sentiment("The movie was amazing and I really enjoyed it")
