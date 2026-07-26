# Lab 13: Building Machine Learning Pipelines

## Overview

This lab introduced **machine learning pipelines**, a powerful technique for organizing preprocessing and model training into a single, repeatable workflow. Rather than manually performing each preprocessing step, I used Scikit-learn pipelines to automate data preparation and model training, making machine learning projects cleaner, more efficient, and less prone to errors.

The lab highlighted how pipelines improve reproducibility and simplify the deployment of machine learning solutions.

---

## Objectives

By completing this lab, I learned how to:

* Understand the purpose of machine learning pipelines.
* Compare manual preprocessing with automated pipeline workflows.
* Build pipelines using Scikit-learn.
* Combine preprocessing and model training into a single workflow.
* Improve code organization and reproducibility.
* Understand why pipelines are considered a best practice in machine learning.

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

* Reviewed the traditional manual approach to data preprocessing.
* Built a machine learning pipeline using Scikit-learn's `Pipeline` tools.
* Combined preprocessing and model training into a single workflow.
* Compared manual and pipeline-based approaches.
* Executed the pipeline to train and evaluate a machine learning model.
* Reflected on the advantages of using pipelines for larger machine learning projects.

---

## What I Learned

This lab demonstrated that machine learning pipelines simplify the development process by keeping preprocessing and model training together. Instead of manually repeating each preparation step, pipelines ensure that the same transformations are consistently applied whenever the model is trained or used for prediction.

I also learned that pipelines:

* Reduce repetitive code.
* Minimize the risk of data leakage.
* Improve code readability and organization.
* Make machine learning workflows easier to reproduce and maintain.
* Simplify deployment by packaging preprocessing and modeling into a single process.

These benefits make pipelines a standard practice in professional machine learning development.

---

## Challenges

The primary challenge was understanding how multiple preprocessing steps and a machine learning model can be combined into one object. Once I saw the workflow in practice, it became clear how pipelines reduce complexity while improving consistency.

Another important lesson was recognizing that pipelines become increasingly valuable as projects grow larger and involve more preprocessing steps.

---

## Results

After completing the lab, I successfully:

* Built a Scikit-learn machine learning pipeline.
* Combined preprocessing and model training into a single workflow.
* Compared manual preprocessing with an automated pipeline.
* Improved the organization and reproducibility of the machine learning process.
* Gained experience using an industry-standard workflow for machine learning development.

These exercises demonstrated how pipelines create cleaner, more reliable, and more maintainable machine learning projects.

---

## Files Included

* `L13_Building_ML_Pipelines.ipynb` — Completed Google Colab notebook
* `README.md` — Documentation for this lab

---

## How to Run

1. Open the notebook in Google Colab.
2. Run all cells from beginning to end.
3. Review both the manual preprocessing workflow and the Scikit-learn pipeline implementation.
4. Compare the two approaches to understand how pipelines simplify machine learning development.

---

## Reflection

This lab brought together many of the concepts learned throughout the course. By combining preprocessing and model training into a single pipeline, I gained a better understanding of how professional machine learning workflows are built. Pipelines not only make code cleaner and easier to maintain, but also help ensure that models can be trained, evaluated, and deployed consistently. This lab provided a fitting conclusion to the course by demonstrating how the individual techniques learned throughout the semester work together in a complete machine learning workflow.
