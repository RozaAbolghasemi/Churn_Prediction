# 📉 Customer Churn Prediction

This project presents a complete data analysis pipeline that includes **pricing model**, **risk analysis**, and **churn prediction** using supervised machine learning models. The workflow covers **data cleaning**, **exploratory data analysis**, **visualizations**, **feature engineering**, and **model training & evaluation**.

A wide range of visualizations — including bar plots, heatmaps, boxplots, correlation matrices, and evaluation metrics — support insights and decisions, making it suitable for data analysts and business stakeholders alike.

---

## 📁 Files in This Repository

- `Churn_prediction.ipynb` – Jupyter notebook containing code, charts, and results.
- `Data_case.csv` – The dataset used for analysis and model development.

---

## 🔍 Project Overview

### 1. Data Exploration & Cleaning
- Checking data types and missing values
- Handling missing/inconsistent values
- Encoding categorical variables
- Standardizing numerical features

### 2. Exploratory Data Analysis (EDA)
- Distribution plots and count plots
- Churn rates by feature groups
- Correlation heatmaps
- Boxplots for numerical variable comparison

### 3. Feature Engineering
- Removing irrelevant or redundant features
- Creating new informative variables (if needed)
- Feature scaling and transformation

### 4. Modeling
- Building models using:
  - Logistic Regression
  - Random Forest
  - XGBoost (optional)
- Hyperparameter tuning (e.g., GridSearchCV)
- Evaluation using:
  - Accuracy, Precision, Recall, F1-score
  - Confusion Matrix and ROC Curve

### 5. Conclusions & Business Recommendations
- Identifying key churn drivers
- Actionable insights for reducing churn

---

## ⚙️ Installation & Setup

To run the project locally:

### 1. Clone the repository
```bash
git clone https://github.com/your-username/churn-prediction.git
cd churn-prediction


### 2. (Optional) Create a virtual environment
```bash
python -m venv env
source env/bin/activate  # Windows: env\Scripts\activate


### 3. Install required packages
```bash
pip install -r requirements.txt



## 🧩 Libraries Used
- **pandas** – data manipulation

- **numpy** – numerical operations

- **matplotlib** – plotting

- **seaborn** – statistical visualization

- **scikit-learn** – ML modeling & evaluation

- **xgboost** – gradient boosting model (optional)

- **missingno** – missing data visualization (optional)

## 🚀 How to Run
Open Jupyter Notebook:
```bash
jupyter notebook Churn_prediction.ipynb


Run all cells to:
- Load and clean the data

- Explore data visually

- Train and evaluate churn prediction models

- Interpret results and draw conclusions

## 📊 Sample Visualizations
- Correlation heatmap for feature relationships

- Count plots showing churn distribution

- Boxplots for outlier and distribution analysis

- Confusion Matrix & ROC-AUC Curve

## 💡 Future Improvements
- Add cross-validation and ensemble models

- Deploy the model using Flask or Streamlit

- Integrate churn predictions with customer lifetime value (CLV)

- Perform time-based churn trend analysis

## 📜 License
This project is licensed under the MIT License. You are free to use, share, and modify it with attribution.

