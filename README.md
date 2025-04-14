# Predicting_Life_expectancy_Using_ML
🌍 Life Expectancy Prediction Using Machine Learning
This project explores how machine learning techniques can be applied to predict life expectancy and classify countries based on their development status. It involves detailed data cleaning, exploratory data analysis (EDA), regression, and classification using a real-world health dataset covering countries from 2000 to 2015.

📌 Objectives
Predict a country's life expectancy using regression models

Classify a country as Developed or Developing using classification models

Clean and preprocess the dataset (missing values, outliers, encoding)

Visualize important trends and correlations between health indicators

Analyze the most important factors influencing longevity

🗂️ Dataset
Source: Kaggle - Life Expectancy (WHO)

Records: 2,938

Features: 22 columns including GDP, schooling, adult mortality, immunization, population, and more

Target Variables:

Life_expectancy: (for regression)

Status: Developed or Developing (for classification)

⚙️ Technologies Used
Python

Pandas & NumPy

Seaborn & Matplotlib

Scikit-learn (Regression & Classification models)

🔍 Exploratory Data Analysis
Key observations from the data:

Positive correlations between life expectancy and:

Schooling

Income composition of resources

Diphtheria immunization

Negative correlations with:

Adult mortality

HIV/AIDS prevalence

Developed countries show consistently higher life expectancy

Visualization types:

Boxplots, heatmaps, scatter plots, violin plots, KDE plots

Time trends and status-wise comparisons

📈 Machine Learning Models
🔹 Regression (Predicting Life Expectancy)
Linear Regression

Random Forest Regressor

Evaluation metrics: RMSE, R² score

🔹 Classification (Status: Developed / Developing)
K-Nearest Neighbors (KNN)

Logistic Regression

Evaluation metrics: Accuracy, Confusion Matrix, Classification Report

🔬 Feature Importance
Using Random Forest, the most important features for predicting life expectancy:

Schooling

Adult Mortality

Income Composition

Diphtheria

HIV/AIDS

✅ Project Outcomes
Built accurate models to predict life expectancy and classify country status

Gained insights into global health trends

Cleaned and transformed complex health data into usable formats for machine learning

🚀 Future Improvements
Add time-series forecasting (e.g., ARIMA, LSTM)

Introduce geospatial visualizations

Build an interactive dashboard (e.g., Streamlit)

Use ensemble methods like XGBoost or LightGBM for better accuracy

