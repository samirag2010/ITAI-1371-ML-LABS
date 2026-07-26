# Lab 05: Data Preparation

## Overview

This lab focused on data preparation, one of the most important stages of the machine learning workflow. Using the Titanic dataset, I learned how to clean data by handling missing values, converting categorical variables into numerical features, and scaling numerical data to prepare it for machine learning models.

The lab demonstrated that high-quality data preparation is essential for building reliable and accurate machine learning models.

---

## Objectives

By completing this lab, I learned how to:

* Identify missing values in a dataset.
* Apply data imputation techniques.
* Encode categorical variables into numerical values.
* Scale numerical features for machine learning.
* Understand why preprocessing improves model performance.
* Prepare a dataset for use in future machine learning models.

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

* Loaded the Titanic dataset into a Pandas DataFrame.
* Examined the dataset for missing values.
* Filled missing values in the **Age** column using the median.
* Converted categorical variables into numerical features using one-hot encoding.
* Scaled the **Age** and **Fare** features using `StandardScaler`.
* Compared the dataset before and after preprocessing to understand how each transformation prepared the data for machine learning.

---

## What I Learned

This lab demonstrated that real-world data is rarely ready for machine learning. Before training a model, datasets often require cleaning and transformation to ensure that algorithms can process the information correctly.

I also learned why different preprocessing techniques are necessary:

* **Median imputation** provides a robust way to handle missing numerical values.
* **One-hot encoding** converts text categories into numerical features without introducing unintended relationships.
* **Feature scaling** places numerical variables on a comparable scale, improving the performance of many machine learning algorithms.

---

## Challenges

One challenge was understanding why different preprocessing techniques are used for different types of data. Numerical variables, categorical variables, and missing values each require their own approach.

Another important lesson was recognizing that preprocessing decisions can significantly influence the accuracy and reliability of a machine learning model.

---

## Results

After completing the preprocessing steps:

* Missing values were successfully handled.
* Categorical variables were converted into numerical features suitable for machine learning.
* Numerical features were standardized using feature scaling.
* The dataset became fully prepared for use in future classification models.

These preprocessing steps created a cleaner, more consistent dataset for model training and evaluation.

---

## Files Included

* `L05_Data_Preparation.ipynb` — Completed Google Colab notebook
* `README.md` — Documentation for this lab

---

## How to Run

1. Open the notebook in Google Colab.
2. Run all cells from top to bottom.
3. The Titanic dataset is loaded directly from an online source.
4. Review the preprocessing steps and observe how the dataset changes after each transformation.

---

## Reflection

This lab helped me understand that data preparation is one of the most important stages of the machine learning process. Even the most advanced algorithms cannot perform well if the underlying data contains missing values, inconsistent formats, or improperly scaled features. Preparing the data correctly provides a stronger foundation for building accurate and dependable machine learning models.
