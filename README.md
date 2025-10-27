# DSA210 Project Proposal: Global Happiness Analysis - Emre Ünal 31142

## 1. Objective
The purpose of this project is to analyze the factors influencing happiness across countries using the **World Happiness Report** dataset. The dataset ranks countries based on their citizens' perceived well-being, along with economic and social indicators.  
The project will explore which variables correlate most strongly with happiness and how these relationships vary by region.

Example guiding questions:
- Which factors best predict a country's happiness score?
- Are richer countries always happier?
- How do happiness scores differ across continents or income groups?

## 2. Data Sources
### 2.1 Base Dataset: World Happiness Report
The data is publicly available from [https://worldhappiness.report/](https://worldhappiness.report/).  
The dataset includes variables such as:
- `Country`  
- `Year`  
- `Happiness Score` (or `Ladder Score`)  
- `GDP per capita`  
- `Social support`  
- `Healthy life expectancy`  
- `Freedom to make life choices`  
- `Generosity`  
- `Perceptions of corruption`

### 2.2 Enrichment Dataset: World Bank Indicators
To enrich the dataset, I will merge it with selected socio-economic indicators from the **World Bank Open Data** (https://data.worldbank.org/), such as:
- Inflation rate  
- Unemployment rate  
- CO₂ emissions per capita  

These will be used to examine additional relationships between economic/environmental factors and happiness.

## 3. Planned Analysis
1. **Correlation Analysis**  
   - Identify which factors correlate most strongly with happiness scores.  
2. **Regional Comparison**  
   - Compare average happiness levels across continents.  
3. **Economic Impact Study**  
   - Analyze whether GDP per capita has diminishing returns on happiness.  
4. **Temporal Trends**  
   - Observe how global happiness and inequality have shifted over the years.  
5. **Environmental Extension (Enrichment)**  
   - Test whether pollution (CO₂ emissions) or inflation relates to happiness differences.

## 4. Data Collection Plan
1. Download the World Happiness Report dataset (available as CSV for multiple years).  
2. Download relevant World Bank indicators (via CSV or API).  
3. Clean and merge datasets on country and year.  
4. Perform exploratory data analysis using Python (pandas, matplotlib, seaborn).  
5. Produce descriptive statistics and correlation visualizations.

## 5. Privacy / Ethics
The data is entirely public and aggregated at the country level. It contains no personal or sensitive information.  
Both the World Happiness Report and World Bank datasets are openly licensed for educational and research use.

## 6. Tools
- Python (pandas, matplotlib, seaborn)  
- Jupyter Notebook for analysis  
- GitHub for version control and project submission  

## 7. Expected Outcome
The final report will present insights on global well-being patterns and the strongest predictors of happiness.  
Key deliverables include:
- Visualizations showing regional and temporal trends.  
- Correlation matrices and regression plots identifying key drivers of happiness.  
- A concise summary discussing how wealth, health, and freedom interact to shape global happiness.
