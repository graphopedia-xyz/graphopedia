---
title: streamgraph
  
functions:
- change over time
- correlation

related:
  - area-chart

tools:
  - name:   D3
    link:   https://beta.observablehq.com/@mbostock/streamgraph-transitions

  - name:   R 
    link:   https://hrbrmstr.github.io/streamgraph/
  
  - name:   PlotDB 
    link:   https://plotdb.com/chart/1038/
    

examples:
  - title:  Growth of Subreddits
    author: Nathan Yau
    link:  https://flowingdata.com/2018/10/30/subreddit-comments/
    image:  comments-for-subreddits.png

  - title:  A Visual History of Which Countries Have Dominated the Summer Olympics
    author: The New York Times
    link:  https://www.nytimes.com/interactive/2016/08/08/sports/olympics/history-olympic-dominance-charts.html?mtrref=undefined&gwh=A81CA2E76FFBB330BC0A04EE77767241&gwt=pay
    image:  visual-history-of-which-countries-dominated-summer-olympics.png
  
  - title:  The Ebb and Flow of Movies
    author:  The New York Times
    link:  https://archive.nytimes.com/screenshots/www.nytimes.com/interactive/2008/02/23/movies/20080223_REVENUE_GRAPHIC.jpg
    image:  movie-box-office-receipts.jpg

order: 280

---

is a type of [stacked area chart](/area-chart) that displays the data curves relative to its central axis.[^byron] 

<!--more-->
Similar to the area chart, the height of each area represents values along the Y-axis. The X-axis reflects the time. Streamgraphs use the smooth spline curve that connects individual data points along the X-axis. The data points are typically not marked with dots.

Unlike stacked area charts with bottom alignment, a Streamgraph aligns to its centers. The alignment is what makes the Streamgraphs aesthetically beautiful. At the same time, Stramgraphs are less readable than an area chart since comparing heights of shapes not aligned in a straight line is less intuitive. [^clevelend]

The layers of the Streamgraph are ordered by rank. There can be no gaps between them since this would skew the other layers.


## Sources
[^byron]: Byron, Lee, and Martin Wattenberg. ["Stacked graphs–geometry & aesthetics."](http://leebyron.com/streamgraph/stackedgraphs_byron_wattenberg.pdf) *IEEE transactions on visualization and computer graphics* 14.6 (2008): 1245-1252.
[^cleveland]: Cleveland, William S., and Robert McGill. ["Graphical perception: Theory, experimentation, and application to the development of graphical methods."](https://doi.org/10.1080/01621459.1984.10478080) *Journal of the American statistical association* 79.387 (1984): 531-554.
