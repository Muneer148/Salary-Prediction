# Salary Prediction

Academic machine-learning project that uses an artificial neural network to predict salary in USD from structured employment data.

> **Project type:** Academic / learning project

## Pipeline

```text
Employment dataset
      ↓
Missing-value / duplicate handling
      ↓
Categorical one-hot encoding
      ↓
Feature standardization
      ↓
Train / test split
      ↓
Keras Sequential ANN
      ↓
RMSE + R² evaluation
```

## Model

The notebook uses a Keras Sequential network with:

- Dense(64, ReLU)
- Dense(32, ReLU)
- Dense(1)

Training uses Adam and mean squared error with validation monitoring.

## Repository structure

```text
Salary-Prediction/
├── README.md
└── requirements.txt
```

The original academic notebook can be added alongside the README when the dataset and notebook are ready to be published.

## Metrics

The project evaluates the regression model using:

- RMSE
- R²
- Training/validation loss curves

No benchmark number is claimed here because the result depends on the supplied dataset and training run.

## Status

Academic/learning project preserved as coursework rather than presented as a production salary-prediction service.

## Author

**Shaik Muneeruddin**
