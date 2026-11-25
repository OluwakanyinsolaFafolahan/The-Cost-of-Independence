# The Cost of Independence

## Housing Affordability and Financial Pressure Among Young Adults in Europe (2003–2025)

**Author:** Oluwakanyinsola Fafolahan  
**Project Category:** Data Analytics | Economic Analysis | Predictive Analytics  
**Tools:** Microsoft Excel, Power Query and Microsoft Power BI  
**Data Source:** Eurostat  

---

## Table of Contents

- Project Overview
- Research Objectives
- Data Source and Dataset
- Business Questions
- Tools and Techniques
- Data Preparation
- Descriptive and Comparative Analysis
- Exploratory Data Analysis
- Correlation Analysis
- Multiple Linear Regression
- Prediction and Model Validation
- Key Findings
- Dashboard Development
- Recommendations
- Project Limitations
- Conclusion

---

## Project Overview

Housing affordability is a significant economic and social challenge, particularly for young adults seeking financial independence.

As a young adult living in Italy, I wanted to understand how housing affordability has changed across Europe and whether economic conditions could help explain the financial pressures experienced by younger generations.

This project investigates historical housing affordability trends, differences across European countries and population groups, and the relationship between economic and demographic indicators and housing-cost overburden.

The analysis combines descriptive statistics, exploratory data analysis, correlation analysis, multiple linear regression, predictive modelling and interactive data visualisation to generate meaningful insights from publicly available economic data.

---

## Research Objectives

- Examine historical housing affordability trends across Europe between 2003 and 2025.
- Identify countries experiencing the highest and lowest housing-cost overburden rates.
- Evaluate improvements and deteriorations in housing affordability over time.
- Compare housing affordability across age, gender and poverty groups.
- Investigate relationships between economic conditions and young-adult housing affordability.
- Develop and validate a multiple linear regression model.
- Translate analytical findings into meaningful insights and recommendations.

---

## Data Source and Dataset

The data used in this project was obtained from Eurostat, the statistical office of the European Union.

Multiple economic, demographic and housing indicators were consolidated into a structured dataset for analysis.

| Dataset Information | Details |
|---|---|
| Source | Eurostat |
| Period | 2003–2025 |
| Total Observations | 717 |
| Total Variables | 19 |
| Geographic Coverage | European Countries |
| Primary Age Group | 15–29 Years |
| Complete Regression Observations | 473 |

### Key Indicators

- Overall housing-cost overburden rate
- Young-adult housing-cost overburden rate
- Male and female housing-cost overburden rates
- Housing-cost overburden below the poverty threshold
- Housing-cost overburden above the poverty threshold
- Youth unemployment rate
- General inflation
- Rental inflation
- Median income (ages 16–24, measured in PPS)
- Young adults living with parents
- Tourism intensity
- Building permits per 1,000 inhabitants

### Definition of Housing-Cost Overburden

The housing-cost overburden rate measures the percentage of the population living in households where total housing costs represent more than 40% of disposable household income, according to Eurostat's methodology.

---

## Business Questions

### Part A — Housing Trends

1. How has the housing-cost overburden rate changed across selected European countries between 2003 and 2025?

2. Which European countries recorded the highest and lowest housing-cost overburden rates in 2025?

3. Which countries experienced the greatest increases or decreases in housing-cost overburden between 2015 and 2025?

### Part B — Population Group Comparisons

4. How does housing-cost overburden among young adults aged 15–29 compare with the overall population across European countries?

5. How does housing-cost overburden differ between people below and above the poverty threshold?

6. Are there differences in housing-cost overburden between males and females across European countries?

### Part C — Economic Relationships and Predictive Analysis

7. What relationships exist between young-adult housing-cost overburden and economic indicators such as youth unemployment, general inflation, rental inflation and median income?

8. To what extent can selected economic and demographic indicators explain variations in housing-cost overburden among young adults using multiple linear regression?

---

## Tools and Techniques

### Microsoft Excel

- Data cleaning and preparation
- Data consolidation
- Excel formulas and functions
- PivotTables and PivotCharts
- Interactive slicers
- Descriptive statistics
- Exploratory data analysis
- Scatter plots and trendlines
- Pearson correlation analysis
- Multiple linear regression
- Analysis of Variance (ANOVA)
- Model training and testing
- Prediction and model validation
- Interactive dashboard development

### Power Query

- Data preparation
- Data transformation
- Data organisation

### Microsoft Power BI

