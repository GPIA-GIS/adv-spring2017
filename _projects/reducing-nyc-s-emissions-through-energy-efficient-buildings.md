---
layout: project-page
title: "Reducing NYC’s Emissions through Energy Efficient Buildings"
linkname: reducing-nyc-s-emissions-through-energy-efficient-buildings
author: "Tara Whalen"
tagline: "This map displays NYCEEC’s completed projects and attempts to locate new projects through spatial analysis of Site EUI and NYC flood zone data
"
location:
    - place: New York, NY, USA
project-link:
    - href: https://tkwhalen.github.io/index.html#
tags:
    - tag: GHG, Buildings, Sustainability, Energy Efficiency
thumbnail-path: img/reducing-nyc-s-emissions-through-energy-efficient-buildings/O4OzxTer.png
img-folder: ../../img/reducing-nyc-s-emissions-through-energy-efficient-buildings/
timestamp: 5/16/2017 9:12:06
---
New York City is vulnerable to the impacts of climate change, such as extreme weather events, flooding, and increased temperatures. Events like Hurricane Sandy in 2012 have caused devastating damage that is still evident in the city today.  To mitigate the effects of climate change New York City has committed to reducing green house gas emissions 80 percent by 2050, otherwise known as 80 x 50, in the initiative titled "One New York: The Plan for. Strong and Just City (1)."

Nearly one million buildings cover an area of approximately 300 square miles in New York City and are responsible for three-quarters of the city's green house gas emissions. In order to achieve an 80 percent reduction in emissions by 2050 it it vital that NYC address the efficiency issues of its buildings. The Greener Greater Buildings Plan (GGBP) was developed to support this effort.  The plan targets large existing buildings of 50,000 square feet or more and consists of four regulatory pieces as well as the implementation of a financing organization, New York City Energy Efficiency Corporation (NYCEEC) (2).  "NYCEEC is a non-profit specialty finance company that develops financing solutions to enable projects that save energy or reduce greenhouse gases (3)." 

Currently, I am interning at NYCEEC where I have been performing research for the organization's Contracting Marketing Strategy. The Contractor Marketing Strategy aims to raise awareness about NYCEEC and its products through increased interaction with contractors and a greater understanding of the individual energy efficiency silos, such as solar, cogeneration, and passive house. Databases of contractor contact information are compiled and  e-mailes  with NYCEEC's marketing material are sent to the contacts.

This project was developed as a resource for NYCEEC and aims to provide a way for the organization to target their marketing strategy and tailor their marketing materials to the identified customer. The project was divided into two parts: 
Part 1: A map of NYCEEC's financed projects. The intention was to create a more visually appealing and user friendly map with project data readily available for internal use and potentially for NYCEEC's website.
Part 2: A spatial analysis of  Local Law site energy usage intensity (EUI) and Hurricane Sandy Inundation  data.  This map attempts to visually depict which buildings or areas of the city are prime candidates for energy efficiency projects, thus allowing NYCEEC to target their marketing strategy geographically and tailor their marketing products. This map has been developed as the inital step towards NYCEEC utilizing GIS in house. Several other datasets could be overlaid with the energy usage data to highlight prime candidates for energy efficiency projects including, but not limited to; solor potential, heat/hot water complaints, affordability, etc. 

Part 1: NYCEEC's Financed Projects- Data was collected internally and from NYCEEC's website and compiled into one database. All projects are visible on one map and can be filtered by project type. Pop ups were enabled to display the project name, project type, other measures taken, total project cost, and the financial product provided by NYCEEC. 
![]({{ page.img-folder }}2SIu4bDr.png)

Part 2: Site EUI data was sourced from NYC Open Data's 2014 Local Law 84 (LL84) dataset.  LL84 is one of the four regulatory pieces of the Greener Greater Buildings Plan which requires buildings larger than 50,000 sq.ft. to annually measure and report their energy and water consumption.  Site EUI is the amount of energy used by the building, it is the amount noted in the building's utility bill.  To minimize the data to a manageable amount and to provide a map with the buildings using the most energy, only the top 5% buildings with the highest EUI were mapped by geocoding street address data. 

Sandy Flood Inundation data was sourced from NYC Open Data as well. By overlaying the EUI data and the flood data we can see buildings with high energy usage that are also in flood zones.  As floods can cause power outages it may be useful for these buildings specifically to invest in energy efficiency and resilency projects, such as cogeneration and battery storage.   

The buildings can be filtered by building type and pop ups were enabled for the building owner name, street address, site EUI, and total greenhouse gas emissions. 

![]({{ page.img-folder }}Wv5fCgb.png)


Sources:
(1)  NYC: Built to Last. (2014). Retrieved May, 2017, from http://www.nyc.gov/html/gbee/html/about/about.shtml
(2)  About OneNYC Green Buildings & Energy Efficiency. (n.d.). Retrieved 2017, from http://www.nyc.gov/html/gbee/html/about/about.shtml 
(3) NYCEEC. (2015). Retrieved March, 2017, from https://nyc
