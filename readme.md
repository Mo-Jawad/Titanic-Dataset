
# 🛳 Titanic Survival Prediction

This is my first Machine Learning project where I apply Logistic Regression on the famous Titanic Dataset to predict passenger survival.
I achieved ~79% accuracy after performing feature engineering and one-hot encoding.


## 📌 Project Overview

The Titanic dataset is a classic beginner-friendly dataset used to practice classification algorithms.
The goal is to predict whether a passenger survived or not, based on features like age, gender, ticket class, etc.

## ⚙️ Steps in the Project

### Exploratory Data Analysis (EDA)

- Checked missing values
- Visualized distributions (Age, Fare, Pclass, etc.)
- Analyzed survival rate based on gender, class, and family size

### Data Preprocessing & Feature Engineering

- Handled missing values (Age, Embarked)

- Created new features (FamilySize, IsAlone)

- Converted categorical variables using one-hot encoding

### Modeling

- Applied Logistic Regression as a baseline model

- Trained on processed features

- Evaluated performance with accuracy score

## Results

- Achieved 79% accuracy on the test set

## 📂 Repository Structure

``` 
├── Titanic_EDA.ipynb   # Jupyter notebook with code and analysis

├── README.md           # Project documentation 
```

## 📊 Model Performance

- Algorithm used: Logistic Regression
- Final Accuracy: 79%

# 📦 Requirements

To run the notebook, install the dependencies:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```
## Dataset

[Titanic Dataset](https://github.com/mwaskom/seaborn-data/blob/master/titanic.csv)





