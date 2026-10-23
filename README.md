# SMS Spam Detection Using Machine Learning

## 1. Project Overview

This project classifies SMS text messages into two categories: **Spam** and **Ham (Not Spam)** using machine learning algorithms. Three algorithms are trained and compared to identify the best-performing model.

## 2. Objectives

- Classify SMS messages as spam or legitimate messages.
- Apply TF-IDF vectorization to convert text into numerical features.
- Train and evaluate K-Nearest Neighbors (KNN), Decision Tree, and Support Vector Machine (SVM).
- Compare the algorithms using accuracy, precision, recall, F1-score, and training time.
- Identify the best-performing algorithm.

## 3. Dataset

**Dataset:** SMS Spam Collection

The dataset contains SMS messages labelled as:
- **Ham:** Legitimate messages.
- **Spam:** Unwanted or fraudulent promotional messages.

Dataset source: https://archive.ics.uci.edu/dataset/228/sms+spam+collection

## 4. Technologies Used

- Python
- Google Colab
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## 5. Machine Learning Algorithms

### K-Nearest Neighbors (KNN)
Classifies a message based on the labels of similar messages.

### Decision Tree
Classifies messages using a sequence of feature-based decision rules.

### Support Vector Machine (SVM)
Finds a decision boundary that separates spam messages from legitimate messages.

## 6. Methodology

1. Load the SMS dataset.
2. Remove duplicate records and prepare the labels.
3. Split the data into training and testing sets.
4. Convert messages into numerical features using TF-IDF.
5. Train the KNN, Decision Tree, and SVM models.
6. Generate predictions for the test data.
7. Evaluate the models using classification metrics.
8. Compare results using a table, graph, and confusion matrices.
9. Select the best-performing algorithm.

## 7. Initial Results

The following results were obtained in the current Google Colab run.

| Algorithm | Accuracy | Precision | Recall | F1-Score |
|---|---:|---:|---:|---:|
| KNN | 95.94% | 97.85% | 69.47% | 