- Business intelligence
- Interactive data visualisation
- KPI development
- Dashboard development
- Analytical reporting
- Data storytelling

---

## Data Preparation

The data preparation process involved:

- Collecting relevant datasets from Eurostat.
- Consolidating housing, economic and demographic indicators.
- Standardising country and year information.
- Organising variables into a structured analytical dataset.
- Identifying missing observations.
- Preparing supporting datasets for correlation and regression analysis.
- Separating complete regression observations into training and testing datasets.

The resulting dataset provided the foundation for descriptive, comparative and predictive analysis.

---

## Descriptive and Comparative Analysis

The first six business questions were addressed using PivotTables, PivotCharts, Excel formulas and interactive slicers.

### Question 1 — Historical Housing Trends

Historical housing-cost overburden trends were examined across selected European countries and compared with the European Union benchmark.

Line charts were used to identify long-term patterns, fluctuations and differences between countries.

### Question 2 — Country Comparisons

European countries were ranked according to their overall housing-cost overburden rates in 2025.

Among the countries analysed:

- Greece recorded the highest rate at 26.4%.
- Cyprus recorded the lowest rate at 2.4%.

These results highlight substantial differences in housing affordability across Europe.

### Question 3 — Changes in Housing Affordability

Housing-cost overburden rates in 2015 and 2025 were compared to identify improvements and deteriorations.

| Country | Change (Percentage Points) |
|---|---:|
| Serbia | -25.8 |
| Greece | -19.1 |
| Romania | -10.9 |
| Netherlands | -8.4 |
| Norway | +4.1 |
| Malta | +4.9 |

Negative values indicate a reduction in housing-cost overburden, while positive values indicate an increase.

Overall, 22 out of 29 countries with comparable observations recorded lower housing-cost overburden rates between 2015 and 2025.

### Question 4 — Young Adults and the Overall Population

Housing-cost overburden among young adults aged 15–29 was compared with that of the overall population.

The results revealed considerable variation across countries, with young adults experiencing higher housing-cost overburden than the overall population in several countries.

An additional indicator examined young adults living with their parents.

The selected-country average for individuals aged 16–29 living with parents was approximately 69.9% in 2025.

### Question 5 — Housing-Cost Overburden and Poverty

Housing affordability was examined among individuals living below and above the poverty threshold.

The analysis revealed substantially higher housing-cost overburden among individuals living below the poverty threshold, highlighting the vulnerability of lower-income households.

### Question 6 — Gender Differences

Male and female housing-cost overburden rates were compared across European countries.

The results indicated that gender-related differences exist, although their magnitude and direction vary across countries.

---

## Exploratory Data Analysis

Exploratory data analysis was conducted to examine the statistical characteristics of young-adult housing-cost overburden and selected economic indicators.

### Descriptive Statistics

The following statistical measures were calculated:

- Mean
- Median
- Mode
- Standard deviation
- Standard error
- Sample variance
- Skewness
- Kurtosis
- Range
- Minimum and maximum
- Observation count

These measures provided insights into the distribution, variability and characteristics of the selected variables.

### Scatter Plot Analysis

Scatter plots and trendlines were developed to examine the relationships between young-adult housing-cost overburden and:

- Youth unemployment
- General inflation
- Rental inflation
- Median income

This stage supported the identification of patterns and potential linear relationships before formal statistical analysis.

---

## Correlation Analysis

Pearson correlation analysis was conducted to measure the direction and strength of linear relationships between selected economic indicators and young-adult housing-cost overburden.

### Correlation Results

| Economic Indicator | Pearson Correlation (r) | Interpretation |
|---|---:|---|
| Youth Unemployment | +0.335 | Moderate positive relationship |
| General Inflation | -0.102 | Weak negative relationship |
| Rental Inflation | -0.116 | Weak negative relationship |
| Median Income | -0.100 | Weak negative relationship |

### Interpretation

Youth unemployment demonstrated the strongest positive correlation among the four economic indicators examined.

Higher youth unemployment was associated with higher housing-cost overburden among young adults.

General inflation, rental inflation and median income exhibited weak negative linear relationships with young-adult housing-cost overburden.

These results suggest that employment conditions are particularly relevant when examining housing affordability and financial pressure among young adults.

However, correlation does not imply causation.

---

## Multiple Linear Regression

A multiple linear regression model was developed to investigate the combined relationship between selected economic, demographic and structural indicators and young-adult housing-cost overburden.

