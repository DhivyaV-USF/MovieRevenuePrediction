# 🎬 Movie Revenue Prediction (2000–2024)

This project builds a machine learning model to **predict movie box office revenue** using historical data. It uses the dataset:

- `enhanced_box_office_data(2000-2024)u.csv`

Developed as part of the **Machine Learning Final Project (Team SZA)** for the AIBA program at USF.

---

## 🚀 Project Objectives

- Explore key factors influencing movie revenue  
- Perform data cleaning, EDA, feature engineering  
- Build and evaluate predictive ML models  
- Use KNN Regression and hyperparameter tuning  
- Provide insights for movie budget planning  

---

## 📁 Repository Structure

```
Movie-Revenue-Prediction/
│
├── ML_FinalProject_Team SZA.ipynb         # Main analysis + ML models
├── enhanced_box_office_data(2000-2024)u.csv  # Dataset used
├── README.md
└── requirements.txt
```

---

## 🔍 Steps Performed in Notebook

### **1. Data Preparation**
- Loaded dataset  
- Handled missing values  
- Removed outliers  
- Encoded categorical features  
- Scaled numerical features  

### **2. Exploratory Data Analysis**
- Distribution analysis for budget & revenue  
- Correlation heatmap  
- Genre-based comparisons  
- Popularity vs revenue trends  

### **3. Feature Engineering**
- One-hot encoding of genres  
- Numerical scaling  
- Derived features for better predictions  

### **4. Model Development: KNN Regression**
- Train-test split  
- Hyperparameter tuning  
- K selection using GridSearch  
- Evaluation with:
  - MAE  
  - RMSE  
  - R² Score  

### **5. Prediction Scenario**
Includes a real example predicting an Action movie’s revenue using the best model.

---

## 📊 Results Summary

- KNN model performed well after tuning  
- Key predictors:
  - Budget  
  - Popularity  
  - Genre features  
- Demonstrated feasibility of predicting revenue pre-release  

---

## 🛠️ Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## ▶️ How to Run

### **1. Install dependencies**
```
pip install -r requirements.txt
```

### **2. Launch notebook**
```
jupyter notebook "ML_FinalProject_Team SZA.ipynb"
```

## 🤝 Team
**Team SZA** — MS AIBA  
University of South Florida
