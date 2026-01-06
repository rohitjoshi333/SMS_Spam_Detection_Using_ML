
# SMS Spam Detection Using Machine Learning

This project is a working implementation of an SMS spam detection system developed as part of Artificial Intelligence Coursework 2. The project builds upon the research and documentation completed in Coursework 1 and focuses on creating a functional machine learning prototype.

## Project Overview
The goal of this project is to automatically classify SMS messages as either **spam** or **ham (legitimate)** using supervised machine learning techniques. With the increasing number of spam messages containing advertisements, phishing links, and scams, automated spam detection has become an important real-world application of machine learning.

This system uses Natural Language Processing (NLP) techniques to convert SMS text into numerical features and applies multiple classification algorithms to detect spam messages.

## Dataset
The dataset used in this project is an SMS spam dataset obtained from **GeeksforGeeks**. It contains real SMS messages labeled as spam or ham.

- Total messages: 5,574
- Classes: Spam and Ham
- Type: Supervised classification dataset

## Exploratory Data Analysis (EDA)
Before training the models, exploratory data analysis was performed to better understand the dataset. The following visualizations are included:
- Bar plot showing class distribution (spam vs ham)
- Histogram of SMS message lengths
- Boxplot to identify outliers in message length
- Scatter plot showing relationship between message length and class label
- Correlation heatmap using derived numeric features

These visualizations help in understanding class imbalance and feature behavior.

## Machine Learning Algorithms Used
The following supervised learning algorithms were implemented and compared:
- Multinomial Naive Bayes
- Logistic Regression
- Decision Tree Classifier

TF-IDF vectorization with unigram and bigram features is used to convert SMS text into numerical form.

## Evaluation Metrics
Each model is evaluated using standard classification metrics:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

The results are compared to identify the best-performing model.

## Application Functionality
The final system allows users to:
- Input an SMS message
- Receive a prediction indicating whether the message is spam or ham

The application runs in a Python/Jupyter Notebook environment and serves as a working AI prototype.

## Tools and Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook
- GitHub

## Project Status
This repository contains the complete implementation and documentation for Coursework 2. The project demonstrates a functional machine learning system based on the research conducted in Coursework 1.

## Author
Student Name  
Course: Artificial Intelligence  
Coursework: Coursework 2
