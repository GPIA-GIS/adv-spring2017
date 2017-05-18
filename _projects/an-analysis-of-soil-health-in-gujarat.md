---
layout: project-page
title: "An Analysis of Soil Health in Gujarat"
linkname: an-analysis-of-soil-health-in-gujarat
author: "Gaurav Gupta-Casale"
tagline: "Through NDVI analysis these maps visualize if there is a correlation between the number of fertilizer distributors and poor soil health."
location:
    - place: Gujarat, India
project-link:
    - href: https://guptg729.github.io/Advanced%20GIS/Final%20Project/index.html
tags:
    - tag: NDVI
    - tag:  fertilizer
    - tag:  food security
thumbnail-path: img/an-analysis-of-soil-health-in-gujarat/insVlTL.png
img-folder: ../../img/an-analysis-of-soil-health-in-gujarat/
timestamp: 5/16/2017 11:59:39
---
According to the Food and Agriculture Organization (FAO) worldwide consumption of fertilizers have been steadily increasing. 

![]({{ page.img-folder }}gIEx1ay.png) 

With this project I synthesize data to help answer these three questions: 1) How will the increase in global demand of fertilizer affect food security?; 2) Is there a correlation between the number of fertilizer distributers and the health of the soil?; and 3) How can these maps influence Indian agricultural policy on the district, state and national level? 

My hypothesis is that the health of Gujarat’s soil will correlate with the national fertilizer consumption. India reached a peak in 2010, however data suggests that fertilizer consumption may reach an apex surmounting 2010 levels.

![]({{ page.img-folder }}GFpM8US.png) 

Understanding soil health is important for two reasons. The first reason is that it plays an important role in climate change. Genetically modified crops which sometimes rely on heavy fertilizer usage typically have a shorter crop cycle. This means that the crops photosynthesize at an expedited rate. When this occurs, the crops use more energy, thus requiring more water. It is for this reason why many farmers have had to resort to flooding to have high crop yields. 

![]({{ page.img-folder }}u6aVJh0.jpg) 

The long-term effect on the climate is that the monsoon season is more erratic: intense rainfalls and longer periods of drought.  An increase in water will mean that when it is hot, more evaporation will occur which leads to the condensation point being lowered. When the atmosphere reaches a certain temperature, there will be more severe rain. This adds uncertainty to farmers who rely on a seasonal rhythm to maximize their crop production.  High crop yields are essential for the livelihood of small stake-holder farmers. Unfortunately, many farmers are unable to feed themselves due to high fertilizer, pesticide and seed prices; structurally weak financial institutions; and low export prices for agricultural commodities. These elements are all factors that lead to food insecurity. 

The first stage of this project is to show the soil health in the state of Gujarat, one of the top fertilizer consumers in India, over time. My results revealed that there were more areas of barren soil in 2010 than there were in 2017.

![]({{ page.img-folder }}0tEYazv.png) 

The reason for this is twofold. In my opinion the 2010 data was more accurate because it was derived from Global Land Survey (GLS) data sets. These satellite images are terrain-corrected, which means that they contain very little light distortion. However, this is not true for the Landsat 8 imagery.   

![]({{ page.img-folder }}Q0aknJu.png) 

With the Landsat 8 imagery there are many corrections that you need to apply to each raster band to get an accurate NDV (Natural Difference Vegetation Index) value. The other possibility is that there are lower fertilizer consumption levels in 2017 than there were in 2010, and thus one finds healthier soil. Since I am at the very beginning stages I was not able to compliment my map analysis with statistics that detail Gujarat’s fertilizer consumption, the percentage of land that is used for agriculture, population density, or even information about crop and fertilizer prices I was able to do a pixel-by-pixel comparison of the two maps to show the percent change of the NDVI values between the two years. 

![]({{ page.img-folder }}insVlTL.png) 

Each pixel represents the photosynthetic capacity of a 30 x 30 meter grid. I overlayed this information by documenting, through India’s Farmer’s Portal (http://farmer.gov.in/) how many fertilizer distributors there are per Taluk (an administrative area that is larger than a village but smaller than a district). 

Next steps incorporating statistics and data to compliment the soil maps. For example, is there a relationship between fertilizer prices and the number of active fertilizer distributors? If there are lower export prices for agricultural commodities, do you find an increase in fertilizer consumption in order to spur high crop yields?
