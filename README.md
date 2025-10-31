# DSA210 Project Phase1 Emre Ünal: Global Happiness & Life Expectancy Analysis

## 1. Objective
The goal of this project is to analyze global happiness scores and investigate how they relate to life expectancy across countries and over time. By combining the World Happiness Report with publicly available life expectancy data, the study aims to identify patterns, trends, and potential correlations between overall well-being and average lifespan.

Key questions include:
- Do happier countries tend to have higher life expectancy?
- How does life expectancy vary among countries with different happiness scores?
- Have improvements in life expectancy aligned with increases in happiness over time?

## 2. Data Sources

### 2.1 Primary Dataset: World Happiness Report
Source: [https://worldhappiness.report/ ](https://www.worldhappiness.report) 
The dataset includes annual happiness scores and indicators such as:
- Country
- Year
- Happiness score 
- GDP per capita
- Social support
- Healthy life expectancy 
- Freedom to make life choices
- Generosity
- Perceptions of corruption

### 2.2 Enhancement Dataset: Life Expectancy Data
Source: Our World in Data — Life Expectancy  
[https://ourworldindata.org/life-expectancy  ](https://ourworldindata.org/life-expectancy)
Direct CSV: https://ourworldindata.org/grapher/life-expectancy.csv

This dataset provides:
- Country
- Year
- Life expectancy at birth

These datasets will be merged by `Country` and `Year` to allow direct comparison, relation and correlation.

## 3. Planned Analysis
1. **Correlation Analysis**
   - Relationship between happiness scores and life expectancy across countries.

2. **Global and Regional Trends**
   - Compare continents or income groups to identify regional differences.

3. **Temporal Analysis**
   - Examine how changes in life expectancy relate to happiness trends over the years or vice versa.

4. **Visualization**
   - Scatter plots
   - Correlation heatmaps
   - Regional comparison charts
   - Time-series line plots

## 4. Data Collection Plan
1. Download the World Happiness Report dataset as CSV.
2. Download the OWID life expectancy dataset as CSV.
3. Clean datasets (standardize country names, handle missing years).
4. Merge datasets on `Country` and `Year`.
5. Perform exploratory data analysis in Python (pandas, matplotlib, seaborn).
6. Create visualizations and summary statistics.

## 5. Tools
- Python
- Jupyter Notebook

## 6. Privacy & Ethics
All data used in this project is publicly available and aggregated at the country level. No personal or sensitive information is included. Data sources allow open use for research and educational purposes.

## 7. Expected Outcome
The final results are expected to:
- Demonstrate statistical relationships between happiness and life expectancy.
- Provide visual insights into global well-being dynamics.
- Highlight regional patterns and outliers.
- Offer a concise, data-driven interpretation of the connection between lifespan and perceived quality of life.
