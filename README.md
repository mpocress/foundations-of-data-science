# Foundations of Data Science

A series of guided tutorials covering the core techniques and tools used in data science. Each notebook builds on the last, progressing from Python fundamentals to advanced machine learning models.

## Notebooks

| # | Notebook | Topics | Dataset |
|---|---------|--------|---------|
| 1 | [Python and Statistics Foundations](01_python_and_stats_foundations.ipynb) | Python essentials, NumPy, Pandas, descriptive statistics, visualization | Simulated weather data |
| 2 | [Web Scraping and Exploratory Data Analysis](02_web_scraping_and_eda.ipynb) | HTTP requests, HTML parsing with BeautifulSoup, data cleaning, EDA | Books (books.toscrape.com) |
| 3 | [Regression Fundamentals](03_regression_fundamentals.ipynb) | kNN regression, simple & multiple linear regression, residual analysis | Simulated housing prices |
| 4 | [Polynomial and Regularized Regression](04_polynomial_and_regularized_regression.ipynb) | Polynomial features, overfitting, LASSO, Ridge, cross-validation | Simulated air quality (PM2.5) |
| 5 | [Classification Models](05_classification_models.ipynb) | Logistic regression, kNN classification, confusion matrices, ROC curves | Simulated heart disease data |
| 6 | [Ensemble Methods](06_ensemble_methods.ipynb) | Decision trees, bagging, random forests, AdaBoost, gradient boosting | Simulated music genre data |

## Learning Path

The notebooks are designed to be completed in order:

```
01 Python & Stats Foundations
 └── 02 Web Scraping & EDA
      └── 03 Regression Fundamentals
           └── 04 Polynomial & Regularized Regression
                └── 05 Classification Models
                     └── 06 Ensemble Methods
```

## Requirements

All notebooks use standard data science libraries. Install them with:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn scipy requests beautifulsoup4
```

## Key Concepts Covered

| Category | Concepts |
|----------|----------|
| **Programming** | Python data structures, functions, classes, file I/O, list comprehensions |
| **Data Wrangling** | Web scraping, parsing, cleaning, merging, grouping, aggregation |
| **Statistics** | Descriptive stats, distributions, correlation, hypothesis testing |
| **Regression** | kNN regression, linear regression, polynomial features, LASSO, Ridge |
| **Classification** | Logistic regression, kNN classification, decision trees, ensemble methods |
| **Evaluation** | MSE, R², confusion matrices, precision/recall/F1, ROC/AUC, cross-validation |
| **Visualization** | Histograms, scatter plots, box plots, line charts, heatmaps, residual plots |
