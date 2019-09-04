---
title: bar chart
  
tags:
- comparison
- change over time

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

  - title: The Space Race Is Dominated By New Contenders
    author: The Economist
    link: https://www.economist.com/graphic-detail/2018/10/18/the-space-race-is-dominated-by-new-contenders
    image: space-race.png

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

Bar charts are often used to compare the change of a variable over time or across categories. This broad application explains the popularity of the bar chart. Functionally, a bar chart is not suitable for showing distributions, medians or means, ratios, correlations or connections, or anything more than a single data point per category. 


The baseline of a bar chart should always start at zero. Otherwise, the bar length will not be interpreted correctly by the reader. [^yau]

The bar width is equal and cannot be used to represent data. Using the width of the bar would transform the bar chart into a [Marimekko Chart](/marimekko-chart). The distance between bars is also equal and not indicative of data values. Bars can be ordered by height or unordered.



William Playfair introduced the bar chart in 1786. Although not popular initially, it has since become the default choice of a chart because of its graphic simplicity and familiarity. *The New York Times* graphics editor Amanda Cox says, "There's a strand of the data viz world that argues that everything could be a bar chart. That's possibly true but also possibly a world without joy." [^beniato] Alternatives to and variations of the bar chart are necessary for large-scale data visualizations.


## Variations
Variations of the bar chart regroup the bars, typically to display more data or make the chart more compact. Bars can be grouped, stacked, and re-oriented. Triangles and other figures can substitute the bar shape. However, shapes other than the rectangle are more difficult for the eye to interpret.

### Grouped bar chart
<img src="grouped-bar-chart.svg" alt="grouped bar chart" class="f-right-half"/> A grouped bar chart, also known as a *clustered bar chart* or a *multiple bar chart*, shows two or more data series with their respective bars displayed side by side. The categories inside each group should appear in the same order through the chart. The maximum number of bars per group is limited to three or four. The bars must have the same width since the chart can only show values through the height of the bars, not the area or the width.

### Stacked bar chart
<img src="stacked-bar-chart.svg" alt= "stacked bar chart" class="f-right-half"/> A stacked bar chart shows two or more data series where each respective bar stacks on top of another along the vertical axis.  In practice, the number of data series is limited. The stacking order of all data series has to be the same order across all the bars.

### Tornado chart
<img src="tornado-chart.svg" alt="tornado chart" class="f-right-half"/> The tornado chart, also known as *tornado diagram*, is a horizontal bar chart with bars ordered from the longest at the top to the shortest at the bottom, creating a funnel-like shape. Tornado charts are useful for situations where the descending ordering of the bars points to a pattern in the data.

### Span chart
<img src="span-chart.svg" alt="span chart" class="f-right-half"/> Span chart, also known as *range bar chart*, *range column chart*, or  *floating bar chart*, displays two data points per bar, with the lowest point showing a minimum and the highest points showing the maximum. Functionally, the span chart is the same as the [waterfall chart](/waterfall-chart).

### Lollipop chart
<img src="lollipop-chart.svg" alt="lollipop bar chart" class="f-right-half" /> Lollipop chart, also known as *lollipop plot*, replaces the bar with a line-and-dot combination. Lollipop charts may be useful in large data sets where bars would be too thin. However, the dot and line combination is less readable than the standard bars. For improved readability, the dots are typically of a more high-contrast color than the lines.

### Dumbbell chart
<img src="dumbbell-chart.svg" alt="dumbbell chart" class="f-right-half" /> Dumbbell chart, also known as *dumbbell plot* and *connected dot plot*, is a variation of the lollipop chart displaying two data points per category. The line connecting them emphasizes the difference between the two data points. Functionally, it is the same as the range bar chart. With large data sets it has the advantage of displaying data more compactly. The dots are typically colored such that they are more visible than the lines.

### Circular bar chart
Circular bar chart positions the bars along a rounded X axis. Rounded charts are known to be harder to interpret for the human eye than the linear variation.[^thudt]
<img src="circular-bar-chart.svg" alt="cirular bar charts" class="f-full" /> 

