# Breast Cancer Classification using Machine Learning
### Project Overview
This project uses the Breast Cancer Wisconsin Dataset from the Scikit-learn library to classify breast tumors as Malignant or Benign using supervised machine learning algorithms.
The project includes data preprocessing, model training, performance comparison, and prediction using a new sample.

### Objective
The objective of this project is to build and compare different supervised machine learning classification models for breast cancer prediction and identify the best-performing model.

### Dataset
Dataset: Breast Cancer Wisconsin Dataset

Source: Scikit-learn (sklearn.datasets.load_breast_cancer)

Number of Samples: 569

Features: 30

Target Classes:

0: Malignant

1: Benign

### Technologies Used
Python

Pandas

NumPy

Scikit-learn

Jupyter Notebook

### Data Preprocessing

The following preprocessing steps were performed:

Loaded the dataset

Checked for missing values

Checked for duplicate values

Detected and handled outliers 

Split the dataset into training and testing sets

Applied feature scaling using StandardScaler

### Machine Learning Models

The following classification algorithms were implemented:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Support Vector Machine (SVM)

K-Nearest Neighbors (K-NN)

### Model Performance

| Model | Accuracy |
|--------|----------|
| Logistic Regression | 98.25% |
| Support Vector Machine (SVM) | 98.25% |
| Random Forest | 95.61% |
| K-Nearest Neighbors (K-NN) | 95.61% |
| Decision Tree | 91.23% |

### Best Model

Logistic Regression

Support Vector Machine (SVM)

Both models achieved the highest accuracy of 98.25%.

### Prediction
The trained model was used to predict whether a new patient has Malignant or Benign breast cancer.

### Conclusion

This project successfully classified breast cancer tumors using five supervised machine learning algorithms. After preprocessing the dataset, the models were trained and evaluated based on their accuracy. Logistic Regression and Support Vector Machine (SVM) achieved the highest accuracy (98.25%), making them the best-performing models for this dataset. Decision Tree showed the lowest accuracy among the five models. Overall, the results show that machine learning can effectively classify breast cancer and support early diagnosis with high accuracy.
