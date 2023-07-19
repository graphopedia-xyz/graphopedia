---
title:  bubble chart

functions:
  - correlation
  - distribution
  - change over time

related:
  - scatter-plot
  - marimekko-chart

tools:
  - name:   Apple Keynote
    link:   https://support.apple.com/kb/ph16952
 
  - name:   Numbers for Mac
    link:   https://support.apple.com/kb/PH17003
 
  - name:   MS Excel
    link:   https://support.office.com/en-us/article/bubble-and-scatter-charts-in-power-view-bae4a433-afae-46eb-9a28-2fe09abb2a8d
    
  - name:   Gapminder (for animated bubble chart)
    link:   https://www.gapminder.org/tools-offline/

examples:

  - title:  South Korea’s fertility rate falls to a record low
    author:  The Economist
    note:
    link:  https://www.economist.com/graphic-detail/2019/08/30/south-koreas-fertility-rate-falls-to-a-record-low
    image:  fertility-rate-rich-nations.png

  - title:  Jobs Most At Risk From Automation
    author:  The Financial Times
    note:
    link:  https://www.ft.com/content/f64089c6-6681-11e9-9adc-98bf1d35a056
    image:  jobs-at-risk-from-automation.png

  - title:  Money Race and Success
    author: The New York Times
    link:   https://www.nytimes.com/interactive/2016/04/29/upshot/money-race-and-success-how-your-school-district-compares.html?mtrref=undefined&mtrref=www.nytimes.com
    image:  school-district-income-race-success.png

synonyms:
  - bubble plot
  - bubble graph
  
order: 70

---

is a type of [scatter plot](/scatter-plot) that displays three variables by using circles of varying size and their positions on the X and Y-axes. 

<!--more-->

The bubble chart displays the ***independent variable*** on the X-axis and the ***dependent variable*** on the Y-axis. A third variable is represented as ***scaled circles*** where the circle area represents the value. Importantly, it is always the circle area, not diameter or radius. Since the human eye cannot easily estimate the size of a circle, bubble charts are not suitable for communicating exact values.[^cleveland]
The bubble size should not be used to represent the independent or the dependent variable, it can only encode secondary information. [^koponen]

It is possible to show more than three variables by color-coding circle groups and by animating the bubble chart. [^magnuson] Clusters, outliers, and overall trends reveal themselves well on a bubble chart. However, bubble charts are easy to over-plot, reducing the readability.

The advantage of bubble charts is their ability to show trends in large data sets. Similar to a [scatter plot](/scatter-plot), the bubble chart makes the distribution shape and the outliers evident.

A disadvantage of the bubble chart is its lack of means for representing negative values and zero. Like scatter plots, they can become cluttered, in which case data can be grouped with each bubble representing an equal number of data points.

The [first bubble chart](https://en.wikipedia.org/wiki/Pie_chart#/media/File:Playfair_piecharts.jpg) appeared in William Playfair's <cite>Commercial and Political Atlas</cite> published in 1786.  Swedish statistician Hans Rosling famously used an animated bubble chart to explain [macro trends in world population](https://youtu.be/FACK2knC08E?t=452).


## Alternatives

1. [*Marimekko chart*](/marimekko-chart) shows categorical data as rectangles with their widths and lengths proportional to quantities and categories represented as columns. 
2. [*Scatter plot*](/scatter-plot) showing the distribution of two variables represented as dots along the horizontal and vertical axes. The dots can use color or shape to represent an additional variable.
3. [*Proportional area chart*](/proportional-area-chart) a type of one-dimensional chart that uses area of a shape to visualize a single variable without the use of axes. With few data points, a bubble chart can potentially be represented as one or a series of proportional area charts.


## Further reading
- [Bubble chart](https://en.wikipedia.org/wiki/Bubble_chart) article on Wikipedia.

## References
[^cleveland]: Cleveland, William S., and Robert McGill. ["Graphical perception and graphical methods for analyzing scientific data."](http://snoid.sv.vt.edu/~npolys/projects/safas/1695272.pdf) *Science* 229.4716 (1985): 828-833. 
[^koponen]: Koponen, Juuso, and Jonatan Hildén. [*Data visualization handbook.*](https://shop.aalto.fi/p/971-data-visualization-handbook/) Aalto korkeakoulusäätiö, 2019. p. 193
[^magnuson]: Magnuson, Lauren, ed. [*Data visualization: a guide to visual storytelling for libraries.*](https://books.google.com/books?id=wxrMDAAAQBAJ) Rowman & Littlefield, 2016. 

