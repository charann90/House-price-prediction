
# House Price Prediction ML Model

This repository contains a machine learning model for predicting house prices. The model is trained using a dataset of house features and corresponding prices to learn the patterns and relationships between the input features and the target variable (house prices). The trained model can be used to predict the prices of new houses based on their features.

## Dataset

The dataset used for training the model is stored in the `dataset.csv` file. It includes various features of houses such as the Transaction date,House Age, Distance from nearest Metro station(km), Number of convenience stores,	latitude,	longitude,	Number of bedrooms	House size (sqft),	House price of unit area

## Model Development

The model development process involved several steps:

1. Data Preprocessing: The dataset was cleaned and preprocessed to handle missing values, outliers, and feature scaling. Categorical variables were encoded using one-hot encoding or label encoding as appropriate.

2. Feature Selection and Engineering: Relevant features were selected based on their importance and correlation with the target variable. New features were engineered if deemed beneficial for improving the model's performance.

3. Model Training: Several regression algorithms, including linear regression, decision tree regression, and random forest regression, were experimented with. The models were trained using the preprocessed dataset and evaluated using suitable evaluation metrics such as R square score and adjusted R square score.

4. Hyperparameter Tuning: The hyperparameters of the selected model were fine-tuned using techniques like grid search or random search to optimize its performance.

5. Model Evaluation: The final trained model was evaluated using cross-validation and performance metrics to assess its generalization ability and accuracy.


## Results

The performance of the trained model on the test dataset was evaluated using the R2 square.
Random forest model is the ideal model for prediction with R2 score of train set- 94% and test set- 78%

## Future Improvements

There are several potential areas for further improvement and enhancement of the house price prediction model:

- Incorporating additional features that might have an impact on house prices, such as proximity to amenities, crime rates, or school ratings.
- Exploring more advanced regression techniques or ensemble models for improved accuracy.
- Gathering more data to increase the size and diversity of the training dataset.
- Implementing a web-based interface or API for easy deployment and usage of the model.


