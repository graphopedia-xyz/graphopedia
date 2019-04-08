---
title:  bubble map
  
tags:

related:

tools:
  - name:   Datamatic
    link:   https://datamatic.io/#id=0B3wq5VFn9PllRUg3X1Z5OWRGd1k

  - name:   Carto
    link:   https://carto.com/blog/proportional-symbol-maps/

  - name:   Tableau
    link:   https://onlinehelp.tableau.com/current/pro/desktop/en-us/maps_howto_symbol.html
    
examples:
  - title:  Deadly Vibrations. Earthquakes resulting in 1000 or more deaths since 1900 
    author: Ben Willers
    link:   https://www.flickr.com/photos/b_willers/6331225797/in/photostream/

  - title:  Where to Live to Avoid Natural Disasters
    author: The New York Times
    link:   https://archive.nytimes.com/www.nytimes.com/interactive/2011/05/01/weekinreview/01safe.html?_r=0
    
synonyms:
  - proportional symbol map
  - graduated symbol map
---
visualizes numeric data associated with locations on a map by using a scaled symbol—typically a circle or a square—proportional to the number it represents and positioned in the location to which it refers.[^cabello]
 Each circle is sized based on its area, not the diameter or the radius, following the same principle as in a bubble chart. The underlying map is divided into regions, with a single circle per region.

<!--more-->
## Purpose
Bubble maps are used to compare data among geographic regions on a map. The comparison can be shown between data points, percentages and ratios.

## Usage
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

## Alternatives

1. [*Choropleth map*](/choropleth-map) 


## Sources

[^cabello]: [Algorithmic Aspects of Proportional Symbol Maps by Sergio Cabello, et al.](https://link.springer.com/content/pdf/10.1007%2Fs00453-009-9281-8.pdf)
[^cairo]: ["The Functional Art: An introduction to information graphics and visualization" by Alberto Cairo, p.](https://books.google.com/books?id=xwjhh6Wu-VUC&pg=PT144&dq=%22proportional+symbol+map%22&hl=en&sa=X&ved=0ahUKEwjZsujj6MDhAhWVKqYKHfXoBr8Q6AEIRjAF#v=onepage&q=proportional%20symbol&f=false)
[^cox]: ["Anchor effects and the estimation of graduated circles and
         squares" by Carleton Cox 1976.The American Cartographer 3(1):65-74. ](https://www.tandfonline.com/doi/abs/10.1559/152304076784080195)
[^crawford]: ["The perception of graduated squares as cartographic symbols" by Crawford, 1973. The Cartographic foumal 10(2):85-88.] (https://www.tandfonline.com/doi/abs/10.1179/caj.1973.10.2.85?journalCode=ycaj20)
[^eells]: ["The Relative Merits of Circles and Bars for Representing Component Parts" by Walter Crosby Eells, Journal of the American Statistical Association Vol. 21, No. 154 (Jun., 1926), pp. 119-132](https://www.jstor.org/stable/2277140)
[^Montello][Cognitive Map-Design Research in the Twentieth Century: Theoretical and Empirical Approaches](https://geog.ucsb.edu/~montello/pubs/history.pdf)
