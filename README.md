# Flight Price Prediction

This project aims to predict flight prices using machine learning techniques. The dataset used in this project is the "Flights" dataset downloaded from Kaggle.

## Data Cleaning

The first step in the project was data cleaning. This involved the following steps:

- Removing duplicate entries from the dataset.
- Applying the `.assign()` function wherever needed to create new columns or modify existing ones.

## Exploratory Data Analysis (EDA)

Exploratory Data Analysis (EDA) was performed to gain insights into the dataset. This included:

- Analyzing the distribution of features.
- Finding correlations between features to understand their relationships.

## Feature Selection

Feature selection is crucial for building a robust machine learning model. In this project, a pipeline of transformers was used for feature selection. This involved:

- Defining a pipeline of transformers to preprocess the data.
- Selecting the most relevant features for prediction.

## Model Training

The selected features were then used to train a Random Forest Regressor model. This model is known for its ability to handle non-linear relationships and provide accurate predictions.

## Deployment

The complete package, including data preprocessing, model training, and prediction, was deployed using Streamlit. Streamlit is a powerful tool for building interactive web applications with Python.

## Acknowledgments

- Special thanks to the documentation on Google and YouTube for providing valuable insights and guidance throughout the project.
- Thanks to the Kaggle community for sharing the "Flights" dataset, which was used in this project.
- Thanks to the Streamlit team for creating an easy-to-use platform for building interactive web applications with Python.
