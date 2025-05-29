📊 Advertising Sales Prediction Using Linear Regression
This project demonstrates a simple but effective application of Linear Regression to predict advertising sales based on marketing budget across various media channels. It uses the classic Advertising dataset, a well-known dataset in machine learning education.

📁 Files Included
Advertising.csv — Dataset containing advertising spend data across TV, Radio, and Newspaper.

ML-Exercise_Advertising_Linear-Regression.ipynb — Jupyter Notebook demonstrating data exploration, visualization, model building, and evaluation.

README.md — Project documentation.

🧠 Objective
To build a linear regression model that predicts sales based on advertising budgets in:

TV

Radio

Newspaper

🗃️ Dataset Description
The dataset includes the following columns:

Column	Description
TV	Budget spent on TV ads (in thousands)
Radio	Budget spent on Radio ads (in thousands)
Newspaper	Budget spent on Newspaper ads (in thousands)
Sales	Sales generated (in thousands of units)

📌 Project Workflow
1. Data Loading & Inspection
Load dataset using pandas

View basic statistics and check for missing values

2. Exploratory Data Analysis (EDA)
Use seaborn and matplotlib for:

Pair plots

Correlation heatmaps

Distribution analysis

3. Data Preprocessing
No missing data treatment required

Feature and target variable split

4. Model Building
Applied Simple Linear Regression and Multiple Linear Regression using sklearn

Evaluated model using:

R-squared score

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

5. Model Evaluation
Plotted actual vs predicted sales

Compared performance of models with and without different feature combinations

📈 Results
TV advertising showed the highest positive correlation with Sales.

A multiple regression model using TV, Radio, and Newspaper gave better prediction results.

Model metrics showed high accuracy with low error values, confirming the effectiveness of linear regression for this dataset.

🛠️ Libraries Used
pandas

numpy

matplotlib

seaborn

scikit-learn

🔍 Key Learnings
How to apply and interpret linear regression in a real-world scenario

How different advertising channels impact product sales

Importance of EDA before model training

How to evaluate regression models using various metrics

