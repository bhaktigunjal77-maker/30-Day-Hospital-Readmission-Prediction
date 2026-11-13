# 30-Day-Hospital-Readmission-Prediction
# 30-Day Hospital Readmission Prediction

## Project Overview
This project develops a machine learning model to predict the likelihood of hospital readmission within 30 days of patient discharge.

## Dataset
The dataset contains 800 patient records and 11 variables, including age, gender, diagnosis, primary medication, comorbidity count, prior admissions, length of stay, discharge disposition, follow-up booking, and 30-day readmission status.

## Methodology
1. Data inspection and preprocessing
2. Stratified training and testing split
3. Categorical encoding and numerical preprocessing
4. Class imbalance handling using SMOTE
5. Random Forest classification
6. Model comparison using class weights
7. Evaluation using accuracy, precision, recall, F1-score, ROC-AUC, and average precision
8. Confusion matrix, ROC curve, and precision-recall curve
9. Permutation feature importance
10. Export of test-set predictions

## Tools and Technologies
- Python
- Pandas and NumPy
- Scikit-learn
- Imbalanced-learn
- Matplotlib
- Google Colab

## Project Outputs
- Trained Random Forest model
- Readmission predictions
- Model evaluation metrics
- Confusion matrix
- ROC curve
- Precision-recall curve
- Feature importance analysis

## Limitation
This is an exploratory machine learning project using a limited dataset. Its predictions are not clinically validated and must not be used as a substitute for professional medical judgment.
