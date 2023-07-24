---
title: bar chart

functions:
  - comparison
  - change over time

visualizationTechniques:
  - techniqueId: AXI
    informationType: quantity
    axisDirection: vertical

  - techniqueId: CON
    informationType: relationship


related:
  - histogram
  - tape-diagram

tools:
  - name:   D3.js
    link:   https://bl.ocks.org/mbostock/3883195

  - name:   Google Charts
    link:   https://developers.google.com/chart/interactive/docs/gallery/barchart

  - name:   Microsoft Excel
    link:   https://office.microsoft.com

  - name:   Apple Numbers
    link:   https://www.apple.com/numbers

  - name:   Google Docs
    link:   https://docs.google.com
    
  - name:   High Charts
    link:   https://www.highcharts.com

  - name:   Adobe Illustrator
    link:   http://www.adobe.com/Illustrator

examples:  
  - title:  The Paintings of Bob Ross
    author:  Walt Hickey
    link:  https://fivethirtyeight.com/features/a-statistical-analysis-of-the-work-of-bob-ross/
    image:  paintings-of-bob-ross.png

  - title:  How Couples Meet
    author: Nathan Yau
    link:   https://flowingdata.com/2019/03/15/shifts-in-how-couples-meet-online-takes-the-top-spot/
    image:  how-couples-meet.jpeg
 
  - title:  Oil Well (Nutrition Facts for Edible Oils)
    author: David McCandless
    link:   https://informationisbeautiful.net/visualizations/oil-well-every-cooking-oil-compared/
    image:  oil-nutrition-facts.png
    
  - title: The most used words for women vs. men
    author: Julia Silge
    link:   https://pudding.cool/2017/08/screen-direction/
    image:  likelihood-of-words-based-on-gender.png

  - title:  World Population Infographic for Popular Science
    author: Ariana Montanez
    link:   http://www.arianamontanez.com/world-population-infographic/
    image:  world-population.jpeg

synonyms:
  - column chart
  - bar graph
  - column graph

order: 10

---

displays the relationship of a category to a numeric variable as the height a rectangle bar.  Each bar represents a single number. Bar charts compare discrete numbers and not continuously changing data.[^harris]

<!--more-->

The bar chart consists of a ***categorical X-axis*** and a ***numeric Y-axis***. The bars represent categories and their heights the values along the Y-axis. 

The ***bar width*** is equal and cannot be used to represent data. Using the width of the bar would transform the bar chart into a [Marimekko Chart](/marimekko-chart). The ***bar distance*** is also equal and not indicative of data values. Bars can be ordered by height or unordered.

The ***baseline*** of a bar chart should always start at zero. Otherwise, the bar length will not be interpreted correctly by the reader. [^yau]

Categories along the X-axis should have a logical ordering which can be numeric ordering intrinsic to the categories, a natural ordering, or ordering based on the data. [^knaflic] Bar charts are often used to compare the change of a variable over time or across categories. This broad application explains the popularity of the bar chart. Functionally, a bar chart is not suitable for showing distributions, medians or means, ratios, correlations or connections, or anything more than a single data point per category. 


William Playfair introduced the bar chart in 1786. Although not popular initially, it has since become the default choice of a chart because of its graphic simplicity and familiarity. *The New York Times* graphics editor Amanda Cox says, "There's a strand of the data viz world that argues that everything could be a bar chart. That's possibly true but also possibly a world without joy." [^beniato] Alternatives to and variations of the bar chart are necessary for large-scale data visualizations.

<!-- from variations -->
Variations of the bar chart regroup the bars, typically to display more data or make the chart more compact. Bars can be grouped, stacked, and re-oriented. Triangles and other figures can substitute the bar shape. However, shapes other than the rectangle are more difficult for the eye to interpret.


## Alternatives

With the bar chart being the ubiquitous default, there is often a need to find an alternative. 

1. [*Isotype diagram*](/isotype-diagram) uses icons to represent a data point as the total length of the row of icons. Isotype chart can help a reader see the semantic meaning of each category in the chart. [^haroz]
2. [*Waterfall chart*](/waterfall-chart) is an alternative to a stacked bar chart. It tracks the change from an initial value through a series of intermediate values to the end value. The first column is the initial value. The last column is a cumulative total.
3. [*Bullet chart*](/bullet-chart) functionally the same as a bar chart, the bullet chart adds a symbol for the target value and a progress bar.
4. [*Slopegraph*](/slopegraph) is an alternative to a stacked bar chart. A slope graph shows the relationship between two sets of categories.

It is worth noting that neither the pie chart nor the bubble, both of which are popular charts, work as functional alternatives to a bar chart.

## Further reading
- [Bar chart](https://en.wikipedia.org/wiki/Bar_chart) article on Wikipedia.

## References
[^harris]: Harris, Robert L. [*Information graphics: A comprehensive illustrated reference.*](https://books.google.com/books?hl=en&lr=&id=qusmDAAAQBAJ) Oxford University Press, 2000. p. 59
[^yau]: Yau, Nathan. ["Bar Chart Baselines Start at Zero"](https://flowingdata.com/2015/08/31/bar-chart-baselines-start-at-zero/) *FlowingData.com. Retrieved from https://flowingdata.com/2015/08/31/bar-chart-baselines-start-at-zero* (2015).
[^knaflic]: Knaflic, Cole Nussbaumer. [*Storytelling with data: A data visualization guide for business professionals.*](https://books.google.com/books?id=IheRCgAAQBAJ) John Wiley & Sons, 2015. pp.58 
[^beniato]: Berinato, S. ["The Power of Visualization's" Aha!" Moments."](https://hbr.org/2013/03/power-of-visualizations-aha-moment) *Harvard Business Review. Retrieved from http://blogs.hbr.org/2013/03/power-of-visualizations-aha-moment* (2013). 
[^haroz]: Haroz, Steve, Robert Kosara, and Steven L. Franconeri. ["Isotype visualization: Working memory, performance, and engagement with pictographs."](https://doi.org/10.1145/2702123.2702275) *Proceedings of the 33rd annual ACM conference on human factors in computing systems.* ACM, 2015. [PDF](http://steveharoz.com/research/isotype/ISOTYPE_Visualization_CHI2015_Haroz_Kosara_Franconeri.pdf)
