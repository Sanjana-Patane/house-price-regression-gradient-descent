# house-price-regression-gradient-descent
# House Price Prediction using Linear Regression and Gradient Descent

## 1. Project Title

**House Price Prediction using Linear Regression and Gradient Descent Optimization**

## 2. Objective

The objective of this project is to develop a regression model for predicting house prices and evaluate its performance using appropriate regression metrics. Gradient Descent is also implemented and analyzed for Linear Regression.

## 3. Application

**Real-world Application:** House Price Prediction

The model predicts house prices using different features of houses such as area, bedrooms, bathrooms, floors, year built, location, condition, and garage.

## 4. Dataset

The House Price Prediction dataset is used in this project.

The main features include:

* Area
* Bedrooms
* Bathrooms
* Floors
* YearBuilt
* Location
* Condition
* Garage
* Price

The **Price** column is used as the target variable.

## 5. Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

## 6. Machine Learning Model

### Linear Regression

Linear Regression is used to predict house prices from the available house-related features.

### Gradient Descent

Gradient Descent is implemented for Linear Regression using Area as the input feature and Price as the target variable.

Learning Rate: **0.01**

Number of Iterations: **1000**

## 7. Performance Metrics

The models are evaluated using:

* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* R² Score

## 8. Implementation Steps

1. Load the dataset.
2. Analyze the dataset.
3. Check missing values and duplicate records.
4. Preprocess categorical features.
5. Split the dataset into training and testing data.
6. Train the Linear Regression model.
7. Generate predictions.
8. Calculate performance metrics.
9. Implement Gradient Descent.
10. Plot Cost versus Iterations.
11. Analyze the results.

## 9. Sample Output

### Linear Regression Performance

| Metric   |               Value |
| -------- | ------------------: |
| MAE      | See notebook output |
| MSE      | See notebook output |
| RMSE     | See notebook output |
| R² Score | See notebook output |


### Gradient Descent

| Parameter       |               Value |
| --------------- | ------------------: |
| Learning Rate   |                0.01 |
| Iterations      |                1000 |
| Final Slope     | See notebook output |
| Final Intercept | See notebook output |
| Final Cost      | See notebook output |

## 10. Results

The Linear Regression model successfully predicts house prices and its performance is evaluated using MAE, MSE, RMSE, and R² Score.

Gradient Descent is implemented for Linear Regression and its optimization process is analyzed using the Cost versus Iterations graph.


## 12. How to Run

The notebook can be opened using Google Colab or Jupyter Notebook.

Required libraries can be installed using:

```bash
pip install -r requirements.txt
```

Then open:

```text
House_Price_Regression.ipynb
```

and run the cells in order.

## 13. Conclusion

A Linear Regression model was developed for the real-world application of house price prediction. The model was evaluated using different regression metrics. Gradient Descent was also implemented for Linear Regression, and its optimization process was analyzed using the Cost versus Iterations graph.
