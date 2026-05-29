Sentiment Analysis using Machine Learning
📌 Project Overview

This project focuses on classifying emotions in text data using Machine Learning techniques. The goal is to predict the emotion expressed in a given comment using natural language processing and classification algorithms.

📂 Dataset
Dataset contains two columns:
Comment: Input text data
Emotion: Target label (emotion class)
⚙️ Workflow
1. Data Preprocessing

The text data was cleaned using the following steps:

Converted text to lowercase
Removed punctuation and numbers
Tokenized text into words
Removed stopwords

These steps help reduce noise and improve model accuracy.

2. Feature Extraction

TF-IDF (Term Frequency–Inverse Document Frequency) was used to convert text into numerical features.

TF-IDF gives higher importance to meaningful words while reducing the weight of commonly occurring words.

3. Model Building

Two machine learning models were trained:

Naive Bayes (MultinomialNB)
A fast probabilistic model suitable for text classification.
Support Vector Machine (LinearSVC)
A powerful classifier that performs well on high-dimensional text data.
4. Model Evaluation

Models were evaluated using:

Accuracy
F1-score
📈 Results
SVM performed better compared to Naive Bayes in terms of accuracy and F1-score.
This is because SVM handles complex decision boundaries in text data more effectively.
🛠️ Technologies Used
Python
Pandas, NumPy
Scikit-learn
NLTK
Google Colab
🚀 How to Run
Open the notebook in Google Colab
Mount Google Drive
Load dataset (nlp_dataset.csv)
Run all cells sequentially
📁 Project Structure
Module 5 Sentiment Analysis/
│
├── nlp_dataset.csv
├── Module 5 Sentiment Analysis.ipynb
└── README.md
👨‍🎓 Learning Outcome
Text preprocessing techniques in NLP
TF-IDF feature extraction
Machine learning classification models
Model evaluation and comparison
📌 Conclusion

This project demonstrates how machine learning can be used to classify emotions from text data effectively using NLP techniques.
