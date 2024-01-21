# credit-risk-classification
Module 20 Challenge - U of T bootcamp Data Visualization
Student Name: Jesus Hernandez

## Overview of the Analysis
This analysis aims to evaluate the performance of a machine learning model, specifically a logistic regression classifier, in predicting credit risk. The dataset contains imbalanced classes, and the analysis compares the model's performance before and after applying resampling techniques.

The inbalanced classes suggest that the "loan_status" column is imbalanced, with a significantly higher number of instances labeled as 0 compared to 1. In this context, it means that there are many more instances of loans with a status of 0 (presumably, something like "fully paid") than 
instances with a status of 1 (possibly indicating "default").

## Results
* Original Model
    Accuracy Score: 0.99
    Precision Score (Class 0): 1.00
    Precision Score (Class 1): 0.87
    Recall Score (Class 0): 1.00
    Recall Score (Class 1): 0.89

* Resampled Model
    Accuracy Score: 1.00
    Precision Score (Class 0): 1.00
    Precision Score (Class 1): 1.00
    Recall Score (Class 0): 1.00
    Recall Score (Class 1): 1.00

# Summary
The machine learning model demonstrates exceptional performance, particularly after applying resampling techniques to address class imbalance. In the original model, there was a slight imbalance in precision and recall for the minority class (Class 1), while the majority class (Class 0) showed near-perfect scores. The resampled model, however, achieves perfect precision, recall, and F1-score for both classes.
# Recommendation
Based on the improved performance of the resampled model, I recommend its use for predicting loan statuses. The model's ability to correctly classify instances of the minority class (loan defaults) has significantly improved, making it a valuable tool for identifying potential risks. The perfect accuracy score indicates that the model is robust in its predictions. However, it is essential to consider business objectives and potential trade-offs before deploying the model in a real-world scenario.
