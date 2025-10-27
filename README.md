## Australia Weather Prediction

Final Project – IBM Data Science Machine Learning (Coursera)

This project was developed as part of the IBM Data Science Machine Learning course on Coursera. It focuses on predicting whether it will rain tomorrow in Australia based on various weather-related features using the Rain in Australia dataset from Kaggle.

# Project Overview

The goal was to build a classification model that predicts the likelihood of rainfall the next day. The dataset includes features like:

Date and Location

Minimum and Maximum Temperature

Humidity, Wind Speed, and Sunshine

Rainfall and Atmospheric Pressure

# Data Processing

Handled missing values using appropriate imputations

Scaled numerical features for balanced model performance

Encoded categorical variables with OneHotEncoder

Combined preprocessing steps using ColumnTransformer for cleaner workflow

# Models Used

Two machine learning models were trained and compared:

🔹 Logistic Regression
Metric	Value
Accuracy	84%
Precision (Yes)	0.74
Recall (Yes)	0.51
F1-Score (Yes)	0.60
🔹 Random Forest Classifier
Metric	Value
Accuracy	83%
Precision (Yes)	0.69
Recall (Yes)	0.51
F1-Score (Yes)	0.59

# Insights

Logistic Regression slightly outperformed Random Forest in this case, achieving better generalization.

The dataset showed class imbalance, which affected the recall for the “Yes” (Rain Tomorrow) class.

Feature scaling and encoding significantly improved model stability.

# Tools & Libraries

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

Jupyter Notebook (for development and analysis)


📁 Dataset

Source: Rain in Australia – Kaggle

# Author

Sahil Negi
Project as part of IBM Data Science Machine Learning Specialization
