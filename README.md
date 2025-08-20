# 💼 Freelancer Gig Price Prediction

This project focuses on predicting freelancer earnings based on job-related features such as category, experience level, country, and other factors. Using data preprocessing and machine learning techniques, the goal is to estimate the potential earnings (USD) for freelancers.

## 📊 Project Overview

- **Dataset**: freelancer_earnings_bd.csv
- **Target Variable**: Earnings_USD
- **Features**: Job Category, Experience Level, Location, Skills, etc.
- **Objective**: Build a regression model that predicts freelancer earnings to provide insights into the freelance economy.

---

## ⚙️ Steps Performed

### Data Loading & Exploration
- Loaded dataset using Pandas
- Inspected structure, missing values, and summary statistics

### Data Cleaning & Preprocessing
- Dropped irrelevant columns (`Freelancer_ID`)
- Encoded categorical variables using `LabelEncoder`
- Standardized numerical features with `StandardScaler`

### Exploratory Data Analysis (EDA)
- Distribution of earnings by experience level
- Correlation heatmap between numerical features

### Model Building
- Train-test split
- Random Forest Regressor for prediction
- (Future scope: try XGBoost, Linear Regression, etc.)

### Evaluation
- Metrics: R² Score, Mean Absolute Error (MAE), Root Mean Squared Error (RMSE)

---


## 🛠️ Installation & Setup

Clone the repository:
```bash
git clone https://github.com/your-username/Freelancer-Price-Prediction.git
cd Freelancer-Price-Prediction
```

Install dependencies:
```bash
pip install -r requirements.txt
```

Run the notebook:
```bash
jupyter notebook
```

---

## 📦 Requirements

The project uses the following Python libraries:
```
pandas
numpy
matplotlib
seaborn
scikit-learn
gradio
```

---

## 🚀 Future Enhancements
- Add XGBoost / LightGBM models for comparison
- Deploy the model with Gradio / Streamlit
- Hyperparameter tuning with GridSearchCV
- Visual dashboard for better interpretability

