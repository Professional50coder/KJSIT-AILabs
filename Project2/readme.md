## Salary Prediction and Classification

This project demonstrates the implementation of linear regression and logistic regression models to predict and classify salaries based on years of experience.

### Linear Regression

The linear regression model is used to predict the salary based on the years of experience. The key steps are:

1. Load the dataset (Salary_Data.csv) and explore the data.
2. Normalize the data using MinMaxScaler.
3. Split the data into training and testing sets.
4. Train the linear regression model.
5. Evaluate the model using performance metrics like Mean Squared Error (MSE), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).
6. Visualize the regression line.

### Logistic Regression

The logistic regression model is used to classify salaries into two classes: low and high, based on the years of experience. The key steps are:

1. Convert the salary column into a binary class (low/high) based on the median salary.
2. Normalize the data using MinMaxScaler.
3. Split the data into training and testing sets.
4. Train the logistic regression model.
5. Evaluate the model using accuracy score, confusion matrix, and classification report.
6. Visualize the decision boundary.

### Dependencies

The project requires the following Python libraries:

* pandas
* scikit-learn (sklearn)
* numpy
* matplotlib
* seaborn

### Usage

1. Ensure you have the required dependencies installed.
2. Load the `Salary_Data.csv` file in the same directory as the code.
3. Run the Jupyter Notebook or Python script to execute the code.

### Conclusion

This project demonstrates the use of linear regression and logistic regression for salary prediction and classification based on years of experience. The results can be further improved by exploring additional features, tuning model hyperparameters, or using more advanced techniques.
