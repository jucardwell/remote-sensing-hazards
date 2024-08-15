---
title: Lab 3
layout: default
parent: Labs
nav_order: 3
---

<style>
div.blue { background-color:#e0f0ff; padding: 10px 10px 3px 10px;}
</style>

------------------------------------------------------------------------
## Lab 3

In this lab, you will use two different gridded climate products- ERA5-Land and RTMA- to extract wind speed values for Wilmington, NC during Hurricane Florence. You should analyze the period from September 12 – September 20, 2018. 

ERA-5 Land and RTMA, like the GRIDMET dataset used in Lab 1, is not remotely sensed data. However, the availability of these datasets on GEE is a huge asset. These products are hourly, meaning that to analyze long time periods, you would be analyzing a huge amount of data which would be very time consuming or impossible to do on your local computer. 

------------------------------------------------------------------------
### Your Google Earth Engine Script should:
1.	Create a feature (point or polygon) for Wilmington, North Carolina.
2.	 Filter ERA5-Land and RTMA to the time period.
3.	Extract the wind speed band. You will use 'wind_speed' in the RTMA data. For the ERA5-Land data, you will need to calculate a new band that combines the v- and u- components of the wind into a single wind speed using this formula:
    'sqrt(u-component^2 + v-component^2)' 
4.	Create two time series charts representing wind speed during the study period in Wilmington based on the two different datasets.


### Your lab report should:
1.	Introduce Hurricane Florence’s impacts in North Carolina and why gridded climate re-analysis products can be helpful for tracking impacts of hurricanes.
2.	Include a screenshot of your two time series charts.
3.	Describe trends seen in the time series, including differences between the two products.
4.	Hypothesize why differences exist between the products.
5.	Conclude with a summary of your results. 

You will submit your GEE script and your completed lab report. Your lab report should be approximately 500 words. You should cite your sources in APA format and include at least 1 peer-reviewed article. 
