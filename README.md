# Food Delivery Time Analysis

## Project Overview

This business analytics project examines the key factors influencing food delivery time using a dataset of more than 45,000 delivery transactions across urban and metropolitan areas in India.

The goal of the analysis is to identify operational and external factors associated with delivery delays and translate the findings into actionable recommendations for improving delivery efficiency.

## Business Question

Which factors—such as courier age, performance ratings, workload, traffic conditions, and weather—most significantly affect delivery time, and how can these insights be used to reduce delays?

## Tools & Methods

- Excel
- SPSS
- Data Cleaning and Preprocessing
- Descriptive Statistics
- Data Visualization
- Shapiro-Wilk Normality Test
- Spearman Correlation Analysis
- Linear Regression Analysis

## Dataset

The dataset contains approximately 45,593 food delivery records.

Key variables include:

- Delivery Time
- Courier Age
- Courier Ratings
- Multiple Deliveries
- Road Traffic Density
- Weather Conditions
- Vehicle Condition
- Order Type
- Vehicle Type

## Key Findings

- **Workload:** Multiple simultaneous deliveries showed the strongest positive association with delivery time.
- **Courier Ratings:** Higher-rated couriers tended to complete deliveries faster.
- **Courier Age:** Courier age showed a positive association with delivery time.
- **Traffic:** Congested traffic conditions contributed additional operational pressure.
- **Delivery Variability:** Average delivery time was approximately 26.3 minutes, with some deliveries exceeding 40–50 minutes.

## Key Visualizations

### Delivery Time Distribution
![Delivery Time Distribution](visuals/delivery_time_distribution.png)

The distribution shows that most deliveries are concentrated around 20–30 minutes, with longer delivery times extending beyond 40 minutes.

### Delivery Time Boxplot
![Delivery Time Boxplot](visuals/delivery_time_boxplot.png)

The boxplot highlights variability in delivery performance and identifies unusually long delivery times that may represent operational bottlenecks.

### Key Drivers of Delivery Time
![Spearman Correlation Matrix](visuals/spearman_correlation_matrix.png)

Spearman correlation analysis shows that multiple deliveries have the strongest positive association with delivery time, while higher courier ratings are associated with shorter delivery times.

### Workload Regression Analysis
![Workload Regression Results](visuals/workload_regression_results.png)

Regression analysis further evaluates the relationship between courier workload and delivery time.

## Business Recommendations

1. Limit the number of concurrent orders assigned to couriers during peak periods.
2. Prioritize high-rated couriers for time-sensitive deliveries.
3. Integrate real-time traffic information into routing decisions.
4. Analyze extreme delivery delays instead of automatically treating them as outliers.

## Business Impact

The analysis demonstrates how operational data can be translated into actionable decisions involving workload allocation, courier assignment, routing, and delivery performance management.

## Project Files

- Full Analysis Report
- Data Visualizations
- Statistical Analysis Results

## Skills Demonstrated

`Business Analytics` `SPSS` `Excel` `Statistical Analysis` `Data Visualization` `Regression Analysis` `Data-Driven Decision Making`
