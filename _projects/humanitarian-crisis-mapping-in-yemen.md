---
layout: project-page
title: "Humanitarian Crisis Mapping in Yemen"
linkname: humanitarian-crisis-mapping-in-yemen
author: "Julian Lattimore, Gregory Smith, and Jalita Moore"
tagline: "An advocacy map created for an NGO - Watchlist on Children and Armed Conflict - depicting the deteriorating healthcare situation in Yemen. "
location:
    - place: Republic of Yemen
project-link:
    - href: https://gasmith721.github.io/watchlist_yemen/
tags:
    - tag: Conflict
    - tag:  healthcare
    - tag:  humanitarian
    - tag:  civilian infrastructure
    - tag:  vulnerability
thumbnail-path: img/humanitarian-crisis-mapping-in-yemen/xRPSntP.png
img-folder: ../../img/humanitarian-crisis-mapping-in-yemen/
timestamp: 5/16/2017 12:27:08
---
In armed conflicts around the world, children and adolescents are subjected to egregious violations of their rights. Sexual violence, maiming, abduction, and recruitment as child soldiers pose real threats to their day-to-day lives. Further, disruption and denial of service with attacks on their schools and hospitals and the blockading of aid are reprehensible conditions caused by the ongoing conflict in Yemen between the government, Saudi-led coalition forces, and Houthi rebels. The Office for the Coordination of Humanitarian Affairs (OCHA) reported in June of 2016 that only 45% of the 3,507 facilities contacted in 16 out of Yemen's 22 provinces reported that they were fully functioning and accessible. There were only two doctors or fewer in 42% of the 276 surveyed districts.” (BBC) The targeting of health care facilities in the conflict has devastated the public health of Yemen and the obstruction of aid flows into the country has left the sick, elderly families and particular children most at risk.

![]({{ page.img-folder }}IbWb6Sa.jpg)

The project is a collaboration between Watchlist on Children and Armed Conflict and Milano School's Studley Graduate Program of International Affairs (SGPIA) to collaboratively develop data, visualization, and humanitarian mapping to assist Watchlist in their ongoing efforts to advocate for the protection of  children and vulnerable civilians in war zones in Yemen and around the world. 

In devising a working plan for production, Watchlist provided the SGPIA with over 500 reports documenting attacks on and the general healthcare situation over the course of the conflict (beginning in March, 2015) produced by organizations such as MSF, UNICEF, OCHA and UNHCR. 

![]({{ page.img-folder }}vmvfd7ur.jpg)

This individual reports were culled for pertinent data for our points map.  Hospital name/location, nature of the attack, injured, casualties, suspected perpetrator etc. and the individual report and its coinciding attack were listed in a google sheet with the rest of the reports. Individual attacks were then researched to trace report back to a specific latitude and longitude of the facility or location of the attack to the rooftop level when possible. 

![]({{ page.img-folder }}E3tRnJu.png)
  
This required a bit of time and effort using google maps, openstreetmap and google translator as many hospital names were in Arabic. Once a latitude/longitude point was found for an attack it was able to be plotted on a map. For instances where rooftops were unable to be identified, attacks were plotted at the district or neighborhood level. 

After culling all of the reports, 57 attacks were developed and mapped and styled using CARTO to develop a points map exhibiting the verifiable attacks against healthcare services, styled to be consistent with Watchlists' reports. 

Current with the points mapping, the SGPIA group worked to develop a contextual map, outlining some of the humanitarian needs data for Yemen's Govenorates most affected by the healthcare situation using mapbox to develop a choropleth basemap. This entailed similar research as exhibited in developing the points map but on an aggregate polygon level as opposed to rooftop or district. 

![]({{ page.img-folder }}1IcW2z9r.jpg)

Finally, the two maps were styled in a consistent manner using css and the points layer, overlaid with the polygon layer to create an interactive map housed on an html page utilizing jquery to pull up the specific attacks against healthcare services to the population and the overall healthcare and needs situation in each governorate  giving the user a wholistic breakdown of the situation in Yemen.
