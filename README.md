# 🏠 House Price Prediction

A complete end-to-end Machine Learning project that predicts house prices using **Linear Regression** and **Random Forest Regression**, built as part of a Data Science internship.

## 📌 Project Overview

This project walks through the full ML workflow — data exploration, cleaning, model training, evaluation, and business insights — on a real housing dataset to predict `price` based on property features such as area, bedrooms, bathrooms, and amenities.

## 📊 Dataset

- **File:** `Housing.csv`
- **Rows:** 545 | **Columns:** 13
- **Target variable:** `price`
- **Features:** `area`, `bedrooms`, `bathrooms`, `stories`, `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `parking`, `prefarea`, `furnishingstatus`

## 🛠️ Tech Stack

- Python
- pandas, NumPy
- matplotlib, seaborn
- scikit-learn

## 🔄 Workflow

1. **Data Loading & Exploration** — shape, data types, missing values, statistical summary
2. **Data Cleaning** — missing value handling, duplicate removal, One-Hot Encoding of categorical features
3. **Model Building** — 80/20 train-test split, trained Linear Regression & Random Forest Regressor
4. **Model Evaluation** — compared models using MAE, RMSE, and R² Score
5. **Visualization** — price distribution, correlation heatmap, actual vs predicted plots, feature importance
6. **Insights & Summary** — business-friendly conclusions generated dynamically from the actual model results

## 📈 Results

| Model | MAE | RMSE | R² Score |
|---|---|---|---|
| **Linear Regression** | 970,043 | 1,324,507 | **0.6529** |
| Random Forest | 1,013,969 | 1,398,116 | 0.6133 |

🏆 **Best Model: Linear Regression**

**Top price drivers:** `area` (46.9% importance), `bathrooms` (15.3%), `air conditioning` (6.0%)

## 📂 Repository Structure

```
├── analysis.ipynb          # Main Jupyter notebook (Colab-compatible)
├── Housing.csv              # Dataset
├── charts/                  # Generated visualizations
│   ├── price_distribution.png
│   ├── correlation_heatmap.png
│   ├── actual_vs_predicted.png
│   └── feature_importance.png
└── README.md
```

## ▶️ How to Run

1. Clone this repository
2. Open `analysis.ipynb` in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook
3. Make sure `Housing.csv` is in the same directory (or upload it when prompted)
4. Run all cells

## 💡 Key Insight

House price in this dataset is driven overwhelmingly by **area**, with bathrooms and air conditioning as secondary factors — a useful signal for real-estate pricing and marketing strategy.

---
*Week 1: House Price Prediction*
