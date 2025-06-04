# 🧠 PRCP-1000: Portuguese Bank Marketing ML Project

This repository contains a complete machine learning project built using the **Portuguese Bank Marketing Dataset**. The goal is to predict whether a client will subscribe to a term deposit (`y`) based on demographic and behavioral features.

## 📁 Project Structure

```
.
├── data/                  <- Sample CSV files (if required)
├── notebooks/             <- Final Jupyter Notebook
├── outputs/               <- Plots, Evaluation Reports
├── requirements.txt       <- Python dependencies
├── .gitignore             <- Ignore unnecessary files
└── README.md              <- Project overview
```

## 📊 Dataset Description

- Source: [UCI Machine Learning Repository - Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- Rows: ~41,188
- Features: 20+
- Target: `y` (binary: `yes`/`no`)

## ✅ Project Highlights

- Data cleaning, handling missing values and outliers
- Industry-standard encoding of categorical features
- Feature selection and dimensionality reduction
- Class imbalance handled using **SMOTE**
- Model training with:
  - Logistic Regression
  - Random Forest
  - XGBoost
  - LightGBM
- Model evaluation using:
  - Confusion Matrix
  - Precision, Recall, F1-Score
  - AUC-ROC
  - Custom threshold tuning for real-world impact

## 🧪 Evaluation Metrics

| Model           | Accuracy | Precision | Recall | AUC-ROC |
|------------------|----------|-----------|--------|---------|
| Logistic Regression | 0.900     | 0.71      | 0.55   | 0.87    |
| Random Forest       | 0.912     | 0.76      | 0.58   | 0.89    |
| XGBoost             | 0.915     | 0.79      | 0.61   | 0.90    |
| LightGBM            | 0.918     | 0.80      | 0.63   | 0.91    |

*(Metrics are obtained from final model evaluation in the notebook)*

## 🛠️ Tech Stack

- Python 3.9+
- Jupyter Notebook
- Pandas, NumPy
- Scikit-learn
- XGBoost, LightGBM
- Matplotlib, Seaborn
- imbalanced-learn (SMOTE)

## 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/yourusername/PortugueseBankML.git
cd PortugueseBankML

# Install dependencies
pip install -r requirements.txt

# Open notebook
jupyter notebook notebooks/PRCP-1000-ProtugeseBank_FINALPROJECT.ipynb
```

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

> Built with ❤️ by Prasad Kamble