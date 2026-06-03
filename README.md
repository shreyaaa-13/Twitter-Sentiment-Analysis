# Twitter Sentiment Analysis

A Natural Language Processing (NLP) project that analyzes sentiment patterns in Twitter data to understand public opinion, attitudes, and sentiment trends toward popular entities and topics.

The project combines text preprocessing, exploratory data analysis, feature engineering, and machine learning to classify tweets into sentiment categories and extract actionable insights from social media conversations.

---

## Problem Statement

Social media platforms generate massive volumes of user-generated content every day. Understanding the sentiment expressed in these conversations can help businesses, organizations, and researchers gauge public opinion, monitor brand perception, and identify emerging trends.

This project analyzes Twitter sentiment data and applies Natural Language Processing techniques to classify tweets into different sentiment categories while uncovering patterns associated with various entities and topics.

---

## Overview

The project explores how users express opinions on Twitter and classifies tweets into the following categories:

* Positive
* Negative
* Neutral
* Irrelevant

The workflow includes data cleaning, exploratory data analysis, TF-IDF feature extraction, and sentiment classification using Logistic Regression.

---

## Features

* Text preprocessing and cleaning
* Stopword removal and normalization
* Exploratory Data Analysis (EDA)
* Sentiment distribution analysis
* Entity-level sentiment analysis
* TF-IDF vectorization
* Logistic Regression classification
* Sentiment visualization

---

## Dataset

Dataset: Twitter Entity Sentiment Analysis Dataset

Source:
https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis

The dataset contains tweets related to various brands, organizations, and public figures along with sentiment labels.

---

## Project Structure

```text
Twitter-Sentiment-Analysis/
│
├── twitter_training.csv             # Dataset
├── Task_4.ipynb                     # NLP pipeline notebook
├── sentiment_distribution.png       # Sentiment distribution chart
├── entity_sentiment_breakdown.png   # Entity sentiment analysis
└── README.md                        # Documentation
```

---

## Methodology

### Data Cleaning

The following preprocessing steps were performed:

* Removed URLs
* Removed user mentions (@)
* Removed hashtags (#)
* Removed special characters
* Converted text to lowercase
* Removed English stopwords

### Exploratory Data Analysis

Visual analysis included:

* Sentiment distribution
* Word clouds
* Entity-level sentiment analysis

### Feature Engineering

Text data was converted into numerical features using:

* TF-IDF Vectorization

### Model Training

A Logistic Regression classifier was trained using TF-IDF features extracted from cleaned tweet text.

### Model Evaluation

The model was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score

---

## Output Samples

### Sentiment Distribution

<img width="585" height="387" alt="Sentiment Distribution" src="https://github.com/user-attachments/assets/58249705-e302-42e9-ba1d-80a57f5bfd0a" />

### Entity Sentiment Breakdown

<img width="1184" height="578" alt="Sentiment Breakdown" src="https://github.com/user-attachments/assets/f96bb0e1-6c29-4526-919e-befd4ec54cf7" />

---

## Key Insights

* Entities such as brands and public figures exhibit diverse sentiment profiles.
* Positive tweets frequently contain expressive and descriptive language.
* Logistic Regression performs effectively when combined with TF-IDF features for short-text classification.
* Proper text cleaning and normalization significantly improve model performance.
* Sentiment analysis can help organizations monitor public perception and brand reputation.

---

## Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* NLTK
* WordCloud
* Scikit-Learn
* Jupyter Notebook

---

## Skills Demonstrated

* Natural Language Processing (NLP)
* Text Preprocessing
* Sentiment Analysis
* TF-IDF Vectorization
* Logistic Regression
* Exploratory Data Analysis (EDA)
* Data Visualization
* Machine Learning
* Feature Engineering
* Python Programming

---

## Getting Started

### 1. Download the Dataset

Download the dataset from:

https://www.kaggle.com/datasets/jp797498e/twitter-entity-sentiment-analysis

### 2. Place the Dataset

Store the dataset as:

```text
twitter_training.csv
```

### 3. Run the Notebook

Open and execute:

```text
Task_4.ipynb
```

---

## Future Enhancements

* Fine-tune transformer-based models such as BERT
* Compare multiple machine learning algorithms
* Build a real-time sentiment monitoring dashboard
* Perform aspect-based sentiment analysis
* Deploy the model using Streamlit

---

## Author

Shreya Jadhav

Artificial Intelligence and Data Science Student
