---
title:  joy plot

tags:
  - distribution
  - correlation

related:
  - histogram
  - violin-plot
  - density plot

tools:
  - name:   R cookbook
    link:   http://www.cookbook-r.com/Graphs/Histogram_and_density_plot/

  - name:   Tableau Sample
    link:   https://www.tableau.com

examples:
  - title:  Peak Time of Day For Sports and Leisure
    author: Henrik Lindberg
    link:   https://github.com/halhen/viz-pub/blob/master/sports-time-of-day/out.png
    image:  peak-time-of-day-for-sports-and-leisure.jpg

  - title:  Politics At Elite Law Schools
    author: Allison McCann
    link:   https://fivethirtyeight.com/features/the-most-conservative-and-most-liberal-elite-law-schools/
    image:  politics-at-elite-law-schools.png

  - title:  Religious leaders’ ages
    author: The New York Times
    link:   https://www.nytimes.com/interactive/2017/06/12/upshot/the-politics-of-americas-religious-leaders.html?mtrref=luisdva.github.io
    image:  religious-leaders-age.png
  
  - title:  Comparing weekly pedestrian activity
    author: Morphocode
    link:   https://morphocode.com/location-time-urban-data-visualization/?utm_source=mailpoet&utm_medium=email&utm_campaign=visualizing+time
    image:  comparing-pedestrian-activity.png
 
  - title:  Population Lines
    author: James Cheshire
    link:   http://spatial.ly/2014/08/population-lines/
    image:  population-lines.jpg
  
  

synonyms:
  - ridgeline plot
  - ridgeplot

---
shows the distribution of a numeric value for several categories over time or at equal intervals. Joy plots are used to compare distributions. 

<!--more-->
The joy plot uses [density distributions](/density-plot) to compare several categories. The time is displayed along the X-axis and the Y-axis shows categories. Density plots are staggered along the Y-axis. There is no separate axis for the densities in each plot. For this reason, the joy plot is best used to show general trends and patterns rather than communicate specific values. 

The density plots partially overlap vertically. This feature of the chart allows for higher data density - displaying more data in a limited space. The consequence of this is that some places the density plots may overlap completely hiding the smaller values.

In theory, joy plots can be made from [histograms](/histogram), another common way to show distributions but since the bars would overlap vertically, it is not recommended.[^wilke]

##Variations

### Horizon plot
Horizon plots show distribution graphs with staggered along the Y-axis while showing only a certain band of the graph. The visible part of the graph is chosen such that it is sufficient to reveal the overall pattern.

## Sources
[^wilke]: Wilke, Claus O. [Fundamentals of Data Visualization: A Primer on Making Informative and Compelling Figures.](https://books.google.com/books?id=WmmNDwAAQBAJ) O'Reilly Media, 2019. p. 89
