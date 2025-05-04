# 📊 Wireless Customer Churn Prediction
This Jupyter Notebook analyzes a wireless telecom customer dataset to predict customer churn using various machine learning techniques. It also applies outlier detection to improve model performance.

## 🔍 Project Overview
Loads and explores a dataset (wireless_churn.csv)

Generates an interactive profile report

Detects and removes outliers using Isolation Forest

Splits the data into training and testing sets

Trains and compares several machine learning models

## 🧰 Tools & Libraries
pandas, numpy, matplotlib, seaborn

pandas_profiling for automatic EDA

scikit-learn for model training and evaluation

IsolationForest for outlier removal

## 🧠 Models & Techniques Used
Outlier detection with Isolation Forest

Train-test split with stratified sampling

Evaluation via accuracy and other metrics (not fully shown but implied)

## 📁 Files Required
wireless_churn.csv: The dataset file

churn.html: Auto-generated pandas profiling report

## 🚀 How to Run
### Install dependencies:

```
bash
Copy
Edit
pip install pandas numpy matplotlib seaborn scikit-learn pandas-profiling
```

### Launch the notebook:

```
bash
Copy
Edit
jupyter notebook final_project.ipynb
```

### Run all cells to:

View the dataset report

Detect and exclude outliers

Train and evaluate predictive models

## 📌 Notes
Outliers are removed from the training set using IsolationForest before model training.

The profiling report (churn.html) provides detailed insights about features, distributions, and correlations.
