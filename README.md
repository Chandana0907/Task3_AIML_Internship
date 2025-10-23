🏠 Housing Price Prediction using Linear Regression
🎯 Objective

The goal of this project is to predict housing prices using Simple and Multiple Linear Regression.

🧰 Tools Used

Python
Pandas → Data loading and preprocessing
Scikit-learn → Model training and evaluation
Matplotlib / Seaborn → Data visualization

📂 Dataset

Dataset: [Housing Price Prediction](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)

🪜 Steps Followed

Import and Preprocess Data
Load the dataset using Pandas
Handle missing values
Encode categorical features if required
Split the Data
Divide the dataset into training and testing sets using train_test_split
Train Linear Regression Model
Use LinearRegression() from sklearn.linear_model
Fit the model on training data
Evaluate the Model

Calculate:

MAE (Mean Absolute Error)
MSE (Mean Squared Error)
R² (Coefficient of Determination)
Visualize Results
Plot the regression line
Compare actual vs predicted prices
Interpret coefficients to understand the effect of each variable on price

📊 Output Example

Regression line plotted for simple regression
Model performance metrics displayed
Predicted prices compared to actual prices

🧠 Interpretation

Positive coefficient → Price increases with that variable
Negative coefficient → Price decreases with that variable
