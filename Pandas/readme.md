# 🐼 Pandas Data Analysis

A collection of examples for **data loading, cleaning, transformation, and visualization** using [Pandas](https://pandas.pydata.org/).

## 📌 Features
- Load data from CSV, Excel, SQL, JSON
- Clean and preprocess datasets
- Group, aggregate, and pivot data
- Merge and join tables
- Time-series handling
- Basic plots with Matplotlib & Seaborn

## 📊 Example
```python
import pandas as pd

df = pd.read_csv('data/sample.csv')
print(df.head())
print(df.describe())

grouped = df.groupby('Category')['Value'].mean()
print(grouped)
```
