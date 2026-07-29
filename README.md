<img width="922" height="438" alt="Screenshot 2026-07-29 181800" src="https://github.com/user-attachments/assets/1cf86b50-5ec4-4bf8-99b7-cad67e06819e" />
# Medical-Insurance-Cost-Predictor
The Medical Insurance Cost Predictor is a machine learning project developed using Python to estimate individual medical insurance charges based on personal and lifestyle attributes.The project follows a complete data science workflow.


Dataset

This project uses the US Health Insurance Dataset, a widely used dataset for regression and predictive analytics tasks. It contains 1,338 records and 7 features, where the target variable is the individual's medical insurance cost (charges).

Features
Age – Age of the insured individual
Sex – Gender (Male/Female)
BMI – Body Mass Index
Children – Number of dependents covered by insurance
Smoker – Smoking status (Yes/No)
Region – Residential region in the United States
Charges – Annual medical insurance cost (Target Variable)
Project Workflow

The project was implemented following an end-to-end machine learning pipeline:

Data collection and inspection
Data preprocessing and cleaning
Handling categorical variables using encoding techniques
Feature engineering and data transformation
Exploratory Data Analysis (EDA)
Data visualization
Feature correlation analysis
Train-test data splitting
Model training and evaluation
Performance comparison and model selection
Exploratory Data Analysis (EDA)

A comprehensive EDA was performed to better understand the dataset and identify important patterns affecting insurance costs. Various visualizations were created using Matplotlib and Seaborn, including:

Distribution plots
Histograms
Count plots
Box plots
Scatter plots
Correlation heatmap
Pair plots
BMI vs Charges analysis
Age vs Charges analysis
Smoking status impact on insurance cost
Regional comparison of insurance charges

These visualizations helped identify trends, detect outliers, understand feature relationships, and support informed model selection.

Machine Learning Models Compared

Several regression algorithms were implemented and evaluated, including:

Linear Regression
Decision Tree Regressor
Random Forest Regressor
Gradient Boosting Regressor
XGBoost Regressor

Each model was trained on the processed dataset and evaluated using standard regression metrics:

R² Score
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
Root Mean Squared Error (RMSE)
Results

After comparing the performance of all regression models, XGBoost Regressor achieved the highest prediction accuracy and the best overall evaluation metrics. Its ability to capture complex, non-linear relationships and reduce overfitting through boosting made it the most effective model for predicting medical insurance costs on this dataset.
<img width="1682" height="575" alt="Screenshot 2026-07-29 181752" src="https://github.com/user-attachments/assets/d62d2879-4297-4316-bda6-878dfcbd80f7" />



<img width="1586" height="641" alt="Screenshot 2026-07-29 181743" src="https://github.com/user-attachments/assets/45f79204-97ee-4c1b-8e23-61be9938bd86" />
Technologies Used
Python , Pandas, NumPy , Matplotlib , Seaborn , Scikit-learn , XGBoost , Jupyter Notebook


