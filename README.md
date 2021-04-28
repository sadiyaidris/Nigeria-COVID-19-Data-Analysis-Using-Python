# NIGERIA COVID19 DATA ANALYSIS USING PYTHON
# Project Overview
In this project, Data science & analytics skills were employed to collect data, explore the data, perform analysis, create visualizations, and generate insights.
# Project Steps
## Data Collection
The data source is divided into different parts, and the data was combined to perform analysis and provide insights.

1. From NCDC COVID-19 official website, you will obtain the data by performing a web extraction or web scraping.
2. From Johns Hopkins University Center for Systems Science and Engineering (JHU CSSE) repository of global daily confirmed, recovered and death cases
3. Nigeria Community Vulnerability Index data
4. Real Domestic Gross Product Data
5. State Budget Data

And additional data from:
6. WHO COVID19 update data
7. Simplemaps
8. Esri Website
## Data Wrangling
- Libraries were imported
- The data sets were loaded
- Data was cleaned to remove unneccessary columns and rows, chage datatypes and rename columns for simplicity
## Data Analysis
Descriptive Analysis was done to determine:
1. Average number of COVID19 deaths across all states in Nigeria.
2. Highest and lowest numbers of deaths recorded in a state.
3. Highest and lowest numbers of discharged cases recorded in a state.
4. Average number of COVID19 admitted cases across all states in Nigeria.

Exploratory Analysis was done to determine:
1.  Top 10 Confirmed, Recovered and Death cases 
2.  Total daily confirmed, recovered and death cases in Nigeria
3.  Daily infection rate in Nigeria
4.  Maximum infection rate in Nigeria
5.  Relationship between lab confirmed cases and overall CCVI Index
6.  Relationship between lab confirmed cases and population density
7.  Degree of Correlation between Lab confirmed cases and various risk factors
8.  Nigeria Region-wise case distribution 
9.  Effect of the pandemic on Nigeria's GDP
10. Effect of the pandemic on Nigeria's Budget
11. Map overview of Nigerian states and COVID19 Cases
12. How does Nigeria's COVID19 case compare to top 5 affected countries? 
13. How does Nigeria's COVID19 case compare to the rest of the world?
14. WHO Region-wise case distribution

## Data Visualization
The findings were communicated and presented using chart visualizations from Python visualization libraries (Folium, Plotly, Seaborn and Matplotlib). The charts were generated as:
-	Bar plots
-   Scatter plots
-   Geographical map
-	Line plots
-	Pie charts
-	Regression plots
-   Heatmap

# Future Work
To explore Nigeria's COVID19 Vaccination dataset and its effect in curbing COVID19 Cases in Nigeria

# NB
I have plotly charts on this jupyter python notebook. Plotly charts work fine on my local system in the notebook. However, plotly charts are not displayed when uploaded to my github page.
The issue is that github performs a static render of the notebooks and it doesn't include the embedded HTML/JavaScript that makes up a plotly graph. See https://help.github.com/articles/working-with-jupyter-notebook-files-on-github/

One nice option is to paste the link to the GitHub notebook into http://nbviewer.jupyter.org/, which will present a rich view of the notebook.

Hope that clear things up!
