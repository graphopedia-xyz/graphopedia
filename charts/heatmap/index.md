---
title:  heatmap

functions:
  - correlation
  - network of relationships

visualizationTechniques:
  - techniqueId: REP
    informationType: quantity

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
  - title:  Incidence of Measles in the United States
    author:  Roy M Francis
    link:  http://www.roymfrancis.com/a-guide-to-elegant-tiled-heatmaps-in-r-2019/
    image:  incidence-measles-united-states.png

  - title:  How Popular Is Your Birthday
    author: Matt Stiles
    link:   http://thedailyviz.com/2016/09/17/how-common-is-your-birthday-dailyviz/
    image:  popular-birthdays.png

  - title:  Five Years of Traffic Fatalities
    author: John Nelson
    link:   https://www.flickr.com/photos/idvsolutions/8265288798/sizes/o/in/photostream/
    image:  traffic-fatalities.png

  - title:  Numbers in Reddit Usernames
    image:  reddit-usernames.png
    link:   https://www.reddit.com/r/dataisbeautiful/comments/7sewjx/heatmap_of_numbers_found_at_the_end_of_reddit/

  - title:  Utilization of Squares by Chess Masters
    author: Seth Kadish
    link:   https://66.media.tumblr.com/87f255cd0024b050c7546f0c595eb1d4/tumblr_n21vkezveA1s3dn7vo1_1280.png
    image:  chess-square-use-by masters.png
  
  - title:  40 Years of Association of Tennis Players Ranking
    author:  Đinh Bá Đức
    link:  http://ledatageek.blogspot.com/2013/12/the-best-tennis-player-of-atp-era.html
    image:  40-years-of-tennis.png   

synonyms:
  - heat map

order: 170

---

is a table in which values of each cell are represented with a color. 
<!--more-->
The ***rows*** and ***columns*** in a heat map represent either numeric values or categories. Each ***cell*** is filled with a color from the ***color value scale***. A color either corresponds to a single value or to a range of values where the data is grouped.

Functionally, heatmaps are best at revealing the lowest and highest values as well as general patterns. 

The advantage of using heatmaps is that encoding quantitative data with color requires a very small area which allows for a data-dense display within a small space. [^munzer]

As with all information graphics that use color to represent data, the choice of the color scheme is important in a heatmap. The designer can choose between greyscale and color. 

In general, the human eye can differentiate chromatic colors easier than shades of gray. Still, even with chromatic color schemes, an obvious ordering of colors perceived the same way universally does not exist. [^ware] For example, in the context of temperatures, red is perceived as being hotter than orange, but purple may or may not be perceived as hotter than red.
 
Another issue with colors is their influence on each other - adjacent cells of different colors can produce the perception of a gradient even when it is not there.
 
Despite its name, a heatmap normally does not refer to a type of map but a table with color-coded values. Maps that use color coding with a rainbow pattern are also sometimes called heatmaps. But they are not to be confused with [choropleth maps](/choropleth-map) that use a single color per geographic region to represent data.

Heatmaps originate from shading matrices that were used as far back as 1873. [^wilkinson]

<!-- from variations -->
Heatmap variations have to do with the orientation and layout of the map. The addition of a [dendrogram](/dendrogram) produces a heatmap that also shows the hierarchy of the values.

                                                                       
## Further reading
- [Heat map](https://en.wikipedia.org/wiki/Heat_map) article on Wikipedia.

## References
[^munzer]: Munzner, Tamara ["Visualization Analysis and Design"](https://books.google.com/books?id=NfkYCwAAQBAJ&pg=PT166&lpg=PT166) CRC Press, 2014, p.136.
[^ware]: Ware, Colin. ["Color sequences for univariate maps: Theory, experiments and principles."](https://ccom.unh.edu/sites/default/files/publications/Ware_1988_CGA_Color_sequences_univariate_maps.pdf) *IEEE Computer Graphics and Applications* 8.5 (1988): 41-49.
[^wilkinson]: Wilkinson, Leland, and Michael Friendly. "The history of the cluster heat map." *The American Statistician* 63.2 (2009): 179-184. [PDF](https://www.cs.uic.edu/~wilkinson/Publications/heatmap.pdf)
