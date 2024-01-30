# Flight Price Prediction

Welcome to the Flight Price Prediction project repository! This Jupyter Notebook focuses on predicting flight prices using different regression models. The dataset includes features related to flights, such as duration, stops, airline, and more. The goal is to build and compare three regression models: Linear Regression, Decision Tree Regressor, and Random Forest Regressor.




## Getting Started

### Prerequisites

Before running the notebook, ensure you have the following dependencies installed:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### Steps to Run the Notebook
1. Clone this repository to your local machine:

```bash
git clone https://github.com/Harbringe/Flight-price-prediction/
```
2. Navigate to the project directory:
```bash
cd Flight-price-prediction
```
3. Download the dataset using the provided link and place it in the project directory.

4. Open and run the "flight_price_prediction.ipynb" notebook using Jupyter Notebook or Jupyter Lab:

```bash
jupyter notebook flight_price_prediction.ipynb
```
Follow the instructions in the notebook to execute each cell.

## Models Included:

1. **Linear Regression**
2. **Decision Tree Regressor**
3. **Random Forest Regressor**


## Model Comparison

| Model No. | Model                    | MSE    | RMSE   | MAE    | R Squared |
|-----------|--------------------------|--------|--------|--------|-----------|
| 1         | Linear Regression        | 0.0033 | 0.0575 | 0.0379 | 0.9043    |
| 2         | Decision Tree Regressor  | 0.0023 | 0.0477 | 0.0287 | 0.9344    |
| 3         | Random Forest Regressor  | 0.0018 | 0.0418 | 0.0218 | 0.9494    |

Feel free to explore the notebook to understand the modeling process and results. Happy predicting!

