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
## Lab 2

In this lab, you will utilize the Normalized Burn Ratio (NBR) to identify burned areas and measure burn severity using Landsat Imagery after the August Complex fire in August-November 2020 in Northern California. 

------------------------------------------------------------------------
### Your Google Earth Engine Script should:
1.	Add the August Complex Fire extent shapefile as an asset in GEE.
2.	Use GEE filtering to select a Landsat 8 image that covers the fire extent area, has limited cloud cover, and was relatively soon after the fire.  
3.	Clip this image to the fire extent
4.	Calculate the NBR on the image (https://www.usgs.gov/landsat-missions/landsat-normalized-burn-ratio)
5.	Create a well-visualized map of the NBR in the study area. 


### Your lab report should include:
1.	Introduce the August Complex fire and how remotely sensed images can be helpful for tracking wildfires and wildfire recovery. Also talk about how spectral indices can be used to highlight patterns in remote sensed image
2.	Include a screenshot of you NBR map
3.	Describe the spatial pattern seen in your NBR map and interpret the NBR values
4.	Conclude with a paragraph that summarizes what you have learned in this lab


You will submit your GEE script and your completed lab report. Your lab report should be approximately 500 words. 
