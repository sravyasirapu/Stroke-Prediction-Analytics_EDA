# Stroke Prediction Analytics

## Project Overview

This project analyzes a healthcare stroke dataset to identify patterns and relationships associated with stroke occurrence.

The project is organized into three sprints:

- **Sprint 1 – Data Preparation:** Data understanding, cleaning, validation and preparation.
- **Sprint 2 – Exploratory Data Analysis:** Descriptive analysis, group-based analysis, correlations, visualizations and interpretation.
- **Sprint 3 – Statistical Analysis & Feature Engineering:** Statistical testing, confidence intervals, feature engineering and evaluation.

## Dataset

The project uses a cleaned stroke dataset containing patient information such as age, gender, hypertension, heart disease, marital status, work type, residence type, average glucose level, BMI, smoking status and stroke.

The cleaned dataset is stored in the `data` folder.

## Project Structure

```text
Stroke-Prediction-Analytics/
│
├── Sprint_1/
│   └── Sprint1.ipynb
│
├── Sprint_2/
│   └── Sprint2.ipynb
│
├── Sprint_3/
│   └── Stroke_Analysis_Sprint3.ipynb
│
├── data/
│   └── stroke_cleaned.csv
│
├── README.md
└── requirements.txt
```

## Sprint 1 – Data Preparation

Sprint 1 focuses on understanding, cleaning and validating the dataset.

Main activities:
- Dataset structure and data types
- Missing-value checks
- Duplicate checks
- BMI missing-value handling
- Categorical and numerical validation
- Preparation of the cleaned dataset

The cleaned dataset from Sprint 1 is used in later sprints.

## Sprint 2 – Exploratory Data Analysis

Sprint 2 explores the cleaned dataset and identifies important patterns.

Main activities:
- Descriptive statistics
- Group-based analysis
- Categorical comparisons
- Stroke-rate comparisons
- Correlation analysis
- Outlier analysis
- Data visualizations
- Interpretation of findings

Important findings include the stronger numerical association of age with stroke compared with BMI, differences in average glucose levels between groups, and differences in stroke rates across selected categorical variables.

## Sprint 3 – Statistical Analysis & Feature Engineering

Sprint 3 builds on the findings from Sprint 1 and Sprint 2.

### Statistical Analysis
- Central tendency
- Dispersion
- Distribution analysis
- Correlation
- Covariance

### Hypothesis Testing
- Welch independent-samples t-tests
- Chi-square tests
- One-way ANOVA
- Null and alternative hypotheses
- Test statistics
- p-values
- Statistical decisions
- Interpretations

### Confidence Intervals

95% confidence intervals are calculated for important numerical variables.

### Feature Engineering

The notebook creates analytical features including:
- Age Group
- BMI Category
- Combined Disease Indicator
- Risk Category
- Health Score
- Lifestyle Index

These features make patient segmentation and interpretation easier.

**Note:** The risk-related features are project-specific analytical features and are not clinical risk scores or medical diagnoses.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook

## Project Workflow

```text
Sprint 1
Data Cleaning & Preparation
        ↓
Sprint 2
Exploratory Data Analysis
        ↓
Sprint 3
Statistical Validation
        ↓
Feature Engineering
        ↓
Feature Evaluation
        ↓
Final Business Recommendations
```

## How to Run

1. Install the libraries listed in `requirements.txt`.
2. Open the required notebook in Jupyter Notebook, JupyterLab or Google Colab.
3. Keep `stroke_cleaned.csv` in the `data` folder.
4. Run the notebook cells from top to bottom.

## Disclaimer

This is an educational data-analysis project. The analytical features and findings should not be interpreted as medical diagnoses or validated clinical prediction models.
