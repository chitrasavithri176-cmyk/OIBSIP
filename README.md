Unemployment in India Analysis Project
Project Overview
This project involves an exploratory data analysis (EDA) of unemployment rates in India, using a dataset spanning from May 2019 to June 2020. The primary goal is to understand various facets of unemployment, including regional disparities, monthly trends, and the impact of significant events such as the COVID-19 pandemic. The analysis utilizes Python with libraries like pandas, matplotlib, and seaborn to clean the data, visualize trends, and extract meaningful insights.

Data Source
The dataset used for this analysis is Unemployment in India.csv.

Methodology
Data Loading and Initial Inspection: The Unemployment in India.csv dataset was loaded into a pandas DataFrame. Initial checks were performed to understand its structure, identify missing values, and inspect data types.
Data Cleaning and Preprocessing:
Column names were stripped of leading/trailing whitespace to ensure consistency.
The 'Date' column was converted to datetime objects for time-series analysis.
Rows with null values were dropped to maintain data integrity.
Exploratory Data Analysis (EDA): Various visualizations and statistical summaries were generated to explore unemployment trends:
Region-wise Analysis: Calculated and visualized average unemployment rates across different regions to identify areas with high unemployment.
Monthly Trends: Examined average unemployment rates by month to detect seasonal patterns or significant peaks.
Top Regions Time Series: Plotted unemployment rate trends over time for the top three highest unemployment regions.
Correlation Analysis: A heatmap was used to visualize correlations between 'Estimated Unemployment Rate (%)', 'Estimated Employed', and 'Estimated Labour Participation Rate (%)'.
COVID-19 Impact Analysis: Compared average unemployment rates before and after March 2020 to assess the pandemic's impact.
Urban vs. Rural Comparison: Analyzed and visualized differences in unemployment rates between urban and rural areas.
Key Findings
Regional Disparities: Tripura, Haryana, and Jharkhand consistently exhibited the highest average unemployment rates, indicating persistent regional challenges.
Monthly Peaks: A significant surge in unemployment was observed during April and May, likely due to seasonal factors and the onset of the COVID-19 lockdown.
COVID-19 Impact: The average unemployment rate nearly doubled from pre-COVID (9.51%) to post-COVID (17.77%), highlighting the severe economic disruption caused by the pandemic.
Urban vs. Rural: Urban areas generally showed higher average unemployment rates (13.17%) compared to rural areas (10.32%).
Weak Correlations: A weak negative correlation was found between unemployment and employment, while the labour participation rate showed very weak correlations with both, suggesting other factors might be at play.
How to Run the Notebook
Environment Setup: Ensure you have Python and necessary libraries (pandas, matplotlib, seaborn) installed.
Data Placement: Place the Unemployment in India.csv file in the same directory as the Jupyter Notebook.
Execute Cells: Run all cells in the Jupyter Notebook sequentially to reproduce the analysis and visualizations.
