# Raisa Jose - EDA Course Project

This project performs a comprehensive Exploratory Data Analysis on the **Auto MPG Dataset**. The script covers the first phase of the data science workflow, from data cleaning and transformation to advanced multivariate visualization.

## Project Overview
The goal of this analysis is to understand the factors affecting vehicle fuel efficiency (MPG), such as weight, horsepower, and origin, using the R programming language.

## Analysis Workflow

1.  **Data Loading**: Importing the dataset and ensuring correct data types.
2.  **Data Cleaning**: 
    *   Identifying and handling missing values.
    *   Converting `horsepower` to numeric (handling non-numeric placeholders like "?").
    *   Imputing missing values using the median.
3.  **Data Transformation**: 
    *   Converting categorical features (`origin`, `cylinders`) into factors for better plotting.
    *   Feature engineering: Created a `weight_per_hp` metric.
4.  **Statistical Analysis**: Generating descriptive statistics to understand the data distribution.

## Visualizations

The script generates **12 high-quality visualizations**:

### 1. Univariate Analysis
*   **MPG Distribution**: Histogram showing the frequency of fuel efficiency.
*   **Origin Count**: Bar chart showing where the vehicles were manufactured.
*   **Acceleration Spread**: Boxplot showing the distribution and outliers of 0-60mph times.
*   **Weight Density**: Density plot visualizing the distribution of vehicle mass.

### 2. Bivariate Analysis
*   **MPG vs. Weight**: Scatter plot with a linear regression line.
*   **Efficiency by Region**: Boxplot comparing MPG across USA, Europe, and Japan.
*   **Horsepower vs. Acceleration**: Scatter plot with a smoothing line.
*   **Cylinder Influence**: Violin plot showing MPG density for different cylinder counts.

### 3. Multivariate Analysis
*   **Bubble Chart**: Weight vs. MPG, colored by Origin and sized by Horsepower.
*   **Correlation Heatmap**: A matrix visualizing the correlation coefficients between all numeric features.
*   **Faceted Scatter Plot**: MPG vs. Displacement, broken down by Region (Faceted).
*   **Faceted Boxplot**: MPG vs. Cylinders, broken down by Region.

