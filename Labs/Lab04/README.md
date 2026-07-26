# Lab 04: Exploratory Data Analysis

## Overview

This lab focused on Exploratory Data Analysis (EDA), one of the most important steps in the machine learning process. Using the Titanic dataset, I learned how to summarize data, identify patterns, detect relationships between variables, and communicate findings through visualizations.

Rather than building predictive models, the goal of this lab was to understand the data before applying machine learning algorithms.

---

## Objectives

By completing this lab, I learned how to:

* Understand the purpose of Exploratory Data Analysis (EDA).
* Load and inspect a real-world dataset.
* Generate descriptive statistics using Pandas.
* Identify missing values and data types.
* Create visualizations to reveal patterns in the data.
* Interpret charts to answer questions about the dataset.
* Draw conclusions from both numerical summaries and visual evidence.

---

## Technologies Used

* Python
* Google Colab
* Pandas
* Matplotlib
* Seaborn

---

## What I Did

During this lab I:

* Loaded the Titanic dataset into a Pandas DataFrame.
* Examined the dataset structure, data types, and summary statistics.
* Explored categorical and numerical variables.
* Created count plots to examine passenger survival.
* Compared survival rates by passenger class.
* Investigated survival differences based on gender.
* Visualized the age distribution of passengers using histograms.
* Conducted additional experiments exploring embarkation location and ticket fare.
* Interpreted each visualization to better understand the factors influencing survival.

---

## What I Learned

This lab reinforced that successful machine learning begins with understanding the data. Exploratory Data Analysis helps uncover trends, relationships, and potential issues before any model is trained.

I also learned that visualizations often communicate insights more effectively than tables of numbers. Charts quickly revealed how variables such as passenger class, gender, fare, and embarkation location were associated with survival outcomes.

---

## Challenges

One challenge was learning which visualization was most appropriate for different types of variables. Choosing between count plots, histograms, and boxplots depends on whether the data is categorical or numerical and on the question being investigated.

Interpreting the results also required thinking beyond the graphs to consider why certain patterns appeared in the dataset.

---

## Results

Through Exploratory Data Analysis, I observed several important trends:

* Passenger survival was not evenly distributed.
* Female passengers had noticeably higher survival rates than male passengers.
* First-class passengers generally survived at higher rates than passengers in lower classes.
* Fare appeared to be associated with survival, with survivors often paying higher ticket prices.
* Embarkation location also showed differences in survival rates.

These observations demonstrate how EDA provides valuable insight before developing predictive machine learning models.

---

## Files Included

* `L04_Exploratory_Data_Analysis.ipynb` — Completed Google Colab notebook
* `README.md` — Documentation for this lab

---

## How to Run

1. Open the notebook in Google Colab.
2. Run the notebook from the first cell to the last.
3. The Titanic dataset is loaded directly from an online source, so no manual download is required.
4. Review the descriptive statistics and visualizations generated throughout the notebook.

---

## Reflection

This lab helped me appreciate the importance of asking questions about the data before attempting to build a machine learning model. By exploring the Titanic dataset through statistics and visualizations, I developed a stronger understanding of how EDA supports better decision-making and improves the quality of machine learning projects.
