# Customer Shopping Behavior Analysis
### Statistical Modelling Project

## Project Overview

This project focuses on analysing customer purchasing behaviour using the UCI Online Retail II dataset, which contains over 1 million transaction records.

The main objective is to understand customer purchasing patterns, identify factors associated with repeat purchases, and develop statistical models to predict customer behaviour.

Using Python and statistical modelling techniques, we transformed raw transaction data into meaningful customer-level insights and explored how businesses can improve customer retention.

## Dataset

**Source:** UCI Machine Learning Repository – Online Retail II Dataset

The dataset contains transactional information, including:
- Invoice numbers
- Product descriptions
- Quantities purchased
- Invoice dates
- Unit prices
- Customer IDs
- Country information

## Project Workflow

The project follows an end-to-end statistical analysis workflow.

### 1. Data Profiling
- Examined the structure and characteristics of the original dataset.
- Identified missing values, duplicates and potential data quality issues.
- Explored the main variables and their distributions.

### 2. Data Cleaning and Feature Engineering
- Cleaned and prepared the transaction data.
- Handled missing values and invalid records.
- Created order-level and customer-level datasets.
- Engineered customer behaviour features for further analysis.

### 3. Descriptive Analysis
- Explored customer purchasing patterns.
- Analysed spending, purchase frequency and customer distributions.
- Used visualisations to identify important behavioural trends.

### 4. Statistical Inference
- Applied Welch's t-test to compare customer spending between groups.
- Used ANOVA techniques to investigate differences in spending across purchase-frequency groups.
- Evaluated statistical significance and differences between customer segments.

### 5. Predictive Statistical Modelling
- Developed logistic regression models to predict repeat purchasing behaviour.
- Evaluated model performance using classification metrics and ROC-AUC.
- Investigated the relationship between customer characteristics and repeat purchasing.

### 6. Principal Component Analysis (PCA)
- Applied dimensionality reduction to explore relationships between customer features.
- Examined how customer behaviour could be represented using fewer principal components.

### 7. Bayesian Logistic Regression
- Applied a Bayesian approach to logistic regression.
- Examined posterior distributions and model uncertainty.
- Used Bayesian diagnostics to assess model convergence.

### 8. Time-Series Analysis
- Explored purchasing trends over time.
- Investigated changes in customer purchasing activity.

## Technologies and Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Scikit-learn
- Statsmodels
- PyMC
- ArviZ
- Jupyter Notebook

## Key Results

- Achieved approximately **75.7% ROC-AUC** in repeat-purchase prediction.
- Identified statistically significant differences in spending behaviour across customer groups.
- Explored the relationship between purchasing frequency and customer spending.
- Used PCA to investigate underlying patterns in customer characteristics.
- Applied Bayesian modelling to examine predictive uncertainty.

## Repository Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── notebooks/
│   ├── 01_Data_Profiling.ipynb
│   ├── 02_Data_Cleaning_Feature_Engineering.ipynb
│   ├── 03_Descriptive_Analysis.ipynb
│   ├── 04_Statistical_Inference.ipynb
│   ├── 05_Statistical_Modelling.ipynb
│   ├── 07_Principal_Component_Analysis.ipynb
│   └── 08_Bayesian_Logistic_Regression.ipynb
│
├── data/
│   ├── order_level_data.csv
│   ├── online_retail_merchandise.csv
│   ├── online_retail_clean.csv
│   └── customer_level_data.csv
│
├── requirements.txt
├── .gitignore
└── README.md
```

## Installation and Usage

1. Clone this repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

2. Navigate to the project directory:

```bash
cd Customer-Shopping-Behavior-Analysis
```

3. Install the required libraries:

```bash
pip install -r requirements.txt
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Open the notebooks and execute them in workflow order.

**Note:** Dataset file paths may need to be adjusted depending on the local environment. The original dataset can be obtained from the UCI Machine Learning Repository.

## Project Outcome

This project demonstrates the application of statistical inference, predictive modelling, dimensionality reduction and Bayesian methods to real-world retail transaction data.

The findings provide insights into customer purchasing behaviour and demonstrate how statistical modelling can support data-driven customer retention strategies.
