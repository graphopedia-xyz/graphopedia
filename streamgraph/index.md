---
title: streamgraph
  
tags:
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

---

is a type of [stacked area chart](/area-chart) that displays the data curves relative to its central axis.[^byron] The function of the Streamgraph is the display of multiple individual time-series while showing their sum.

<!--more-->
Similar to the area chart, the height of each area represents values along the Y-axis. The X-axis reflects the time.

Unlike stacked area charts with bottom alignment, Streamgraphs align to their centers. The center alignment is what makes the Streamgraphs aesthetically beautiful. At the same time, it makes it less readable since comparing heights of shapes not aligned in a straight line is less intuitive.

The layers of the Streamgraph are ordered, and there can be no spaces between them since that would skew the other layers.


## Sources
[^byron]: [L. Byron, M. Wattenberg, "Stacked graphs &minus geometry & aesthetics," IEEE Trans. Vis. and Comp. Graphics, vol. 14, no. 6, pp. 1245-1252, 2008.](http://leebyron.com/streamgraph/stackedgraphs_byron_wattenberg.pdf)
