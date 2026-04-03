# AI-ML-Task2-House-Price-Prediction
**House Price Prediction (AI/ML Task 2)**

## Overview

This project focuses on predicting house prices using Machine Learning techniques.
The **California Housing Dataset** is used to train and evaluate multiple regression models.

The goal is to apply feature engineering, improve model performance, and compare different algorithms to select the best model.


## Technologies Used

* Python
* Jupyter Notebook
* pandas
* NumPy
* scikit-learn
* matplotlib


## Dataset

* **Dataset:** California Housing Dataset
* **Target Variable:** Median House Value
* **Features include:**

  * Median Income
  * House Age
  * Average Rooms
  * Population
  * Location-based attributes

---

## Machine Learning Workflow

1. Data Loading
2. Data Exploration
3. Feature Scaling (StandardScaler)
4. Train-Test Split (80-20)
5. Model Training
6. Model Evaluation
7. Model Comparison
8. Visualization
9. Final Conclusion

---

## Models Used

* Linear Regression
* Ridge Regression
* Decision Tree Regressor

---

## Evaluation Metrics

* RMSE (Root Mean Squared Error)
* R² Score

---

## Results & Comparison

| Model             | RMSE      | R² Score  |
| ----------------- | --------- | --------- |
| Linear Regression | 0.745     | 0.575     |
| Ridge Regression  | 0.745     | 0.575     |
| Decision Tree     | **0.703** | **0.622** |

**Best Model: Decision Tree Regressor**


## Visualization

* Actual vs Predicted values plotted using scatter plot
* Points closer to diagonal line indicate better predictions
* Decision Tree shows better alignment → higher accuracy


## Conclusion

The **Decision Tree Regressor** performed the best among all models.
It captured non-linear relationships in the dataset more effectively than linear models.

Proper preprocessing, feature scaling, and model comparison significantly improved performance.

This project demonstrates a real-world machine learning workflow used in industry.


## 🚀 Future Improvements

* Hyperparameter tuning
* Feature importance analysis
* Model deployment
* Saving model using joblib

## 👨‍💻 Author

**Anshi Agrawal**

