---
categories:
- datavis
- tidyverse
- ggplot
date: '2019-07-24'
description: "Using NYC open data, doing a quick spatial visualisation with leaflet"
image: nyc_cat.jpg
tags:
- public_data
- spatial_data
- cats
- datavis
title: NYC trash bins availability
---


To finally try my hands on map visualisations, I used this publicly available dataset from [NYC Open Data](https://data.cityofnewyork.us/Environment/Public-Recycling-Bins/sxx4-xhzg)

Data is very nice and tidy so it actually took less than an hour to create a simlpe interactive plot using *Leaflet*:

<iframe src="/images/map.html" width = 100% height = 600px></iframe> 

This is using the following libraries:
<ul>
<li>- lettercase (has a neat substitution for make.names but uses underscores instead!)</li>
<li>- tidyverse</li>
<li>- leaflet </li>
<li>- mapview </li>
<li>- webshot </li>
<li>- htmlwidgets</li>
<li>- htmltools</li>
<li>- magrittr</li>
</ul>