# Credit Card Balance Prediction


Project Overview
This project focuses on predicting credit card balances using a machine learning approach. The dataset contains information about individuals' financial and demographic characteristics, and the goal is to build and optimize a predictive model to forecast credit card balances.

Dataset
The dataset includes the following columns:

ID: A unique identifier for each individual.
Income: The individual's annual income (in thousands of dollars).
Limit: The credit limit assigned to the individual's credit card account.
Rating: A credit rating score for the individual.
Cards: The number of credit cards the individual possesses.
Age: The age of the individual.
Education: The number of years of education completed by the individual.
Gender: The gender of the individual (Male/Female).
Student: Whether the individual is a student (Yes/No).
Married: The marital status of the individual (Yes/No).
Ethnicity: The ethnic background of the individual.
Balance: The current balance on the individual's credit card account (target variable).

Project Phases
1. Exploratory Data Analysis (EDA)
Initial Exploration: Analyzed basic statistics and distribution of the dataset.
Correlation Analysis: Used heatmaps to identify strong correlations between variables such as 'Income', 'Limit', 'Rating', and 'Balance'.
Outlier Detection: Implemented methods to detect and cap outliers in the 'Income' column, using percentile-based capping.
Visualization: Created scatter plots and box plots to understand relationships between variables.

2. Data Preprocessing
Outlier Capping: Applied capping to outliers based on the 1st and 99th percentiles for key numerical features.
Encoding Categorical Variables: Converted categorical variables into numerical format for model compatibility.

3. Model Building
Linear Regression: Initially used Linear Regression to predict credit card balance. Evaluated performance using Mean Squared Error (MSE) and R² score.
Random Forest Regression: Implemented Random Forest Regression and performed hyperparameter tuning to optimize the model. Evaluated with improved MSE and R² score.

4. Model Evaluation
Mean Squared Error (MSE): Compared MSE values to assess model accuracy.
R² Score: Evaluated the proportion of variance explained by the model.

5. Results
Linear Regression:

MSE: 33,789.15
R² Score: 0.7978
Optimized Random Forest Regression:

MSE: 24,106.97
R² Score: 0.8557
The optimized Random Forest model demonstrated improved accuracy and a higher R² score, indicating better performance in predicting credit card balances.
