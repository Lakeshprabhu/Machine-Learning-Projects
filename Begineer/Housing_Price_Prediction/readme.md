# Housing Price Prediction: New York & California

This project predicts housing prices for properties in **New York** and **California** using two regression models:

- **Linear Regression**
- **Random Forest Regressor**

## Dataset
The dataset includes housing features such as:
- Area (square footage)
- Number of bathrooms
- Number of stories
- Parking spaces
- Price (target variable)

Filtered data covers only **New York** and **California**.

## Approach
1. Data cleaning and feature selection.
2. Splitting into training (80%) and testing (20%) sets.
3. Training models:
   - Linear Regression for baseline performance.
   - Random Forest Regressor for improved accuracy.
4. Model evaluation using:
   - Mean Absolute Error (MAE)
   - R² Score

## Results
- **Linear Regression** provided a quick baseline with moderate accuracy.
- **Random Forest Regressor** captured non-linear relationships, achieving higher accuracy and lower MAE after trainging in certain scenario's . 
