# Titanic Passenger Survival Prediction 

This repository contains my first complete Machine Learning project to predict passenger survival on the Titanic using Python and the Random Forest Classifier.

# Project Workflow
* **Data Cleaning:** Handled missing values in `Age` dynamically using the median based on passenger class (`Pclass`) and gender (`Sex`).
* **Feature Engineering:** Converted categorical text columns into numerical values using One-Hot Encoding (`pd.get_dummies`) for the `Embarked` column.
* **Feature Selection:** Dropped non-informative columns like `PassengerId`, `Name`, and `Ticket` to optimize model performance and prevent overfitting.
* **Model Training:** Trained a **Random Forest Classifier** (`n_estimators=100`, `max_depth=5`) to benefit from multiple decision trees and voting mechanisms.

# Results
* Successfully submitted the predictions to the Kaggle Competition!
