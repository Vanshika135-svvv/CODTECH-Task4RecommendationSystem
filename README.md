# RECOMMENDATION-SYSTEM

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: VANSHIKA TIWARI

**INTERN ID**: CTIS7866

**DOMAIN**: MACHINE LEARNING

**DURATION**: 4 WEEKS

**MENTOR**: NEELA SANTOSH

---

## Overview
This repository contains the implementation of a Recommendation System built using Matrix Factorization techniques. This project was developed as Task 4 during my Machine Learning Internship at CODTECH IT Solutions.

## Objective
To design and build a collaborative filtering recommendation engine capable of predicting user preferences for unrated items based on underlying (latent) patterns in the data.

## Tech Stack
* **Language:** Python
* **Libraries:** scikit-learn, pandas, numpy, matplotlib, seaborn
* **Algorithm:** Matrix Factorization via Truncated Singular Value Decomposition (SVD)
* **Environment:** VS Code (Jupyter Notebook)

## Methodology & Deliverables
* **Data Engineering:** Generated a sparse User-Item rating matrix to simulate real-world user behavior.
* **Matrix Factorization:** Applied `TruncatedSVD` to reduce dimensionality and extract hidden user preferences, effectively solving the matrix sparsity problem.
* **Evaluation:** Monitored the Root Mean Squared Error (RMSE) to ensure the model generalized accurately without overfitting the known ratings.
* **Visualization:** Created a heatmap side-by-side comparison illustrating how the algorithm transforms a sparse matrix into a fully predicted, dense recommendation space.