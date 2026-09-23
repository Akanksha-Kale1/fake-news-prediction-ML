# Fake News Prediction Using Machine Learning

# Project Overview
This project predicts whether a news article is Fake News or True News using Machine Learning.
The project uses a dataset containing fake and true news articles. The news text is processed and converted into numerical features using TF-IDF Vectorization. Three classification algorithms are then trained to classify the news.

# Technologies Used
* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* Matplotlib
* Seaborn
* Google Colab

# Text Preprocessing

The project includes text preprocessing techniques such as:
* Converting text to lowercase
* Removing punctuation
* Removing URLs
* Removing non-alphabetic characters
* Removing stopwords
* Removing digits
* Stemming

## Feature Extraction

* TF-IDF (Term Frequency-Inverse Document Frequency)** is used to convert text data into numerical features that can be used by machine-learning algorithms.

## Classification Algorithms

The following classification algorithms are used:
1. Logistic Regression 
2. Decision Tree Classifier 
3. Random Forest Classifier 

# Dataset

The dataset contains two types of news:
* `0` → Fake News
* `1` → True News

The dataset contains * 44,898 news articles * in total.

The original dataset files are not included in this repository.

# Project Workflow

```text
Dataset
   ↓
Data Preprocessing
   ↓
Text Cleaning
   ↓
Train-Test Split
   ↓
TF-IDF Vectorization
   ↓
Machine Learning Models
   ↓
Model Evaluation
   ↓
Fake News / True News Prediction

# Model Results

The following accuracy values were obtained in the notebook:

| Model               | Accuracy |
| ------------------- | -------: |
| Logistic Regression |   98.79% |
| Decision Tree       |   99.58% |
| Random Forest       |   99.08% |

These results are based on the particular train-test split used in the notebook.

# Model Evaluation

The models were evaluated using:
* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix
* Classification Report

# Prediction

The project also contains a `manual_testing()` function that accepts a new news article as input and predicts whether it is:
* Fake News *
* True News *

# Project Objective

The objective of this project is to demonstrate how text processing, TF-IDF feature extraction, and machine learning classification algorithms can be used to classify news articles based on patterns learned from a labeled dataset.

