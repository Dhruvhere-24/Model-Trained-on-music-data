# 🎧 Predicting Track Popularity Using Audio Features

This project explores the use of machine learning regression models to predict the popularity of songs using Spotify-style audio features.

---

## 📊 Objective

The goal is to build supervised regression models that estimate **track popularity** based on selected audio features. These features were chosen after exploratory data analysis, including correlation checks and scatter plots:

- **release_year**
- **loudness**
- **speechiness**
- **instrumentalness**
- **acousticness**

---

## 🧪 Workflow

### 1. Data Preprocessing
- Loaded and cleaned a dataset of **21,000+ songs**
- Removed irrelevant columns and handled missing values
- Selected key features based on correlation and visualization

### 2. Model Training
Implemented and compared several regression models using `scikit-learn`:

- **Linear Regression**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- *(Optional)* Ridge, Lasso, K-Nearest Neighbors (KNN)

All models were evaluated using **Root Mean Squared Error (RMSE)**.

### 3. Model Evaluation
- Used `test.csv` as a real-world test set
- Compared **actual vs. predicted** popularity scores
- Visualized results with **scatter plots** and **error metrics**

---

## 🧠 Key Results

- **Random Forest** and **Gradient Boosting** outperformed Linear Regression
- RMSE metrics confirmed higher accuracy of ensemble models
- Visualizations showed consistent and reliable predictions

---

## 📁 Files Included

- `train.csv` – Training data with full audio features  
- `test.csv` – Real-world test set for evaluation  
- `modeling.ipynb` – Jupyter notebook with code for EDA, modeling, and evaluation  
- `README.md` – Project overview and explanation (this file)

---


## 🛠️ Tech Stack

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---
