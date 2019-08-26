---
title: scatter plot

tags:
- distribution
- correlation

functions: correlation

related:
  - bubble-chart

tools:
  - name:   Adobe Illustrator
    link:   https://helpx.adobe.com/illustrator/using/graphs.html

  - name:   PowerPoint
    link:   https://products.office.com/en/powerpoint
  
  - name:   Apple Numbers
    link:   https://support.apple.com/kb/PH17003?locale=en_US&viewlocale=en_US
    

examples:
  - title:  Why biggest is not fastest in the animal kingdom
    author:  The Economist
    link:   https://www.economist.com/graphic-detail/2017/07/26/why-biggest-isnt-fastest-in-the-animal-kingdom
    image:  man-vs-beast-speeds.png

  - title:  Greying of The Nobel Laureates
    author: The Economist
    link:  https://www.economist.com/graphic-detail/2016/10/03/greying-of-the-nobel-laureates
    image:  age-of-nobel-prize-winners.png

  - title:  Birth Month and Disease Incidence
    author:  Nick Tatonetti
    link:  https://www.cuimc.columbia.edu/news/data-scientists-find-connections-between-birth-month-and-health
    image:  birth-month-and-disease-incidence.jpg
    
  - title:  Best in Show - The Ultimate Data Dog
    image:  best-in-show-whats-the-top-data-dog.png
    author: David McCandless
    link:   https://informationisbeautiful.net/visualizations/best-in-show-whats-the-top-data-dog/

  - title:  1,780 Habitable Exoplanets, 2014
    image:  habitable-exoplanets-asof-2014.png
    author: National Geographics
    link:   https://web.archive.org/web/20140822200552/http://news.nationalgeographic.com:80/news/2014/04/140417-exoplanet-interactive/


synonyms:
  - scatter graph
  - scatter chart
  - scattergram
  - scatter diagram

---

is a visualization method for showing the distribution of two variables along the horizontal and vertical axes. Scatter plots are used to show correlation and detect outliers. [^friendly]

<!--more-->
The scatter plot first appeared in the work of English statistician Francis Galton, who also created the concept of correlation in statistics.

Scatter plots are used to show a correlation between two variables because they show the exact distribution of all individual data points. To display a correlation, a graph must have one independent variable and one dependent variable. The independent variable usually appears on the X-axis and the dependent on the Y-axis.  A trendline also called the *line of best fit* can be drawn to emphasize the outliers and identify trends. 
 
Scatter plots are common in scientific publications, making up to 80% of all charts.[^tufte]
 
Since scatter plots display a dot for every data point, overplotting is a common problem. [^carr] The existing solutions include representations of densities, not individual data points, using greyscale or using a symbol, often a hexagon. An example of such a density distribution scatter plot is a hexagonal bin plot.

[//]: # (Todo: Add 3 types of correlation types: direction, form, and strength https://www.westga.edu/academics/research/vrc/assets/docs/scatterplots_and_correlation_notes.pdf)

## Variations

### Multicolor scatter plot
<img src="multi-color-scatterplot.svg" class="f-right-half" /> Color could be used to show different data series in one plot...

### Multi symbol scatter plot
<img src="multi-symbol-scatterplot.svg" class="f-right-half" /> Multiple symbols could be used to show different data series in one plot...

### Radial scatter plot
<img src="radial-scatterplot.svg" class="f-right-half" /> Radial scatter plot is functionally the same except it is set into polar coordinates. This variety of scatter plot is useful for visualizing cyclical or seasonal phenomena. One example below shows the incidence of disease by birth month.

### Hexagonal bin plot
<img src="hexagonal-bin-plot.svg" alt="hexagonal bin plotlot" class="f-right-half" /> Hexagonal bin plot is a scatter plot where individual observations were put into bins. Binning is a process of grouping observations at a set interval, which is the bin size. Each bin is represented as a symbol colored to show the density.


## Sources
[^friendly]: [Friendly, Michael and Daniel J. Denis. “The early origins and development of the scatterplot.” Journal of the history of the behavioral sciences 41 2 (2005): 103-30 .](http://datavis.ca/papers/friendly-scat.pdf)
[^tufte]: Tufte, E. R. (1983). The visual display of quantitative information. Cheshire, CT: Graphics Press.
[^carr]: [Carr, D., Littlefield, R., Nicholson, W., & Littlefield, J. (1987). Scatterplot Matrix Techniques for Large N. Journal of the American Statistical Association, 82(398), 424-436. doi:10.2307/2289444](https://www.jstor.org/stable/2289444)

