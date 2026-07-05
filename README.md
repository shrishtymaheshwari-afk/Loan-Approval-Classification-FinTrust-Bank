# Loan-Approval-Classification-FinTrust-Bank
Machine Learning project to predict loan approval status for FinTrust Bank customers — built as part of YBI Foundation Data Analytics Internship


![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Python](https://img.shields.io/badge/Python-3.x-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Classification-orange)

**📁 YBI Foundation — Data Analytics Internship | Final Project**

---

## Problem Statement
FinTrust Bank was manually processing loan applications, leading to slow turnaround times and inconsistent decisions. This project builds a Machine Learning model that automatically predicts whether a loan application should be **Approved ✅** or **Rejected ❌**, based on the applicant's financial and personal details.

## Objective
To analyze customer financial data and build a reliable classification model that helps the bank make **faster, consistent, and unbiased** loan approval decisions.

## Dataset Overview
| Feature | Description |
|---------|-------------|
| Credit Score | Applicant's credit score |
| Annual Income (₹) | Yearly income |
| Existing Debts (₹) | Current outstanding debt |
| Employment History (Years) | Years of employment |
| Loan Amount (₹) | Requested loan amount |
| Loan Term (Months) | Duration of loan |
| Interest Rate (%) | Applicable interest rate |
| **Approval Status** | Target variable |

## Project Workflow
1. **Exploratory Data Analysis (EDA)** — distribution plots, boxplots, correlation heatmap
2. **Data Preprocessing** — label encoding, 80-20 train-test split
3. **Model Building** — Logistic Regression & Random Forest
4. **Model Evaluation** — Accuracy, Confusion Matrix, ROC-AUC Curve, Feature Importance
5. **Live Prediction Testing** — tested model on sample applicant data

## Tech Stack
`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Scikit-learn`

## Model Performance
| Model | Accuracy |
|-------|:--------:|
| Logistic Regression | 94% |
| **Random Forest** | **99%** |

## Key Insight
**Credit Score** is the most influential factor in loan approval decisions, followed by Existing Debts and Interest Rate.

## 🔗 Project Notebook
▶️ **[Open in Google Colab](https://colab.research.google.com/drive/1cpHSn67OQpnEAHQ459tTmIbrbRTAlJJf?usp=sharing)**

## Conclusion
The project successfully built a loan approval prediction system for FinTrust Bank. The Random Forest model outperformed Logistic Regression and can help the bank **automate loan decisions, reduce processing time, and ensure fair, consistent approvals.**

---
### Submitted as part of the YBI Foundation Data Analytics Internship
