# 📉 Bayesian Logistic Regression for Churn Prediction

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Ensemble_Learning-F7931E.svg)
![Pandas](https://img.shields.io/badge/Pandas-Data_Wrangling-150458.svg)
![PyMC](https://img.shields.io/badge/PyMC-Bayesian_Inference-2E4A62.svg)
![ArviZ](https://img.shields.io/badge/ArviZ-MCMC_Diagnostics-00A6D6.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)

An advanced statistical modeling project that predicts customer churn using **Bayesian Logistic Regression**. Instead of outputting single-point estimates like traditional machine learning models, this approach quantifies uncertainty, providing actionable probabilistic insights for business retention strategies.

## 📖 Project Overview
In a business context, predicting *if* a customer will churn is only half the battle; knowing the *certainty* of that prediction dictates how much budget should be spent to retain them. 

While standard Logistic Regression (via Scikit-Learn) provides a fixed probability, this project leverages **Bayesian Inference** to compute a full posterior distribution for the churn probability of each customer. This allows for rigorous risk management, credible intervals, and a deeper understanding of how different features impact customer retention.

## 🧠 Modeling Approach & Applied Statistics
* **Algorithm:** Bayesian Logistic Regression
* **Inference Method:** Markov Chain Monte Carlo (MCMC) Sampling
* **Key Statistical Advantages Highlighted in this Project:**
  * **Uncertainty Quantification:** Generates a distribution of possible churn probabilities rather than a single black-box number.
  * **Informative Priors:** The ability to encode prior business knowledge about customer behavior directly into the model's math before seeing the data.
  * **MCMC Diagnostics:** Rigorous evaluation of chain convergence and posterior distributions using trace plots and Highest Density Intervals (HDI).

## 🚀 How to Run

### 1. Install Dependencies
This project relies heavily on the modern Python Bayesian ecosystem.
```bash
pip install pandas numpy pymc arviz scikit-learn matplotlib
