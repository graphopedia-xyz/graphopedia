---
title:  heatmap

functions:  correlation

related:
  - dendrogram

tools:
  - name:   Plotly
    link:   https://plot.ly/python/heatmaps/
  
  - name:   ZingChart
    link:   https://www.zingchart.com/gallery/chart/#!heatmap-color-rules-tooltips
  
  - name:  Gitools
    link:  http://www.gitools.org/
  
  - name:  HighCharts
    link:  https://www.highcharts.com/demo/heatmap

  - name:  Heatmapper
    link:  http://www.heatmapper.ca/
    
  - name:  Shinyheatmap
    link:  http://shinyheatmap.com/
    



examples:
  - title:  How Popular Is Your Birthday
    author: Matt Stiles
    link:   http://thedailyviz.com/2016/09/17/how-common-is-your-birthday-dailyviz/
    image:  popular-birthdays.png

  - title:  Five Years of Traffic Fatalities
    author: John Nelson
    link:   https://www.flickr.com/photos/idvsolutions/8265288798/sizes/o/in/photostream/
    image:  traffic-fatalities.png

  - title:  Utilization of Squares by Chess Masters
    author: Seth Kadish
    link:   https://66.media.tumblr.com/87f255cd0024b050c7546f0c595eb1d4/tumblr_n21vkezveA1s3dn7vo1_1280.png
    image:  chess-square-use-by masters.png
    
  - title:  Incidence of Measles in the United States
    author:  Roy M Francis
    link:  http://www.roymfrancis.com/a-guide-to-elegant-tiled-heatmaps-in-r-2019/
    image:  incidence-measles-united-states.png
  
  - title:  40 Years of Association of Tennis Players Ranking
    author:  Đinh Bá Đức
    link:  http://ledatageek.blogspot.com/2013/12/the-best-tennis-player-of-atp-era.html
    image:  40-years-of-tennis.png

  - title:  Shanghai Temperatures
    author: 
    link: 
    image:  shanghai-temperatures.jpg
    
  

synonym:
  -heat map
---

is a table in which values in every cell are represented with color. Functionally, heatmaps are best at revealing the lowest and highest values and patterns, and sometimes patterns. Heatmaps represent a single variable (univariate data) by using color that either corresponds exactly to the value or to its range, if the data is grouped. 
<!--more-->
Heatmaps originate from shading matrices that were used as far back as 1873. [^wilkinson]


The rows and columns in a heat map represent either numbers or categories. 
The advantage of using heatmaps is that encoding quantitative data with color requires a very small area which allows for displaying a lot of data within a small space. [^munzer]
As with all information graphics that use color to represent data, the choice of the color scheme is important in a heatmap. The designer can choose between greyscale and color. 
In general, the human eye can differentiate chromatic colors easier than shades of gray; however, there is no obvious ordering of colors that is universally perceived the same way. [^ware] For example, showing red is perceived hotter than orange, but purple may or may not be perceived as hotter than red.
 
 Another issue with colors is their influence on each other - adjacent cells of different can create the perception of a gradient even when it is not there.
 
 Despite its name, *heatmap* normally does not refer to a type of map but a table with color-coded values. Maps that use color coding with a rainbow pattern are also sometimes called heatmaps. But they are not to be confused with [choropleth maps](/choropleth-map) that use a single color per geographic region to represent data.
 
## Variations
Heatmap variations have to do with the orientation and layout of the map as well as adding another type fo chart - the [dedrogram](/dendrogram). A special case of heatmap usage when no relevant data exists for large parts of the matrix as in the tennis example below, produces a chart that does not show the entire matrix. 

1. *Circular heat map* displays the axes along the radius of the circles and its perimeter. This layout is normally used for cyclical events such as climate visualizations.
2. *Spiral heat map* winds the X axis along a spiral. This space-saving layout has the disadvantage of difficulty when labeling the chart.
3. *Cluster heatmap* also called "double dendrograms* [^ncss] is a combination of heatmap and [dendrogram](/dendrogram) showing how the ordering of the cells in the heatmap matrix was obtained, showing one dedrogram for the matrix rows and one for the columns. The cluster heat simultaneously reveals row and column hierarchical cluster structure.
                                                                           
## Sources

[^wilkinson]: ["The History of the Cluster Heatmap" by Leland Wilkinson and Michael Friendly, The American Statistician, May 2009, Vol. 63, No. 2, pp.](https://www.cs.uic.edu/~wilkinson/Publications/heatmap.pdf)

[^munzer]: ["Visualization Analysis and Design" by Tamara Munzner, p.136](https://books.google.com/books?id=NfkYCwAAQBAJ&pg=PT166&lpg=PT166)

[^ware]: [C. Ware, "Color Sequences for Univariate Maps: Theory, Experiments, and Principles" IEEE Computer Graphics and Applications, vol. 8, no.5, 1988, pp. 41–49](https://ccom.unh.edu/sites/default/files/publications/Ware_1988_CGA_Color_sequences_univariate_maps.pdf)

[^ncss]: [NCSS Statistical Sotfware. Chapter 450](https://ncss-wpengine.netdna-ssl.com/wp-content/themes/ncss/pdf/Procedures/NCSS/Clustered_Heat_Maps-Double_Dendrograms.pdf)
