# Lab 06: Regression and Classification

## Overview

This lab introduced two of the most common supervised machine learning approaches: **regression** and **classification**. Using the Titanic dataset, I built both a Linear Regression model and a Logistic Regression model to understand the differences between predicting continuous values and predicting categories.

The lab emphasized selecting the appropriate algorithm based on the type of problem being solved and evaluating each model using suitable performance metrics.

---

## Objectives

By completing this lab, I learned how to:

* Differentiate between regression and classification problems.
* Train and evaluate a Linear Regression model.
* Train and evaluate a Logistic Regression model.
* Split data into training and testing sets.
* Make predictions using supervised learning models.
* Evaluate regression and classification models using appropriate metrics.
* Interpret model results in the context of the problem being solved.

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn

---

## What I Did

During this lab I:

* Loaded and prepared the Titanic dataset.
* Removed records with missing values where appropriate.
* Selected features and target variables for two different prediction tasks.
* Built a **Linear Regression** model to predict a continuous value.
* Evaluated the regression model using Mean Squared Error (MSE).
* Built a **Logistic Regression** model to classify passenger survival.
* Evaluated the classification model using prediction accuracy.
* Compared the strengths and purposes of regression and classification algorithms.

---

## What I Learned

This lab demonstrated that choosing the correct machine learning algorithm depends on the type of prediction being made.

* **Linear Regression** is used when the target is a continuous numerical value.
* **Logistic Regression** is used when the target belongs to one of two or more categories.

I also learned that different machine learning models require different evaluation methods. Regression models focus on prediction error, while classification models are evaluated using metrics such as accuracy.

---

## Challenges

One challenge was understanding why Logistic Regression is considered a classification algorithm despite its name. Learning how probabilities are converted into class predictions helped clarify this concept.

Another challenge was recognizing that the same dataset can support different prediction tasks depending on the selected target variable.

---

## Results

After completing the lab, I successfully:

* Trained a Linear Regression model.
* Calculated Mean Squared Error to evaluate regression performance.
* Trained a Logistic Regression classifier.
* Predicted passenger survival using classification techniques.
* Measured classification accuracy on unseen test data.

These exercises demonstrated how different supervised learning algorithms are applied to different types of prediction problems.

---

## Files Included

* `L06_Regression_and_Classification.ipynb` — Completed Google Colab notebook
* `README.md` — Documentation for this lab

---

## How to Run

1. Open the notebook in Google Colab.
2. Run all cells from the beginning to the end.
3. The Titanic dataset is loaded directly from an online source.
4. Review the regression and classification outputs along with the evaluation metrics.

---

## Reflection

This lab strengthened my understanding of supervised learning by showing how different algorithms solve different types of prediction problems. I gained practical experience training both regression and classification models and learned the importance of selecting evaluation metrics that match the model's purpose. These concepts provide an important foundation for more advanced machine learning techniques introduced later in the course.
