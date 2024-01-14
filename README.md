## Mine v/s Rock Prediction using Machine Learning.
This system in Python that can predict whether an object is either Rock or Mine with SONAR Data. For this use case, we are using Logistic Regression Model for our prediction.

## Importing the Dependencies

Ensure you have the following dependencies installed:
- [Pandas](https://pandas.pydata.org/): Data manipulation library.
- [scikit-learn](https://scikit-learn.org/stable/): Machine learning library.
  - `train_test_split`: For splitting the dataset.
  - `LogisticRegression`: Logistic Regression model.
  - `accuracy_score`: Metric for evaluating the model.

1.Pandas:

Pandas is a powerful and easy-to-use data manipulation and analysis library for Python. It provides data structures like DataFrames for efficiently working with structured data such as CSV files.

2.scikit-learn:

Scikit-learn is a versatile machine learning library for Python. It includes various tools for data preprocessing, model training, evaluation, and more. It is built on NumPy, SciPy, and Matplotlib and is designed to work seamlessly with other scientific and data analysis libraries.

- Submodules:

- train_test_split:
train_test_split is a function in scikit-learn that allows you to split your dataset into training and testing sets. This is crucial for assessing the model's performance on unseen data.
- LogisticRegression:

LogisticRegression is a class in scikit-learn used for logistic regression modeling. Logistic regression is commonly used for binary classification problems.
- accuracy_score:
accuracy_score is a metric provided by scikit-learn to measure the accuracy of classification models. It compares the predicted labels to the true labels and calculates the accuracy of the model.

## Loading the dataset to pandas Dataframe

- The script uses Pandas to read a CSV file named 'Copy of sonar data.csv' into a DataFrame (`sonar_data`).
- The `header=None` argument indicates that the CSV file doesn't have a header row.
- The project is designed to be a starting point for further analysis or machine learning tasks using the sonar data.
