# Airbnb Singapore Price Prediction

Data science project to predict nightly Airbnb listing prices
in Singapore as part of the OmahTI Academy Data Science & AI Final Project.

## Objective

Predict the nightly price of Airbnb listings based on listing
characteristics and location-related features.

## Dataset

[Dataset information / Kaggle competition link]

## Methodology

1. Import libraries & load data
2. Feature engineering — comment sentiment
3. Merging all data tables
4. Feature engineering — parsing raw columns into numeric features
5. Defining feature columns (categorical & numeric)
6. Cleaning the target (`price`) & log-transform
7. Cross-validation (KFold) for model evaluation
8. Training the final model & creating the submission file

## Model

LGBMRegressor

## Results

### Kaggle Public Leaderboard

- MAPE: **27.17%**

The leaderboard score was calculated by Kaggle using the
competition's hidden test data.
