# Weather Classification using Decision Trees

## Overview

This project performs **weather classification** using a **Decision Tree Classifier**.
The dataset (`Weather Data.csv`) contains various meteorological attributes and a target column `Weather` that describes the weather condition.

The notebook walks through data cleaning, feature encoding, model training, evaluation, and visualization.

---

## Files

* **Weather_Classification_DecisionTree.ipynb** — Main Jupyter Notebook containing all steps of the assignment.
* **Weather Data.csv** — Input dataset (must be placed in the same directory as the notebook).
* *(Optional)* **weather_dt_model.joblib** — Trained model file if you choose to save it.

---

## Requirements

Install the following Python packages before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Steps in the Notebook

1. **Setup & Imports**
   Import necessary libraries for data analysis and machine learning.

2. **Load Dataset**
   Load `Weather Data.csv` and display basic information.

3. **Data Inspection & Cleaning**

   * Remove missing values.
   * Drop unnecessary columns (`Date/Time`).
   * Combine rare weather categories into “Other”.

4. **Feature Preparation**

   * Encode categorical features using `LabelEncoder`.
   * Encode target variable (`Weather`).

5. **Train-Test Split**
   Split the data into 75% training and 25% testing sets.

6. **Model Training**
   Train a `DecisionTreeClassifier` using scikit-learn.

7. **Model Evaluation**

   * Accuracy Score
   * Classification Report
   * Confusion Matrix
   * Decision Tree Visualization

8. **Feature Importance**
   Display and plot the most important features.

9. **Optional Extensions**

   * Hyperparameter tuning (e.g., GridSearchCV)
   * Cross-validation
   * Model saving using `joblib`

---

## How to Run

1. Place `Weather Data.csv` in the same folder as the notebook.
2. Open and run each cell in `Weather_Classification_DecisionTree.ipynb` sequentially.
3. Review the model performance metrics and visualizations.
4. (Optional) Save the trained model for later use.

---

## Expected Output

* Cleaned dataset summary
* Model accuracy and classification report
* Confusion matrix and Decision Tree visualization
* Bar plot of feature importances

---

## Submission

* Ensure the notebook runs without errors.
* Save and upload your `.ipynb` file to the **Student Portal**.
* Include this README in your submission package.

---

**Author:** [Muhammad Ghufran]
**Date:** [27-10-2025]
**Institution:** [Saylani Zaitoon Ashraf IT Park]
