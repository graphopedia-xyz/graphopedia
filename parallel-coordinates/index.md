---
title:  parallel coordinates
  
tags:
- distribution

related:
  - alluvial-diagram

tools:
  - name:   D3
    link:   https://syntagmatic.github.io/parallel-coordinates/

  - name:   Plotly
    link:   https://plot.ly/r/parallel-coordinates-plot/
  
  - name:  Protovis
    link:  http://mbostock.github.io/protovis/ex/cars.html

examples:
  - title:  Nutrient Contents
    author: Kai Chang
    link:   http://bl.ocks.org/syntagmatic/raw/3150059/
    image:  nutrient-content.png
    
  - title:  Chinese Investment in World's Largest Ports
    author: The Financial Times
    link:  https://ig.ft.com/sites/china-ports/
    image:  chinese-investment-in-worlds-largest-ports.png

  - title:  Women's Heptathlon Rio 2016
    author: The Guardian
    link:   https://www.theguardian.com/sport/ng-interactive/2016/aug/14/how-nafissatou-thiam-beat-the-odds-to-claim-the-heptathlon-gold-in-rio
    image:  how-nafissatou-thiam-beat-the-odds-to-claim-heptathlon-gold.png

  - title:  The Most Valuable Brands
    author: Valerio Pellegrini
    link:   https://www.behance.net/gallery/27306035/100-MOST-VALUABLE-BRANDS-201015-Corriere-della-Sera
    image:  most-valuable-brands.jpg
  
  - title:  Indicators of Slavery of Each EU Country
    author: Valerio Pellegrini
    link:   http://www.studentshow.com/gallery/15893753/WIRED-ITA-Un-Mondo-di-Schiavi
    image:  indicators-of-slavery-eu.jpg

---

is displays multiple variables along vertical axes while tracing the relationship between them using a connecting line. [^wilkinson] Each variable has its own axis and all the axes are parallel to each other. Each axis may have a different scale expressed in a different unit of measurement. Values are displayed as a series of lines that are connected between all the axes.

<!--more-->

Parallel coordinates plot was first used by American geographer Henry Gannetts in 1880 when he ranked the U.S. states by economic performance such as manufacturing, taxation, and education. [^rumsey]

Parallel coordinates shows multivariate data by imitating a multi-dimensional space. Multi-dimensional space is hard to image. Normally we see up to 3 dimensions in graphs. Parallel coordinates plot imitates what multi-dimensional graph would look like by showing multiple axes in parallel. [^inselberg] [^andrews]
Still, the limitation is that the reader can only compare a maximum of two other dimensions directly to any value. This does not allow for all possible patterns to emerge. Parallel coordinates plot also has the disadvantage of presenting overly general view of the data with visually overwhelming complexity. [^wilkinson2]
 

## Alternatives
1. [*Radar chart*](/radar-chart) is in principle a parallel coordinates chart plotted in polar coordinates.
2. [*Alluvial diagram*](/alluvial-diagram) is a combination of parallel coordinates plot and [Sankey chart](/Sankey-chart) for categorical variables that are represented as clusters linked with flow lines of different thickness. They represent changes in the composition of these clusters over time.


## Sources
[^wilkinson]: [Wilkinson, L., 2005. The Grammar of Graphics, Second Edition. Springer. pp.251-252](https://www.cs.uic.edu/~wilkinson/TheGrammarOfGraphics/GOG.html)
[^rumsey]: ["General Summary, Showing the Rank of States, by Ratios, 1880" by Henry Gannetts In: The David Rumsey Collection](https://www.davidrumsey.com/luna/servlet/s/jq78gr)
[^inselberg]: [Inselberg A., Dimsdale B. (1987) Parallel Coordinates for Visualizing Multi-Dimensional Geometry. In: Kunii T.L. (eds) Computer Graphics 1987. Springer, Tokyo p.69](https://doi.org/10.1007/978-4-431-68057-4_3)
[^andrews]: [Andrews, D. (1972). Plots of High-Dimensional Data. Biometrics, 28(1), 125-136. doi:10.2307/2528964](https://www.jstor.org/stable/2528964)
[^wilkinson2]: [ L. Wilkinson, A. Anand, and R. Grossman. High-dimensional visual analytics: Interactive exploration guided by pairwise views of point distributions. Visualization and Computer Graphics, IEEE Transactions on, 12(6):1363–1372, 2006.](https://www.cs.uic.edu/~wilkinson/Publications/sorting.pdf)

