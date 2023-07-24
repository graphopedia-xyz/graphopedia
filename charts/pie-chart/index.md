---
title:  pie chart

functions: 
  - part-to-whole relationship

visualizationTechniques:
  - techniqueId: PSF
    informationType: proportion
    axisDirections: angular


related:
  - bar-chart

tools:
  - name:   Adobe Illustrator
    link:   https://helpx.adobe.com/illustrator/using/graphs.html

  - name:   PowerPoint
    link:   https://products.office.com/en/powerpoint

examples:

  - title:  William's Playfair pie chart
    author: William Playfair
    image:  william-playfair.png
    
  - title:  Van Gogh's paintings
    note: 28 van Gogh painting visualised as a grid of pie charts showing the five most common colours in each as a pecentage.
    image:  van-gogh-paintings.jpg
    

synonyms: 
  - circular chart

order: 100

---

is a type of graph that displays numbers as segments of a circle with the circle representing one hundred percent. The wedge-shaped parts represent percentages equal to their arc lengths. 

<!--more-->
A pie chart consists of wedge-shaped ***segments*** that represent a ***fraction*** or a ***percentage*** through the length of their ***arcs***.

The function of a pie chart is the visual illustration of part-to-whole relationships. Pie charts are best used to show values of 25%, 50%, and 75%. The wedges in these cases have right angles, which are easy for the human eye to interpret accurately.
 
Values smaller than 10% are difficult for viewers to estimate. Fractions such as 38.5% and unrounded numbers such as 38% are virtually impossible to see on a pie chart.

Pie charts are criticized for their overuse because human perception is not capable of accurately comparing wedge-shaped slices. This is especially true for comparisons between multiple pie charts.[^tufte] 

Charts that use rectangular shapes are thought to be easier to perceive, especially when readers need to see specific values.

Pie charts should not be used to represent sums of parts where the sum is not meaningful to the reader. For example, showing the total number of goals across several soccer teams would not be useful because it makes sense to compare them and not to add. [^good]
 
Pie charts are one of the most widely used types of data visualization likely because of the human predisposition towards circles and radiating patterns.[^lima]

Scottish engineer William Playfair is the creator of the first pie chart published in *Statistical Breviary* in 1801.  [^spence]

<!-- from variations -->
Many stylistic variations of the pie chart exist. Since the exact sizes of segments are difficult for the human eye to compare, techniques such as exploding the pie chart separate the segments for easier comparison. However, there is evidence that distorting the basic pie chart only makes it more unreadable. [^kosara]


## Alternatives
1. [*Stacked Bar Chart*](/stacked-bar-chart) a pie chart is essentially a stacked bar chart with a single bar shown in polar coordinates.[^wilkinson2] Functionally absolutely the same, but the bar chart rectangles give readers a more natural way of judging the areas.
2. [*Polar area chart*](/polar-area-chart) is a type of pie chart in which all sectors have equal angles, but they differ in how far each segment extends from the center of the circle. The polar area chart is used to plot cyclic phenomena, for example, the amount of rain each month appears as 12 sectors at 30 degrees each.
3. [*Waffle chart*](/waffle-chart) shows ratios using a grid of squares representing one hundred percent and coloring the part representing a fraction of the whole.


## Further reading
- [Pie chart](https://en.wikipedia.org/wiki/Pie_chart) article on Wikipedia.

## References
[^tufte]: Tufte, Edward R. [*The visual display of quantitative information.*](https://www.edwardtufte.com/tufte/books_vdqi) Vol. 2. Cheshire, CT: Graphics press, 2001. p.178. Tufte advises against using multiple pie charts using a proportional symbol map with pie charts as an anti-example of aesthetics in data graphics.
[^good]: Good, Phillip I., and James W. Hardin. [*Common Errors in Statistics (and How to Avoid Them)*](https://books.google.com.ua/books?hl=en&lr=&id=jiAwiY9DS9EC) John Wiley & Sons, 2012. p.117.
[^lima]: Lima, Manuel. "Why humans love pie charts: a historical and evolutionary perspective." *Noteworthy*, retrieved May 10, 2019 from https://blog.usejournal.com/why-humans-love-pie-charts-9cd346000bdc
[^spence]: Spence, Ian. ["No humble pie: The origins and usage of a statistical chart."](https://doi.org/10.3102%2F10769986030004353) *Journal of Educational and Behavioral Statistics* 30.4 (2005): 353-368. [PDF](http://www.psych.utoronto.ca/users/spence/Spence%202005.pdf)
[^kosara]: Kosara, Robert, and Skau, Drew "Judgment error in pie chart variations." Proceedings of the *Eurographics/IEEE VGTC conference on visualization: Short papers.* 2016. [PDF](https://kosara.net/papers/2016/Kosara-EuroVis-2016.pdf)
[^wilkinson2]: Wilkinson, Leland. [*The Grammar of Graphics.*]((https://books.google.com/books?hl=en&lr=&id=_kRX4LoFfGQC)) Springer Science & Business Media, 2005. p.23
