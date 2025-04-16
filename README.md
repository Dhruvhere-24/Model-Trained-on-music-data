🎧 Predicting Track Popularity Using Audio Features
This project explores the prediction of song popularity using machine learning regression models. Leveraging Spotify-style audio features, we aim to build a robust model that can estimate a track's popularity score.

📊 Objective
The goal is to train supervised regression models that predict track_popularity based on meaningful audio features such as:

release_year

loudness

speechiness

instrumentalness

acousticness

These features were selected after exploratory data analysis, including correlation checks and scatter plots.

🧪 Workflow
Data Preprocessing

Loaded and cleaned a dataset of 21,000+ songs.

Removed unnecessary columns and handled missing values.

Selected key features based on visual and statistical correlation with track_popularity.

Model Training

Applied multiple regression models:

Linear Regression

Random Forest Regressor

Gradient Boosting Regressor

Ridge, Lasso, KNN (optional)

Tuned models using scikit-learn defaults and evaluated with RMSE (Root Mean Squared Error).

Evaluation

Used a separate test.csv file as a real-world test set.

Compared actual vs predicted values.

Visualized performance with scatter plots and error metrics.

🧠 Key Results
Models were evaluated using RMSE.

Random Forest and Gradient Boosting showed better performance over simple Linear Regression.

Visualizations demonstrated reasonable prediction accuracy and consistency.

📁 Files Included
train.csv – Training data with full audio features.

test.csv – Real-world test set for final evaluation.

modeling.ipynb – Jupyter notebook with code for EDA, modeling, and evaluation.

README.md – Project overview and explanation (this file).


