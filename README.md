# Forest Cover Type Prediction

## 🌳 Project Overview

This project aims to build a machine learning model to predict the type of forest cover for a given patch of land. Using a dataset from the Roosevelt National Forest, the system classifies land into one of seven distinct forest cover types based on cartographic and environmental features. This demonstrates a complete and professional machine learning workflow, from data exploration to model deployment.



## 🎯 Problem Statement

The goal is to solve a **multi-class classification** problem. The model is trained to accurately predict the `Cover_Type` (the target variable) using a variety of geographical features. This system can be used by forestry departments for rapid land classification.

The seven forest cover types are:
1. Spruce/Fir
2. Lodgepole Pine
3. Ponderosa Pine
4. Cottonwood/Willow
5. Aspen
6. Douglas-fir
7. Krummholz

## 📊 Methodology

The project follows a standard machine learning pipeline:

1.  **Data Exploration**: Initial analysis to understand the dataset's structure, check for missing values, and visualize the distribution of the target variable and key features.
2.  **Data Preprocessing**: Numerical features are scaled using `StandardScaler`, and the data is split into training and testing sets.
3.  **Model Training**: A **Random Forest Classifier** was chosen for its robustness and strong performance on this type of tabular data. The model was trained using `class_weight='balanced'` to handle the dataset's class imbalance.
4.  **Model Evaluation**: The model's performance was validated using **5-fold cross-validation** and a detailed **classification report** and **confusion matrix**.
5.  **Feature Importance**: The project analyzes which features are most influential in the model's predictions.

## 📈 Model Performance

The final Random Forest model achieved a high level of performance:

* **Overall Accuracy**: 86%
* **Mean Cross-Validation Accuracy**: 87%


