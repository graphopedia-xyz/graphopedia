---
title: scatter plot

functions:
  - distribution
  - correlation

visualizationTechniques:
  - techniqueId: AXI
    informationType: quantity
    axisDirection: horizontal

  - techniqueId: AXI
    informationType: quantity
    axisDirection: vertical


related:
  - bubble-chart

tools:
  - name:   Adobe Illustrator
    link:   https://helpx.adobe.com/illustrator/using/graphs.html

  - name:   PowerPoint
    link:   https://products.office.com/en/powerpoint
  
  - name:   Apple Numbers
    link:   https://support.apple.com/kb/PH17003?locale=en_US&viewlocale=en_US

  - name:   DataWrapper (template)
    link:   https://academy.datawrapper.de/article/65-how-to-create-a-scatter-plot

  - name:   FusionCharts (code)
    link:   http://jsfiddle.net/fusioncharts/6deM9
  
  
    
    

examples:
  - title:  Sound Effects - Productivity in Offices
    author: The Economist
    link:  https://www.economist.com/graphic-detail/2019/10/24/why-open-plan-offices-get-a-bad-rap
    image:  noise-level-in-offices-economist.png

  - title:  Greying of The Nobel Laureates
    author: The Economist
    link:  https://www.economist.com/graphic-detail/2016/10/03/greying-of-the-nobel-laureates
    image:  age-of-nobel-prize-winners.png

  - title:  1,780 Habitable Exoplanets, 2014
    image:  habitable-exoplanets-asof-2014.png
    note:   This is an example of one dimensional scatter plot
    author: National Geographics
    link:   https://web.archive.org/web/20140822200552/http://news.nationalgeographic.com:80/news/2014/04/140417-exoplanet-interactive/


synonyms:
  - scatter graph
  - scatter chart
  - scattergram
  - scatter diagram

order: 60

---

is a visualization method for showing the distribution of two variables along the horizontal and vertical axes. Scatter plots are used to show correlation and detect outliers. [^friendly]

<!--more-->
Scatter plots show the relationship of two variables plotted along ***numeric axes***, with the one axis, usually horizontal, showing the independent variable and the other the dependent one. Each ***data point*** is represented with a dot. In plots where the data points form a pattern of correlation, a ***line of best fit*** shows the trend. The data points far outside the direction of the trendline are the ***outliers***.

Scatter plots are used to show a correlation between two variables because they show the exact distribution of all individual data points. To display a correlation, a graph must have one independent variable and one dependent variable. The independent variable usually appears on the X-axis and the dependent on the Y-axis. 
 
Scatter plots are common in scientific publications, making up to 80% of all charts.[^tufte]
 
Since scatter plots display a dot for every data point, overplotting is a common problem. [^carr] The existing solutions include representations of densities, not individual data points, using greyscale or using a symbol, often a hexagon. An example of such a density distribution scatter plot is a hexagonal bin plot.

The scatter plot first appeared in the work of English statistician Francis Galton, who also created the concept of correlation in statistics.

[//]: # (Todo: Add 3 types of correlation types: direction, form, and strength https://www.westga.edu/academics/research/vrc/assets/docs/scatterplots_and_correlation_notes.pdf)

[//]: # (Todo: mention 1 dimensional and 3 dimensional scatter plot)


## Further reading
- [Scatter plot](https://en.wikipedia.org/wiki/Scatter_plot) article on Wikipedia.

## References
[^friendly]: Friendly, Michael, and Daniel Denis. ["The early origins and development of the scatterplot."](https://doi.org/10.1002/jhbs.20078) *Journal of the History of the Behavioral Sciences* 41.2 (2005): 103-130. [PDF](http://datavis.ca/papers/friendly-scat.pdf)
[^tufte]: Tufte, Edward R. [*The visual display of quantitative information.*](https://www.edwardtufte.com/tufte/books_vdqi) Vol. 2. Cheshire, CT: Graphics press, 2001.
[^carr]: Carr, Daniel B., et al. ["Scatterplot matrix techniques for large N."](https://www.jstor.org/stable/2289444) *Journal of the American Statistical Association* 82.398 (1987): 424-436.

