# Lab 11: Hyperparameter Tuning and AutoML

## Overview

Lab 11 consisted of two complementary notebooks that explored how machine learning models can be improved through **hyperparameter tuning** and **Automated Machine Learning (AutoML)**. Rather than creating entirely new algorithms, these activities focused on optimizing existing models to improve predictive performance.

Throughout the lab, I compared manual tuning techniques with automated search methods, including Grid Search, Random Search, and AutoML. These exercises demonstrated how different optimization strategies can improve model accuracy while balancing computational efficiency.

---

## Objectives

By completing this lab, I learned how to:

* Understand the difference between model parameters and hyperparameters.
* Tune machine learning models using manual experimentation.
* Apply Grid Search to systematically evaluate hyperparameter combinations.
* Use Random Search as a more efficient alternative for large search spaces.
* Understand the purpose and advantages of AutoML.
* Compare multiple hyperparameter optimization strategies.
* Evaluate how hyperparameter tuning affects model performance and generalization.

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* AutoGluon

---

## Notebook A: Hyperparameter Tuning

In the first notebook, I explored the fundamentals of hyperparameter optimization.

Activities included:

* Understanding the role of hyperparameters.
* Performing Grid Search using `GridSearchCV`.
* Performing Random Search using `RandomizedSearchCV`.
* Comparing different Random Forest configurations.
* Learning how automated searches identify optimal model settings.
* Exploring AutoML concepts using AutoGluon.

This notebook introduced the core techniques used to improve machine learning models without changing the underlying algorithm.

---

## Notebook B: Advanced Hyperparameter Tuning and AutoML

The second notebook expanded these concepts using a more detailed workflow.

Activities included:

* Working with the Wine Quality dataset.
* Preparing and scaling data.
* Exploring hyperparameters for Logistic Regression and Random Forest models.
* Performing manual hyperparameter tuning.
* Comparing manual tuning with Grid Search and Random Search.
* Applying cross-validation during model selection.
* Training an AutoML model using AutoGluon.
* Comparing the performance of all optimization approaches.

This notebook demonstrated how automated tools can simplify model optimization while maintaining strong predictive performance.

---

## What I Learned

This lab showed that building a machine learning model is only the beginning. Model performance can often be improved significantly by selecting better hyperparameter values.

I learned that:

* **Grid Search** evaluates every specified parameter combination to find the optimal configuration.
* **Random Search** explores a random subset of combinations, making it faster for large search spaces.
* **Cross-validation** provides more reliable performance estimates during tuning.
* **AutoML** automates model selection, hyperparameter tuning, and evaluation, allowing developers to build strong models more efficiently.

These techniques help create models that generalize better to unseen data.

---

## Challenges

The largest challenge was understanding the difference between parameters learned during training and hyperparameters selected before training begins.

It was also interesting to compare the tradeoffs between exhaustive search methods, faster randomized searches, and fully automated machine learning pipelines.

---

## Results

By completing both notebooks, I successfully:

* Tuned Random Forest hyperparameters.
* Compared manual tuning, Grid Search, and Random Search.
* Applied cross-validation during model optimization.
* Explored AutoML using AutoGluon.
* Compared multiple optimization techniques and their performance.
* Developed a stronger understanding of improving model accuracy through systematic tuning.

These exercises demonstrated that thoughtful hyperparameter optimization is an essential step in developing high-performing machine learning models.

---

## Files Included

* `L11A_Hyperparameter_Tuning.ipynb` — Introduction to hyperparameter tuning with Grid Search and Random Search.
* `L11B_Hyperparameter_Tuning_AutoML.ipynb` — Advanced tuning techniques, model comparison, and AutoML using AutoGluon.
* `README.md` — Documentation for Lab 11.

---

## How to Run

1. Open each notebook in Google Colab.
2. Run all cells from beginning to end.
3. Install AutoGluon if prompted.
4. Review the tuning results, model comparisons, and AutoML outputs.

---

## Reflection

Lab 11 demonstrated that improving a machine learning model often depends more on selecting the right hyperparameters than changing the algorithm itself. Learning how to optimize models through Grid Search, Random Search, and AutoML gave me practical experience with techniques commonly used in professional machine learning workflows. I also gained a deeper appreciation for balancing model performance with computational efficiency when selecting optimization methods.
