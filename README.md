# Task 4: Classification with Logistic Regression

This repository contains the fourth task of my internship at **Elevate Labs**, focused on building a binary classifier using **Logistic Regression**.

## 📌 Objective

The objective of this task was to build a binary classifier using logistic regression, evaluating its performance with common metrics, and tuning the threshold for optimal results.

## 🛠️ Tools Used

- Python
- Scikit-learn
- Pandas
- Matplotlib
- Seaborn

## 🔍 Steps Performed

1. **Dataset**  
   Used the Breast Cancer Wisconsin dataset to predict whether a tumor is malignant (M) or benign (B).

2. **Preprocessing**  
   - Dropped unnecessary columns (`id`, `Unnamed: 32`)  
   - Encoded target variable `diagnosis`: M = 1, B = 0  
   - Split data into training and testing sets  
   - Standardized features using `StandardScaler`

3. **Model Training**  
   - Fitted a Logistic Regression model using Scikit-learn  
   - Predicted the test set and evaluated the model

4. **Model Evaluation**  
   - Evaluated model using:
     - Confusion Matrix
     - Precision, Recall, F1-Score
     - ROC-AUC score
     - ROC Curve

5. **Threshold Tuning**  
   - Tuned the decision threshold (e.g., 0.3) and observed its impact on performance metrics

## 📁 Files

- `task4.ipynb` - Notebook containing all model implementation and evaluation
- `Breast_Cancer_Wisconsin.csv` - Original dataset
- `README.md` - Documentation for this task

## 📊 Dataset

Dataset: [Breast Cancer Wisconsin (Diagnostic) Dataset](https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(diagnostic))

## 📈 Evaluation Metrics

- **Confusion Matrix**  
- **Precision**  
- **Recall**  
- **F1-Score**  
- **ROC-AUC**  
- **ROC Curve**

## 🔑 Key Learnings

- Logistic Regression for binary classification
- Model evaluation using confusion matrix and other metrics
- Threshold tuning to balance precision and recall
