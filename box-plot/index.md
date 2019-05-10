---
title: box plot

functions: distribution

related:
  - violin-plot

tools:

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
    note:   Distribution of page lengths of doctoral dissertations by discipline. The data is sorted by median. Number of records for each discipline is in parentheses.
    

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
  

---

shows a summary of distribution of data from its minimum to its maximum values, the upper and lower quartiles, and the median. The box represents 50% of data points and the whiskers the other 50%. The middle band always represents
the median which means that 50% of data is above the live and the other 50% is below. Outliers are plotted outside the box and whiskers as dots.

<!--more--> 
The box plot was first introduced in 1970 by American Statistician John Tukey [^wickham] who early in his career worked on developing statistical methods for computers at Bell Labs where he invented the term "bit".[^billinger]

The main function of a box plot is generalized comparison of distributions. Since box plots only summarize the distribution, they can only show a generalized comparison of medians, minimums, maximums and quartiles. Box plots can also be used to show variation and uncertainty. 

A single box in a box plot shows a summary of distribution of data by showing the median, the upper and lower quartiles and the maximum and minimum.[^potter]

This generalized view does not show where exactly the data points fall. If it is important to show the exact location all all data points, then a scatter plot is best for a single data series or a bees swarm plot for comparing multiple data series.
 
Box plots are best for comparing minimums, maximums, and the middles (medians) of data series.

Box plots are shown on the X, Y axes, where the X axis can be categorical or numeric. The Y axis is numeric. The median is usually shown as a line or a line with a dot in the middle. The outliers are show as dots. They always fall outside the whiskers of the box since any number that falls between the maximum and minimum is not an outlier.

Tick marks on both axes help a reader locate the corresponding values since box plots tend to be visually complex.

## Variations

### Histplot 
Histplots estimate the distribution of data at the median and the two quartiles. The width of the box plot at these locations is then modified to be proportional to the density estimation. The box shape becomes a polygon. [^potter2] 

### Beanplot 
Bean plots show individual observations as lines while the showing the distribution as area, similar to a density plot.[^kampstra]

### Vase plot 
 Vase plots add estimated densities for every point between the upper and lower quartiles to the histplot. 

### Box-percentile plot
 Box-percentile plots use both sides of the box plot to show the distribution at each point. For each point in the plot, the width of the box is proportional to the percentile of that data value, up to the 50th percentile. After that it switches to being proportional to values outside the percentile. The the plot is symmetrical. The upper quartile, median, and lower quartile are marked with a line. Similarly to a violin plot, the advantages of this plot is that it covers the entire range of data.



## Alternatives
Charts that show distributions are all potential alternatives to a box plot. With few data series, using a histogram ofr a density plot may be possible, otherwise, to compare multiple data sets, the violin plot or the beeswarm plot are better.

1. [*Histogram*](/histogram) shows a estimate of the probability distribution of a continuous variable using discrete values.

2. [*Violin plot*](/violion-plot) displays the density for all data points, not just the middle half.

3. [*Scatter plot*](/scatter-plot) shows distribution by plotting every data point on the X, Y coordinates. The overall shape as well as individual data points are best seen on a scatter plot unlike the box plot that does not show how individual data points are distributed.

4. *Beeswarm Plot* is a one-dimensional scatter plot with closely-packed points that do not overlap[^tud].

## Sources
[^wickham]: [40 Years of Boxplots](http://vita.had.co.nz/papers/boxplots.pdf)
[^billinger]: [John Wilder Tukey by David R. Brillinger, p.200](https://www.ams.org/notices/200202/fea-tukey.pdf)
[^potter]: [Methods for Presenting Statistical Information: The Box Plot, p 97](http://www.sci.utah.edu/~kpotter/publications/potter-2006-MPSI.pdf)
[^potter2]: [Methods for Presenting Statistical Information: The Box Plot by Kristin Potter p. 100](http://www.sci.utah.edu/~kpotter/publications/potter-2006-MPSI.pdf)
[^kampstra]: [Beanplot: A Boxplot Alternative for Visual Comparison of Distributions by Peter Kampstra, p. 4](https://cran.r-project.org/web/packages/beanplot/vignettes/beanplot.pdf)
[^tud][R package by Aron Charles Eklund, Ph.D., Technical University of Denmark, retrieved Apr. 8, 2019](http://www.cbs.dtu.dk/~eklund/beeswarm/)
