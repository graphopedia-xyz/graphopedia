---
title: box plot

tags:
  - distribution
  
related:
  - violin-plot

tools:
  - name:  BoxPlotR
    link:  http://shiny.chemgrid.org/boxplotr/
  
  - name:   D3.js
    link:   https://observablehq.com/@d3/box-plot

  - name:   MatPlotLib
    link:   https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.axes.Axes.boxplot.html
    
  - name:   Notched Boxplots
    link:   https://wessa.net/rwasp_notchedbox1.wasp

examples:
  - title:  Age Distribution of Olympic Athletes By Sport and Gender
    author:  Gregory Matthews
    link:  https://statsinthewild.files.wordpress.com/2012/07/screen-shot-2012-07-09-at-11-49-59-am.png
    image:  olympic-athlete-age.png
  
  - title:  Perceptions of Probability
    author: Zoni Nation
    link:   https://github.com/zonination/perceptions
    image:  perceptions-of-probability.png

  - title:  Ranking The Ivies
    author: The Washington Post
    link:   https://www.washingtonpost.com/news/wonk/wp/2015/09/14/this-chart-shows-why-parents-push-their-kids-so-hard-to-get-into-ivy-league-schools
    image:  ivy-league-graduate-salaries.png

  - title:  Page Lengths of Doctoral Dissertations by Major
    author: Marcus
    link:   https://beckmw.wordpress.com/2014/07/15/average-dissertation-and-thesis-length-take-two
    image:  distribution-of-number-of dissertation-pages-by-discipline.png
    note:   Distribution of page lengths of doctoral dissertations by discipline. The data is sorted by the median. The number of records for each discipline is in parentheses.
    

  - title:  Median Ages of Females With The 25 Most Common Names
    author: Nate Silver and Allison McCann
    link:   https://fivethirtyeight.com/features/how-to-tell-someones-age-when-all-you-know-is-her-name/
    image:  median-ages-of-females.png
  
  - title:  When Presidential Candidacy Is Announced
    author: Ritchie King
    link:   https://fivethirtyeight.com/features/how-to-tell-someones-age-when-all-you-know-is-her-name/
    image:  when-presidential-candidacy-is-announced.png
    
synonyms:
  - box and whisker plot
  - box and whisker chart
  - Tukey's box plot
  - schematic plot
  - quantile plot
  

---

shows a summary of data distribution, including the minimum, maximum, upper and lower quartiles, and the median.

<!--more--> 

A box plot displays a summary of data distribution by showing the median, the upper and lower quartiles, the maximum and minimum, and the outliers.[^potter] Since box plots only summarize the distribution, they do not show the actual shape of distribution as, for example, a [histogram](/histogram) does.
 
Box plots are best fit for comparing the minimums, maximums, and the medians across multiple data series.

Box plots are shown on the X, Y-axes, where the X-axis can be categorical or numeric. The Y-axis is numeric. The combination of the box and whiskers represents the distribution of all data points except the outliers. The box shows the two quartiles in the middle, also called the interquartile range. The middle line is the median, which is the value separating the upper and lower halves of the data. The dots outside the whiskers represent the outliers.

Tick marks on both axes help a reader locate the corresponding values since box plots tend to be visually complex.

The box plot was introduced in 1970 by John Tukey [^wickham] who also invented the term "bit."


## Variations

### Beanplot 
<img src="bean-plot.svg" alt="bean plot" class="f-right-half" /> Bean plots show individual observations as lines while showing the distribution as area, similar to a [density plot](/density-plot). [^kampstra] Functionally, bean plots are similar to a combination of a [violin plot](/violin-plot) and a [strip plot](/strip-plot).

### Vase plot 
<img src="vase-plot.svg" alt="vase plot" class="f-right-half" /> Vase plots add estimated densities for every point between the upper and lower quartiles to the histplot. 

