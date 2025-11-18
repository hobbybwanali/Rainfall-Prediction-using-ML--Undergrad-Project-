# Rainfall Prediction Using Machine Learning – Mkwinda, Malawi

This project compares the performance of three ML models for predicting rainfall occurrence:

- Logistic Regression.  
- Random Forest  
- Multi-Layer Perceptron (MLP)

The study used historical and real-time data collected using **Arduino-based tipping bucket rain gauges** that I designed and deployed.

## Features
- Full preprocessing pipeline (KNN imputation, scaling, feature engineering)
- Class imbalance handling (Random Oversampling)
- Model evaluation with Accuracy, Precision, Recall, F1, ROC-AUC
- January rainfall prediction for real-world validation.

## Results
- **MLP achieved highest accuracy (83.6%)**
- **Logistic Regression achieved highest recall (90%)**
- **MLP had best balance of accuracy, precision & ROC-AUC**

## Tools Used
Python, Pandas, Scikit-learn, Matplotlib, NumPy

