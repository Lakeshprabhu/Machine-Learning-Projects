# E-Commerce Sales Prediction using Linear Regression

## 📌 Overview

This project applies **Linear Regression** to an **E-commerce customer dataset** to predict the yearly amount spent by a customer on the website, based on features like time spent on the site, length of membership, and more. The goal is to help the company understand which factors influence purchasing behavior the most.

## 📂 Dataset

The dataset includes the following features for each customer:

- `Email`: Customer's email address
- `Address`: Customer's physical address
- `Avatar`: Profile image
- `Avg. Session Length`: Average session time (minutes)
- `Time on App`: Average time spent on the mobile app (minutes)
- `Time on Website`: Average time spent on the website (minutes)
- `Length of Membership`: Number of years the customer has been a member
- `Yearly Amount Spent`: Target variable (in USD)

You can download a similar dataset [here](https://www.kaggle.com/datasets/thedevastator/customer-analytics).

## 🧪 Objective

Predict **Yearly Amount Spent** using the other numerical features to:

- Identify key drivers of revenue.
- Help in marketing strategy and app/website optimization.

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

## 🧮 Methodology

1. **Data Exploration**
   - Checked for missing values and data types.
   - Visualized relationships using pairplots and heatmaps.

2. **Feature Selection**
   - Dropped irrelevant columns (`Email`, `Address`, `Avatar`).
   - Selected numerical features for regression.

3. **Model Building**
   - Split data into training and testing sets.
   - Trained a **Linear Regression** model using `scikit-learn`.

4. **Evaluation**
   - Evaluated model using:
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - R² Score
   - Visualized predicted vs actual values.

## 📊 Results

- **R² Score**: ~0.98 (indicating a very good fit)
- **Most influential features**:
  - `Length of Membership` (strongest predictor)
  - `Time on App`
