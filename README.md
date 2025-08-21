# 🛡️ Fraud Detection using Machine Learning
## 📌 Project Overview
This project focuses on detecting fraudulent transactions in financial datasets using Machine Learning techniques.
The dataset is highly imbalanced, so we apply class_weights to handle class imbalance.
We perform Exploratory Data Analysis (EDA), feature scaling, and build a Random Forest Classifier to identify fraudulent transactions with high accuracy.

The project is implemented in Google Colab with Python, Pandas, Scikit-learn, Seaborn, and Matplotlib.

## 🔑 Features

Exploratory Data Analysis (EDA):
* Transaction type distribution
* Fraud vs non-fraud comparison
* Correlation heatmaps

Data Preprocessing:
* Handling missing values
* Label encoding for categorical features
* Feature scaling with StandardScaler

Modeling:
* Random Forest Classifier
* Performance metrics: Precision, Recall, F1-score, ROC-AUC

Evaluation:
* Classification Report
* Confusion Matrix
* ROC Curve & AUC Score

## ⚙️ Tech Stack
* Languages: Python
* Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* Platform: Google Colab / Jupyter Notebook

## 🚀 How to Run
1. Clone this repository:
   ```
   git clone https://github.com/Devyash-jain/Fraud-Transaction-Prediction.git
   cd Fraud-Transaction-Prediction
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Open in Jupyter Notebook or Google Colab
4. Run all cells to reproduce results.

## 📊 Results
Achieved ~99% precision, recall, and F1-score on the imbalanced dataset after applying SMOTE and Random Forest.
Clear fraud vs non-fraud separation in EDA visualizations.

## 📄 File Structure
```
├── Fraudlent_Transaction_Prediction.ipynb    # Main notebook with code & analysis
├── requirements.txt                          # Dependencies
├── README.md                                 # Project documentation
```

