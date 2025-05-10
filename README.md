# Ames Housing Price Prediction 🏠

A beginner machine learning project using the **Ames Housing dataset** to predict house prices using **Multiple Linear Regression**. This project covers a complete pipeline: data preprocessing, feature engineering, modeling, evaluation, and feature selection.

## Dataset

- Source: [Ames Housing Dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)
- Target: `SalePrice` (final sale price of the house in USD)

## Project Structure

- `/ml-multiple-linear-regression/notebooks/ames_housing_multiple_linear_regression.ipynb`: Main notebook
- `pyproject.toml`: Poetry-managed dependencies
- `poetry.lock`: Locked versions for reproducibility
- `/data/AmesHousing.csv`: Raw dataset

## Features & Tools

- 🧼 Data preprocessing using `ColumnTransformer` and `Pipeline`
- 🧠 Handling missing values (`SimpleImputer`)
- 🔤 Encoding categorical variables (`OneHotEncoder`)
- 📈 Multiple linear regression modeling (`LinearRegression`)
- 🔍 Forward stepwise feature selection (`SequentialFeatureSelector`)
- 📊 Evaluation using RMSE, MSE, and R²
- 📉 Visualization of actual vs predicted prices

## How to Run

1. Clone the repository
2. Run: `poetry install`
3. Activate: `poetry shell`
4. Launch Jupyter: `jupyter notebook`
5. Open the notebook in `/notebooks/` and run all cells

## Steps Covered

✅ Data loading and preview  
✅ Exploratory Data Analysis (EDA)  
✅ Missing value treatment  
✅ Feature identification: numeric vs categorical  
✅ ColumnTransformer for preprocessing  
✅ Splitting into training/test sets  
✅ Preprocessing and transformation  
✅ Forward stepwise feature selection  
✅ Linear regression modeling  
✅ Model evaluation with RMSE, MSE, and R²  
✅ Actual vs predicted plot  
✅ Result interpretation

## Results

- **Model:** Multiple Linear Regression  
- **Feature selection:** Forward selection (15 best features)  
- **RMSE:** ~24,485  
- **R²:** ~0.903

> Final scatter plot shows predictions align well with actual values for mid-range homes. Some underprediction at high-value properties is expected due to limited data in that range.
