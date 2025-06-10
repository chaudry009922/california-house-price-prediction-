California House Price Prediction Project
=========================================

Project Description:
--------------------
This project predicts California house prices using features like median income, house age, average number of rooms, and more. The dataset used is from the California Housing Dataset provided by Scikit-learn.

Two models were trained:
1. Linear Regression
2. Random Forest Regressor

The dataset was split into training and testing sets. The performance was evaluated using R² Score and RMSE.

Key Steps:
----------
- Loaded and cleaned the California Housing dataset
- Performed feature scaling using StandardScaler
- Trained Linear Regression and Random Forest models
- Evaluated models using R² Score and RMSE
- Visualized feature importance for Random Forest
- Saved the trained Random Forest model using joblib

Technologies Used:
------------------
- Python
- Scikit-learn
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Joblib

How to Run:
-----------
1. Clone this repo
2. Install dependencies from `requirements.txt`
3. Run the notebook: `House_Price_Prediction.ipynb`

 Note: Trained model (`random_forest_model.pkl`) is too large to upload to GitHub. You can regenerate it by running the notebook.


Author:
-------
[Usama Ashraf]

