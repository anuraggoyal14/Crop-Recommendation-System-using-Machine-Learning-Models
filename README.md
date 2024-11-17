# Crop-Recommendation-System-using-Machine-Learning-Models

## Overview
The **Crop Recommendation System** is a machine learning-based application designed to assist farmers and agricultural professionals in identifying the most suitable crop for cultivation under given environmental conditions. By analyzing key parameters such as soil composition, weather, and nutrient content, this system provides data-driven recommendations to optimize agricultural productivity.

## Features
- **Machine Learning Models**:
  - Employs advanced algorithms for accurate crop predictions.
  - Trained on a dataset containing essential agricultural features and optimal crop outcomes.

- **Input Parameters**:
  - **N**: Nitrogen content in the soil.
  - **P**: Phosphorous content in the soil.
  - **K**: Potassium content in the soil.
  - **Temperature**: Climatic temperature.
  - **Humidity**: Climatic humidity percentage.
  - **pH**: Acidity/alkalinity level of the soil.
  - **Rainfall**: Amount of rainfall (in mm).

- **Output**:
  - Recommends the most suitable crop to plant based on the input parameters.

- **User-Friendly**:
  - Provides easy-to-use functionalities for farmers, agronomists, and other users.

- **Performance Evaluation**:
  - Model evaluation metrics such as accuracy, precision, recall, and F1-score are computed for performance validation.

## Dataset
- The system uses the **Crop Recommendation Dataset** (`Crop_recommendation_dataset.csv`), which includes:
  - Soil nutrient values.
  - Environmental conditions (temperature, humidity, rainfall, etc.).
  - Crop types suitable for these conditions.

## How It Works
1. **Data Preprocessing**:
   - Handles missing values, data normalization, and scaling to ensure robust model performance.
2. **Model Training**:
   - Trains machine learning models on labeled data for crop recommendations.
3. **Prediction**:
   - Predicts the best crop based on user-provided input features.
4. **Performance Metrics**:
   - Evaluates the model using metrics like accuracy, precision, and recall to ensure reliability.

## System Requirements
- **Programming Language**: Python 3.8 or higher.
- **Libraries**:
  - `pandas`: For data manipulation.
  - `numpy`: For numerical computations.
  - `scikit-learn`: For machine learning algorithms.
  - `matplotlib`: For visualization.
  - `seaborn`: For data exploration and visualization.

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/anuraggoyal14/crop-recommendation-system.git
