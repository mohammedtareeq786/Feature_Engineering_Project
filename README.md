# Feature_Engineering_Project
# Predictive Modeling of Housing Prices with TensorFlow and Keras

## Project Description
This project involves the development of a machine learning model to predict median house values based on various housing features. The model is built using TensorFlow and Keras, popular libraries for machine learning.

## Data Processing
The first step in the project is data processing. The 'housing.csv' dataset is loaded into a DataFrame. This dataset is then split into training, validation, and test sets. An input pipeline is created using TensorFlow's `tf.data` API, which allows for efficient batching and shuffling of the data.

## Model Building
The next step is model building. A Sequential model is constructed using Keras, with Dense layers added to process the features. Feature columns are created for both numeric and categorical data, allowing the model to interpret the data correctly.

## Training
The model is trained on the dataset using Mean Squared Error (MSE) as the loss function. This function measures the average squared difference between the predicted and actual values, providing a quantifiable measure of the model's performance.

## Evaluation
After training, the model's performance is evaluated using MSE. Additionally, loss curves are visualized to provide insight into the training process over epochs. These curves can help identify issues like overfitting or underfitting.

## Feature Engineering
The project also explores advanced feature engineering techniques to improve model performance. These techniques include scaling, bucketization, and feature crosses. Scaling adjusts the range of numeric features, bucketization groups numeric features into different categories, and feature crosses combine features to create new ones.
