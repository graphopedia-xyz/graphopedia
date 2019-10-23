---
title:  proportional area chart

tags:
- part-to-whole relationship
- comparison

related:
  - sunburst-chart
  - venn-diagram

tools:

examples:
  - title:  Analysis of the Italian population, Audipress Visual Report
    image:  analysis-of-the-italian-population-by-audipress.png
    author: Audipress
    note:   This is proportional area chart made out of four grouped squares, according to profession type.
    link:   http://audipress.it/visual_report/a/2018_I
    
  - title:  Where Oil Is King
    image:  where-oil-is-king.jpg
    author: The Washington Post
    note:   This is proportional area chart made out of nested squares
    link:   https://www.washingtonpost.com/news/worldviews/wp/2016/08/02/how-the-crash-in-oil-prices-devastated-angola-and-venezuela/

  - title:  "Urban Story: Lisbon is On Par With Honolulu"
    author: Accurat
    link:  https://www.accurat.it/works/la-lettura/
    note:   
    image:  latitude-urbanism.jpg

  - title:  The Analytical Tourism Map of Piedmont
    image:  the-analytical-tourism-map-of-piedmont.jpg
    author: Marco Bernardi, Federica Fragapane, Francesco Majno
    link:   https://www.behance.net/gallery/15058221/The-Analytical-Tourism-Map-of-Piedmont
        
  - title:  All 786 Known Planets to Scale
    image:  all-known-exoplanets-2012.png
    author: xkcd
    link:   https://xkcd.com/1071/
    note:  This proportional area chart uses circle packing to show all 786 extrasolar planets (as of june 2012). Planets are categorized based on their mass which is shown with different color.
    
  - title:  Global Carbon Emissions
    author: Stanford Kay
    note:   Circle-packed proportional area chart showing emissions per country
    link:   http://www.stanfordkaystudio.com/information.html
    image:  global-carbon-footprint.png

  - title:  Trumps Tweets Spiralling Out Of Control
    image:  trumps-tweets-spiralling-out-of-control.png
    author: Neil Richards
    note:   Spriral proportional area chart visualizing Donald Trump tweets. Each circle represent number of re-tweets and favorites. See the interactive visualizatioin to explore content of each tweet.
    link:   https://public.tableau.com/profile/neil.richards#!/vizhome/trump_5/Dashboard1

order: 130

---

is a type of one-dimensional chart that uses area of a shape to visualize a single variable without the use of axes. A shape, usually a rectangle, is scaled proportionally to the value it represents.

<!--more-->
Proportional area charts communicate a single variable through the area of a figure. Rectangles are the most common shape because estimating their areas is more intuitive for the human eye than areas of circles and other polygons.

Shapes typically align along their bottom edges, which enables the reader to compare their heights. The amount typically appears next to the shape. The chart is typically ordered in decreasing order of magnitude.

The chart uses no axes.[^harris] The shapes appear in a line or a grid. The absence of axes makes it possible to use this chart as [small multiples](/small-multiples).

With circular shapes, the area, not the radius, is used. 

Pictographs and illustrations are not the best choices of shape for a proportional area chart since the areas of such complex shapes are not possible to compare effectively.


## Variations

### Split proportional area chart
<img src="split-proportional-area-chart.svg" class="f-right-half" /> uses halves of two circles, the area of which can be inferred from the half. This variation encourages a more precise comparison of the two shapes.

### Quadruple proportional area chart
<img src="quadruple-proportional-area-chart.svg" class="f-right-half" /> Similar to a split proportional chart, the quadruple proportional chart locates a group of shapes in close proximity to each other to enable the reader to compare their areas.

### Nested proportional area chart
<img src="nested-proportional-area-chart.svg" class="f-right-half" /> Nested proportional area charts overlap the shapes to facilitate comparison between them. The nested shapes are typically aligned either at their bottom edge or in the lower left corner. The nesting tends to negatively impact the chart's readability. At the same time, the chart becomes more compact. Although it is difficult to extract precise values from this chart for a reader, when accompanied by values written out next to shapes, this chart variation can be useful. A common use case is the legend of a bubble chart or a [proportional symbol map](/bubble-map). 

### Spiral proportional area chart
<img src="spiral-proportional-area-chart.svg" class="f-right-half" /> Shapes in a proportional area chart can be arranged in a spiral as a space-saving technique. Partial overlap of shapes is possible when circles are used since their area can be inferred even when partially hidden.

### Proportional area chart with circle packing
<img src="circle-packing-proportional-area-chart.svg" class="f-right-half" /> Shapes can be arranged in a space-saving layout such that they are located closest to each other while avoiding overlapping, called circle packing. 

## Sources
[^harris]: Harris, Robert L. [*Information graphics: A comprehensive illustrated reference.*](https://books.google.com/books?id=LT1RXREvkGIC) Oxford University Press, 2000, p.680-81.
