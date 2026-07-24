# Submarine-survival-ML-model

This repository contains a beginner-friendly machine learning model predicting submarine survival outcomes.  
Originally developed and published on Kaggle: [View Notebook](https://www.kaggle.com/code/addiya/submarine-survival-beginner-ml-model).

--

A beginner-friendly machine learning notebook comparing Logistic Regression and Random Forest on survival prediction. Includes confusion matrix visualizations and performance metrics.

Table of Contents¶

Step 1: Load and Explore Data

We begin by importing the submarine survival dataset...

Step 2: Preprocessing

We handle missing values and encode categorical features...

Step 3: Model Training

We compare Logistic Regression and Random Forest...

Step 4: Confusion Matrix and Prediction Analysis

We visualize classification performance for both models and interpret prediction outcomes...

Step 5: Model Comparison

We summarize performance metrics for both models...



--

# 📊 Model Evaluation Report

This report compares the performance of **Logistic Regression** and **Random Forest** classifiers on the same dataset.

---

## ✅ Logistic Regression
- **Accuracy:** 0.63  

### Classification Report
| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0     | 0.59      | 0.53   | 0.56     | 88      |
| 1     | 0.66      | 0.71   | 0.68     | 112     |

**Overall Metrics:**
- Accuracy: **0.63** (200 samples)  
- Macro Avg: Precision 0.62, Recall 0.62, F1-score 0.62  
- Weighted Avg: Precision 0.63, Recall 0.63, F1-score 0.63  

---

## 🌲 Random Forest
- **Accuracy:** 0.565  

### Classification Report
| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0     | 0.51      | 0.48   | 0.49     | 88      |
| 1     | 0.61      | 0.63   | 0.62     | 112     |

**Overall Metrics:**
- Accuracy: **0.565** (200 samples)  
- Macro Avg: Precision 0.56, Recall 0.56, F1-score 0.56  
- Weighted Avg: Precision 0.56, Recall 0.56, F1-score 0.56  

---

## 📌 Key Insights
- Logistic Regression **outperforms Random Forest** on this dataset.  
- Both models predict **Class 1 better than Class 0**, but Logistic Regression achieves higher recall and precision.  
- Dataset size: **200 samples** (88 in Class 0, 112 in Class 1).  
- Random Forest may benefit from **hyperparameter tuning** or feature engineering.

---

# Dataset Link: https://www.kaggle.com/datasets/addiya/submarine-survival-dataset

<img width="2270" height="952" alt="image" src="https://github.com/user-attachments/assets/5d91d635-fba2-4964-936b-a1cf887526bf" />


<img width="1774" height="1238" alt="image" src="https://github.com/user-attachments/assets/5032659f-2d35-450f-9d00-a694080223a1" />



<img width="1168" height="1134" alt="image" src="https://github.com/user-attachments/assets/e113d034-2be7-4857-87e6-6eef666d8500" />




