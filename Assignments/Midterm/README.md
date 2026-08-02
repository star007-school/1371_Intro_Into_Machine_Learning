# Midterm Project – End-to-End Machine Learning Investigation

## Project Overview

The goal of this project was to complete an end-to-end machine learning investigation using the Titanic dataset. The objective was to analyze passenger data, prepare it for machine learning, build multiple classification models, and evaluate their ability to predict passenger survival. This project combined many of the concepts learned throughout the course into a complete machine learning workflow.

## My Approach

I began by performing **Exploratory Data Analysis (EDA)** to better understand the dataset. Using visualizations, I explored relationships between passenger characteristics and survival, finding that gender and age appeared to influence survival outcomes.

Next, I prepared the data by handling missing values and encoding categorical variables. Missing values in the **Age** feature were replaced using the median, and the **Embarked** feature was converted into numerical values using one-hot encoding. These preprocessing steps ensured the data was suitable for machine learning models.

I then trained two classification models:

* Logistic Regression (baseline model)
* Random Forest Classifier

Both models were evaluated using accuracy, a confusion matrix, and a classification report to compare their performance.

## Results

Both the Logistic Regression and Random Forest models achieved an accuracy of approximately **81%** on the testing data. I also analyzed precision, recall, and the confusion matrix to better understand each model's strengths and limitations. Although both models produced similar overall accuracy, the additional evaluation metrics provided deeper insight into prediction performance beyond a single accuracy score.

## What I Learned

This project reinforced the importance of following the complete machine learning process—from data exploration and preprocessing to model training and evaluation. I gained practical experience interpreting model performance, comparing different algorithms, and understanding that selecting the best model requires more than simply comparing accuracy. This project strengthened my confidence in applying machine learning techniques to solve real-world classification problems.

## Skills & Tools

* Python
* Jupyter Notebook
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Exploratory Data Analysis (EDA)
* Data Preprocessing
* Logistic Regression
* Random Forest Classifier
* Model Evaluation
* Confusion Matrix
* Classification Report

## Files

* `MT_Star_Yarbrough_ITAI1371.ipynb`
