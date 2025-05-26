# Titanic-Dataset
Data cleaning and preprocessing on the Titanic dataset using Python. Includes handling missing values, encoding categorical variables, feature scaling, outlier removal, and logistic regression model training and evaluation.

## Dataset##
Source: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
File Used: `Titanic-Dataset.csv`

##Tools Used##
 Python
 Pandas
 NumPy
 Matplotlib
 Seaborn
 Scikit-learn (sklearn)
 Jupyter Notebook

##Steps done##
1. Import the dataset and explore basic structure and null values.
2. Handle missing data using median/mode and drop high-null columns.
3. Convert categorical variables (`Sex`, `Embarked`) into numerical format.
4. Normalize numerical columns (`Age`, `Fare`) using `StandardScaler`.
5. Visualize outliers using boxplots and remove them with the IQR method.
6. Split the dataset into train and test sets.
7. Train a Logistic Regression model and evaluate it using accuracy, classification report, and confusion matrix.

##Contact##
Feel free to reach out via [rpkroja@gmail.com] for any queries.
