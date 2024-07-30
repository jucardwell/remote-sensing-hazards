---
title: Lab 2
layout: default
parent: Labs
nav_order: 2
---

<style>
div.blue { background-color:#e0f0ff; padding: 10px 10px 3px 10px;}
</style>

------------------------------------------------------------------------
## Lab 2

In this lab, you will utilize the Normalized Burn Ratio (NBR) index to identify burned areas and measure burn severity using Landsat Imagery after the August Complex fire in August-November 2020 in Northern California. 

You can download a shapefile of the August Complex Fire [here](https://drive.google.com/uc?export=download&id=1lYwC9K09iL48KR3GeLZoXta6EGZNea0m)

------------------------------------------------------------------------
### Your Google Earth Engine Script should:
1.	Add the August Complex Fire extent shapefile as an asset in GEE.
2.	Use GEE filtering to select a Landsat 8 image that covers the fire extent area, has limited cloud cover, and was relatively soon after the fire.   
3.	Clip this image to the fire extent.
4.	Calculate the NBR on the image (https://www.usgs.gov/landsat-missions/landsat-normalized-burn-ratio)
5.	Create a well-visualized map of the NBR in the study area. 


### Your lab report should:
1.	Introduce (2-3 paragraph) the August Complex fire and describes how remotely sensed images can be helpful for tracking wildfires and wildfire recovery. The introduction should also describe spectral indices and how they can be useful. 
2.	Include a screenshot of your NBR map and a description of the spatial pattern you see in your NBR map (and an interpretation of the NBR values).
3.	Conclude by summarizing your results. 



You will submit your GEE script and your completed lab report. Your lab report should be approximately 500 words. Only one person needs to submit the material, so please include the name of both lab partners. You will also complete a self-evaluation of your contribution to the lab.  

You should cite your sources in APA format and include at least 1 peer-reviewed article. 
