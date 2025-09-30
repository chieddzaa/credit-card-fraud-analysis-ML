# Credit Card Fraud Detection  
## 📌 Project Overview  
This project analyzes credit card transactions to detect fraudulent activity using machine learning.  
The dataset contains anonymized transaction features (V1–V28, Time, Amount) and a binary target indicating fraud (1) or non-fraud (0).  

## ⚙️ Features  
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Model training with Random Forest  
- Model evaluation with precision, recall, F1 score, and ROC-AUC  
- Cost-sensitive analysis (fraud cost vs. false alarm cost)  

## 📊 Results  
- **Fraud cost:** $400  
- **False alarm cost:** $100  
- **TP (True Positives):** 295  
- **FP (False Positives):** 9  
- **FN (False Negatives):** 11  
- Model showed strong precision on desktops and good performance on mobile, with ROC-AUC ≈ *0.9474969996439769*  

## 📈 Visualizations  
- Fraud vs. Non-Fraud distribution  
- Correlation heatmap of features  
- Confusion Matrix  
- ROC Curve  

## 💻 Tech Stack  
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
## 🚀 How to Run  
1. Clone the repository:
  ''bash
   git clone https://github.com/chieddzaa/credit-card-fraud-analysis-ML.git
   ```bash
   git clone https://github.com/your-username/credit-card-fraud-detection.git
