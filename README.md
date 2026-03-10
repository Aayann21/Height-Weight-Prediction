# 📊 Height Weight Prediction

## Project Overview

This project predicts **weight based on height** using a **Linear Regression machine learning model**. The model learns the relationship between height and weight from the dataset and predicts weight for new height values.

## Libraries Used

* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

## Dataset

The dataset contains two attributes:

* **Height** – Input feature
* **Weight** – Target variable

## Algorithm Used

**Linear Regression**

Linear Regression is a supervised machine learning algorithm used to predict continuous values. It finds the best linear relationship between the input feature (height) and the output variable (weight).

## Steps / Algorithm

1. Import required libraries.
2. Load the dataset using pandas.
3. Display dataset using `head()` function.
4. Check for missing values in the dataset.
5. Select **Height** as the input feature and **Weight** as the target variable.
6. Split the dataset into **training and testing sets**.
7. Train the **Linear Regression model** using training data.
8. Predict weight values using the test dataset.
9. Evaluate the model using performance metrics.
10. Visualize the relationship between height and weight using plots.

## Visualizations

The project includes several visualizations such as:

* Scatter plot (Height vs Weight)
* Histogram of Height
* Correlation Heatmap
* Violin Plot
* Pairplot for feature relationships

## Result

The Linear Regression model successfully learns the relationship between **height and weight** and predicts weight values for the given height data.

## Conclusion

From the analysis, we observe that **height and weight have a positive relationship**. As height increases, weight also tends to increase. The Linear Regression model can effectively predict weight based on height using the dataset.

---
