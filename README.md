# Fake News Detection using Machine Learning

This project implements a Natural Language Processing (NLP) pipeline to classify news articles as Fake or Real using supervised machine learning techniques.

The model processes textual data, converts it into numerical representations, and predicts authenticity based on learned patterns.

---

## Features
- Text cleaning and preprocessing
- Stopword removal
- Tokenization
- TF-IDF vectorization
- Supervised model training
- Accuracy and evaluation metrics
- Prediction on custom news input

---

## Technologies Used
- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib / Seaborn

---

## Methodology

### 1. Data Preprocessing
- Remove punctuation and special characters
- Convert text to lowercase
- Remove stopwords
- Tokenization

### 2. Feature Extraction
- Convert text into numerical vectors using TF-IDF

### 3. Model Training
- Split dataset into training and testing sets
- Train classification model (Logistic Regression / Naive Bayes / etc.)
- Evaluate using:
  - Accuracy
  - Precision
  - Recall
  - F1-score

### 4. Prediction
- Input new news article
- Transform using trained TF-IDF vectorizer
- Predict label (Fake / Real)

---

## Model Pipeline

- Load Dataset
- Clean Text
- Vectorize Text (TF-IDF)
- Train Model
- Evaluate Performance
- Predict New Input

---

## Project Structure

fake-news-detection/
│
├── fake_new_detection.ipynb
├── dataset.csv
├── model.pkl (if saved)
├── vectorizer.pkl (if saved)
└── README.md

---

## Results
- Successfully classified news articles
- Demonstrated strong performance on test dataset
- Effective text pattern learning using TF-IDF

---

## How to Run

Open Jupyter Notebook:

```bash
jupyter notebook fake_new_detection.ipynb
```

Run all cells to train and evaluate the model.

---

## Future Improvements
- Use LSTM / BERT models
- Add cross-validation
- Deploy as web application
- Improve preprocessing pipeline
