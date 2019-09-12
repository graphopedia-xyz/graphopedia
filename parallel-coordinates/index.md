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

is displays multiple variables along vertical axes while tracing the relationship between them using a connecting line. [^wilkinson] Each variable has its axis, and all the axes are parallel to each other. Each axis may have a different scale expressed in its unit of measurement. Values show up as a series of lines connected between all the axes.

<!--more-->

Parallel coordinates plot was first used by American geographer Henry Gannetts in 1880 when he ranked the U.S. states by economic performance such as manufacturing, taxation, and education. [^rumsey]

Parallel coordinates show multivariate data by imitating a multi-dimensional space. Multi-dimensional space is hard to image because normally we see only up to 3 dimensions in graphs. Parallel coordinates plot imitates what multi-dimensional graph would look like by showing multiple axes in parallel. [^inselberg] [^andrews]
Still, the limitation is that the reader can only compare the two adjacent dimensions directly to any value. This limitation does not allow for all possible patterns to emerge. Parallel coordinates plot also has the disadvantage of presenting an overly general view of the data with visually overwhelming complexity. [^wilkinson2]
 

## Alternatives
1. [*Radar chart*](/radar-chart) is in principle a parallel coordinates chart plotted in polar coordinates.
2. [*Alluvial diagram*](/alluvial-diagram) is a combination of parallel coordinates plot and [Sankey chart](/Sankey-chart) for categorical variables represented as clusters linked with flow lines of different thickness. They represent changes in the composition of these clusters over time.


## Sources
[^wilkinson]: Wilkinson, Leland. [*The Grammar of Graphics.*]((https://books.google.com/books?hl=en&lr=&id=_kRX4LoFfGQC)) Springer Science & Business Media, 2005. pp.251-252.
[^rumsey]: Gannett, H., and F. W. Hewes. ["General summary showing the rank of states by ratios 1880."](https://www.davidrumsey.com/luna/servlet/s/jq78gr) *Scribner’s statistical atlas of the United States showing by graphic methods their present condition and their political, social and industrial development*, Hewes FW,(Ed.). United States. Census Office (1883): 151.
[^inselberg]: Inselberg, Alfred, and Bernard Dimsdale. ["Parallel coordinates for visualizing multi-dimensional geometry."](https://doi.org/10.1007/978-4-431-68057-4_3) *Computer Graphics* 1987. Springer, Tokyo, 1987. 25-44. p.69.
[^andrews]: Andrews, David F. ["Plots of high-dimensional data."](https://www.jstor.org/stable/2528964) *Biometrics* (1972): 125-136.
[^wilkinson2]: Wilkinson, Leland, Anushka Anand, and Robert Grossman. ["High-dimensional visual analytics: Interactive exploration guided by pairwise views of point distributions."](https://doi.org/10.1109/TVCG.2006.94) *IEEE Transactions on Visualization and Computer Graphics* 12.6 (2006): 1363-1372. [PDF](https://www.cs.uic.edu/~wilkinson/Publications/sorting.pdf)

