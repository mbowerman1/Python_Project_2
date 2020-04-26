# Analyzing the Spread and Prevalence of COVID-19 Across U.S. Counties

## Business Question
How can we visualize and better understand the overall toll of the COVID-19 pandemic on US counties or county equivalents?

## Data Visualizations
Gif of og choropleth map: ![](Images/)

Gif of raw data choropleth map: ![](Images/)

Images of final results (if necessary): ![](Images/)

## Data Insights
__We standardized the data to shade our choropleth map so that we could better compare the toll on different counties with each other, but what does the choropleth map look like if we used the raw case data instead of the standardized data? Why would we not want to use the raw data in this visualization?__
Using just raw data doesn't account for the population of each county and thereby the relative density of confirmed cases in each county. As can been seen when comparing the choropleth maps made using the number of confirmed cases per county versus confirmed cases per capita per county, using the raw data obscures the prevalence of the pandemic in the US. Looking at cases per capita also helps highlight which counties are experiencing more overloading their health systems.

__How is this animated data visualization helpful for county and state leadership or business owners in the US? What other data might we want to incorporate into an animated choropleth map to better understand the toll of the novel coronavirus in the United States?__

### DATA LIMITATIONS TO ACKNOWLEDGE IN INSIGHTS
_We shaded values based on the number of COVID-19 cases per 1,000 residents to standardize the comparisons between counties, however, this is based on the reported numbers from each county. Each county and city have different protocols and resources for testing, which means that part of our visualization might indicate a county's capacity to test for COVID-19
These values are the total, cumulative reported confirmed COVID-19 cases, which means that many of the counted patients might have recovered from the virus already. We use this value to represent the overall toll that the virus has taken on a particular geographic region instead of the number of active cases at any given time.  
We can intuit how fast the number of cases increases based on how fast the color scale changes in any given city, but we'd probably want to calculate additional growth rates to quantify this for any specific point in time._

