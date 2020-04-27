# Analyzing the Spread and Prevalence of COVID-19 Across U.S. Counties

## Business Question
How can we visualize and better understand the overall toll of the COVID-19 pandemic on US counties or county equivalents?

## Data Visualizations: Spread of Coronavirus January 21 - April 25 on Choropleth Maps
JupyterLab Notebook has been uploaded to this repository. Bubble map wasn't showing up in JupyterLab, but has been uploaded to "Images" folder in this repository along with density heatmap.

The following data was used in analysis: [JHU CSSE COVID-19 Case Data](), [New York Times COVID-19 Data](), and [US County Geospatial Data]().

### Confirmed Cases Per Capita Data
![](Images/covid19_cases_us_county.gif)

As of April 25th:
![](Images/covid19_cases_us_county.PNG)

### Raw Confirmed Cases Data
![](Images/covid19_cases_us_county_rawdata.gif)

As of April 25th:
![](Images/covid19_cases_us_county_rawdata.PNG)

## Data Insights
Comparing the choropleth maps made using the number of confirmed cases per county versus confirmed cases per capita per county demonstrates that using the raw data obscures the prevalence of the pandemic in the US. This is because the raw data doesn't account for the population of each county and thereby the relative density of confirmed cases in each county.

Standardizing our data by looking at cases per capita also helps highlight which counties are more likely to risk overloading their health systems with coronavirus patients, which would be useful to government officials and business owners involved in resource diversion and supply chain decisions. Incorporating further data on hospitals and hospital beds per capita would also inform these kinds of decisions. Further data on business closures or unemployment claims would also help illuminate the effect of the pandemic on the US beyond its medical impact.
