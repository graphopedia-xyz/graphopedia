---
layout: post

title:  Density Plot

image:
  featured: density-plot.png
  main: change-this.png
  anatomy: change-this.png
  
tags:
  - lorem
  - dolor
  - sit-amet

related:
  - title: Histogram
    link: histogram
    image: histogram.png
  - title: Violin plot
    link: violin-plot
    image: violin-plot.png

tools:
  - name:   R cookbook
    link:   http://www.cookbook-r.com/Graphs/Histogram_and_density_plot/

  - name:   Tableau Sample
    link:   https://www.tableau.com

examples:
  - title:  <cite>Nadal and Federer Two Paths to Greatness</cite> by The Financial Times
    link:   https://ig.ft.com/features/baseline/federer-nadal-different-paths-greatness/

  - title:  <cite>Summer temperatures in the Northern Hemisphere</cite> by The New York Times
    link:   https://www.nytimes.com/interactive/2017/07/28/climate/more-frequent-extreme-summer-heat.html

---

Alternative name: Kernel Density plot. The <dfn>density plot</dfn> shows a smoothed distribution of values. Similar to a histogram, a density plot is suitable for showing continuously changing values. But compared to a histogram, the density plot is better at showing the shape of a distribution because it is not affected by bin size. Density plots can be considered of as plots of smoothed histograms. 

<!--more-->

The smoothness of a density plot is regulated by bandwidth that is analogous to the histogram bin size. The technique for estimating the bandwidth for a density plot is called <dfn>kernel smoothing</dfn>.  If the bandwidth is too small, the density estimate becomes less smooth which results in a visually busy graph. The main trends might become overpowered by the noise. Conversely, if the bandwidth is too large, the local features in the distribution of the data might not be revealed. 

Sources:

1. [NCSS Statistical Software Chapter 154](https://ncss-wpengine.netdna-ssl.com/wp-content/themes/ncss/pdf/Procedures/NCSS/Density_Plots.pdf)
2. [Exploratory data analysis Chapter 1](http://theta.edu.pl/wp-content/uploads/2012/10/exploratorydataanalysis_tukey.pdf)
