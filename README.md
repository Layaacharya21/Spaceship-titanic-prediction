# Spaceship Titanic Prediction

## Overview
Spaceship Titanic Prediction is a machine learning project designed to predict whether passengers were transported to another dimension during the Spaceship Titanic disaster. This project analyzes passenger data to determine their outcomes using classification models.

## Project Features
- **Passenger Classification**: Predicts whether a passenger was transported to another dimension.
- **Feature Engineering**: Handles missing values, scales features, and extracts insights.
- **Visualization**: Provides data visualizations to explore trends and patterns.

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - TensorFlow

## Dataset
The dataset includes information such as:
- Passenger ID
- Home Planet
- CryoSleep status
- Cabin details
- Age
- VIP status
- Expenses on amenities (FoodCourt, ShoppingMall, etc.)
- Destination
- Transported (target variable)

### Source
The dataset was sourced from the [Kaggle Spaceship Titanic Competition](https://www.kaggle.com/competitions/spaceship-titanic). Ensure compliance with usage policies.

## Model Description
The project employs the following steps:
1. **Data Preprocessing**: Handles missing values, encodes categorical variables, and scales features.
2. **Feature Engineering**: Extracts meaningful insights from cabin details and expenses.
3. **Classification Models**: Utilizes XGBoost, Random Forest, and Logistic Regression to predict the "Transported" status.
4. **Hyperparameter Tuning**: Optimizes model performance using GridSearchCV.

## Results
- Achieved an accuracy of **80%** on the validation set.
- Visualized important features such as CryoSleep status, Home Planet, and Age.

## Future Enhancements
- Incorporate ensemble methods for improved accuracy.
- Analyze model interpretability using SHAP values.
- Deploy the model as a web application using Flask or Streamlit.

### Contact
If you have any questions or suggestions, feel free to reach out:
- Email: srilayakarampudi@gmail.com
- GitHub: [layaacharya21](https://github.com/layaacharya21)

