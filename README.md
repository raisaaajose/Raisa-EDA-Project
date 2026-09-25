# Raisa Jose - EDA Course Project

This project performs Exploratory Data Analysis on the **Auto MPG Dataset** using **R and Python**. The analysis covers data cleaning, transformation, 1D, 2D, and 3D statistical analysis, visualization, and clustering.

## Project Overview

The objective is to analyze the factors influencing vehicle fuel efficiency (`mpg`) using variables such as weight, horsepower, displacement, cylinders, model year, and origin.

## Analysis Workflow

1. **Data Cleaning**
   - Checked missing values and corrected data types.
   - Converted `horsepower` to numeric and handled missing values.
   - Converted categorical variables such as `origin` and `cylinders`.
   - Created the derived feature `weight_per_hp`.

2. **1D Analysis**
   - Descriptive statistics including mean, median, variance, standard deviation, IQR, skewness, and kurtosis.
   - Frequency distributions, quantiles, coefficient of variation, and outlier analysis.
   - Distribution and boxplot-based visualizations.

3. **2D Analysis**
   - Covariance and correlation analysis.
   - Pearson and Spearman correlation tests.
   - Grouped statistics and contingency tables.
   - Chi-square test, one-way ANOVA, Tukey HSD, and simple linear regression.
   - Scatterplot matrix and regression diagnostics.

4. **3D / Multivariate Analysis**
   - Three-variable grouped summaries.
   - 3D scatter visualization.
   - Multiple linear regression.
   - Two-way ANOVA.
   - Analysis of MPG trends across model years and origins.

5. **Clustering**
   - Standardized numerical features before clustering.
   - Applied **K-Means clustering** with Elbow and Silhouette methods for cluster selection.
   - Applied **Hierarchical clustering** using Ward, Single, Complete, and Average linkage.
   - Generated dendrograms, PCA cluster visualizations, silhouette plots, and cluster profiles.
   - Compared K-Means and Hierarchical clustering results.