### Radial bar chart
Radial bar chart, also known as *radial column chart* and *polar bar chart*, is a bar chart wrapped around a circular X-axis. It is useful for showing repeating or cyclical events. Even though it is visually similar to the [polar area chart](/polar-chart), it uses the bar length, not the area of a segment to encode values.
<img src="radial-bar-chart.svg" alt="radial bar charts" class="f-full" />

### Spiral bar chart
<img src="spiral-bar-chart.svg" alt="spiral bar charts" class="f-right-half" /> Spiral bar chart, also known as *spiral column chart*, wraps the X-axis around the center in a spiral. This variation is useful for showing large data sets in a space-saving format. Spiral bar charts are less readable than the linear kind.  In a situation where indicating the exact values is less important than showing a trend, a spiral bar chart has the advantage of displaying a lot of data points at once. If the X-axis shows time, the more recent events are typically plotted on the outer coil going inward.


## Alternatives
With the bar chart being the ubiquitous default, there is often a need to find an alternative. 

1. *Dot chart* uses a dot to represent a data point and otherwise works the same way as a bar chart. Dot plots allow for a more elegant way of displaying large data sets.[^robbins] The dot chart is not to be confused with the [dot plot](/dot-plot), a statistical graphic that shows the distribution of individual observations represented as dots at regular intervals. It is similar to the [histogram](/histogram), but it is more accurate since the data is not binned.
2. [*Isotype diagram*](/isotype-diagram) uses icons to represent a data point as the total length of the row of icons. Isotype chart can help a reader see the semantic meaning of each category in the chart. [^haroz]
3. [*Waterfall chart*](/waterfall-chart) is an alternative to a stacked bar chart. It tracks the change from an initial value through a series of intermediate values to the end value. The first column is the initial value. The last column is a cumulative total.
4. [*Bullet chart*](/bullet-chart) functionally the same as a bar chart, the bullet chart adds a symbol for the target value and a progress bar.
5. [*Slopegraph*](/slopegraph) is an alternative to a stacked bar chart. A slope graph shows the relationship between two sets of categories.

It is worth noting that the pie chart and the bubble, both of which are other popular charts, are not functional alternatives to a bar chart.

## References
[^harris]: Harris, Robert L. [Information graphics: A comprehensive illustrated reference.](https://books.google.com/books?hl=en&lr=&id=qusmDAAAQBAJ) Oxford University Press, 2000. p. 59
[^berinato]: ["The Power of Visualization's "Aha!" Moments" by Scott Berinato, Harvard Business Review, retrieved Apr 3, 2019](https://hbr.org/2013/03/power-of-visualizations-aha-moment)
[^yau]: [FlowingData.com by Nathan Yau, retrieved Apr 3, 2019](https://flowingdata.com/2015/08/31/bar-chart-baselines-start-at-zero/)
[^thudt]: Thudt, Alice, et al. ["Assessing the Readability of Stacked Graphs."](https://dx.doi.org/10.20380/GI2016.21) 2016. [PDF](https://hal.inria.fr/hal-01587962/document)
[^robbins]: Robbins, Naomi B. ["Dot Plots: A Useful Alternative to Bar Charts."]((http://perceptualedge.com/articles/b-eye/dot_plots.pdf)) Business Intelligence Network Newsletter (2006). p.3
[^knaflic]: Knaflic, Cole Nussbaumer. [Storytelling with data: A data visualization guide for business professionals.](https://books.google.com/books?id=IheRCgAAQBAJ) John Wiley & Sons, 2015. pp.55-56 
[^haroz]: Haroz, Steve, Robert Kosara, and Steven L. Franconeri. ["Isotype visualization: Working memory, performance, and engagement with pictographs."](https://doi.org/10.1145/2702123.2702275) Proceedings of the 33rd annual ACM conference on human factors in computing systems. ACM, 2015. [PDF](http://steveharoz.com/research/isotype/ISOTYPE_Visualization_CHI2015_Haroz_Kosara_Franconeri.pdf)
