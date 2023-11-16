# ML_Project_Prediction


![ML_Project_Prediction](https://drive.google.com/uc?export=view&id=1Bzt_bWHAwYlUZyuEnVv2gmMrbiARx4Fq)

<br><b>Overview</b><br>
<br>This project involves a detailed analysis and prediction of player values in FIFA 20 using various machine learning models. The dataset used is an Excel file named 'fifa20ex.xlsx', which includes various player attributes.<br>

<br><b>Dependencies</b><br>
Numpy
Pandas
Seaborn
Matplotlib
hvPlot
xlrd
scikit-learn

<br>Installation<br>
Use the following command to install necessary packages:

<br>Copy code<br>
pip install numpy pandas seaborn matplotlib hvplot xlrd scikit-learn
Data Preprocessing
Data is loaded from an Excel file.
Player positions are encoded into dummy variables.
Columns related to player skills are split and median filled for NaN values.<br>

<br><b>Feature Engineering</b><br>
A set of 45 features are selected for model building including 'age', 'height_cm', 'weight_kg', 'overall', etc.
The target variable is 'value_eur'.<br>

<br><b>Visualization</b><br>
![ML_Project_Prediction](https://drive.google.com/uc?export=view&id=1HvH4RQcPP0I_XgLE_kzcmg28RDeipY6d)


<br><b>Model Training</b><br>
Multiple models are trained on the dataset:<br>

Linear Regression: To establish a baseline.<br>
Ridge Regression: To check for improvements with regularization.<br>
Lasso Regression: For feature selection and handling multicollinearity.<br>
Support Vector Regression (SVR): With hyperparameter tuning using GridSearchCV.<br>
Decision Tree Regressor: Both basic and pre-pruned versions are trained.<br>
Random Forest Regressor: An ensemble method for improved generalization.<br>
AdaBoost Regressor: To boost performance of the decision tree model.<br>
K-Nearest Neighbors (KNN): A non-parametric method for regression.<br>
![ML_Project_Prediction](https://drive.google.com/uc?export=view&id=1Lqd9Ci0jAsnmOrTJz7MWS9OEjfxC_rC1)<br>

<br><b>Evaluation</b><br>
Each model is evaluated using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared. Cross-validation is also used to ensure the model's effectiveness.<br>

<br><b>Feature Importance</b><br>
Feature importance is visualized for tree-based models to understand the significant predictors.<br>

<br><b>Conclusion</b><br>
This project aims to accurately predict player values in FIFA 20 using various regression techniques, with a focus on model selection and performance evaluation.<br>

