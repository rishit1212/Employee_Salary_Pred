# Employee_Salary_Pred
<br /> 
This project is focused on predicting employee salaries based on various factors such as age, gender, education level, job title, and years of experience. Here’s an overview of the process:
<br /> 
Data Preparation<br /> 
Dataset:
<br /> 
Contains 375 entries with the following columns: Age, Gender, Degree, Job Title, Experience Years, and Salary.
After handling duplicates and missing values, 324 records remained.
<br /> 
Preprocessing:
Renamed columns for better readability.<br /> 
Encoded categorical features (e.g., Gender, Degree, Job Title) using LabelEncoder.<br /> 
Scaled numerical features (Age and Experience Years) using StandardScaler.<br /> 
Exploratory Data Analysis<br /> 
Correlation Analysis:
High correlation among Age, Experience Years, and Salary.<br /> 
Visualizations:
Distribution of categorical and numerical variables through bar charts, histograms, and box plots.<br /> 
Model Development:-<br /> 
Features Used:
Scaled numerical features and encoded categorical variables.
Train-Test Split:
Split the dataset into 80% training and 20% testing sets.<br /> 
Linear Regression Model<br /> 
Model Metrics:<br /> 
Accuracy (R²): 89.11%<br /> 
Mean Absolute Error (MAE): $10,570.79<br /> 
Root Mean Squared Error (RMSE): $14,344.13<br /> 
Model Parameters:<br /> 
Coefficients and intercepts of the model were analyzed to understand feature importance.
