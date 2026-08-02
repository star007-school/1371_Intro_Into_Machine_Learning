# Final Project – Airline Tweet Sentiment Analysis

## Project Overview

The goal of this project was to develop a machine learning model capable of automatically classifying airline customer tweets as **positive**, **neutral**, or **negative**. Airlines receive thousands of customer comments every day, making it difficult to manually review every message. By applying Natural Language Processing (NLP) and machine learning, this project demonstrates how customer feedback can be analyzed automatically to provide faster insights and improve customer service.

## My Approach

I began by exploring the Airline Tweets dataset through **Exploratory Data Analysis (EDA)** to understand class distribution, tweet lengths, and overall dataset characteristics. I then cleaned and preprocessed the text by converting it to lowercase, removing URLs, mentions, hashtags, punctuation, numbers, and extra whitespace.

Next, I transformed the cleaned text into numerical features using **TF-IDF (Term Frequency–Inverse Document Frequency)**. I trained and compared two machine learning models:

* Logistic Regression
* Multinomial Naive Bayes

Both models were evaluated using accuracy, precision, recall, F1-score, and confusion matrices to compare their effectiveness at sentiment classification.

## Results

The **Logistic Regression** model produced the strongest overall performance, achieving approximately **76.5% accuracy** while outperforming the Naive Bayes model across the primary evaluation metrics. The project also identified common classification errors, particularly between neutral and negative tweets, and highlighted how class imbalance affected model performance.

## What I Learned

This project combined many of the machine learning concepts covered throughout the course into a complete Natural Language Processing workflow. I gained practical experience cleaning text data, creating TF-IDF features, training and evaluating multiple classification models, interpreting performance metrics, and understanding the challenges of sentiment analysis using real-world social media data. This project also reinforced the importance of thoughtful preprocessing and model evaluation when working with unstructured text.

## Skills & Tools

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Scikit-learn
* Natural Language Processing (NLP)
* Text Preprocessing
* TF-IDF Vectorization
* Logistic Regression
* Multinomial Naive Bayes
* Model Evaluation
* Confusion Matrix
* Sentiment Analysis

## Files

* `FP_AirlineTweets_StarYarbrough.ipynb`
