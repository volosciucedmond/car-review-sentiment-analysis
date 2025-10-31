# Car Review Sentiment Analysis
End-to-end sentiment analysis project using scikit-learn and Balanced Random Forest

A machine learning project for classifying car reviews as positive or negative using Python and scikit-learn.

---

## Overview
This project builds and evaluates a sentiment classifier trained on car review data.
It focuses on handling class imbalance, tuning decision thresholds, and interpreting model performance.

---

## Key Features
- Data preprocessing and scaling  
- Balanced Random Forest for imbalanced classification  
- Threshold tuning for improved minority recall  
- Evaluation with confusion matrix, ROC AUC, and Precision–Recall curves  
- Feature importance visualization  

---

## Results
| Metric | Score |
|:--|:--|
| **Accuracy** | 83% |
| **Macro F1-score** | 0.66 |
| **ROC AUC** | 0.90 |
| **Average Precision (PR AUC)** | 0.99 |
| **Minority Recall** | 82% |

---

## Tools & Libraries
- Python 3.10  
- scikit-learn  
- pandas, numpy, matplotlib  
- imbalanced-learn  

---

## Learning Outcome
Developed with ChatGPT guidance to explore ML best practices:
- Understanding model calibration and threshold tuning  
- Visualizing classification performance  
- Managing large datasets within Colab resource limits  

---

## How to Run
1. Open the notebook in Google Colab  
2. Upload dataset or connect to Google Drive  
3. Run all cells to reproduce the results  

---

## Files
- `sentiment_analysis.ipynb` – Main notebook  
- `requirements.txt` – Dependencies  

---
