# Email Spam Detection Using Machine Learning

## 📌 Project Overview

This project develops a machine learning-based system to classify text messages as **Spam** or **Ham (Not Spam)**.

Natural Language Processing (NLP) techniques are used to convert text messages into numerical features, which are then used to train classification models.

## 🎯 Objective

The main objectives of this project are:

- Preprocess text messages
- Convert text into numerical features using TF-IDF
- Train multiple machine learning classification models
- Compare model performance
- Evaluate the models using accuracy, precision, recall, F1-score and confusion matrix
- Predict whether new messages are Spam or Ham

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TF-IDF
- Multinomial Naive Bayes
- Logistic Regression

## 📊 Dataset

The project uses an SMS Spam dataset containing messages labelled as:

- **Ham** – legitimate messages
- **Spam** – unwanted messages

The dataset is loaded directly in the Jupyter Notebook.

## 🔄 Project Workflow

1. Import required libraries
2. Load the dataset
3. Explore the dataset
4. Check missing values
5. Convert labels into numerical values
6. Split the dataset into training and testing sets
7. Apply TF-IDF vectorization
8. Train Multinomial Naive Bayes
9. Train Logistic Regression
10. Evaluate model performance
11. Generate confusion matrix
12. Test the system with new messages

## 🤖 Machine Learning Models

### 1. Multinomial Naive Bayes

Used as the primary text classification algorithm because it works effectively with TF-IDF-based text features.

### 2. Logistic Regression

Used as a second classification model to compare performance.

## 📈 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Recall is particularly important in spam detection because incorrectly classifying spam as legitimate messages should be minimized.

## 🧪 Sample Prediction

The trained model can classify new messages as:

```text
SPAM
