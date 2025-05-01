# Breast Cancer Detection ML Pipeline
This project provides a complete machine learning pipeline for breast cancer detection using the Wisconsin Diagnostic Breast Cancer (WDBC) dataset. It includes data loading, preprocessing, visualization, model training, evaluation, hyperparameter tuning, and prediction functionalities.

Features
Automatic Dataset Loading: Attempts to load data from UCI, GitHub, or prompts for manual upload.

Data Preprocessing: Cleans data, encodes diagnosis labels, handles missing values, and scales features.

Visualization: Generates plots for diagnosis distribution, feature correlations, and relationships between top features and the target.

Model Training & Evaluation: Trains and evaluates multiple classifiers:

Logistic Regression

K-Nearest Neighbors

Support Vector Machine

Random Forest

Model Selection & Tuning: Selects the best model based on cross-validation accuracy and performs hyperparameter tuning using grid search.

Feature Importance: Displays and visualizes feature importances for Random Forest.

Learning Curve Analysis: Plots learning curves to assess model performance and overfitting.

Prediction Function: Provides a function to predict cancer diagnosis for new input data.

Usage
Install Dependencies:

Python 3.x

numpy, pandas, matplotlib, seaborn, scikit-learn

For Colab: google.colab

Run the Script:

The script will attempt to load the dataset automatically. If unsuccessful, it will prompt for manual upload.

Follow the outputs for visualizations, model performance, and best model selection.

Make Predictions:

Use the predict_cancer(model, scaler, input_data) function to predict on new samples.

Outputs
Saves plots for:

Diagnosis distribution

Feature correlation matrix

Top feature boxplots

Pairplots of top features

Confusion matrices

ROC curves

Feature importance (Random Forest)

Learning curves
