# california-housing-model
Linear Regression model on California Housing dataset
# 🏡 California Housing Price Prediction

Predicting California housing prices using **Linear Regression** on the `fetch_california_housing` dataset from scikit-learn. This project involves data cleaning, outlier removal, model training, evaluation, and result visualization.

---

## 📊 Project Highlights

- 📌 **Dataset:** California Housing (from `sklearn.datasets`)
- 🧹 **Cleaning:** Outlier removal using IQR method
- 🧠 **Model Used:** Linear Regression
- 📈 **Evaluation Metrics:** MAE, RMSE, R² Score
- 💾 **Exported:** Trained model `.pkl` and prediction `.csv`

---

## 📁 Files Included

| File                          | Description                                 |
|------------------------------|---------------------------------------------|
| `California_House_prediction.ipynb` | Jupyter notebook with full analysis |
| `linear_regression_model.pkl` | Saved trained model using Joblib            |
| `test_predictions.csv`        | Actual vs Predicted values on test data     |
| `cleaned_training_data.csv`   | Training dataset after outlier removal      |
| `README.md`                   | Project documentation (this file)           |

---

## 📉 Model Performance

| Metric   | Training Set | Test Set |
|----------|--------------|----------|
| MAE      | 0.4231       | 0.4717   |
| RMSE     | 0.5580       | 0.6552   |
| R² Score | 0.6408       | 0.6145   |

---

## 🚀 How to Use

### 📦 1. Install Required Libraries
```bash
pip install pandas scikit-learn matplotlib joblib
