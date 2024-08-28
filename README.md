# Housing Prices Prediction

## Introduction
This project predicts housing prices using machine learning models. It includes data preprocessing, model training, and evaluation.

## Model Architecture
- **Linear Regression**: A basic regression model to predict prices based on features.
- **Random Forest Regressor**: An ensemble method for improving prediction accuracy by combining multiple decision trees.

## Training Process
1. **Data Loading**: The dataset is loaded from a CSV file.
2. **Preprocessing**: Missing values are handled, categorical variables are encoded, and features are scaled.
3. **Model Training**: Models are trained and evaluated using cross-validation.
4. **Hyperparameter Tuning**: RandomizedSearchCV is used to find the best hyperparameters for the Random Forest model.

## Usage Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/housing.prices.prediction.git
2. **Install Dependencies**: Make sure you have the required libraries installed. You can use pip to install them:  
        (pip install pandas scikit-learn matplotlib) and other required libraries.
3. **Predict House Prices**: Use the provided code to input new data and predict house prices
