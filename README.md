# Univariate Linear Regression

A from-scratch implementation of univariate linear regression in Python, trained with gradient descent to model the relationship between work experience and salary.

## Table of Contents

- [Purpose of the Project](#purpose-of-the-project)
- [The Dataset](#the-dataset)
- [Technologies & Dependencies](#technologies--dependencies)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Implementations](#implementations)
- [What I Learned](#what-i-learned)

## Purpose of the Project

This project implements a **Univariate Linear Regression** model using Python and gradient descent. The objective is to explore the relationship between **months worked** and **yearly salary earned** using a dataset of 1,000 observations.

The model was implemented from scratch to build a deeper understanding of how linear regression works, particularly how the weight and bias are adjusted through gradient descent to minimize prediction error.

## The Dataset

The dataset was downloaded from Kaggle, with credit to **Saquib Hussain** ([@saquib7hussain](https://www.kaggle.com/saquib7hussain)).

**Source:** [Experience Salary Dataset](https://www.kaggle.com/datasets/saquib7hussain/experience-salary-dataset)

It contains observations relating work experience to corresponding salary values.

## Technologies & Dependencies

| Tool | Purpose |
| --- | --- |
| Python | Core language |
| NumPy | Numerical computation |
| Matplotlib | Data visualization |
| KaggleHub | Dataset download |
| Jupyter Notebook | Interactive development environment |

## Project Structure

```text
Univariate-Linear-Regression/
├── data/
│   └── Experience-Salary.csv
├── linearRegressionModel.ipynb
├── requirements.txt
└── README.md
```

## Installation

**1. Clone this repository**

```bash
git clone https://github.com/eCarCodes/Univariate-Linear-Regression.git
cd Univariate-Linear-Regression
```

**2. Install the required dependencies**

```bash
python -m pip install -r requirements.txt
```

> **Note:** On macOS/Linux, you may need to use `python3` instead of `python`.

**3. Launch Jupyter Notebook**

```bash
jupyter notebook
```

Then open `linearRegressionModel.ipynb` in your browser.

> **Using VS Code instead?** Open `linearRegressionModel.ipynb`, click **Select Kernel** in the top-right, and choose the Python environment you installed the requirements into.


## Implementations

This project explores the following concepts:

- **Prediction Function**: computes $\hat{y} = wx + b$
- **Cost Function**: measures prediction error with mean squared error
- **Gradient Descent**: iteratively updates $w$ and $b$ to minimize the cost
- **Data Visualization**: plots the data and the fitted regression line

## What I Learned

This project served as an introduction to implementing machine learning algorithms from scratch. It helped me better understand linear equations, cost functions, optimization, and the relationship between model parameters and prediction accuracy.
