# Fake News Detection Project

This project implements an end-to-end Fake News Detection system using Natural Language Processing (NLP) and Machine Learning.

## Project Structure

├─ data/
│ ├─ train.tsv
│ ├─ valid.tsv
│ ├─ test.tsv
├─ notebooks/
│ ├─ fake_news_model.ipynb
├─ scripts/
│ ├─ preprocess.py
│ ├─ train_model.py
│ ├─ evaluate.py
│ └─ predict.py
├─ outputs/
│ ├─ confusion_matrix.png
│ ├─ roc_curve.png
├─ README.md
├─ requirements.txt

## Features

- Data cleaning and preprocessing
- TF-IDF vectorization
- Logistic Regression model
- Model evaluation: Accuracy, Classification Report, Confusion Matrix
- Top contributing words for fake and real news

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/YourUsername/FakeNewsDetection.git
