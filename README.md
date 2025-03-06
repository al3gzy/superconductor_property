# Superconductor Property Prediction

## Introduction
This project is focused on predicting the superconducting critical temperature (**Tc**) of materials using machine learning models. Superconductors are materials that allow electricity to flow without resistance at low temperatures, and discovering new ones can have far-reaching implications for technology, including power transmission and medical devices. The goal is to predict the **Tc** based on material properties like composition, atomic structure, and other characteristics.

## Features
- **Data Exploration**: The dataset of superconducting materials is analyzed by plotting correlations, distributions, and category comparisons to better understand the factors influencing **Tc**.
- **Data Preprocessing**: In this step, continuous variables are normalised, and categorical variables (such as material composition and category) are encoded. This makes the data suitable for training machine learning models.
- **Model Selection**: Different machine learning models, including Linear Regression, Random Forest, and Gradient Boosting, are tested to predict **Tc**.
- **Model Evaluation**: Each model’s performance is evaluated by calculating MSE and R² scores, where **MSE** measures the error in predictions, and **R²** shows how well the model explains the variance in **Tc**.
- **Cross-Validation**: Cross-validation is performed to assess the stability and generalization of the models. This step ensures that the models are not overfitting the data.
- **Hyperparameter Tuning**: A Randomized Search is used to fine-tune the hyperparameters of the Random Forest model. This allows us to find the most optimal configuration for the model’s performance.
- **Feature Importance**: The relative importance of each feature in predicting **Tc** is analyzed to understand which factors are the most influential in determining the superconducting temperature.
- 
## Results
After evaluating the models, the **Random Forest** model outperforms the others, with the lowest MSE and the highest R² score, making it the best choice for predicting **Tc**.
