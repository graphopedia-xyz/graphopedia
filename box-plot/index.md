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
  
  - name:   HDR Box Plots in R (tutorial)
    link:   https://pkg.robjhyndman.com/hdrcde/reference/hdr.html

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

order: 210

---

shows a summary of data distribution, including the median, the minimum and maximum, the interquartile range, and the outliers.

<!--more--> 
Box plots are shown on the X, Y-axes, where the X-axis can be categorical or numeric. The Y-axis is numeric. 

Each box plot shows its ***median***, the point in the data dividing the upper 50% of values from the lower 50%. The median is indicated as either a horizontal line or a dot. It is the mean of the two middle values.

The box shape indicates the ***interquartile range*** which includes one quartile immediately above and below the median.

The ***upper quartile***, also called *first quartile*, *Q1*, or *25th percentile*, is a median of the data points *above* the median. 

The ***lower quartile***, also called *third quartile*, *Q3*, or *75th percentile*, is a median of the data points *below* the median.

The T-shaped bars beyond the box are called ***whiskers*** or *fences*. They show the ***minimum*** and ***maximum*** values. The *inner fence* is the minimum value and the *upper fence* is the maximum value.

The ***outliers*** are represented as dots outside the fences. *Mild outliers* are data points 1.5 times higher or lower than interquartile range.  *Extreme outliers* are data points 3 times higher or lower than the interquartile range.

Tick marks on both axes help a reader locate the corresponding values where box plots tend to become visually complex.

Since box plots only summarize a distribution, they do not show the actual shape of distribution as, for example, a [density plot](/density-plot) does.  Many variations of the box plot exist with the purpose of revealing the hidden shape of distribution while keeping the box plot's ability to summarize a distribution.
 
The box plot was introduced in 1970 by John Tukey [^wickham] who also invented the term "bit."


## Variations

### Beanplot 
<img src="bean-plot.svg" alt="bean plot" class="f-right-half" /> Bean plots show individual observations as lines while showing the distribution as area, similar to a [density plot](/density-plot). [^kampstra] Functionally, bean plots are similar to a combination of a [violin plot](/violin-plot) and a [strip plot](/strip-plot).

### Vase plot 
<img src="vase-plot.svg" alt="vase plot" class="f-right-half" /> Vase plots add estimated densities for every point in the interquartile range, making the "box" of the box plot similar to a [density plot](/density-plot). 

### Box-percentile plot
<img src="box-percentile-plot.svg" alt="box-percentile plot" class="f-right-half" /> Box-percentile plots use both sides of the box plot to show the distribution at each point. For each point in the plot, the box width is proportional to the percentile of that data value, up to 50th percentile. After that, it switches to being proportional to values outside the percentile. The plot is symmetrical. The upper quartile, median, and lower quartile are marked with a line. Similarly to a violin plot, the advantages of this plot is that it covers the entire range of data.[^esty]

### Notched box plot
<img src="notched-box-plot.svg" alt="notched box plot" class="f-right-half" /> A notched box plot adds confidence intervals around the median. This allows a reader to visually assess its statistical significance. [^mcgill] The space between the notches represents a 95% confidence interval of the median.

### Letter-value box plot
<img src="letter-value-box-plot.svg" alt="letter-value box plot" class="f-right-half" /> Letter-value box plots address the problem of box plots not showing the tail behavior of the data.  Letter-value plots include more information about the tails by displaying the median and quartiles, which are the first two letter values. Further letter values are displayed as long as they are reliable estimates of their corresponding quantiles. [^hofmann]

### Variable-width box plot
<img src="variable-width-box-plot.svg" alt="variable width box plot" class="f-right-half" /> The variable-width box plot uses the width of the box to show the number of data points that a each box plot represents. [^tukey] The variable-width boxplot can be combined with the notched box plot to represent the median confidence interval for each group.

### Highest density region (HDR) boxplot
<img src="hdr-box-plot.svg" alt="HDR box plot" class="f-right-half" /> The HDR box plot is a combination of a box plot with a density plot that shows the zones of highest density that fall anywhere in the distribution. The HDR boxplot is able to display multi-modality if it appears in the data. [^hyndman]

### Raincloud chart
A raincloud chart combines the box plot with a density distribution chart and a jittered strip plot. [^allen]

## Alternatives
Charts that show distributions are all potential alternatives to a box plot. With few data series, using a histogram or a density plot may be possible, otherwise, to compare multiple data series, the violin plot or the beeswarm plot are better.

1. [*Histogram*](/histogram) shows an estimate of the probability distribution of a continuous variable using discrete values.

2. [*Violin plot*](/violin-plot) displays the density for all data points, not just the middle half.

3. [*Scatter plot*](/scatter-plot) shows distribution by plotting every data point on the X, Y coordinates. The overall shape, as well as individual data points, are better displayed on a scatter plot because the box plot only summarizes the distribution.

4. [*Beeswarm Plot*](/scatter-plot/#beeswarm-plot) is a one-dimensional scatter plot with closely-packed points that do not overlap.


## Sources

### Further Reading
1. Potter, Kristin, et al. ["Methods for presenting statistical information: The box plot."]((http://www.sci.utah.edu/~kpotter/publications/potter-2006-MPSI.pdf)) Visualization of large and unstructured data sets 4 (2006): 97-106, p.100.

### References
[^wickham]: Wickham, Hadley, and Lisa Stryjewski. ["40 years of boxplots."](http://vita.had.co.nz/papers/boxplots.pdf) *Am. Statistician* (2011). [PDF](http://vita.had.co.nz/papers/boxplots.pdf)
[^kampstra]: Kampstra, Peter. ["Beanplot: A boxplot alternative for visual comparison of distributions."](http://dare.ubvu.vu.nl/bitstream/handle/1871/39954/221014.pdf) (2008) p.4. [PDF](http://dare.ubvu.vu.nl/bitstream/handle/1871/39954/221014.pdf)
[^esty]: Esty, Warren W., and Jeffery D. Banfield. ["The box-percentile plot."](http://dx.doi.org/10.18637/jss.v008.i17) *Journal of Statistical Software* 8.17 (2003): 1-14.
[^mcgill]: McGill, Robert, John W. Tukey, and Wayne A. Larsen. ["Variations of box plots."](https://www.tandfonline.com/doi/abs/10.1080/00031305.1978.10479236) *The American Statistician* 32.1 (1978): 12-16.
[^hofmann]: Hofmann, Heike, Hadley Wickham, and Karen Kafadar. ["Value plots: Boxplots for large data."](https://vita.had.co.nz/papers/letter-value-plot.pdf) *Journal of Computational and Graphical Statistics* 26.3 (2017): 469-477.
[^tukey]: Cleveland, William S. *The Collected Works of John W. Tukey: Graphics 1965-1985.* Vol. 5. CRC Press, 1988, p.69. (https://books.google.com/books?id=z_F5Tyt66c0C)
[^hyndman]: Hyndman, Rob J. "Computing and graphing highest density regions." *The American Statistician* 50.2 (1996): 120-126.
[^allen]: Allen, Micah, et al. ["Raincloud plots: a multi-platform tool for robust data visualization."](https://doi.org/10.12688/wellcomeopenres.15191.1) Wellcome open research 4 (2019). (https://doi.org/10.12688/wellcomeopenres.15191.1)
