
# **Game Success Prediction Project**

This project aims to predict the success of mobile games by using various features such as pricing, size, user ratings, and more. The dataset used contains information about different mobile games and their attributes. The project involves several steps, including data exploration, visualization, data preprocessing, feature engineering, and model training.

# Importing Necessary Packages:
Imported various Python libraries like Pandas, NumPy, Matplotlib, Seaborn, Plotly, and more for data analysis, visualization, and machine learning.

# Data Exploration & Visualization:
Conducted data exploration and visualization to better understand the dataset's characteristics:
Printed the dataset's information.
Checked for unique values and the count of missing values in each attribute.
Calculated and displayed important statistical values for selected columns (Price, Size, Average User Rating).
Explored unique values in the 'Age Rating' and 'Primary Genre' attributes.
Extracted and processed the 'Languages' attribute to find unique languages used in the dataset.
Visualized the distribution of prices using bar plots.
Created a pie chart to compare free-to-play and pay-to-play games.
Plotted the distribution of age ratings using a pie chart.
Analyzed the distribution of average user ratings using a bar plot.
Visualized the distribution of game genres using a bar plot.
Plotted a correlation heatmap to visualize attribute correlations.
Data Preprocessing:
# Performed data preprocessing steps to prepare the dataset for machine learning:
Split the 'Languages' attribute into separate tokens and one-hot encoded languages.
Kept the top languages and genres, dropping the rest.
Created binary columns for the top appearing developers.
Transformed date-related columns into the 'duration_days' attribute.
Filled missing values in 'In-app Purchases' and language columns.
Converted 'Age Rating' to numeric values and 'Size' to float.
Handled missing values and scaled features appropriately.
# Feature Selection:
Selected relevant features for the machine learning model using feature selection techniques:
Imputed missing values and standardized the dataset.
Used SelectKBest with f_regression to select the top features.

# Model Training and Evaluation:
Trained regression models to predict game success and evaluated their performance:
Utilized Linear Regression, Ridge Regression, Lasso Regression, and Gradient Boosting Regressor.
Split the data into training and testing sets.
Evaluated each model's performance using metrics like Mean Squared Error, R-squared, and cross-validation scores.
Visualized the predicted values against the actual values using scatter plots.
The project showcases a comprehensive approach to predicting game success by exploring, visualizing, preprocessing, and modeling the dataset. It emphasizes the importance of feature engineering, model selection, and evaluation in achi
