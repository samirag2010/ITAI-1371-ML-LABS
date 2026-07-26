# Lab 07: Model Evaluation

## Overview

This lab focused on evaluating machine learning models beyond simple accuracy. Using a Logistic Regression model trained on the Titanic dataset, I explored several evaluation techniques that provide a more complete picture of model performance, including confusion matrices, precision, recall, F1-score, and cross-validation.

The lab demonstrated that selecting the right evaluation metric depends on the problem being solved and that relying solely on accuracy can sometimes produce misleading conclusions.

---

## Objectives

By completing this lab, I learned how to:

* Understand the limitations of accuracy as a performance metric.
* Generate and interpret a confusion matrix.
* Calculate precision, recall, and F1-score.
* Produce a classification report.
* Perform cross-validation to better estimate model performance.
* Compare evaluation metrics to determine the strengths and weaknesses of a model.

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## What I Did

During this lab I:

* Trained a Logistic Regression model using the Titanic dataset.
* Generated predictions using the test dataset.
* Created a confusion matrix to visualize correct and incorrect predictions.
* Produced a classification report containing precision, recall, F1-score, and accuracy.
* Performed 5-fold cross-validation using `cross_val_score`.
* Compared evaluation metrics to better understand overall model performance.
* Reflected on situations where different metrics are more appropriate than accuracy.

---

## What I Learned

This lab showed me that accuracy alone does not always tell the full story of a machine learning model. A model may achieve high accuracy while still performing poorly for an important class.

I learned the purpose of several important evaluation metrics:

* **Confusion Matrix** summarizes prediction outcomes.
* **Precision** measures how many positive predictions were actually correct.
* **Recall** measures how many actual positive cases were successfully identified.
* **F1-score** balances precision and recall into a single metric.
* **Cross-validation** provides a more reliable estimate of model performance by evaluating the model across multiple training and testing splits.

These evaluation methods help determine whether a model is reliable enough for real-world use.

---

## Challenges

A challenge in this lab was understanding the differences between precision, recall, and F1-score since they each evaluate performance from a different perspective.

Another important lesson was recognizing that the "best" evaluation metric depends on the application. For example, in medical diagnosis or fraud detection, maximizing recall may be more important than simply achieving the highest overall accuracy.

---

## Results

After completing the lab, I successfully:

* Evaluated a classification model using multiple performance metrics.
* Generated and interpreted a confusion matrix.
* Produced a detailed classification report.
* Performed 5-fold cross-validation to estimate model reliability.
* Compared the strengths and limitations of different evaluation methods.

These activities demonstrated why comprehensive model evaluation is an essential part of the machine learning workflow.

---

## Files Included

* `L07_Model_Evaluation.ipynb` — Completed Google Colab notebook
* `README.md` — Documentation for this lab

---

## How to Run

1. Open the notebook in Google Colab.
2. Run all cells from beginning to end.
3. The Titanic dataset is loaded directly from an online source.
4. Review the confusion matrix, classification report, and cross-validation results to understand the model's performance.

---

## Reflection

This lab helped me understand that evaluating a machine learning model involves much more than calculating its accuracy. By using confusion matrices, precision, recall, F1-score, and cross-validation, I gained a more complete understanding of model performance and learned how different metrics support better decision-making when selecting and improving machine learning models.
