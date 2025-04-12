# 🏦 AllLife Bank: Personal Loan Prediction

## 📌 Project Overview

AllLife Bank is a growing U.S.-based financial institution with a large customer base. Most customers are liability customers (depositors), while a small segment are borrowers (loan customers). The bank aims to **convert more depositors into personal loan customers** to grow its loan portfolio and revenue through interest earnings.

In this project, we build a **machine learning model** to predict whether a liability customer is likely to purchase a personal loan. This will enable the marketing team to **better target high-probability customers**, design more effective campaigns, and improve the overall conversion rate.

---

## 🎯 Objective

- Predict whether a liability customer will buy a personal loan.
- Identify key customer attributes influencing loan purchases.
- Help the marketing department target the right customer segments to increase conversions.

---

## 🧾 Dataset Description

The dataset contains customer information related to demographic, financial, and account activity.

| Column Name          | Description |
|----------------------|-------------|
| `ID`                 | Customer ID |
| `Age`                | Age of the customer |
| `Experience`         | Number of years of professional experience |
| `Income`             | Annual income of the customer (in $000) |
| `ZIP Code`           | ZIP Code of residence |
| `Family`             | Number of family members |
| `CCAvg`              | Average credit card spending per month (in $000) |
| `Education`          | Education Level (1: Undergrad, 2: Graduate, 3: Advanced/Professional) |
| `Mortgage`           | Value of mortgage loan (if any) |
| `Securities Account` | Does the customer have a securities account? (1: Yes, 0: No) |
| `CD Account`         | Does the customer have a certificate of deposit (CD)? (1: Yes, 0: No) |
| `Online`             | Does the customer use internet banking? (1: Yes, 0: No) |
| `CreditCard`         | Does the customer use a credit card issued by the bank? (1: Yes, 0: No) |
| `Personal Loan`      | **Target variable** — Did the customer buy a personal loan? (1: Yes, 0: No) |

---

## 🛠️ Tools & Technologies Used

- **Python 3.x**
- **Pandas, NumPy** for data processing
- **Matplotlib, Seaborn** for visualization
- **Scikit-learn** for model building and evaluation
- **Jupyter Notebook** for interactive development

---

## 🔍 Project Workflow

1. **Data Cleaning & Exploration**
   - Handle missing or incorrect values
   - Perform exploratory data analysis (EDA)
2. **Feature Engineering**
   - Transform or encode categorical variables
   - Scale numerical features (if necessary)
3. **Model Building**
   - Train classification models (e.g., Logistic Regression, Decision Trees, Random Forest)
   - Evaluate using metrics like Accuracy, ROC AUC, Precision, and Recall
4. **Insights**
   - Identify top predictive features
   - Recommend target customer segments

---

## 📈 Evaluation Metrics

- Accuracy
- Precision & Recall
- F1 Score
- ROC AUC
- Confusion Matrix

---

## 📊 Sample Visualizations

> Include sample charts like:
> - Distribution of loan vs non-loan customers
> - Correlation heatmap
> - Feature importance bar charts
> - ROC curve comparisons

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/alllife-loan-prediction.git
   cd alllife-loan-prediction

