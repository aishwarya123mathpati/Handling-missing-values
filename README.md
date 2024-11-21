# Handling-missing-values on tiatanic dataset
The Titanic dataset is a classic dataset used for demonstrating various machine learning and data preprocessing techniques. It contains information about passengers aboard the Titanic and whether they survived the tragic sinking of the ship. This project demonstrates how to clean and preprocess the dataset by handling missing values and dropping unnecessary columns.

Objectives:
- Impute missing values in categorical and numerical columns using the most frequent value and the mean, respectively.
- Drop the Cabin column, which has too many missing values to be useful in the model.

# Missing Value Handling
- The project uses the fillna method from pandas to handle missing values in both categorical and numerical columns.

- For categorical columns (Sex, Embarked), we replace missing values with the most frequent value using the mode.
- For numerical columns (Age, Fare), we replace missing values with the mean value of the column.
