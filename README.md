# Hate Speech Detection

A machine learning project for detecting and classifying hate speech in text data using natural language processing techniques.

## Dataset

The project uses the **HateSpeechData.csv** dataset which contains:
- The dataset contains tweets collected from Twitter and labeled for hate speech detection. Each tweet is annotated by multiple reviewers and classified into three categories: Hate Speech, Offensive Language, or Neither. The dataset includes information about the number of annotators who labeled the tweet as hate speech, offensive language, or neither, along with the final class label.

## Features

- **Text Preprocessing**: Remove URL's, puctuations, stopwords, perform tokenization, lowercasing and stemming.
- **Feature Engineering**: TF-IDF vectorization to convert the text -> numeric
- **Multiple ML Models**: Training and comparison of various classification algorithms
  - Logistic Regression
  -  Naive Bayes
  - Support Vector Machine (SVM)
  - Random Forest
  - Decision Tree
- **Performance Evaluation**: Comprehensive metrics including accuracy, precision, recall, and F1-score
- **Final Classification with Random Forest**:
  - Integration of polarity scores as features
  - Random Forest Classifier training
  - Final prediction of the a tweet using Random Forest classifier