### Stage 1 — Correlation Screening of Potential Predictors

A correlation matrix was developed to examine relationships between the dependent variable and potential explanatory variables, as well as relationships among the predictors themselves.

This preliminary analysis supported the evaluation of potential predictors before regression modelling.

### Stage 2 — Model Development

#### Dependent Variable

- Young-adult housing-cost overburden rate (ages 15–29)

#### Independent Variables

1. Youth unemployment rate
2. General inflation
3. Rental inflation
4. Median income
5. Young adults living with parents
6. Tourism intensity
7. Building permits per 1,000 inhabitants

### Regression Equation

The general multiple linear regression model is expressed as:

Y = β₀ + β₁X₁ + β₂X₂ + β₃X₃ + β₄X₄ + β₅X₅ + β₆X₆ + β₇X₇ + ε

Where:

- Y represents young-adult housing-cost overburden.
- β₀ represents the intercept.
- β₁ to β₇ represent the regression coefficients.
- X₁ to X₇ represent the explanatory variables.
- ε represents the error term.

### Training and Testing Strategy

A chronological data split was applied to evaluate the model using more recent observations.

| Dataset | Period | Observations |
|---|---|---:|
| Training Dataset | Through 2021 | 355 |
| Testing Dataset | 2022–2025 | 118 |
| Total Complete Observations | | 473 |

### Regression Statistics

| Statistical Measure | Result |
|---|---:|
| Multiple R | 0.5707 |
| R Square | 0.3256 |
| Adjusted R Square | 0.3120 |
| Standard Error | 6.7467 |
| Training Observations | 355 |

The model explained approximately 32.56% of the variation in young-adult housing-cost overburden within the training dataset.

### Analysis of Variance (ANOVA)

ANOVA was used to evaluate the overall statistical significance of the fitted regression model.

| Statistical Measure | Result |
|---|---:|
| Regression Degrees of Freedom | 7 |
| Residual Degrees of Freedom | 347 |
| Total Degrees of Freedom | 354 |
| F-Statistic | 23.9357 |
| Significance F | < 0.001 |

The overall regression model was statistically significant at the 5% significance level under the assumptions of the fitted model.

### Regression Coefficients

| Variable | Coefficient | P-value | Significant at 5% |
|---|---:|---:|---|
| Intercept | 25.8454 | < 0.001 | Yes |
| Youth Unemployment | 0.3772 | < 0.001 | Yes |
| General Inflation | -0.2349 | 0.3622 | No |
| Rental Inflation | 0.0102 | 0.9153 | No |
| Median Income | -0.0001103 | 0.2274 | No |
| Living with Parents | -0.2564 | < 0.001 | Yes |
| Tourism Intensity | 0.0691 | 0.4434 | No |
| Building Permits | -0.4653 | < 0.001 | Yes |

### Statistically Significant Predictors

Three explanatory variables emerged as statistically significant within the fitted regression model:

**Youth Unemployment**

Higher youth unemployment was associated with higher young-adult housing-cost overburden, holding the other explanatory variables constant.

**Living with Parents**

A higher proportion of young adults living with parents was associated with lower housing-cost overburden, holding the other explanatory variables constant.

**Building Permits**

Higher building permit rates were associated with lower young-adult housing-cost overburden, holding the other explanatory variables constant.

These findings highlight the relevance of employment conditions, living arrangements and residential housing development when examining housing affordability.

The estimated relationships should not be interpreted as evidence of causation.

---

## Prediction and Model Validation

### Stage 3 — Prediction and Validation

The fitted regression model was applied to the testing dataset covering 2022–2025.

Predicted housing-cost overburden values were compared with actual observed values to evaluate the model's predictive performance.

### Model Performance

| Performance Metric | Result |
|---|---:|
| Training R² | 32.56% |
| Adjusted Training R² | 31.20% |
| Testing Observations | 118 |
| Mean Absolute Error (MAE) | 3.88 pp |
| Root Mean Squared Error (RMSE) | 5.64 pp |

*pp = percentage points.*

### Mean Absolute Error (MAE)

The model's predictions differed from the actual housing-cost overburden rates by approximately 3.88 percentage points on average in absolute terms.

### Root Mean Squared Error (RMSE)

The model recorded an RMSE of approximately 5.64 percentage points.

The higher RMSE relative to MAE reflects the greater influence of larger prediction errors.

### Actual vs Predicted Analysis

An Actual vs Predicted scatter plot was developed to visually assess the relationship between observed housing-cost overburden rates and model predictions.

