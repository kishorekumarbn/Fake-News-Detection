# Fake-News-Detection
This project involves building a machine learning algorithm to detect fake news.Naive Bayes Algorithm has been used here

Fake News Detection

This is a beginner-level project aimed at building a Fake News Detection System to classify news articles as either Real or Fake using machine learning.
🌟 Project Overview

With the growing prevalence of misinformation, this project leverages a machine learning model to tackle the challenge of fake news classification. The goal is to provide an accurate and user-friendly system.
✨ Features

    Detects whether news articles are Real or Fake.
    User-friendly interface for inputting custom news articles.
    Achieved an accuracy of 86%.

🛠️ Technologies Used

    Python: Programming language.
    Multinomial Naive Bayes: Classification algorithm.
    TF-IDF Vectorizer: Feature extraction for text data.

🔍 Dataset

    Source: Kaggle
    Size: 6335 rows with 3 columns:
        Title: News article title.
        Text: News article body.
        Label: Real or Fake.

📖 Steps Followed

    Data Preprocessing:
        Removed unnecessary columns.
        Handled missing data.
        Split data into 80% training and 20% testing sets.
        Transformed text into numerical vectors using TF-IDF Vectorizer.
    Model Training:
        Trained the model on labeled data.
    Evaluation:
        Achieved an accuracy of 86% with an F1-score of 0.88 for Real news detection.

📊 Results

    Accuracy: 86%
    Key Metrics:
        Precision: High for detecting Fake news.
        Recall: Excellent for identifying Real news.

🚀 How to Use

    Clone the repository:

git clone <repository-url>

Install dependencies:

pip install -r requirements.txt

Run the application:

    python app.py

    Enter a news article and get predictions.

🙌 Acknowledgments

    Dataset: Kaggle
    Guidance and tutorials from the ML community.

