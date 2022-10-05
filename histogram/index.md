---
title:  histogram

functions: 
  - distribution

related:
  - bar-chart

tools:
  - name:   D3.js
    link:   https://bl.ocks.org/mbostock/3883195

  - name:   Protovis
    link:   http://mbostock.github.io/protovis/ex/histogram.html

  - name:   Google Charts
    link:   https://developers.google.com/chart/

  - name:   Microsoft Excel
    link:   https://office.microsoft.com

  - name:   Apple Numbers
    link:   https://www.apple.com/numbers

  - name:   Google Docs
    link:   https://docs.google.com

  - name:   High Charts
    link:   https://www.highcharts.com

  - name:   R
    link:   http://www.r-graph-gallery.com/83-histogram-with-colored-tail/

examples:
  - title:  Boston Marathon Finishers By Age and Gender
    author: Bill Mill
    link:  https://github.com/llimllib/bostonmarathon
    image:  boston-marathon-finishers.png
    note:  This comparative histogram shows us that the older finishers are male, or it could be that older women do not even enter the race.
 
  - title:  Distribution of Marathon Finishing Times
    author: The New York Times
    link:  https://www.nytimes.com/2014/04/23/upshot/what-good-marathons-and-bad-investments-have-in-common.html?_r=0
    image:  marathon-result-motivation.png
    note:  The finishing times plotted here seem to follow a pattern - there is a drop in people finishing after every round number.
 
  - title:  Age Distribution of American Boys Named Joseph
    author: FiveThirtyEight
    link:  https://fivethirtyeight.com/features/how-to-tell-someones-age-when-all-you-know-is-her-name
    image:  age-distribution-of-american-boys-named-joseph.png
    note:  The histogram shows the age distributions of all American men named Joseph who were alive in 2014. Most alive Josephs were 37 years old. Above the histogram, a line chart shows how many Josephs were born each year, with a peak in 1914.
  
  - title:  Age Distribution of American Girls Named Anna
    author: FiveThirtyEight
    link:  https://fivethirtyeight.com/features/how-to-tell-someones-age-when-all-you-know-is-her-name
    image:  age-of-girls-named-anna.png
    note:  The histogram shows the age distributions of all American women named Anna, who were alive in 2014. (Anna happens to be an extraordinarily enduring name, with about a quarter of Annas being under age 14 and a quarter over the age 62 in 2014. You can see this in the box plot examples.) Most alive Annas were 31 years old. Above the histogram, a line chart shows how many Annas were born a year.
    

    
  - title:  The Blue of 2015 Beijing Sky
    author: Yasai Wang
    link:   https://www.behance.net/gallery/35401355/The-Blue-of-2015-Beijing-Sky
    image:  blue-sky-beijing-2015.jpg
    note:  This chart plots the level of air pollution (PM 2.5) against the color of the sky. The circular layout here creates the feeling of the cyclical nature of the calendar, but it also makes the bars of the histogram more difficult to compare. Still, we can see on a macro level that winter sees higher levels of pollution.

  - title:  Searching for Peace in Old Age
    author: Hyperakt
    link:   http://www.hyperakt.com/items/corriere-infographic/
    image:  what-happens-as-world-ages.jpg
    note:  Comparative histogram of age distribution now and in 2050 across all parts of the world.

order: 30

---

is a graphic representation of the distribution of one continuous variable.  The height of each bar shows the frequency of observations in a bin, which is the interval at which the data is split.

<!--more-->
Histograms are built using raw data that is split into ***intervals***, called *bins*. The ***bar height*** shows ***frequency*** - the number of data points that appear in a bin. 

The bin size is the tool that groups data points such that they could be represented as a single bar. The larger the bin size, the less accurate the value of each bar, at the same time, the more normal the distribution as a whole. Conversely, smaller bin size leads to more accurate individual bars and more irregular overall shape of the graph. 

Bin size is represented as the width of bars of a histogram. If the bins are set to equal intervals, then all the bars are the same width. If the bin size varies, it is the *area*, not the height that will show frequency.

Histograms are the most common way of showing distributions because they reveal their shape and a possible skewness.

Even though a histogram is visually similar to a [bar chart](/bar-chart), functionally it is different. Unlike a bar chart, a histogram shows the distribution of only one variable, whereas a bar chart relates two. In a histogram, data points are grouped by setting bin size, while in a bar chart data points are already grouped in categories.[^wilkinson] 

Histograms are similar to the [density plot](/density-plot) in that both show distributions. The concept of bins is related to the density plot's bandwidth. But unlike a density plot, a histogram shows the distribution discretely, not continuously. [^tutorial]

Histograms were introduced by English mathematician Karl Pearson in 1895.[^rufilanchas] Pearson proposed the histogram as a 'time-gram' to show change over time.[^flood]


## Alternatives
The alternatives to the histogram, the chart synonymous with distribution, are the other charts that show distribution.
The general trade-offs among distribution-displaying charts are that the more individual data points they display, the less the overall pattern is clear, and vice versa. 

1. [*Dot plot*](/dot-plot) shows individual data points for each point in time plotted on the X-axis. Functionally, it is similar to the histogram. Visually, the dots may be more difficult to read and compare than the bars of a histogram.
2. [*Scatter plot*](/scatter-plot) shows individual data points of bivariate (two-variable) data.
3. [*Beeswarm plot*](/scatter-plot#beeswarm-plot) shows individual data points along a single axis. Normally, it is used to compare several distributions.
4. [*Density plot*](/density-plot) shows a density estimate of a distribution as a smooth curve.
5. [*Violin plot*](/violin-plot) shows a double-sided density estimate of the distribution, comparing several such distributions.
6. *Barcode chart* shows a distribution using lines that represent individual points along a single axis. Bar code chart compares multiple distributions within compact space.


## Sources

### Further reading
1. [Histogram](https://en.wikipedia.org/wiki/Histogram) article on Wikipedia.

### References
[^wilkinson]:  Wilkinson, Leland. [*The Grammar of Graphics.*]((https://books.google.com/books?hl=en&lr=&id=_kRX4LoFfGQC)) Springer Science & Business Media, 2005. p.49.
[^tutorial]: To see how raw data is transformed into a histogram and how the bin size affects the shape of the histogram, see this [interactive visualization on how histograms work](http://tinlizzie.org/histograms)
[^rufilanchas]: Rufilanchas, Daniel Riaño. "On the origin of Karl Pearson’s term “histogram”." *Estadística española* 59.192 (2017): 29-35.
[^flood]: Flood, Raymond, Adrian Rice, and Robin Wilson, eds. [*Mathematics in Victorian Britain.*](https://books.google.com/books?id=l5YiddUUfl4C) Oxford University Press, 2011. p.291. 



