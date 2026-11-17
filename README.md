# Used Car Price Estimation

## Project Overview
This project focuses on classifying used cars into different price segments using machine learning techniques. It analyses various vehicle attributes to predict the appropriate price category, helping understand how factors such as brand, model, manufacturing year, fuel type, transmission and kilometres driven influence a car's market value.

## Problem Statement
The objective is to develop a machine learning classification model that categorises used cars into five price segments:

- Budget
- Economy
- Mid Range
- Premium
- Luxury

## Technologies Used
- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- XGBoost

## Project Workflow
1. Data loading and exploration
2. Data cleaning and preprocessing
3. Handling missing values and duplicate records
4. Exploratory Data Analysis (EDA)
5. Feature engineering and categorical encoding
6. Feature scaling using RobustScaler
7. Training and evaluating multiple machine learning models
8. Hyperparameter tuning and model evaluation

## Machine Learning Models
The project explores and compares the performance of:

- Logistic Regression
- K-Nearest Neighbours (KNN)
- Support Vector Machine (SVM)
- Decision Tree
- Random Forest
- XGBoost

## Results
The models were evaluated using classification accuracy. The notebook records the following results:

| Model | Accuracy |
|---|---:|
| Logistic Regression | 78.37% |
| KNN | 77.59% |
| SVM | 81.26% |
| Decision Tree | 77.87% |
| Random Forest | 83.04% |
| XGBoost | 84.15% |

The final tuned Random Forest model recorded a test accuracy of **83.51%** in the notebook.

## Key Learning Outcomes
- Practical experience with machine learning classification.
- Data preprocessing and feature engineering.
- Exploratory data analysis and visualisation.
- Comparing multiple classification algorithms.
- Model evaluation and hyperparameter tuning.

## How to Run
1. Clone this repository.
2. Open the Jupyter Notebook in Google Colab or Jupyter Notebook.
3. Install the required dependencies.
4. Update the dataset path according to your local environment.
5. Run the notebook cells sequentially.

## Future Improvements
- Improve model generalisation through a leakage-safe preprocessing pipeline.
- Experiment with additional feature engineering techniques.
- Deploy the trained model through a simple web application.

---
**Developed as a Machine Learning project.**
