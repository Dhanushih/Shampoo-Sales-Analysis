# Shampoo-Sales-Analysis

## Project Overview

This project analyzes the monthly shampoo sales dataset over a three-year period. The objective is to explore sales patterns, detect anomalies, and identify trends using various data visualization and statistical techniques.

## 1. Data Overview

The dataset contains monthly shampoo sales data for a 3-year period.

Columns:
Month - Represents the month and year in YYYY-MM format.
Sales - The number of sales recorded for that month.
Year - Extracted from the Month column.

Total records: 36 observations (12 per year).

## 2. Data Preprocessing

### Extracted Year and Month:
The Month column was split into Year and Month for better analysis.

Justification: Separating Year and Month allows us to analyze trends more effectively across different years and months individually.

### Checked for Missing Values & Duplicates:
No missing values were found.
No duplicate entries were detected.

Justification: Ensuring data quality and consistency before proceeding with analysis.

### Basic Statistical Analysis:
Computed key statistics such as mean, median, mode, variance, standard deviation, interquartile range (IQR), skewness, and kurtosis.

Justification: These measures help understand the distribution of sales data, detect skewness, and identify potential anomalies.

## 3. Exploratory Data Analysis (EDA)

### 3.1 Summary Statistics
Summary statistics provide a quick overview of data distribution and variability, helping identify potential data trends or issues.

### 3.2 Outlier Detection
Identified outliers based on the IQR method. Visualized outliers were  using a boxplot.

Justification: Outliers can indicate anomalies or special cases in sales (e.g., promotional events or unexpected drops). Identifying them helps in understanding irregular sales behavior.

### 3.3 Visualizations & Insights

#### a. Sales Distribution Over Time
A line plot shows overall trends and seasonality.
Observed patterns suggest that sales follow an upward trend with periodic fluctuations.

Justification: A time series line plot helps visualize trends and seasonality, giving insights into how sales behave over time.

#### b. Monthly Sales Trends (Yearly Comparison)
Used a grouped bar chart to compare sales per month across different years.
Certain months consistently have higher sales.

Justification: This comparison helps identify months with peak sales, which can be useful for forecasting and business planning.

#### c. Heatmap of Monthly Sales (Seasonal Pattern Detection)
Used a heatmap to identify seasonal sales variations.
Some months have significantly higher sales, indicating seasonality.

Justification: Heatmaps provide an intuitive way to visualize seasonality, highlighting peak and low sales periods.

#### d. Moving Average Analysis
A 3-month moving average was calculated to smooth short-term fluctuations and highlight long-term trends.

Justification: Moving averages help in trend analysis by reducing noise from short-term variations, making overall patterns clearer.

#### e. Correlation Analysis
A correlation heatmap was generated to check relationships between Sales, Year, and Month.
Findings suggest that sales are positively correlated with time, indicating a growth trend.

Justification: Correlation analysis helps understand how different variables relate, confirming trends or dependencies in the dataset.

#### f. Autocorrelation & Partial Autocorrelation Plots
These plots confirm that sales exhibit strong seasonality.

Justification: These statistical methods help in forecasting by identifying repeating patterns or lags in sales data.

## 4. Key Findings & Patterns

Sales show an increasing trend over time.

Certain months consistently experience higher sales, confirming seasonality.

Autocorrelation analysis confirms periodic sales cycles.

Moving averages smooth out short-term fluctuations, confirming the general growth pattern.
