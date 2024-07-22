---
title: Lab 4
layout: default
parent: Labs
nav_order: 4
---

<style>
div.blue { background-color:#e0f0ff; padding: 10px 10px 3px 10px;}
</style>

------------------------------------------------------------------------
## Lab 4

In this lab, you will calculate median temperature values across census tracts in Raleigh, North Carolina during the summer of 2024 (June 1 – Sept 1, 2024) to demonstrate the urban heat island effect and explore temperature disparities across the city. You will utilize your newly acquired skills in presenting results to create a short Executive Summary report on your results. 

Satellites capture Land Surface Temperature (LST), which represents the temperature of the land surface itself. However, they do not measure ambient temperature, which is the temperature of the air. This distinction is crucial, as LST and ambient temperature can vary significantly. Understanding this difference is important because it affects how temperature is actually experienced by people in an area. The implications of these differences are essential for accurately studying phenomena like the urban heat island effect and for making informed decisions in urban planning and public health.

You can download the Raleigh Census Tract shapefile [here](https://drive.google.com/uc?export=download&id=1lviugjcKYZ7-WtjkRe3iR2bMlR83fQiX)

------------------------------------------------------------------------
### Your Google Earth Engine Script should:
1.	Upload the Raleigh Census Tract shapefile as an asset in GEE.
2.	Filter the MODIS Terra satellite data (https://developers.google.com/earth-engine/datasets/catalog/MODIS_061_MOD11A1) to the study period
3.	Create a composite image that represents the median LST.
4.	Convert the LST value from Kelvin to degrees Fahrenheit. 
5.	Reduce the composite image to the census tracts using the .mean() reducer.
6.	Map the average summer temperature across Raleigh census tracts. 

### Your lab report should:
1.	Introduce of the urban heat island effect, a description of the impacts of the urban heat island, and an argument for why studying the urban heat island in Raleigh is important
2.	Include screenshot of your map. 
3.	Describe the results you have found. What important patterns exist? What are the potential implications of these patterns across the city? Can you make connections between these patterns and any social or economic factors?
4.	Conclude with a description of why these results are important. 

You will submit your GEE script and your completed lab report. Your lab report should be approximately 500 words. 
You should cite your sources in APA format and include at least 1 peer-reviewed article. 
