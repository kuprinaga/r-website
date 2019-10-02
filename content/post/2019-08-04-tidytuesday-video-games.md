---
author: kuprina
categories:
- datavis
- tidyverse
- ggplot
date: '2019-08-04'
description: "Using SteamSpy data to discover trends in game releases"
image: plot_over_time.png
tags:
- public_data
- games
- datavis
- tidytuesday
- ggplot
title: 'TidyTuesday: Video Games'
---

Using SteamSpy data, I was interested in seeing how many games are released on a daily basis. There was a clear trend in some days having higher number of new releases than others. It appears that most popular release day is Friday, followed by Thursday!


<img src="/img/plot_release_day.png" alt="drawing" width="100%"/>


## Total releases by dates

The trend highlighted that there are a lot less releases on the weekends compared to the weekdays!


Original data: https://github.com/rfordatascience/tidytuesday/tree/master/data/2019/2019-07-30 

Libraries used: 

- - tidyverse
- - lubridate
- - ggthemes
- - magrittr
- - gridExtra
- - ggrepel
- - glue
- - grid
