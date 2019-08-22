---
title:  density plot

tags:
  - distribution

related:
  - histogram
  - violin-plot

tools:
  - name:   R cookbook
    link:   http://www.cookbook-r.com/Graphs/Histogram_and_density_plot/

  - name:   Tableau Sample
    link:   https://www.tableau.com

examples:
  - title:  When Are People Working?
    author: Quoctrung Bui for NPR
    link:   https://www.npr.org/sections/money/2014/08/27/343415569/whos-in-the-office-the-american-workday-in-one-graph?/templates/story/story_php=&t=1557322302795
    image:  when-are-people-working.png

  - title:  Summer Temperatures in The Northern Hemisphere
    author: The New York Times
    link:   https://www.nytimes.com/interactive/2017/07/28/climate/more-frequent-extreme-summer-heat.html
    image:  summers-getting-hotter.png
 
  - title:  Surprising Variety in Aging
    author: Truth and Beauty
    link:   http://truth-and-beauty.net/projects/mpg-graphics
    image:  aging-fertility-mortality.png

  - title:  Religious leaders’ ages
    author: The New York Times
    link:   https://www.nytimes.com/interactive/2017/06/12/upshot/the-politics-of-americas-religious-leaders.html?mtrref=luisdva.github.io
    image:  religious-leaders-age.png
  
  - title:  Comparing weekly pedestrian activity
    author: Morphocode
    link:   https://morphocode.com/location-time-urban-data-visualization/?utm_source=mailpoet&utm_medium=email&utm_campaign=visualizing+time
    image:  comparing-pedestrian-activity.png
 


  
  - title:  Tide Predictions
    author: Joan Ang
    link:   http://www.joanangdesign.com/
    image:  tide-prediction.jpg
  
  - title:  Population Lines
    author: James Cheshire
    link:   http://spatial.ly/2014/08/population-lines/
    image:  population-lines.jpg
  
  

synonyms:
  - kernel density plot
  - kernel density estimates
  - density trace

---

shows a smoothed distribution of values over a continuous period. Similar to a [histogram](/histogram), a density plot is suitable for showing continuously changing values. But compared to a histogram, the density plot is better at showing the shape of distribution because it is not affected by bin size. Density plots can be considered as plots of smoothed histograms. 

<!--more-->

Density plots produce a smooth curve *estimating* the distribution function of a continuous
variable from a set of values that are not absolutely precise.

Density plots are what an averaged and smoothed histogram would look like with the gaps between bars being "filled" with estimated values.

The smoothness of a density plot is regulated by the bandwidth that is analogous to the histogram bin size. The technique for estimating the bandwidth for a density plot is called *kernel smoothing*.  If the bandwidth is too small, the density estimate becomes less smooth which results in a visually busy graph. The main trends might become overpowered by the noise. Conversely, if the bandwidth is too large, the local features in the distribution of the data might not be revealed. 



## Alternatives

1. [*Histogram*](/histogram) shows the distribution of one continuous variable represented as the height of bars. Histograms are built using raw data that is split into intervals, called bins. 
2. [*Violin plot*](/violin-plot) is a combination of a [box plot](/box-plot) and [density plot](/density-plot).
3. [*Joy plot*](/joy-plot) also known as a *ridgeplot* is a series of partially overlapping density plots positioned on two value axes.
 

## Sources

[^tukey]:[Tukey, J. W. (1977). Exploratory data analysis. Reading, PA: Addison-Wesley.](http://theta.edu.pl/wp-content/uploads/2012/10/exploratorydataanalysis_tukey.pdf)
