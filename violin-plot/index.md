---
title:  violin plot

functions: 
  - distribution

related:
  - box-plot

tools:
  - name:   ggplot2
    link:   https://ggplot2.tidyverse.org/reference/geom_violin.html
  
  - name:   Matplotlib
    link:   https://matplotlib.org/examples/statistics/violinplot_demo.html

  - name:   Seaborn
    link:   http://seaborn.pydata.org/generated/seaborn.violinplot.html?highlight=violin

examples:
  - title:  Boston Marathon Finish Times by Year
    author: Bill Mill
    link:  https://github.com/llimllib/bostonmarathon
    image:  boston-marathon-finishers-by-year.png

  - title:  Welfare Atlas
    author: The Center for Leadership and Values in Society of the University of St.Gallen
    link:   https://www.gemeinwohl.ch/en/atlas
    image:  public-value-atlas.png
    

order: 220

---
is a combination of a [box plot](/box-plot) and a kernel [density plot](/density-plot) added on both sides. Similar to a box plot, a violin plot shows four types of values. The outer shape represents all possible results with the thickest section representing the mode average.

<!--more-->
The violin plot aims to solve the problem of over-generalization in a box plot by showing how the values are distributed using the density plot. In data sets with *multimodal distributions*, those with multiple peaks, box plots would not reveal them. [^hintze]  

Violin plots offer the advantage of comparing both the distributions and the medians across categories. 

Violin plot anatomy is similar to the box plot. The media is the white dot in the middle. The thick bar along the center shows the interquartile range, which is the two middle quartiles. The thin line in the center is the 95% confidence interval, which is the rest of the distribution except the outliers. 

The distribution of all the data points is shown symmetrically as density plots on both sides. The thicker parts mean a higher probability that a data point falls in that range, and thinner sections show a lower probability. The violins in the chart typically have an ordering, often by the median.


[//]: # (TODO: Here is a paper https://peerj.com/preprints/27137v1 )


## Combinations
In principle, any chart that shows a [distribution](/function/distribution) can replace half of a violin in violin plot. Such complementary plots include the [beeswarm plot](/strip-plot#beeswarm-plot), [histogram](/histogram), [jitter plot](/strip-plot), and barcode chart.

[//]: # (TODO: add combinations illustrations for violin plot with beeswarm plot, violin plot with histogram, violin plot with barcode chart)
[//]: # (Combination of violin and jitter plot https://twitter.com/lenkiefer/status/805186350760755200/photo/1 )


## Sources

### Further reading
1. [Violin plot](https://en.wikipedia.org/wiki/Violin_plot) article on Wikipedia.

### References
[^hintze]: Hintze, Jerry L., and Ray D. Nelson. ["Violin plots: a box plot-density trace synergism."](https://doi.org/10.1080/00031305.1998.10480559) *The American Statistician* 52.2 (1998): 181-184. [PDF](https://search.proquest.com/openview/dcd68eb137d2d6b08aa23f37e34e0b01/1)
