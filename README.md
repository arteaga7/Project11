# Project11
This repository presents a sales funnel analysis of a company. The results of the A/A and A/B tests are analyzed using the proportions test and the Mann-Whitney U test. The dataset contains the user activity (date of logging, visits in the main web page, products added to the cart, payments, etc.). Visualizations and hypotheses tests are performed.

**Objective:** To clean data and create data (from the cleaned one) to determine whether there is a statistically significant difference between the samples and their proportions, considering outliers and non-normal distributions to make decisive decisions.

## Overview
First, the exploratory data analysis (EDA) is performed to show the data in the non-cleaned datasets. Second, the data preprocessing is made, which consist of filling null values, dropping duplicates, verifying if data format is correct and processing the outliers. Third, to create data from the previously cleaned one. Fourth, the formal Mann-Whitney U and the proportion tests are performed to determine if the following questions:

• There is a statistically significant difference between the samples and their proportions in the A/A test (to verify if A/A test was performed correctly).

• There is a statistically significant difference between the samples and their proportions in the A/B test.

Finally, some decisive conclusions are given.

🛠️**Libraries used**: Pandas, Matplotlib, Seaborn, NumPy, SciPy.

The Jupyter Notebook is in scripts/project11.ipynb.

## 🚀 Installation
1. Clone this repository:
```
git clone https://github.com/arteaga7/Project11.git
```
2. Set virtual environment and install dependencies:
```
python3 -m venv env
source env/bin/activate
pip3 install -r requirements.txt
```
3. Run Jupyter Notebook in scripts/project11.ipynb.