The results demonstrated that the model captures some of the variation in housing-cost overburden, although considerable prediction errors remain.

### Overall Model Evaluation

The regression model provides useful insights into the economic and structural indicators associated with young-adult housing affordability.

However, its explanatory and predictive capabilities are limited, indicating that additional variables and alternative modelling approaches could improve future analysis.

---

## Key Findings

### 1. Significant Cross-Country Disparities

Greece recorded an overall housing-cost overburden rate of 26.4% in 2025, compared with 2.4% in Cyprus.

### 2. Long-Term Improvements

22 out of 29 countries with comparable observations experienced reductions in housing-cost overburden between 2015 and 2025.

### 3. Challenges to Financial Independence

Approximately 69.9% of young adults aged 16–29 were living with their parents in 2025, based on the selected-country average.

### 4. Poverty and Housing Vulnerability

Individuals living below the poverty threshold generally experienced substantially greater housing-cost overburden than those living above it.

### 5. Gender and Age Differences

Housing affordability pressures varied across population groups and countries.

### 6. Youth Unemployment and Housing Affordability

Youth unemployment recorded the strongest positive correlation among the four economic indicators examined in Question 7, with a Pearson correlation coefficient of approximately +0.335.

### 7. Economic and Structural Predictors

Youth unemployment, living with parents and building permits emerged as statistically significant predictors in the multiple linear regression model.

### 8. Predictive Model Performance

The regression model explained 32.56% of the variation in young-adult housing-cost overburden within the training dataset and achieved a testing MAE of 3.88 percentage points.

---

## Dashboard Development

The analytical findings were consolidated into interactive dashboards using Microsoft Excel and Microsoft Power BI.

The dashboards were developed to communicate historical trends, country comparisons, population disparities, economic relationships and regression model performance.

Interactive filters, visualisations and key performance indicators were incorporated to support data exploration and interpretation.

---

## Recommendations

Based on the analytical findings, the following recommendations are proposed for consideration by policymakers and relevant stakeholders:

- Strengthen youth employment and economic inclusion initiatives.
- Improve access to affordable housing for young adults.
- Develop targeted housing support for financially vulnerable households.
- Encourage sustainable residential housing development.
- Monitor housing affordability alongside employment, income and demographic indicators.
- Develop country-specific housing affordability strategies.
- Investigate additional barriers to financial independence among young adults.
- Expand future predictive models to include additional socioeconomic and housing market variables.

---

## Project Limitations

- Data availability varies across countries, indicators and years.
- Missing observations reduced the sample available for regression analysis.
- Country-level averages may conceal regional and household-level differences.
- Correlation and regression relationships do not establish causation.
- The regression model explains only part of the variation in housing-cost overburden.
- Repeated country-year observations may introduce dependencies that conventional linear regression does not fully account for.
- Prediction accuracy depends on the availability and reliability of explanatory variables.
- Further analysis could incorporate additional predictors and alternative statistical modelling techniques.

---

## Skills Demonstrated

- Data Collection
- Data Cleaning and Preparation
- Data Transformation
- Exploratory Data Analysis
- Descriptive Statistics
- Comparative Analysis
- Pearson Correlation Analysis
- Multiple Linear Regression
- Analysis of Variance (ANOVA)
- Predictive Analytics
- Model Training and Testing
- Model Validation
- Statistical Interpretation
- Microsoft Excel
- Power Query
- Microsoft Power BI
- Business Intelligence
- Dashboard Development
- Data Visualisation
- Data Storytelling
- Economic and Business Analysis

---

## Conclusion

Housing affordability among young adults is a multidimensional challenge shaped by economic, demographic and structural conditions.

The findings highlight the importance of examining housing affordability beyond housing costs alone, considering employment conditions, income disparities, living arrangements and residential housing development.

Through descriptive analysis, correlation analysis, multiple linear regression and interactive dashboard development, this project demonstrates how publicly available economic data can be transformed into meaningful analytical insights.

The project also illustrates the practical application of data analytics, statistical modelling and business intelligence to a real-world socioeconomic challenge.

---

## Data Source

Eurostat — European Statistical Office

https://ec.europa.eu/eurostat/

---

## About the Author

**Oluwakanyinsola Fafolahan**

Financial and Business Management Graduate | Data Analytics | Business Intelligence

Interested in applying financial knowledge, analytical thinking and business intelligence to real-world business and socioeconomic challenges.

