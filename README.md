# Project1_Group2
Repo for Group Project 1

Group Members: Zac Williams, Cole O'Neill, Joel Fisher, Justin Clawson, Selena Passeno

This project aims to investigate the relationships and impacts associated with inflation and  unemployment rates utilizing the Federal Reserve Economic Data (FRED). The analysis was conducted using Pandas and Jupyter Notebook, with data visualization performed using Matplotlib. Conducting a comprehensive five-year analysis, categorizing the data into pre-COVID, during, and post-COVID periods (2017-2023). This timeline will provide insights into how economic indicators such as inflation and unemployment have evolved over these crucial phases.

Our data sources are from the Federal Reserve Economic Data (FRED) website. We chose FRED as our source of data because we wanted a reliable source of economic information that would help us answer our project questions. Also, FRED is a very user-friendly and data-dense platform, which allowed us to gather ample economic data that we could trust to test our hypotheses.

Data was pulled from 1982. Using Pandas, multiple dataframes were created and merged together, and using Matplotlib several graphs and charts were generated, as well as performing ANOVA, hypothesis testing, pearson's correlation. Instructor assisted with coding to clean the dates shown on the x-axis in the graphs.

The questions we seek to answer in this analysis are as follows - 
1) Is there a relationship between inflation and unemployment?
2) Is there a relationship between CPI (Consumer Price Index) and Nationwide Inflation Rate?
3) Is there a difference in the impact of unemployment on a national and state basis (Michigan, California, Texas, New Jersey - Each representitive of one of the 4 Census-defined regions).

Our findings -
1) The inflation rate and unemployment rate were steady prior to covid and showed an inverse relationship during covid. As nationwide inflation rate increases the unemployment rate decreases (Pearson -0.381, pvalue 0.00035). 
2) As median CPI increases, nationwide inflation rate also increases. There is a strong correlation between the Nationwide Inflation Rate and the Median CPI (r=.79).
3) Hypothesis testing -
Ho - There is no significant difference in the unemployment rates between 2017 to 2023 by state/region.
Ha - There is a significant difference in unemployment rates across state/regions.
If we include all five data points in our analysis (Four states, One Nationwide) we would fail to reject our hypothesis. Including the nationwide data the p value is 0.0634. When we drop the Nationwide data our P-value spiked up to 0.137.

Considerations for future research -
1) Deeper analysis of the data we already have - regression etc., or a longer time-period to assess past recessions.
2) Finding other data sources.
3) Finding other variables to test if there is a stronger impact on  unemployment/inflation...automation, demand, productivity, wages, etc.
4) Drop the outliers, rerun analysis on the unemployment.
