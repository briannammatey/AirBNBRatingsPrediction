# Ratings Prediction, BreakThroughTech Final Project 

This project is a Machine Learning model that predicts Airbnb property review scores based on features such as host details, listing attributes, and pricing information.

## Objectives
- Frame the review score prediction as a supervised regression problem.
- Clean and prepare the dataset for modeling.
- Explore the data for patterns, trends, and outliers.
- Train multiple models, including Linear Regression and Random Forest.
- Tune hyperparameters to improve model performance.
- Evaluate model performance using appropriate metrics (RMSE, R²).
- Prevent overfitting and ensure generalization to new data.

## Tech Stack
- **Python**
- **scikit-learn**
- **Pandas**
- **Matplotlib**

## Project Workflow
1. **Data Loading** – Imported Airbnb NYC dataset.
2. **Data Preprocessing** – Removed irrelevant columns, handled missing values, applied one-hot encoding to categorical variables.
3. **Exploratory Data Analysis (EDA)** – Visualized data distributions, identified trends and relationships between features and review scores.
4. **Model Training** – Implemented Linear Regression and Random Forest models.
5. **Hyperparameter Tuning** – Used GridSearchCV to optimize Random Forest parameters.
6. **Model Evaluation** – Compared models using RMSE and R²; best model achieved an R² score of ~0.83.
7. **Overfitting Check** – Evaluated training vs. testing performance to ensure generalization.

## Results
- **Best Model**: Random Forest Regressor (tuned with GridSearchCV)
- **Test RMSE**: ~0.209
- **Test R²**: ~0.833





