# Student-Performance-Prediction---Machine-Learning
Machine learning project that predicts student academic performance using regression and classification models, achieving sub-1 RMSE grade prediction and up to 90% classification accuracy.

This project applies machine learning techniques to predict student academic performance using demographic, academic, and behavioral data from the UCI Machine Learning Repository.

The analysis explores both:

* Regression models to predict final student grades (G3)
* Classification models to categorize students into Low, Medium, and High performance groups

The objective is to help educational institutions identify at-risk students early and support data-driven intervention strategies.

## Dataset

Source: UCI Machine Learning Repository – Student Performance Dataset

The dataset contains student demographic information, family background, academic history, study habits, and lifestyle factors.

## Models Evaluated

### Regression Models

* Linear Regression
* Random Forest Regressor
* Gradient Boosting Regressor
* Support Vector Regressor
* K-Nearest Neighbors Regressor

### Classification Models

* Random Forest Classifier
* AdaBoost Classifier
* Support Vector Classifier
* K-Nearest Neighbors Classifier
* Neural Network (MLPClassifier)
* Naive Bayes

## Key Results

### Best Regression Model

Random Forest Regressor

* RMSE: 0.97
* MAE: 0.63

### Best Classification Model

Random Forest Classifier (Undersampled Dataset)

* 100% Recall for High Performers
* 93% Recall for Low Performers
* 98% Precision for Medium Performers

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Seaborn
* Imbalanced-Learn

## Business Impact

Educational institutions can use these models to:

* Identify at-risk students earlier
* Improve intervention programs
* Monitor academic progress
* Support scholarship and retention initiatives
* Make data-driven academic decisions
