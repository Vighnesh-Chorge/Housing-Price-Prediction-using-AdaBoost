# 🏠 Housing Price Prediction using AdaBoost

This project applies the AdaBoost classification algorithm to predict housing prices based on features such as furnishing status, guestroom, air conditioning, and more.

## 📌 Overview

- Converts categorical data to numerical format using custom mapping
- Splits data into training and test sets
- Trains an AdaBoostClassifier
- Evaluates prediction accuracy by comparing with actual prices

> 🔍 Note: This approach treats price as a categorical target. For continuous values, `AdaBoostRegressor` is more appropriate.

## 📂 Dataset

- Source: `Housing.csv`
- Features include:
  - `furnishingstatus`, `guestroom`, `mainroad`, `basement`
  - `hotwaterheating`, `airconditioning`, `prefarea`
- Target: `price`

## ⚙️ Technologies Used

- Python  
- NumPy  
- Pandas  
- scikit-learn  

## 🚀 How to Run

1. Install required libraries:

```bash
pip install pandas numpy scikit-learn
````

2. Run the script:

```bash
python housing_adaboost.py
```

## 📈 Output

* Prints the percentage of correct predictions using AdaBoostClassifier

## 📌 Future Improvements

* Use `AdaBoostRegressor` for continuous price prediction
* Apply feature scaling
* Use metrics like RMSE or MAE for better evaluation
