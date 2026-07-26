# Lab 08: Bias-Variance Tradeoff

## Overview

This lab explored one of the most important concepts in machine learning: the **bias-variance tradeoff**. Using a synthetic dataset, I investigated how model complexity affects performance and learned how underfitting and overfitting influence a model's ability to generalize to new data.

The lab also introduced learning curves as a tool for diagnosing model performance and determining whether a model suffers from high bias or high variance.

---

## Objectives

By completing this lab, I learned how to:

* Understand the concepts of bias and variance.
* Differentiate between underfitting and overfitting.
* Compare models with different levels of complexity.
* Visualize how model complexity affects predictions.
* Generate and interpret learning curves.
* Diagnose model performance using training and validation scores.

---

## Technologies Used

* Python
* Google Colab
* NumPy
* Matplotlib
* Scikit-learn

---

## What I Did

During this lab I:

* Generated a synthetic dataset with a known pattern and random noise.
* Trained models with different levels of complexity.
* Compared simple and complex models to observe underfitting and overfitting.
* Visualized each model's predictions.
* Generated learning curves using Scikit-learn's `learning_curve` function.
* Compared training and validation performance as the amount of training data increased.
* Interpreted the results to identify signs of high bias and high variance.

---

## What I Learned

This lab demonstrated that increasing model complexity does not always improve performance. A model that is too simple may fail to capture meaningful patterns in the data, resulting in **underfitting** (high bias). On the other hand, a model that is too complex may memorize the training data instead of learning general patterns, resulting in **overfitting** (high variance).

I also learned that learning curves provide valuable insight into how a model performs as more training data becomes available and can help determine whether changes to the model or dataset are needed.

---

## Challenges

One challenge was interpreting learning curves and understanding what different patterns reveal about model performance. It was also important to distinguish between training accuracy and validation accuracy, since a model that performs exceptionally well on training data may still perform poorly on unseen data.

---

## Results

After completing the lab, I successfully:

* Compared models with varying levels of complexity.
* Observed examples of underfitting and overfitting.
* Generated learning curves to evaluate model behavior.
* Interpreted the relationship between bias, variance, and generalization.
* Gained a deeper understanding of how to balance model complexity for better predictive performance.

These exercises demonstrated why selecting an appropriately complex model is essential for building reliable machine learning systems.

---

## Files Included

* `L08_Bias_Variance_Tradeoff.ipynb` — Completed Google Colab notebook
* `README.md` — Documentation for this lab

---

## How to Run

1. Open the notebook in Google Colab.
2. Run all cells from beginning to end.
3. The notebook generates a synthetic dataset automatically, so no external data files are required.
4. Review the model visualizations and learning curves to observe the effects of bias and variance.

---

## Reflection

This lab helped me understand that successful machine learning is about finding the right balance between simplicity and complexity. By exploring the bias-variance tradeoff and analyzing learning curves, I gained practical experience diagnosing model behavior and learned why avoiding both underfitting and overfitting is critical for creating models that generalize well to new data.
