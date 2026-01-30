# Sampling

## Overview
This project analyzes the effect of different sampling techniques on an imbalanced dataset and compares the performance of multiple machine learning models using accuracy.

---

## Dataset
- Credit Card Fraud Detection Dataset  
- Target column: `Class`  
  - `0` → Normal transaction  
  - `1` → Fraudulent transaction  
- The dataset is initially imbalanced and is balanced using random under-sampling.

---

## Sampling Techniques Used
1. Random Sampling  
2. Stratified Sampling  
3. Cluster Sampling  
4. K-Fold Sampling  
5. Bootstrap Sampling  

---

## Machine Learning Models
- M1: Logistic Regression  
- M2: Decision Tree  
- M3: Random Forest  
- M4: Naive Bayes  
- M5: Support Vector Machine (SVM)  

---

## Evaluation Metric
- **Accuracy** is used as the evaluation metric for all five machine learning models:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Naive Bayes
  - Support Vector Machine (SVM)

- Accuracy is calculated as the ratio of correctly predicted instances to the total number of instances.

- For **Random, Stratified, Cluster, and Bootstrap sampling**, accuracy is computed on the test dataset obtained after splitting the sample.

- For **K-Fold sampling**, accuracy is calculated as the **average accuracy across all folds** for each model to provide a more reliable performance estimate.


---

## Results
- Accuracy results for each model and sampling technique are stored in:
  sampling_model_accuracy_results.csv  
- Bar graphs are plotted to compare model performance for each sampling method.

---

## Conclusion
The results show that different sampling techniques significantly impact model performance. Stratified and K-Fold sampling provide more stable results, while Bootstrap sampling may lead to overfitting.

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
