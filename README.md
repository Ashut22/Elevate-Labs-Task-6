# Elevate-Labs-Task-6
# Iris Species Classification Using K-Nearest Neighbors (KNN)

## Overview
This task implements a K-Nearest Neighbors classifier to predict Iris species using the classic Iris dataset. It includes data preprocessing, model training, evaluation, and visualization of decision boundaries.

## Data Preparation
- The dataset is loaded from CSV and cleaned by dropping the `Id` column.
- Column names are standardized for consistency.
- The target variable `species` is label-encoded to numeric values.
- Features are standardized using `StandardScaler` to normalize the data.

## Model Training and Evaluation
- The data is split into training and test sets (80-20 split).
- KNN classifiers are trained for values of K from 1 to 10.
- Accuracy scores are computed on the test set to find the best K.
- The best model (K=3) achieved 100% accuracy.
- A confusion matrix is plotted to evaluate the model performance visually.

## Visualization
- A 2D decision boundary visualization is generated using the first two features (`sepallengthcm` and `sepalwidthcm`).
- The plot shows clear separation of classes and decision regions of the trained KNN model.

## Dependencies
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Usage
1. Load the dataset.
2. Preprocess and split the data.
3. Train KNN with desired K values.
4. Evaluate accuracy and plot confusion matrix.
5. Visualize decision boundaries using two features.

---

This implementation provides a clear example of applying KNN for multiclass classification with effective preprocessing and visualization.
