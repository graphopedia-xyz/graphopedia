---
title: bar chart
  
tags:

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

  - title:  Oil Well (Nutrition Facts for Edible Oils)
    author: David McCandless
    link:   https://informationisbeautiful.net/visualizations/oil-well-every-cooking-oil-compared/
    image:  oil-nutrition-facts.png

  - title:  How Couples Meet
    author: Nathan Yau
    link:   https://flowingdata.com/2019/03/15/shifts-in-how-couples-meet-online-takes-the-top-spot/
    image:  how-couples-meet.jpeg
    
  - title: The most used words for women vs. men
    author: Julia Silge
    link:   https://pudding.cool/2017/08/screen-direction/
    image:  likelihood-of-words-based-on-gender.png
    
  - title: The space race is dominated by new contenders
    author: The Economist
    link: https://www.economist.com/graphic-detail/2018/10/18/the-space-race-is-dominated-by-new-contenders
    image: space-race.png
    
  - title:  Codebases - Millions of Lines of Code
    author: David McCandless
    link:   https://informationisbeautiful.net/visualizations/million-lines-of-code/
    image:  lines-of-code.png

  - title:  World Population Infographic for Popular Science
    author: Ariana Montanez
    link:   http://www.arianamontanez.com/world-population-infographic/
    image:  world-population.jpeg

synonyms:
  - column chart
  - bar graph

---

displays the relationship of a category to a number in the form of a rectangle bar. The bar height along the Y axis or its length along the X axis represents a number.  Each bar represents a single number. For this reason, bar charts can be used to compare discrete numbers but not continuously changing numbers.[^harris]

<!--more-->

The bar chart was first introduced by William Playfair. It has become the default choice of chart. The New Work Times graphics Editor Amanda Cox says, "There’s a strand of the data viz world that argues that everything could be a bar chart. That’s possibly true but also possibly a world without joy."[^beniato]
## Purpose
Often, bar charts are used to compare the change of a value over time. The basic application os the representation of change in numbers across categories. This is a very broad application which explains the popularity of a bar chart. 

Since the bar chart is often a default, it is worth mentioning what it does not show: distribution, median or mean, ratios, correlation, relationships or connections, or anything more than a single data point.

## Usage
The baseline of a bar chart should always start at zero. Otherwise, the bar length will not be interpreted correctly by the reader. [^yau] While there are not many rules about chart design, this particular one is. A bar chart with the Y axis not starting at zero can never represent its data truthfully and so it defeats the purpose of the chart.

The bar width is equal and cannot be used to represent data. Using the width of the bar would turn the bar chart into a [Marimekko Chart](/marimekko-chart). The distance between bars is also equal and not indicative of data values.

Bars can be ordered or unordered.

## Types
Bars can be grouped and stacked. Bars can be oriented around a radial layout making a radial bar chart. The shape of the bar can be substituted with other shapes, as in a lollipop chart.

1. *Grouped bar chart* shows two or more data series where their respective bars are displayed side by side. This types of chart can also be called a "clustered bard chart" or a "multiple bar chart". In this types of chart the bars must be kept the same width since the chart can only show the difference in the height of the bars, not the area.

2. *Stacked bar chart* shows two or more (but in practice the number is quite limited) where each respective bar is stacked on top of the other along the vertical axis.

3. *Radial bar chart* positions the bars along a rounded X axis. Rounded charts are known to be harder to interpret for the human eye than the linear variation.[^thudt]

4. *Lollipop chart* replaces a bar with a line and a dot at the far end. Lollipop charts may be useful in situations when there are a lot of data points and bars would be either too thin to read or too wide to fit.

## Bar Chart Alternatives
The bar chart being the default choice of a chart, there is often a need to find an alternative. Sometimes the need comes from the data and other times it si an editorial decision made with the purpose of diversifying charts in an article or a report to make each more memorable. 
In either case, there are many ways to substitute a bar chart with another chart without losing clarity, and sometimes even making the data clearer.

1. *Dot plot* uses a dot to represent a data point and otherwise works the same way as a bar chart. When one needs to show several types of categories, instead of showing multiple bar or stacked bar charts, dot plots allow for a more elegant way to show the same data.[^robbins]
2. [*Isotype diagram*](/isotype-diagram) uses icons to represent a data point as the total length of the row of icons. Isotype chart can help a reader see the semantic meaning of each category in the chart. [^haroz]
3. [*Waterfall chart*](/waterfall-chart) is an alternative to a stacked bar chart. In a waterfall chart we can see each bar separated by category on the X axis which makes the size of the bar easier to perceive than in a stacked bar chart.[^knaflic]
4. [*Bullet chart*](/bullet-chart) functionally the same as a bar chart, the bullet chart adds a symbol for the target value and a progress bar.
5. *Slope graph* is an alternative to a stacked bar chart. A slope graph shows the relationship between two sets of categories.

The need to find an alternative to a bar chart sometimes leads people to substitute it with a chart that is not functionally the same, for example, the pie chart, the bubble or the histogram. For this reason, it is important to look for an alternative that is functionally the same.[citation needed]

## References
[^harris]: [Information Graphics: A Comprehensive Reference by Robert L. Harris](https://books.google.com/books?id=LT1RXREvkGIC)
[^berinato]: ["The Power of Visualization’s “Aha!” Moments" by Scott Berinato, Harvard Business Review, retrieved Apr 3, 2019](https://hbr.org/2013/03/power-of-visualizations-aha-moment)
[^yau]: [FlowingData.com by Nathan Yau, retrieved Apr 3, 2019](https://flowingdata.com/2015/08/31/bar-chart-baselines-start-at-zero/)
[^thudt]: [Assessing the Readability of Stacked Graphs by Alice Thudt , et al. ](https://hal.inria.fr/hal-01587962/document)
[^robbins]: [Dot Plots: A Useful Alternative to Bar Charts by Naomi B. Robbins, p.3](http://perceptualedge.com/articles/b-eye/dot_plots.pdf)
[^knaflic]: [Storytelling with Data: A Data Visualization Guide for Business Professionals by Cole Nussbaumer Knaflic, pp.55-56](https://books.google.com/books?id=IheRCgAAQBAJ&printsec=frontcover&dq=alternative+to+%22bar+graph%22&hl=en&sa=X&ved=0ahUKEwib7qDuyrbhAhUlGKYKHWDxAqAQ6AEILzAB#v=onepage&q=bar%20chart&f=false)
[^haroz]: [ISOTYPE Visualization – Working Memory, Performance, and Engagement with Pictographs, p.1](http://steveharoz.com/research/isotype/ISOTYPE_Visualization_CHI2015_Haroz_Kosara_Franconeri.pdf)

