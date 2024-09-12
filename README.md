# Iris Classification using Logistic Regression

This project demonstrates the use of **Logistic Regression** to classify the famous Iris dataset. The dataset contains various features of iris flowers, and the goal is to predict the species based on these features.

## Dataset

- **Source**: [Iris Dataset](https://gist.githubusercontent.com/netj/8836201/raw/6f9306ad21398ea43cba4f7d537619d0e07d5ae3/iris.csv)
- **Features**: Sepal Length, Sepal Width, Petal Length, Petal Width
- **Target**: Flower Species

## Libraries Used

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Steps

1. **Importing Libraries**: Import necessary libraries for data manipulation and visualization.
   
2. **Load Data**: Load the Iris dataset using `sklearn.datasets.load_iris()` and read the dataset from a CSV file.

3. **Data Exploration**:
   - Display the first and last few rows of the dataset.
   - Check dataset shape and info.
   - Visualize unique values and missing values.

4. **Preprocessing**:
   - Encode the target variable.
   - Handle missing values if necessary.
   - Visualize the data using pair plots and heatmaps.

5. **Splitting the Data**:
   - Split the data into training and testing sets.

6. **Feature Scaling**:
   - Standardize the feature values.

7. **Model Training**:
   - Train a Logistic Regression model.

8. **Prediction**:
   - Make predictions on the test set.
   - Compare predicted and actual values.

9. **Evaluation**:
   - Calculate the accuracy score of the model.
   - Visualize the correlation between actual and predicted values.


