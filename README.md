# 💳 Credit Card Fraud Detection

This project applies machine learning techniques to detect fraudulent credit card transactions using anonymized data from Kaggle. The goal is to build a classifier capable of distinguishing between fraudulent and legitimate transactions, and to visualize results in a Power BI dashboard.

---

## 📁 Dataset

**Source**: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)

- Contains transactions made by European cardholders in September 2013.
- Features are PCA-transformed due to confidentiality.
- Imbalanced dataset: 492 frauds out of 284,807 transactions.

> ⚠️ The CSV file is **not included in this repository** due to GitHub's 100MB file size limit. Please download it directly from Kaggle.

---

## 🧠 ML Techniques Used

- Data normalization (Min-Max and Standard Scaler)
- Class imbalance handled with **SMOTE**
- Model training with:
  - Logistic Regression
  - Random Forest
  - XGBoost
- Performance Evaluation:
  - Confusion Matrix
  - Precision, Recall, F1-Score
  - ROC Curve & AUC

---

## 📊 Visualization

- Power BI Dashboard:
  - Fraud vs Non-Fraud distribution
  - Prediction probability trends
  - Top 10 feature importance
  - Model performance metrics

---

## 🛠️ Tools & Libraries

- Python: `pandas`, `numpy`, `scikit-learn`, `seaborn`, `matplotlib`, `xgboost`, `imblearn`
- Power BI
- Jupyter Notebook / VS Code

---

---

## 📌 How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/Credit-Card-Fraud-Detection.git
pip install -r requirements.txt


🙌 Acknowledgements
Kaggle Dataset by ULB

scikit-learn & XGBoost documentation


Feel free to reach out via GitHub Issues


