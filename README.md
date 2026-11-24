# RCA-Activity2-Binary-Classification_AD3137

# Activity 2: Binary Classification using Logistic Regression

## Objective
Build and evaluate a Logistic Regression model for a binary classification
problem. Compare decision thresholds and recommend a threshold based on
classification results.

## Dataset
- Name: Breast Cancer Wisconsin Diagnostic
- Source: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html
- Records: 569
- Features: 30 numerical features
- Target: Diagnosis
- Positive class (1): Malignant
- Negative class (0): Benign

## Work Completed
- Inspected the dataset and class distribution
- Split the data using stratification
- Scaled numerical features using training data only
- Trained Logistic Regression
- Generated predicted probabilities and class labels
- Evaluated the model using confusion matrix, accuracy, precision, recall,
  specificity, F1-score, and ROC-AUC
- Compared the model with a majority-class baseline
- Compared thresholds 0.3, 0.5, and 0.7
- Plotted the sigmoid curve, ROC curve, and decision behaviour
- Classified a new example and documented the decision log

## Results
Add the actual results from your executed notebook:
- Accuracy:
- Precision:
- Recall:
- Specificity:
- F1-score:
- ROC-AUC:
- Recommended threshold and reason:

## Files
- `Activity2_Binary_Classification_Logistic_Regression.ipynb` — completed notebook

## Faculty Reference
https://github.com/complexiota

## Note
This is an educational project. The model is not intended for medical diagnosis
or real-world clinical decisions.
