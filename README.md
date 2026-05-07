# Autism-prediction-ml
Machine learning models for autism prediction using ROC curve and confusion matrix evaluation.

# Autism Prediction using Machine Learning

# Project Overview
This project applies machine learning models to predict autism.
Three models  were implemented and compared using ROC curves and confusion matrices.

# Workflow
1. Data cleaning and preprocessing
2. Model training (Logistic Regression, Random Forest, SVM)
3. Evaluation using ROC curve and confusion matrix
4. Comparison of model performance

# Results
- Best performing model: Random Forest
- ROC AUC: 0.85
- Confusion matrix insights:
  Random Forest performance: Showed the highest accuracy with balanced predictions across classes.
  Low false negatives: Correctly identified most positive autism cases, minimizing missed detections.
  Reduced false positives: Fewer incorrect predictions compared to Logistic Regression and SVM.
  Overall reliability: The confusion matrix confirmed Random Forest as the most robust model for this dataset.

# Requirements 
pandas
numpy
matplotlib
seaborn
scikit-learn

