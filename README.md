# Palmer Penguins Statistical Analysis

Statistical analysis of the **Palmer Penguins** dataset focused on descriptive statistics, confidence intervals, hypothesis testing and ANOVA.

The project explores differences in penguin body measurements across species, sex and islands using statistical methods and data visualisation.

## Dataset

The dataset comes from Kaggle and contains information about penguins from the Palmer Archipelago in Antarctica.

Main variables include:

- species
- island
- sex
- culmen length
- culmen depth
- flipper length
- body mass

Dataset source: Palmer Archipelago Antarctica Penguin Data on Kaggle.

## Project Scope

The analysis includes:

- data loading and initial inspection
- missing data handling
- descriptive statistics
- distribution analysis
- histograms and boxplots
- empirical cumulative distribution function (ECDF)
- confidence intervals
- parametric hypothesis testing
- non-parametric hypothesis testing
- two-way ANOVA

## Statistical Methods

### Descriptive Statistics

The project analyses numerical variables using:

- mean
- median
- standard deviation
- variance
- quartiles and IQR
- skewness
- kurtosis

### Confidence Intervals

95% confidence intervals are calculated for:

- mean body mass using Student's t-distribution
- body mass variance using the chi-square distribution

### Parametric Tests

Body mass differences between male and female penguins are analysed separately for each species.

Before selecting the appropriate test, assumptions are checked using:

- Shapiro-Wilk normality test
- Levene's test for equality of variances
- Student's t-test / Welch's t-test

### Non-Parametric Analysis

A chi-square test of independence is used to investigate the relationship between:

**penguin species and island**

### ANOVA

A two-way ANOVA is performed to analyse the influence of:

- species
- sex
- interaction between species and sex

on penguin body mass.

## Data Visualisation

The project includes:

- histograms of numerical variables
- boxplots comparing body mass between species
- boxplots comparing body mass between sexes
- body mass comparison by species and sex
- ECDF of penguin body mass

## Technologies

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- Seaborn
- Statsmodels
- Jupyter Notebook

## Repository Structure

```text
penguins-statistical-analysis/
├── penguins_statistical_analysis.ipynb
├── penguins_size.csv
└── README.md
