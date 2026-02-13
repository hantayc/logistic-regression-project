# Bank Churn Prediction
*Kaggle Playground Series - Season 4, Episode 1* 

Binary classification of customer churn using tabular banking data.
Goal: Predict whether a customer will exit the bank (`Exited = 1`) and optimize for ROC-AUC

-- 
## 📁 Dataset

Provided from Kaggle: 

- `train.csv` - Training features + target 
- `test.csv` - Test features (no target) 
- `sample_submission.csv` - Submission Format

Feature Examples: 

- `CreditScore`
- `Geography`
- `Gender`
- `Age`
- `Balance` 
- `NumOfProducts`
- `IsActiveMember`
- `EstimatedSalary`
- `Exited` (target)

## Project Structure

.
├── poetry.lock
├── pyproject.toml
├── README.md
├── src
│   ├── bank_churn_log_regression
│   │   └── __init__.py
│   ├── data
│   │   ├── sample_submission.csv
│   │   ├── test.csv
│   │   └── train.csv
│   ├── evaluate.py
│   ├── models
│   ├── notebooks
│   └── train.py
└── tests
    └── __init__.py

## Setup 

This project will use **Poetry** for dependency management. 

### Install dependencies 
```bash 
poetry install 
```

### Activate Environment 
```bash 
poetry env activate
```