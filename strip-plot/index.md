---
title:  strip plot
  
tags: 
- distribution
- correlation

tools:

examples:
  - title:  2009 Ideb Score of Schools in Brazil
    image:  2009-ideb-score-of-schools-in-brazil.jpg
    author: DoingData, Alberto Cairo
    link:   https://www.doingdata.org/blog/how-to-create-jitter-plot-strip-plot-in-tableau
    note:   This chart is a strip plot (a.k.a. jitter plot). Each dot represents a school. Alberto Cairo used it in his book 'The Truthful Art' to visualize Ideb Score (quality of education) of more than 19,000 schools in Brazil.

  - title:  Population of the densest 200 grid cells in each city
    image:  population-of-the-densest 200-grid-cells-in-us-cities.png
    author: CityLab
    link:   https://www.citylab.com/perspective/2019/07/urban-density-map-city-population-data-geography/591760/


synonyms:
  - jitter plot
  - jittered scatter plot

order: 80

---

is a type of [scatter plot](/scatter-plot) where one variable is categorical.


<!--more-->
A strip plot shows the distribution of values in a category. Typically, categories are plotted on the X-axis and the numeric variable on the Y-axis. 

A single dot represents a data point. The dots only reflect values on the Y-axis. However, strip plots have too many overlapping dots if the values in a distribution are concentrated in one area. The dots can be "jittered" or spread along the X-axis without acquiring new values on the X-axis. The jittered plot does not eliminate the eclipsing of the dots completely, normally using transparency to improve readability. 

Strip plots allow for data-dense visualizations comparing multiple distributions side by side. [^cairo] A [box plot](/box-plot) is sometimes overlaid on top of a strip plot, either showing only the median or the median and the interquartile range.

Jittering is only useful with sparse counts[^wilkinson]. For larger numbers of data points, data can be binned.


## Alternatives
1. [*Dot plot*](/dot-plot) shows the distribution of one variable represented as dots at regular intervals.
2. [*Scatter plot*](/scatter-plot) shows the distribution of two variables along the horizontal and vertical axes.
3. [*Density plot*](/density-plot) shows a smoothed distribution of values over a continuous period.
4. [*Joy plot*](/joy-plot) shows the distribution of a variable for several categories over time or at equal intervals
5. [*Box plot*](/box-plot) shows a summary of data distribution, including the minimum, maximum, upper and lower quartiles, and the median.
6. [*Violin plot*](/violion-plot) is a combination of a box plot and a kernel density plot added on both sides


## Sources
[^cairo]: Cairo, Alberto. [*The truthful art: data, charts, and maps for communication.*](http://www.thefunctionalart.com/p/the-truthful-art-book.html) New Riders, 2016, pp. 153-154.
[^wilkinson]: Wilkinson, Leland. [*The Grammar of Graphics.*]((https://books.google.com/books?hl=en&lr=&id=_kRX4LoFfGQC)) Springer Science & Business Media, 2005. p. 175.