### Box-percentile plot
<img src="box-percentile-plot.svg" alt="box-percentile plot" class="f-right-half" /> Box-percentile plots use both sides of the box plot to show the distribution at each point. For each point in the plot, the box width is proportional to the percentile of that data value, up to 50th percentile. After that, it switches to being proportional to values outside the percentile. The plot is symmetrical. The upper quartile, median, and lower quartile are marked with a line. Similarly to a violin plot, the advantages of this plot is that it covers the entire range of data.[^esty]

### Notched box plot
<img src="notched-box-plot.svg" alt="notched box plot" class="f-right-half" /> A notched box plot adds confidence intervals around the median. This allows a reader to visually assess its statistical significance. [^mcgill] The space between the notches represents a 95% confidence interval of the median.


### Letter-value box plot
<img src="letter-value-box-plot.svg" alt="letter-value box plot" class="f-right-half" /> Letter-value box plots address the problem of box plots not showing the tail behavior of the data.  Letter-value plots include more information about the tails by displaying the median and quartiles, which are the first two letter values. Further letter values are displayed as long as they are reliable estimates of their corresponding quantiles.
[^hofmann]

### Variable width box plot
<img src="variable-width-box-plot.svg" alt="variable width box plot" class="f-right-half" /> Uses the width of the box to represent ...
<!-- @anna rewrite this -->

### HDR box plot
<img src="hdr-box-plot.svg" alt="HDR box plot" class="f-right-half" /> HDR Box Plot, or the *highest density region* (HDR) boxplot (Hyndman, 1996) is a compromise between a boxplot and a density boxplot.
<!-- @anna rewrite this, copy-pasted from paper -->


## Alternatives
Charts that show distributions are all potential alternatives to a box plot. With few data series, using a histogram of a density plot may be possible, otherwise, to compare multiple data sets, the violin plot or the beeswarm plot are better.

1. [*Histogram*](/histogram) shows an estimate of the probability distribution of a continuous variable using discrete values.

2. [*Violin plot*](/violin-plot) displays the density for all data points, not just the middle half.

3. [*Scatter plot*](/scatter-plot) shows distribution by plotting every data point on the X, Y coordinates. The overall shape, as well as individual data points, are better displayed on a scatter plot because the box plot only summarizes the distribution.

4. [*Beeswarm Plot*](/scatter-plot/#beeswarm-plot) is a one-dimensional scatter plot with closely-packed points that do not overlap.

## Sources
[^wickham]: Wickham, Hadley, and Lisa Stryjewski. ["40 years of boxplots."](http://vita.had.co.nz/papers/boxplots.pdf) Am. Statistician (2011). [PDF](http://vita.had.co.nz/papers/boxplots.pdf)
[^potter]: Potter, Kristin, et al. ["Methods for presenting statistical information: The box plot."]((http://www.sci.utah.edu/~kpotter/publications/potter-2006-MPSI.pdf)) Visualization of large and unstructured data sets 4 (2006): 97-106, p.97.
[^potter2]: Potter, p.100.
[^kampstra]: Kampstra, Peter. ["Beanplot: A boxplot alternative for visual comparison of distributions."](http://dare.ubvu.vu.nl/bitstream/handle/1871/39954/221014.pdf) (2008) p.4. [PDF](http://dare.ubvu.vu.nl/bitstream/handle/1871/39954/221014.pdf)
[^esty]: Esty, Warren W., and Jeffery D. Banfield. ["The box-percentile plot."](http://dx.doi.org/10.18637/jss.v008.i17) Journal of Statistical Software 8.17 (2003): 1-14.
[^hofmann]: Hofmann, Heike, Hadley Wickham, and Karen Kafadar. ["Value plots: Boxplots for large data."](https://vita.had.co.nz/papers/letter-value-plot.pdf) Journal of Computational and Graphical Statistics 26.3 (2017): 469-477.
[^mcgill]: McGill, Robert, John W. Tukey, and Wayne A. Larsen. ["Variations of box plots."](https://www.tandfonline.com/doi/abs/10.1080/00031305.1978.10479236) The American Statistician 32.1 (1978): 12-16.
