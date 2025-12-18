# Cancer_disease-Multiple_linear_regression


A machine learning project using Multiple Linear Regression to predict the cancer_Score based on various patient lifestyle and health factors.



📌 Project Overview



The goal of this project is to analyze the linear relationship between features such as Age, Smoking, and Genetic Risk to predict the likelihood or severity of cancer (represented by a score).

🛠️ Feature Engineering



To prepare the data for the model, the following engineering steps were performed:


Column Selection: Removed non-predictive identifiers such as Patient_ID, Country_Region, and Year.


Ordinal Encoding: Transformed Cancer_Stage (Stage 0 to Stage IV) into a numerical scale (0–4) to preserve the inherent order.


One-Hot Encoding: Converted the categorical Gender column into dummy variables to avoid the "Dummy Variable Trap."


Feature Scaling: Applied Standardization (StandardScaler) to ensure all numerical features (like Age vs. Obesity Level) are on the same scale for better model convergence.



🚀 Model & Implementation



Algorithm: Multiple Linear Regression.



Libraries: Python, Pandas, Scikit-Learn, Seaborn, Matplotlib.


Data Split: 80% Training, 20% Testing.


📊 Evaluation


The model's performance is evaluated using:



R² Score: To measure how well the independent variables explain the variance in cancer scores.


