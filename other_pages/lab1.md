---
title: Lab 1
layout: default
parent: Labs
nav_order: 1
---

<style>
div.blue { background-color:#e0f0ff; padding: 10px 10px 3px 10px;}
</style>

------------------------------------------------------------------------
## Lab 1

In this lab, you will use GRIDMET data to calculate the mean temperature and precipitation values for the United States from 1980-2020. You will create maps of these values and calculate mean values for each US county. You can download a shapefile of US counties [here](https://drive.google.com/uc?export=download&id=1NUDtSHKRC9Lmgm9vx8wAtDRIIUA4ElGn)

GRIDMET is a gridded surface meteorological dataset that provides daily estimates of temperature, precipitation, winds, humidity, and radiation across the US. GRIDMET data is not necessarily remote sensing data in the traditional sense, as it does not involve direct observation of the Earth’s surface from satellites or aircraft. Instead, GRIDMET combines observational data from weather stations, satellite-derived information, and atmospheric reanalysis models.

------------------------------------------------------------------------
### Your Google Earth Engine Script should:
1.	Load the GRIDMET data as an .ImageCollection() variable (https://developers.google.com/earth-engine/datasets/catalog/IDAHO_EPSCOR_GRIDMET#bands)
2.	Filter the GRIDMET data to only include images from 1980-2020
3.	Create two composite images—one representing mean temperature (which is represented in degrees Kelvin), and one representing mean precipitation (which is represented in millimeters).
4.	Create two well-visualized maps. One represents mean daily temperature, and one represents mean daily precipitation.
5.	Upload the US counties shapefile as an asset. 
6.	Use the .reduceRegions function to calculate the mean value of your two composites in US counties and export this as an .csv file. 


### Your lab report should include:
1.	An introduction (2-3 paragraphs) that talks about the importance of understanding climate averages of different regions and how remotely sensed data (and other gridded data products available in GEE) are helpful for this task.  In addition, it should introduce the GRIDMET dataset and why it is an appropriate product for this type of analysis. 
2.	Screenshots of the two maps you have created and a description of the spatial pattern of the two variables across the US. 
3.	A description of the output of your .reduceRegions function, and how it aligns with the maps.
4.	A concluding paragraph that summarizes your results from this lab. 


You will submit your GEE script, your .csv file, and your completed lab report. Your lab report should be approximately 500 words. 
You should cite your sources in APA format and include at least 1 peer-reviewed article. 

