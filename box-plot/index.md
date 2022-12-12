---
title: box plot

functions:
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

## Alternatives
Charts that show distributions are all potential alternatives to a box plot. With few data series, using a histogram or a density plot may be possible, otherwise, to compare multiple data series, the violin plot or the beeswarm plot are better.

1. [*Histogram*](/histogram) shows an estimate of the probability distribution of a continuous variable using discrete values.

2. [*Violin plot*](/violin-plot) displays the density for all data points, not just the middle half.

3. [*Scatter plot*](/scatter-plot) shows distribution by plotting every data point on the X, Y coordinates. The overall shape, as well as individual data points, are better displayed on a scatter plot because the box plot only summarizes the distribution.

4. [*Beeswarm Plot*](/scatter-plot/#beeswarm-plot) is a one-dimensional scatter plot with closely-packed points that do not overlap.


## Further reading
1. Potter, Kristin, et al. ["Methods for presenting statistical information: The box plot."]((http://www.sci.utah.edu/~kpotter/publications/potter-2006-MPSI.pdf)) Visualization of large and unstructured data sets 4 (2006): 97-106, p.100.
2. [Box plot](https://en.wikipedia.org/wiki/Box_plot) article on Wikipedia.

## References
[^wickham]: Wickham, Hadley, and Lisa Stryjewski. ["40 years of boxplots."](http://vita.had.co.nz/papers/boxplots.pdf) *Am. Statistician* (2011). [PDF](http://vita.had.co.nz/papers/boxplots.pdf)
