---
title:  bubble map
  
tags:
- comparison
- geospatial data

related:

tools:
  - name:   Datamatic
    link:   https://datamatic.io/#id=0B3wq5VFn9PllRUg3X1Z5OWRGd1k

  - name:   Carto
    link:   https://carto.com/blog/proportional-symbol-maps/

  - name:   Tableau
    link:   https://onlinehelp.tableau.com/current/pro/desktop/en-us/maps_howto_symbol.html
    
examples:
  - title:  Robocalls in the United States in 2018
    author: Harry Stevens for Axios
    link:   https://www.axios.com/48-billion-robocalls-americans-3017a1c6-4406-4305-82c0-9d7c9ef84548.html
    image:  robocalls-in-united-states.png
  
  - title:  France’s Nuclear Landscape
    author:  Bloomberg
    link:  https://www.bloomberg.com/graphics/2019-nuclear-waste-storage-france
    image:  nuclear-waste-storage-france.png
    
  - title:  Deadly Vibrations - Earthquakes Resulting in 1000 or More Deaths Since 1900 
    author: Ben Willers
    link:   https://www.flickr.com/photos/b_willers/6331225797/in/photostream/
    image:  deadly-earthquakes.jpg

  - title:  Where to Live to Avoid Natural Disasters
    author: The New York Times
    link:   https://archive.nytimes.com/www.nytimes.com/interactive/2011/05/01/weekinreview/01safe.html?_r=0
    image:  natural-disaster-risk.png
  
  - title:  Wealthiest Zip Codes In America
    author: Experian
    link:   https://www.edq.com/globalassets/infographics/wealthiest-zip-codes.png
    image:  wealthiest-zip-codes-in-america.png
  
    
synonyms:
  - proportional symbol map
  - graduated symbol map
---
visualizes numeric data referring to locations on a map by using a scaled symbol—typically a circle or a square—proportional to the number it represents and positioned in the location to which it refers.[^cabello]
 Each circle is sized based on its area, not the diameter or the radius, following the same principle as in a bubble chart. The underlying map is divided into regions, with a single circle per region.

<!--more-->

Bubble maps are used to compare data among geographic regions on a map. The comparison can be shown between data points, percentages and ratios.

One of the main challenges in a bubble map is the choice of bubble sizing.  There are three ways in which bubbles can be scales:
mathematical scaling, perceptual scaling, and range grading. [^cabello]

*Mathematical scaling* reflects the data as it is. And yet, the human eye is known to not judge the relative areas of shapes, especially circles, correctly. 
To compensate for this, *perceptual scaling*, also called "apparent value scaling" turns larger symbols on the map even larger. 

*Range grading*, groups data into classes and represents each class with a single symbol. The need for range grading comes from the nature of maps themselves-some regions are larger than others and yet each region is represented by a single symbol. Following a symbol-per-region logic can lead to misleading representations of data. [^cairo]

A legend that contains three sizes of symbols - small, medium, and large relative to the mapped data - is recommended as a way to help a reader to correctly judge the size of the symbols.[^cox]

### How to Choose the Right Symbol?
Many studies have been done to find the geometric shape that is most accurately interpreted by the human eye. 

Square symbols are easier for the human eye to judge correctly than a circle.[^crawford] Using scaled bars that represented data as their lengths, not area, produced even better perception results than squares. 

However, when the symbol also shows percentage relationships, readers see 25%, 50% and 75% better represented as wedges of a circle than parts of a bar.[^eells]

The main alternatives for proportional symbols are geometric shapes and pictographs. Geometric shapes are generally easier to interpret correctly for their size, while pictographs are easier to remember for their context.  [^montello]

Bubble map symbols need to be properly scaled to avoid clutter. Ideally, bubbles should not overlap. To avoid obstruction of the map itself, bubbles can be made partially transparent.

<img src="types-of-symbols-areal.jpg" alt="areal univariate point symbols" />
<img src="types-of-symbols-linear.jpg" alt="linear univariate point symbols" />
<!-- TODO: redraw types of symbols as svg. From 'Beyond Graduated Circles: Varied Point Symbols for Representing Quantitative Data on Maps' by Cynthia A. Brewer, p.14 -->

## Alternatives

1. [*Choropleth map*](/choropleth-map) uses colored areas to represent the measurement of a variable proportional to the colored area.

2. [*Cartogram*](/cartogram) substitutes land area with time, population or any other variable, distorting the geometry of the map. There are three ways in which the map can be distorted: 1. by bulging out the areas; 2. by splitting map features; 3. by representing each map feature as a simple geometric shape such as a circle.

3. [*Dot Distribution Map*](/dot-distribution-map) uses a dot symbol to represent a data point showing the distribution of values through the scatter pattern similar to a scatter plot.


## Sources

[^cabello]: [Algorithmic Aspects of Proportional Symbol Maps by Sergio Cabello, et al.](https://link.springer.com/content/pdf/10.1007%2Fs00453-009-9281-8.pdf)
[^cairo]: ["The Functional Art: An introduction to information graphics and visualization" by Alberto Cairo, p.](https://books.google.com/books?id=xwjhh6Wu-VUC&pg=PT144&dq=%22proportional+symbol+map%22&hl=en&sa=X&ved=0ahUKEwjZsujj6MDhAhWVKqYKHfXoBr8Q6AEIRjAF#v=onepage&q=proportional%20symbol&f=false)
[^cox]: ["Anchor effects and the estimation of graduated circles and
         squares" by Carleton Cox 1976.The American Cartographer 3(1):65-74. ](https://www.tandfonline.com/doi/abs/10.1559/152304076784080195)
[^crawford]: ["The perception of graduated squares as cartographic symbols" by Crawford, 1973. The Cartographic foumal 10(2):85-88.](https://www.tandfonline.com/doi/abs/10.1179/caj.1973.10.2.85?journalCode=ycaj20)
[^eells]: ["The Relative Merits of Circles and Bars for Representing Component Parts" by Walter Crosby Eells, Journal of the American Statistical Association Vol. 21, No. 154 (Jun., 1926), pp. 119-132](https://www.jstor.org/stable/2277140)
[^montello]: [Cognitive Map-Design Research in the Twentieth Century: Theoretical and Empirical Approaches](https://geog.ucsb.edu/~montello/pubs/history.pdf)
