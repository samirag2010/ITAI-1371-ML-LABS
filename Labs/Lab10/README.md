# Lab 10: Unsupervised Learning

## Overview

This lab introduced **unsupervised learning**, a branch of machine learning that identifies hidden patterns in data without using labeled outcomes. Using the Iris dataset, I explored clustering techniques with the K-Means algorithm and applied Principal Component Analysis (PCA) to reduce the dimensionality of the dataset for visualization.

The lab demonstrated how unsupervised learning can reveal natural groupings within data and simplify complex datasets while preserving their most important information.

---

## Objectives

By completing this lab, I learned how to:

* Understand the differences between supervised and unsupervised learning.
* Apply the K-Means clustering algorithm.
* Determine an appropriate number of clusters using the Elbow Method.
* Visualize clusters in a dataset.
* Perform dimensionality reduction using Principal Component Analysis (PCA).
* Interpret clustering results and explained variance.

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Scikit-learn

---

## What I Did

During this lab I:

* Loaded the Iris dataset from Scikit-learn.
* Applied the K-Means clustering algorithm to group similar observations.
* Used the Elbow Method to identify an appropriate number of clusters.
* Visualized the resulting clusters.
* Applied Principal Component Analysis (PCA) to reduce the dataset from four features to two principal components.
* Created scatter plots to visualize the transformed data.
* Examined how much variance was retained after dimensionality reduction.
* Compared unsupervised learning techniques with previously studied supervised learning methods.

---

## What I Learned

This lab demonstrated that unsupervised learning differs from supervised learning because it does not rely on labeled target values. Instead, algorithms search for natural patterns, similarities, and relationships within the data.

I also learned that:

* **K-Means** groups similar observations into clusters based on feature similarity.
* **The Elbow Method** helps estimate an appropriate number of clusters.
* **Principal Component Analysis (PCA)** reduces the number of features while preserving most of the important information, making high-dimensional data easier to visualize and analyze.

These techniques are valuable when working with datasets where labels are unavailable or when simplifying complex data for further analysis.

---

## Challenges

One challenge was understanding how clustering differs from classification. Unlike supervised learning, there are no correct labels to compare predictions against, making interpretation more exploratory.

Another challenge was learning how PCA transforms the original features into new principal components while retaining as much variance as possible.

---

## Results

After completing the lab, I successfully:

* Applied K-Means clustering to the Iris dataset.
* Used the Elbow Method to evaluate cluster selection.
* Reduced the dataset to two principal components using PCA.
* Visualized clusters in two-dimensional space.
* Interpreted the amount of variance explained by the principal components.

These activities demonstrated how unsupervised learning can uncover meaningful structure within data without requiring labeled outcomes.

---

## Files Included

* `L10_Unsupervised_Learning.ipynb` — Completed Google Colab notebook
* `README.md` — Documentation for this lab

---

## How to Run

1. Open the notebook in Google Colab.
2. Run all cells from beginning to end.
3. The Iris dataset is loaded directly from Scikit-learn, so no external files are required.
4. Review the clustering visualizations, Elbow Method results, and PCA plots to understand the patterns identified by the algorithms.

---

## Reflection

This lab expanded my understanding of machine learning by introducing techniques that discover patterns without relying on labeled data. Learning how K-Means clustering and Principal Component Analysis work showed me how unsupervised learning can organize complex datasets and make them easier to interpret. These methods provide valuable tools for exploratory analysis and serve as an important complement to supervised learning techniques.
