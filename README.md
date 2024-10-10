Boston House Price Prediction

In this project, I developed a predictive model to estimate house prices in Boston using data from the Boston Housing Dataset. The goal was to analyze the relationships between various housing features and predict the median house prices (MEDV).

Steps Involved:
Data Exploration: I started by importing the dataset, which contains 506 rows and 14 columns representing different features like crime rate (CRIM), number of rooms (RM), tax rate (TAX), and percentage of lower status population (LSTAT). Initial data analysis revealed no missing values, allowing for seamless model development.

Correlation Analysis: A correlation matrix was used to identify key features affecting house prices. The features LSTAT and RM showed the strongest correlation with MEDV, the target variable. This guided the selection of features for modeling.

Data Visualization: I visualized relationships between the variables using scatterplots and a heatmap. For example, a negative correlation was observed between LSTAT and MEDV, while RM had a positive relationship with house prices.

Model Development: Three regression models were implemented to predict house prices:

Linear Regression
Decision Tree Regression
Random Forest Regression
After splitting the data into training and test sets (70/30 split), each model was trained and evaluated using R-squared scores to measure accuracy. Random Forest Regression performed the best among the three, providing a balance between bias and variance.

Model Evaluation: The models were evaluated based on their performance on both the training and testing datasets. The final R-squared scores for each model were compared, allowing me to conclude which model was most suitable for this prediction task.

Conclusion:
This project provided valuable insights into the factors influencing house prices in Boston. By comparing different regression models, I was able to identify Random Forest Regression as the most effective model for predicting home prices. The analysis demonstrates how data-driven approaches can provide powerful insights into real estate markets.
