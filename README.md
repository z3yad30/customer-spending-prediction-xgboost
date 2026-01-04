# customer-spending-prediction-xgboost
# Customer Spending Prediction using XGBoost Regression

  ## Project Goal
  The objective of this project is to predict the **Total Amount Spent** by customers using advanced regression techniques. By understanding the drivers of customer spending, businesses can accurately forecast revenue and identify high-value customer segments for personalized loyalty programs.

  ## Dataset & Features
  The model is trained on customer transaction and demographic data, utilizing key features such as:
  * **Demographics**: Age, Gender, and Marital Status.
  * **Socio-economics**: Annual Income, Education level, and Occupation.
  * **Target Variable**: `Total_Spent` (Numerical value representing the sum of customer purchases).

  ## Model Architecture
  This project implements an **XGBoost (Extreme Gradient Boosting) Regressor**, chosen for its high performance with tabular data and its ability to handle non-linear relationships.

  ### Performance Metrics:
  The model's effectiveness is evaluated using:
  - **R-squared (R²)**: To measure the variance explained by the model.
  - **Mean Absolute Error (MAE)**: To understand the average prediction error in currency units.
  - **Mean Squared Error (MSE)**: To penalize larger prediction outliers.

  

  ## Key Visualizations
  The notebook includes critical performance plots:
  - **Actual vs. Predicted Plot**: A scatter plot visualizing how closely the XGBoost predictions align with real spending values.
  - **Feature Importance**: Identifying which factors (e.g., Income or Age) most significantly impact customer spending.

  ## Technical Stack
  * **Language**: Python
  * **Libraries**: 
    * `XGBoost`: Gradient boosting framework.
    * `Scikit-Learn`: Model evaluation and data splitting.
    * `Pandas & Numpy`: Data cleaning and transformation.
    * `Matplotlib & Seaborn`: Visualization of regression results.

  ## How to Use
  1. Clone the repository.
  2. Install the necessary dependencies:
     ```bash
     pip install xgboost pandas scikit-learn matplotlib seaborn
     ```
  3. Run `06_Task_02.ipynb` to execute the data preprocessing, model training, and evaluation steps.
