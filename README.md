# ML_projects
Implementations of different Machine Learning projects

# 1. Cancer Death Rate Prediction:
This project is based on the prediction of cancer death rates. It is a regression problem as it involves prediction on numeric quantity (Death Rates). The steps performed are as follows:
1. Importing necessary libraries
2. Importing the "cancer_death_rate.csv" dataset using 'pandas' library.
3. Exploratory Data Analysis in which we deal with the missing values (imputation) and the characteristics of numeric columns are observed. Then, outliers are treated using box-whisker plots for different variables.
4. The dependent variable (TARGET_deathRate) is separated from the independent variables.
5. The entire data is then split into train and test sets with 20% of data given to test set.
6. First, the linear regression model is trained and evaluation metrics (MSE, R2 score) are observed.
7. Then, it is compared with the Random Forest and XGBoost models for evaluation metrics.
8. In this case, it is observed that Random Forest gives the best result based on r2 score.
9. Further, Hyperparameter tuning is performed along with Feature selection to improve the evaluation metrics.
