Banana Quality Prediction Using Machine Learning
I worked on a project to predict the quality of bananas using various regression machine learning models. Below is a summary of the steps involved:

Data Preprocessing:

Cleaned the dataset and selected features relevant to predicting banana quality.
Defined input (X) and output (y) variables.
Split the data into training (80%) and testing (20%) sets using train_test_split.
Feature Engineering:

Separated the data into numerical (X_train_numerical, X_test_numerical) and categorical (X_train_categorical, X_test_categorical) columns.
Applied StandardScaler to normalize numerical features.
Used OrdinalEncoder to convert categorical features into numerical values.
Combined processed numerical and categorical data using np.concatenate(axis=1).
Model Building:

Trained and evaluated multiple regression models:
K-Nearest Neighbors (KNN)
Decision Tree Regressor
Random Forest Regressor
AdaBoost Regressor
Extreme Gradient Boosting (XGBoost)
Model Evaluation:

Used Root Mean Squared Error (RMSE) and R² Score as validation metrics.
Selected the best model based on prediction accuracy and performance metrics.
This project highlighted the importance of feature engineering, model selection, and evaluation in building effective machine learning solutions for regression problems.
