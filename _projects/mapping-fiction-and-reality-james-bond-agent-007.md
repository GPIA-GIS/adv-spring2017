---
layout: project-page
title: "Mapping Fiction and Reality: James Bond, Agent 007"
linkname: mapping-fiction-and-reality-james-bond-agent-007
author: "N. Ama A. Kusi"
tagline: "Exploring geopolitical themes taken from the 2006 - 2015 Bond movies. Specifically, terrorism, cyber warfare, and surveillance."
location:
    - place: Global
project-link:
    - href: https://naakusi.github.io/GIS2/Project/index.html
tags:
    - tag: geopolitics
    - tag:  movies
thumbnail-path: img/mapping-fiction-and-reality-james-bond-agent-007/jz5kQi9r.png
img-folder: ../../img/mapping-fiction-and-reality-james-bond-agent-007/
timestamp: 5/17/2017 0:27:03
---
The aim of this project was to create a fun map based on a work of fiction. The character of James Bond was chosen, not only because of his many globetrotting adventures, but because the Bond movies also touch on geopolitical themes. This project focuses mainly on the Bond films produced between 2006 and 2015. The reason for this choice was because their geopolitical themes would more likely reflect current events. In the words of Bond producer, Gregg Wilson (2008-2015), “Each script process begins when we ask ourselves the question ‘What is the world afraid of now?’” The themes for the more recent films revolved around; terrorism, corporatism, cyber warfare, and surveillance. 

The countries featured in the movies, for the most part,  serve mostly as scenic backdrops. There isn’t any real engagement with political issues of the state. The movies’ antagonists do not have political allegiances to any particular nation state, but are rather rogue individuals working in the shadows to drive their nefarious agendas. So, for the purpose of this project, the countries featured in the 2006-2015 Bond movies and highlighted in this project map are instead used as points of reference to explore geopolitics relating to terrorism, cyber warfare, and surveillance.
Data used for this map are based on the following indexes:

Global Terrorism Index (2016), Institute for Economics and Peace (IEP)
- Used to map the degree of impact on countries affected by terrorism

Global Cybersecurity Index (2015), International Telecommunications Union (ITU)
- Used to map the cyber security readiness  - i.e -  the existence of national structures in place to implement and promote cybersecurity

Surveillance Industry Index (2016), Transparency Toolkit and Privacy International
-Used to map the general geolocations of private surveillance/security firms (suppliers) and the national governments that purchase their technology (buyers)

This project, in its current state, is a fun and interesting way to visualize movie trivia, it isn’t that useful. Ideally, being able to visualize changes in geopolitical status over a period of time could add a bit more utility. It would also make sense to expand the number of countries being explored beyond those from the 2006 - 2015 Bond movie franchise. Surveillance data could also be more specific by geolocating the office headquarters for each of the supplier countries (visualized as points). 

Although, seemingly incomplete, this project map presents an opportunity for further research and fine tuning to build on what has already been assembled here. 

Methodology:
--Map
Components are polygon features sourced from world countries boundary shapefile from Esri.org. 
Columns were added to the boundary map table to include movie and geopolitical data. 
The map contains six layers, one for each map filter, including a layer that contains no visualizations which serves as a preliminary clear filter.
--Webpage 
Template used: CARTODB Publishing template
A screenshot of the map legend was taken from CARTO and placed in an HTML div for the map web page (which works as long as visualizations remain static). 
Structure, styling, and interactivity are based on HTML, CSS, JavaScript, and JQuery coding language.


WEBPAGE AND MAP DESIGN: N. Ama A. Kusi
FOR: Advanced GIS, JJS Graduate Program in International Affairs, The New School