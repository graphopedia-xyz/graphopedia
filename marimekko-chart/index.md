---
title:  Marimekko chart
  
tags:
- 

related:
  - tree-map
  - bubble-chart

tools:
  - name:   D3
    link:   https://www.jasondavies.com/mekko/

  - name:   FusionCharts
    link:   https://www.fusioncharts.com/dev/chart-guide/standard-charts/marimekko-chart

examples:
  - title:  Billions of People In Asia Are Exposed to High Levels of Pollution
    author:  The Financial Times
    link:  https://ig.ft.com/india-pollution/
    image:  billions-of-people-in-asia-are-exposed-to-high-levels-of-pollution.png
    
  - title:  How many years we lose to the air we breathe
    author: The Washington Post
    link:   https://www.washingtonpost.com/graphics/2018/national/health-science/lost-years/?noredirect=on&utm_term=.bd1237ceb18d
    image:  years-of-life-lost-to-fine-particle-pollution.png
    
  - title:  How Different Income Groups Spend Money
    author:  Nathan Yau
    link:  https://flowingdata.com/2018/02/08/how-different-income-groups-spend-money
    image:  how-different-income-groups-spend-money.png

synonyms:
  - mosaic plot
  - Marimekko diagram
  - mosaic graph
  - Mekko chart
  - eikosogram

---

is a method for showing categorical data as rectangles where the widths and lengths are proportional to quantities and categories are represented as columns. [^wilkinson]

<!--more-->
The Marimekko chart is useful for discovering unusually high or low values and for discovering dependencies between variables. [^hartigan] Mosaic plots represent contingency tables, a common statistics tool for showing distribution in matrix or table for categorical data.  It uses rectangular tiles that are sized proportionally to values to show their distributions.[^friendly] 

Marimekko charts are similar to a stacked [bar chart](/bar-chart) but they add one more dimension of data through varying column widths. 

Although Marimekko charts can look similar to [tree maps](/tree-map), they are different in that Marimekko charts do not show a hierarchy as tree maps do. A Marimekko chart cannot have one of its rectangles include another. 


The Marimekko chart was introduced in 1981 as an adaptation of [histogram](/histogram) for showing two-variables.[^hartigan]
The area of a tile is known as the *bin size* which is a concept derived from histogram.

## Alternatives

[*Stacked bar chart*](/bar-chart) uses bar length to represent values for a category. In a stacked bar chart each category contains multiple values.


## Sources
[^wilkinson]: [Wilkinson, L. (2005), The Grammar of Graphics(2nd ed.). Statistics and Computing, New York: Springer. p. 342 ](https://cds.cern.ch/record/1250322/files/9780387245447_TOC.pdf)
[^friendly]:  [Friendly M. (1994). Mosaic displays for multi-way contingency tables. Journal of the American Statistical Association, 89, p. 190-200.](https://www.researchgate.net/publication/243765611_Mosaic_Displays_for_Multi-Way_Contingency_Tables)
[^hartigan]: [Hartigan, J. A., and Kleiner, B. (1984). A mosaic of television ratings. The American
 Statistician, 38, p.32-35.](https://www.jstor.org/stable/2683556)



