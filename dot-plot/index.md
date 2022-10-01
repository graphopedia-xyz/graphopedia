---
title:  dot plot

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

  - title:  Every goal scored in the football World Cup by minute
    author:  The Economist
    link:  https://www.economist.com/node/21603828
    image:  every-goal-scored-in-the-football-world-cup.png

order: 40

---
shows the distribution of individual observations represented as dots at regular intervals. Dots are placed as close to their position along the scale as possible but without overlapping other dots. 

<!--more-->
Dot plots are displayed along an X-axis with an ***interval scale*** and a Y-axis that shows ***frequency***.

There are two types of dot plots: symmetric and asymmetric.

*Asymmetric dot plots* align the dot columns along the X-axis.
*Symmetric dot plots* align the dots along their center on the Y-axis.

Dot plots are similar to [histogram](/histogram), but they are more accurate since the data has not been binned. For this reason, dot plots are considered a better starting point for getting a sense of the distribution of a variable than a histogram.[^wilkinson] 

Dot plots can be thought of as one-dimensional [scatter plots](/scatter-plot) positioned along the X-axis.

Dot plots have a long history, but the first formal description comes from Leland Wilkinson who makes a distinction between the hand-drawn dot plots that placed dots as close as possible to their position on the X-axis and computer-drawn dot plots that simply *bin* dots as in a histogram. [^wilkinson1]

## Alternatives

1. [*Histogram*](/histogram) bin individual observations and represent their quantities with bars of proportional heights.
2. [*Scatter plot*](/scatter-plot) shows individual data points of bivariate (two-variable) data.
3. [*Beeswarm plot*](/strip-plot#beeswarm-plot) shows individual data points along a single axis. It is typically used to compare several distributions.
4. [*Density plot*](/density-plot) shows a density estimate of a distribution as a smooth curve.
5. [*Box plot*](/box-plot) shows an overview of the distribution with median values, 25th, and 75th quartiles, and outliers but does not show actual data points. 


## Sources
[^wilkinson]: Wilkinson, Leland. [*The Grammar of Graphics.*]((https://books.google.com/books?hl=en&lr=&id=_kRX4LoFfGQC)) Springer Science & Business Media, 2005. p.316.
[^wilkinson1]: Wilkinson, Leland. ["Dot plots."](https://www.cs.uic.edu/~wilkinson/Publications/dotplots.pdf) *The American Statistician* 53.3 (1999): 276-281. doi: 10.1080/00031305.1999.10474474 
