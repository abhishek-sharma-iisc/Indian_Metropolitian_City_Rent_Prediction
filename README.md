# Indian Metropolitan City Rent Prediction

This project aims to predict the rent prices in various metropolitan cities in India using machine learning techniques. The project utilizes various regression models and grid search for hyperparameter tuning to achieve accurate predictions. As part of this project, we analyzed different models such as LinearRegression(), KNeighborsRegressor(), DecisionTreeRegressor(), GradientBoostingRegressor(), RandomForest() etc. Finally after analyzing there performance, we implemented XGBOOST with parameters optimized using Optuna.

## Project Structure

- **Indian_Metropolitian_City_Rent_Prediction.ipynb**: The main Jupyter Notebook containing the data preprocessing, model training, and evaluation steps.
- **data/**: Directory containing the dataset used for training and testing the models.
- **models/**: Directory where trained models are saved.

## Key Components

- **Data Preprocessing**: Handling missing values, encoding categorical variables, and feature scaling.
- **Model Training**: Training various regression models including Bagging Regressor.
- **Hyperparameter Tuning**: Using grid search to find the best hyperparameters for the models.

## Usage

1. Clone the repository:
    ```sh
    https://github.com/abhishek-sharma-iisc/Indian_Metropolitian_City_Rent_Prediction.git
    ```
2. Open the Jupyter Notebook:
    ```sh
    jupyter notebook Indian_Metropolitian_City_Rent_Prediction.ipynb
    ```

## Library Requirements
These are some of the major libraries used for implementation of the project.

``` numpy
pandas
matplotlib.pyplot
seaborn
plotly.express
plotly.graph_objects
plotly.subplots
optuna
sklearn
xgboost
```
