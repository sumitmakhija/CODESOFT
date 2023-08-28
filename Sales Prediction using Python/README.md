# Sales Prediction using Machine Learning in Python

Sales prediction is a fundamental task in the world of business, allowing companies to make informed decisions on marketing strategies, inventory management, and more. This project dives deep into predicting sales based on advertising expenditures across different media channels: TV, Radio, and Newspaper.

## Dataset

The dataset used in this project, `advertising.csv`, contains information about money spent on advertisements in TV, Radio, and Newspaper, along with the corresponding sales figures.

## Steps Involved:

### 1. Loading the Data
   - The dataset is loaded into a pandas dataframe for analysis and model training.
   
import pandas as pd

# Load the dataset
data = pd.read_csv('/mnt/data/advertising.csv')
data.head()

## Exploratory Data Analysis (EDA)
A summary of the data is generated to understand its distribution.
Missing values, if any, are identified.
Scatter plots are used to visualize the relationships between advertising costs (TV, Radio, and Newspaper) and sales.
-------------------------------------------------
## Data Splitting:
The dataset is split into training (80%) and testing (20%) sets for model training and validation.
Building a Sales Prediction Model
A linear regression model is trained on the training data.
Predictions are made on the test set and the model is evaluated using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R2 score.
-------------------------------------------------
## Interpretation of Coefficients:
The coefficients and intercept of the trained linear regression model are extracted for interpretation.
---------------------------------------------
## Residual Analysis:
The residuals (difference between actual and predicted values) are plotted against the fitted values to check for any patterns or outliers.
--------------------------------------------------
## Feature Engineering:
Interaction terms are added to the dataset to potentially improve the model's predictive power.
---------------------------------------------------
## Cross-validation:
Cross-validation is performed to assess the model's performance across different subsets of the training data.
----------------------------------------------------------------
## Correlation Analysis:
A correlation matrix is generated to understand the relationships between different features.
--------------------------------------------------------------
## Accuracy Check
The Mean Absolute Error (MAE) is calculated to evaluate the model's accuracy.
----------------------------------------------------------------
## Conclusion
This project showcases the potential of machine learning in making informed predictions about sales based on advertising data. By understanding the relationships between advertising expenditures and sales, businesses can optimize their strategies and achieve better outcomes.
