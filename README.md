Boston Housing Price Prediction Project

This project aims to predict house prices in Boston using data from the Boston Housing Dataset. The primary objective was to analyze key factors influencing house prices and build an accurate predictive model.

Project Overview:
Data Exploration: I began by loading the dataset, which contains 506 rows and 14 features related to housing characteristics, such as crime rate (CRIM), average number of rooms (RM), and the percentage of lower-status population (LSTAT). An initial review of the data showed no missing values, making it suitable for immediate analysis.

Correlation Analysis: To understand the relationships between features, I generated a correlation matrix. This revealed that LSTAT (negative correlation) and RM (positive correlation) were most strongly related to the target variable, MEDV (median house price). These insights guided feature selection for model training.

Data Visualization: I visualized the data using scatterplots and heatmaps to better understand the relationships between variables. For instance, as the percentage of lower-status population (LSTAT) increased, house prices tended to decrease. Similarly, houses with more rooms (RM) tended to have higher prices.

Model Building: I applied three machine learning models to predict house prices:

Linear Regression
Decision Tree Regression
Random Forest Regression
The dataset was split into training and testing sets (70% training, 30% testing), and each model was evaluated for accuracy using R-squared scores. Random Forest Regression emerged as the best-performing model due to its ability to handle complex data and prevent overfitting.

Model Evaluation: The performance of the models was measured on both the training and testing datasets. The Random Forest model provided the highest R-squared score, indicating better predictive accuracy compared to Linear Regression and Decision Tree Regression.

Conclusion:
Through this project, I gained valuable insights into the factors affecting house prices in Boston. Linear Regression proved to be the most effective model for this prediction task, delivering the highest accuracy. This project showcases how data analysis and machine learning techniques can be leveraged to predict housing prices and guide real estate decision-making.
