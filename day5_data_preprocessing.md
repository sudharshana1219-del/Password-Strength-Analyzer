# Day 5 - Data Preprocessing

## Derived Features Creation

Two new features were created from existing columns:

1. Password Length
   - Number of characters in each password.

2. Password Complexity Score
   - Based on uppercase letters, lowercase letters, numbers, and special characters.

## Categorical Variable Encoding

The categorical variables were converted into numerical format using Label Encoding.

Action Taken:
- Password categories were encoded into numeric values.
- This makes the data suitable for machine learning algorithms.

## Feature Scaling

Numerical features were scaled to ensure consistent values across the dataset.

Action Taken:
- Password Length was scaled.
- Complexity Score was scaled.

## Train/Test Split

The dataset was divided into training and testing sets.

Split Ratio:
- Training Data: 80%
- Testing Data: 20%

Purpose:
The training set is used to train the model, and the testing set is used to evaluate its performance.

## Code Documentation

All preprocessing steps were documented with clear comments.
