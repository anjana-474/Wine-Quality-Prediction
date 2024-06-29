# Wine Quality Prediction Using Logistic Regression

The goal is to classify wine quality based on its chemical properties using logistic regression. The quality is assessed on a scale, and we simplify it into binary categories for classification purposes.

# Dataset
The dataset contains the following features:
- fixed acidity
- volatile acidity
- citric acid
- residual sugar
- chlorides
- free sulfur dioxide
- total sulfur dioxide
- density
- pH
- sulphates
- alcohol
- quality (target variable)

# Implementation
The key steps involved in the implementation are:

**Data Preprocessing:**
- Handle missing values if any.
- Normalize or scale features as necessary.
- Convert the 'quality' feature into binary categories (e.g., good/bad).

**Model Training:**
- Use logistic regression to train the model on the training set.

**Model Evaluation:**
- Evaluate the model performance on the test set using classification metrics like confusion matrix, classification report, accuracy score, recall score, precision score, f1 score

# Conclusion

The logistic regression model effectively predicts wine quality based on its physicochemical properties. With proper preprocessing and feature selection, it provides reliable classification, aiding in quality control in the wine industry.
