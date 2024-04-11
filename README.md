# ProsperNet: Predicting High-Income Individuals

## Project Overview
This project develops a predictive model to determine if an individual's income exceeds $50K using supervised learning algorithms applied to the 1994 U.S. Census data. The goal is to enhance fundraising strategies for non-profit organizations by targeting potential donors more effectively.

## Dataset
The dataset, known as the "Adult" dataset, comes from the UCI Machine Learning Repository. It includes over 32,000 records with 14 features plus a target label. For more details, visit [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/20/census+income).

## Methodology
- Data Acquisition and Pre-processing: Data is cleaned, normalized, and split into training and testing sets.
- Exploratory Data Analysis (EDA): We conduct an initial analysis to understand patterns and correlations.
- Feature Selection: The chi-squared method is used to determine the most relevant features.
- Model Fitting and Hyperparameter Tuning: We fit Logistic Regression, AdaBoost, Decision Trees, and MLP Classifier models, tuning them for optimal performance.
- Model Evaluation: Models are tested for accuracy, precision, recall, F1 score, and ROC-AUC.

## Results
AdaBoost and Decision Trees outperform other models in accuracy and ROC-AUC score, demonstrating their effectiveness in classification tasks within this context.

## Ethical Considerations
The aim is to ensure fairness and avoid biases in predictions, maintaining a commitment to inclusivity.

## Conclusion and Recommendations
AdaBoost is recommended for its balance between performance and training time, while Decision Trees offer versatility and interpretability. Logistic Regression provides a baseline for comparison.

## Usage
This model can assist non-profits in identifying potential donors, contributing to more informed and efficient fundraising strategies.
