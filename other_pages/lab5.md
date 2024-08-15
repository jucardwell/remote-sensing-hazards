---
title: Lab 5
layout: default
parent: Labs
nav_order: 5
---

<style>
div.blue { background-color:#e0f0ff; padding: 10px 10px 3px 10px;}
</style>

------------------------------------------------------------------------
## Lab 5

In this lab, you will execute a change detection on two Sentinel-1 images – one soon before 
Hurricane Florence and one during Hurricane Florence—to detect potentially flooded areas. 

------------------------------------------------------------------------
### Your Google Earth Engine Script should:
1.	Load two preselected Sentinel-1 images that cover eastern NC
Pre-Florence image (09-04-2018): "COPERNICUS/S1_GRD/S1A_IW_GRDH_1SDV_20180914T230548_20180914T230617_023701_029566_B76A"
Florence image (09-14-2018):
"COPERNICUS/S1_GRD/S1A_IW_GRDH_1SDV_20180902T230552_20180902T230617_023526_028FCB_0AE6"
2.	Smooth the images. This reduces the radar speckle which can result in inaccurate change detection. Your smoothing radius should be 50 feet and should be applied to both images using the .focal_mean() function.
3.	Calculate the difference between the after and before images using division. Subtraction can be more sensitive to noise, especially in SAR images. 
4.	Set a difference threshold of 1.25 and identify areas that exceed this difference threshold. These areas represent potential flooding
5.	Create a well-visualized map identifying potentially flooded areas. 


### Your lab report should:
1.	Introduce why SAR can be a useful tool for flood analysis and why obtaining quality satellite images during hurricanes can be challenging. Also describe why satellites often cannot perfectly capture flooded areas. 
2.	Include a screenshot of your map
3.	Describe the spatial pattern of your map and identify areas that may have experienced significant flooding
4.	Conclude with a paragraph that summarizes your results. 
 

You will submit your GEE script and your completed lab report. Your lab report should be approximately 500 words. You should cite your sources in APA format and include at least 1 peer-reviewed article.
