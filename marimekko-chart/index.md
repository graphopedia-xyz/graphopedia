---
title:  Marimekko chart
  
functions:

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

order: 140

---

is a type of visualization showing categorical data as rectangles with their widths and lengths proportional to quantities and the categories represented as columns. [^wilkinson]

<!--more-->
Both ***value axes*** of a Marimekko chart have ***percentage scales***. The lengths and widths of all rectangles in a chart equal one hundred percent respectively. ***Categories*** are represented as rectangles the widths and heights of which are proportional to their values along horizontal and vertical scales. 


The Marimekko chart is useful for discovering unusually high or low values and dependencies between variables. Mosaic plots represent contingency tables, a basic statistics tool for showing distributions in a matrix for categorical data.  It uses rectangular tiles sized proportionally to values to show their distributions.[^friendly] 

The Marimekko chart is similar to a stacked [bar chart](/bar-chart), but it adds one more dimension of data through varying column widths. 

Although Marimekko charts can look similar to [treemaps](/tree-map), they are different in that Marimekko charts do not show a hierarchy as treemaps do. A Marimekko chart cannot have one of its rectangles include another. 


The Marimekko chart appeared in 1981 as an adaptation of [histogram](/histogram) for showing two variables.[^hartigan]
The area of a tile is known as the *bin size* which is a concept derived from histograms.

## Alternatives

1. [*Stacked bar chart*](/bar-chart) uses bar length to represent values for a category. In a stacked bar chart, each category contains multiple values.
2. [*Proportional area chart*](/proportional-area-chart) uses proportionally sized shapes without the axes to represent one variable. A Marimekko chart can be redesigned as a series of proportional area charts when the data set is small.

## Sources
[^wilkinson]: Wilkinson, Leland. [*The Grammar of Graphics.*]((https://books.google.com/books?hl=en&lr=&id=_kRX4LoFfGQC)) Springer Science & Business Media, 2005. p. 342 [PDF](https://cds.cern.ch/record/1250322/files/9780387245447_TOC.pdf)
[^friendly]:  Friendly, Michael. ["Mosaic displays for multi-way contingency tables."](https://www.researchgate.net/publication/243765611_Mosaic_Displays_for_Multi-Way_Contingency_Tables) *Journal of the American Statistical Association* 89.425 (1994): 190-200, pp.190-200.
[^hartigan]: Hartigan, John A., and Beat Kleiner. ["A mosaic of television ratings."](https://www.jstor.org/stable/2683556) *The American Statistician* 38.1 (1984): 32-35.



