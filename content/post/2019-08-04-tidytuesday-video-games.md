---
title: 'TidyTuesday: Video Games'
author: kuprina
date: '2019-08-04'
slug: video-games
categories:
  - tidytuesday
tags:
  - datavis
  - tidytuesday
  - tidyverse
cover: '/img/games_by_day.png'
description: ''
keywords:
  - 'datavis'
  - 'tidytuesday'
showFullContent: no
---

Using SteamSpy data, I was interested in seeing how many games are released on a daily basis. There was a clear trend in some days having higher number of new releases than others. It appears that most popular release day is Friday, followed by Thursday!


<img src="/img/plot_release_day.png" alt="drawing" width="100%"/>


## Total releases by dates

The trend highlighted that there are a lot less releases on the weekends compared to the weekdays:

<img src="/img/plot_over_time.png" alt="drawing" width="100%"/>


Original data: https://github.com/rfordatascience/tidytuesday/tree/master/data/2019/2019-07-30 

Libraries used: 

- tidyverse
- lubridate
- ggthemes
- magrittr
- gridExtra
- ggrepel
- glue
- grid
