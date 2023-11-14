# Predicting Fraudulent Credit Card Transactions

## Main Challenge
The main challenge of this project is to analyze credit card transactions and create a model to predict the probability that a transaction is fraudulent.

## Folder Structure

```
├── xgb.log
├── data/
│ └── [Download data from the link provided in ReadMe below] # Although we used Parquet for the project, the CSV data link should suffice
├── notebooks/
│ └── CC_FINAL.ipynb # Jupyter notebooks for exploration and analysis
```

Link to data: https://www.kaggle.com/datasets/ealtman2019/credit-card-transactions

## Code Order

### Part 1:
- EDA
- Data Cleaning
- Initial Random Forest Model Testing

### Part 2:
- Code Refactoring
- Testing Additional Tuned XGBoost Model
- Plotting Model Results
- Testing the Model on Unseen Data (Predicting the Probability of Fraudulent Transactions)

### Part 3 (Optional):
- This part can be safely ignored because the XGBoost model above performed better (at least for now)
- Tuned Random Forest Model

## Libraries Used
- **pandas** (version 1.5.3)
- **numpy** (version 1.23.5)
- **missingno** (version 0.5.2)
- **sklearn** (not installed)
- **flaml** (version 2.1.1)
- **imblearn** (not installed)
- **xgboost** (version 2.0.1)
- **matplotlib** (version 3.7.3)
- **seaborn** (version 0.13.0)

