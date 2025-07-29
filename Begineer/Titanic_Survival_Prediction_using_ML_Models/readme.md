🚢 Titanic Survival Prediction


This project predicts the survival of passengers on the Titanic using machine learning models after performing exploratory data analysis (EDA) and preprocessing. 
Various classification models were evaluated, and K-Nearest Neighbors (KNN) gave the best performance on the testing dataset.


📊 Dataset


Source: Kaggle Titanic Dataset

Features: Age, Sex, Pclass, Fare, Embarked, SibSp, Parch, etc.

Target: Survived (0 = No, 1 = Yes)



🔍 Exploratory Data Analysis (EDA)

Checked missing values (Age, Cabin, Embarked)

Visualized survival rates by gender, class, age, and more

Performed feature engineering:

Imputed missing values

Converted categorical variables to numeric (e.g., Sex, Embarked)

Created new features (e.g., FamilySize)




🛠️ Models Trained



The following classification models were trained and evaluated:

Logistic Regression

Support Vector Machine (SVM)

Decision Tree

K-Nearest Neighbors (KNN)

All models were trained using the same split of training and testing data for fair comparison.



✅ Evaluation Metric

Accuracy Score




🏆 Best Model

K-Nearest Neighbors (KNN) achieved the highest accuracy on the testing dataset.

Accuracy Comparison:

The accuracy score of SVM is 82.8 %

The accuracy score of Logastic Regression is 100.0 %

The accuracy score of Decision Tree classification is 82.78 %

The accuracy score of KNN classification is 82.78 %
