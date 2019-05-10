---
title:  violin plot

tags:

functions: distribution

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
    
  - title:  Life Expectancy at Birth
    author:  Andy Kriebel (VizWizBI)
    link:  https://public.tableau.com/views/LifeExpectancyAtBirth/7
    image:  life-expectancy-at-birth.png


---
is a combination of a box plot and a kernel density plot. It is a box plot with kernel density plots added to each side. Similar to a box plot, a violin plot shows four types of values. The outer shape represents all possible results with the thickest section representing the mode average. The next layer inside represents the values that occur 95% of the time. The next layer inside represents the values that occur 50% of the time. The central dot represents the median value.

<!--more-->

## Variations
[Split violin](http://seaborn.pydata.org/examples/grouped_violinplots.html?highlight=violin) plot shows two different groups of data on the left and right side of the central axis. This is useful in examples where all data be be divided into two groups, for example male and female.

## Sources
1. [NIST DataPlot. National Institute of Standards and Technology.](https://www.itl.nist.gov/div898/software/dataplot/refman1/auxillar/violplot.htm)
2. [Violin plots: A box plot-density trace synergism](https://search.proquest.com/openview/dcd68eb137d2d6b08aa23f37e34e0b01/1?pq-origsite=gscholar) 
