Boston Housing Price Prediction
This project explores predictive modeling for housing prices using the Boston Housing dataset. It compares multiple regression techniques and evaluates the impact of feature selection on model performance.

 Objectives
Predict MEDV (Median value of owner-occupied homes in $1000s)

Compare regression models: Linear, Ridge, Lasso, and Random Forest

Evaluate performance using R² and Mean Squared Error (MSE)

Analyze feature correlations and apply feature reduction

Visualize model performance and residuals

Models Used
Model	Description
Linear Regression	Baseline model for comparison
Ridge Regression	Regularized linear model (L2 penalty)
Lasso Regression	Regularized linear model with feature selection (L1 penalty)
Random Forest	Ensemble model capturing nonlinear relationships
 Evaluation Metrics
R² Score: Measures how well the model explains variance in the target

MSE: Measures average squared error between predicted and actual values

 Feature Engineering
Used mutual information to identify top 5 influential features

Applied correlation heatmap to detect multicollinearity

Compared model performance on full vs reduced feature sets

 Visualizations
Residual plots for models.

Bar charts comparing R² and MSE across models

Correlation heatmap to guide feature selection

 Results Summary
Spoiler Alert: Random Forest outperformed all other models with highest R² and lowest MSE

Linear, Ridge, and Lasso showed similar performance, with slight degradation after feature reduction

Feature reduction helped simplify models but slightly reduced accuracy

 Technologies
Python

Pandas, NumPy

Scikit-learn

Seaborn, Matplotlib

Google Colab

 How to Run
Clone the repository

Open the notebook in Google Colab or Jupyter

Run all cells sequentially

Modify parameters or models to experiment

📬 Contact
Created by Atinuke 
This is a supervised learning ML project, to predict the house price using "features" of the house provided.

Feel free to reach out for collaboration or questions!
