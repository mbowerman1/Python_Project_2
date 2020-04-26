# Analyzing the Spread and Prevalence of COVID-19 Across U.S. Counties

## Business Question
How can we visualize and better understand the overall toll of the COVID-19 pandemic on US counties or county equivalents?

## Data Visualizations
Gif of og choropleth map: ![](Images/)

Gif of raw data choropleth map: ![](Images/)

Images of final results (if necessary): ![](Images/)

## Data Insights
Comparing the choropleth maps made using the number of confirmed cases per county versus confirmed cases per capita per county demonstrates that using the raw data obscures the prevalence of the pandemic in the US. This is because the raw data doesn't account for the population of each county and thereby the relative density of confirmed cases in each county.  Standardizing our data by looking at cases per capita also helps highlight which counties are more likely to risk overloading their health systems with coronavirus patients, which would be useful to government officials and business owners involved in resource diversion and supply chain decisions. Incorporating further data on hospitals and hospital beds per capita would also inform these kinds of decisions. Further data on business closures or unemployment claims would also help illuminate the effect of the pandemic on the US beyond its medical impact.

### DATA LIMITATIONS TO ACKNOWLEDGE IN INSIGHTS
_We shaded values based on the number of COVID-19 cases per 1,000 residents to standardize the comparisons between counties, however, this is based on the reported numbers from each county. Each county and city have different protocols and resources for testing, which means that part of our visualization might indicate a county's capacity to test for COVID-19
These values are the total, cumulative reported confirmed COVID-19 cases, which means that many of the counted patients might have recovered from the virus already. We use this value to represent the overall toll that the virus has taken on a particular geographic region instead of the number of active cases at any given time.  
We can intuit how fast the number of cases increases based on how fast the color scale changes in any given city, but we'd probably want to calculate additional growth rates to quantify this for any specific point in time._

