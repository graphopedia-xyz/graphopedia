---
title:  joy plot

functions:
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

  - title:  Religious leaders' ages
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

order: 270

---
shows the distribution of a numeric value for several categories over time or at equal intervals. Joy plots are used to compare distributions. 

<!--more-->
The joy plot uses multiple [***density plots***](/density-plot) to compare several ***categories***. The density plots are positioned along the ***time or interval axis***. Density plots are staggered along the categorical axis. There is no separate axis for the densities in each density plot. For this reason, the joy plot is best used to show general trends and patterns rather than communicate specific values. 

The density plots partially overlap vertically. This feature of the chart allows for higher data density. The consequence of this is that some places the density plots may overlap completely hiding the smaller values.

In theory, joy plots can be made from [histograms](/histogram), another common way to show distributions, but since the bars would overlap vertically, it is not recommended.[^wilke]

## References
[^wilke]: Wilke, Claus O. [*Fundamentals of Data Visualization: A Primer on Making Informative and Compelling Figures.*](https://books.google.com/books?id=WmmNDwAAQBAJ) O'Reilly Media, 2019. p. 89.
