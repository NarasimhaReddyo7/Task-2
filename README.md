Name : KOTA UGRA NARASIMHA REDDY
Company : CODTECH IT SOLUTIONS
ID : CT6WDS2240
Domain : Machine Learning
Duration : October to December 2024
Mentor : NEELA SANTOSH KUMAR

**Overview of the Project:**
**Linear Regression on Housing Prices: Project Report**
**1. Introduction**
The aim of this project was to predict housing prices based on various features using a linear regression model. For this purpose, we utilized the California Housing Dataset, which is a widely accepted alternative to the deprecated Boston Housing Dataset. This dataset includes features like average room size, population, and income, which influence median house values.

**2. Dataset Overview**
Dataset: California Housing Dataset (available in Scikit-learn).
Target Variable: MedHouseVal (Median House Value).
Features:
AveRooms: Average number of rooms per household.
AveBedrms: Average number of bedrooms per household.
Population: Population in the area.
AveOccup: Average number of occupants per household.
Latitude and Longitude: Geographical location.
MedInc: Median income in the area.
**3. Objectives**
Train a linear regression model to predict median house values.
Evaluate the model's performance using metrics like Mean Squared Error (MSE) and R-squared (R²).
Visualize the data to understand feature relationships and evaluate model accuracy.
Provide insights into feature importance.
**4. Methodology**
The project was divided into the following stages:

**Data Preprocessing:**

Loaded the California Housing dataset.
Split the data into training (80%) and testing (20%) subsets.
Model Training:

A Linear Regression model was trained using the training set.
**Model Evaluation:**

Predicted house values on the testing set.
Evaluated the performance using:
Mean Squared Error (MSE): Measures the average squared difference between actual and predicted values.
R-squared (R²): Indicates how much variance in the target variable is explained by the features.
**Data Visualization:
**
Scatter plots, heatmaps, and residual plots were used to visualize relationships and model performance.
Feature importance was analyzed using the model's coefficients.
5. Results
**Model Performance:**

Mean Squared Error (MSE): The error value was calculated, indicating the model's predictive accuracy.
R-squared (R²): The model explained a significant portion of the variance in the target variable.
Adjusted R²: Considered the number of predictors, ensuring a fair evaluation of model performance.
**Feature Importance:
**
Features like MedInc (Median Income) and AveRooms had the highest impact on housing prices.
Geographical factors (Latitude and Longitude) also contributed significantly.
**Visualization Insights:**

Correlation Heatmap: Highlighted strong positive correlation between MedInc and MedHouseVal.
Residual Plot: Residuals were normally distributed, indicating no major model bias.
Actual vs Predicted Values: Close alignment for most predictions, with some deviations.
**6. Key Visualizations**
Scatter Plot:

Visualized the relationship between MedInc and MedHouseVal, showing a strong positive correlation.
Residual Distribution:

Verified normal distribution of residuals, confirming model reliability.
Feature Importance:

Barplot of linear regression coefficients highlighted the relative importance of features.
![Screenshot 2024-12-07 165304](https://github.com/user-attachments/assets/fcec71bf-b636-423b-ba49-b3ecafc7435e)

![Screenshot 2024-12-07 165245](https://github.com/user-attachments/assets/fff621c5-d9ac-434d-8fcc-8f26fad16787)
![Screenshot 2024-12-07 165227](https://github.com/user-attachments/assets/011a5f27-8140-4e75-a161-ad8dcdf39726)
![Screenshot 2024-12-07 165205](https://github.com/user-attachments/assets/90f55065-ff31-49f9-8116-1e58cc63da7a)
