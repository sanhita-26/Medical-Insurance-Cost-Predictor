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

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
XGBoost
Jupyter Notebook
Key Learning Outcomes

Through this project, I gained practical experience in:

Data preprocessing and feature engineering
Exploratory Data Analysis (EDA)
Data visualization techniques
Regression model development
Model comparison and performance evaluation
Hyperparameter tuning concepts
Machine learning workflow using Python
Interpreting results to build reliable predictive models
Future Improvements
Hyperparameter optimization using GridSearchCV or RandomizedSearchCV
Deployment using Flask or Streamlit
Integration with a web-based user interface
Support for additional healthcare and lifestyle parameters
Real-time insurance cost prediction through a web application
