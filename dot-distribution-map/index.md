---
title:  dot distribution map
  
tags:
- distribution
- geospatial data

related:
  - bubble-map
  - choropleth-map

tools:
  - name:   Carto
    link:   https://observatory.carto.com/viz/582f22f2-d682-11e5-a3bd-0ecfd53eb7d3/public_map

  - name:   D3 workbook by Ian Johnson
    link:   https://bl.ocks.org/enjalot/2c7eec93ce68551627d4
    
  - name:   R tutorial by Paul Campbell
    link:   https://www.cultureofinsight.com/blog/2018/05/02/2018-04-08-multivariate-dot-density-maps-in-r-with-sf-ggplot2

examples:
  - title:  Mapping Immigrant America
    author: Kyle Walker
    link:   http://personal.tcu.edu/kylewalker/immigrant-america/
    image:  immigrant-america.png
  
  - title:  Flavors of Blur - Annual Household Income in Chicago
    author: Radical Cartography
    link:   http://www.radicalcartography.net/index.html?chicagodots
    image:  income-in-chicago.jpg

  - title:  When You Greet a Friend, How Many Times Do You Kiss?
    author: Bill Rankin
    link:   http://www.radicalcartography.net/index.html?frenchkisses
    image:  how-many-times-french-kiss.png
    
  - title:  Cholera Cases In the London Epidemic of 1854
    author: John Snow
    link:  https://en.wikipedia.org/wiki/John_Snow#/media/File:Snow-cholera-map-1.jpg
    image:  john-snow-cholera-map.jpg


synonyms:
  - dot density map
---
is a map type that uses a dot symbol to show the presence of a feature emphasizing the distribution of values through the scatter pattern similar to a scatter plot.

<!--more-->
The dot distribution map was first introduced in the early 1830 by a French monk Armand Joseph Frère de Montizon. The map showed the population of France by administrative district.[^palsky]

Dot distribution maps use dots or another symbol to mark the location of specific data points.

There are two types of these maps:

1. One-to-one dot distribution shows a single dot per data point.

2. One-to-many dost distribution allows a single dot to represent equal groups of data points per dot. This is called "subsampling".[^castillo]

The advantage of a dot distribution map is in displaying the pattern formed by the data point, similar to a [scatter plot](/scatter-plot). An important dor distribution map made by John Snow revealed a pattern of cholera a outbreak connected to the location of water pumps. (See the example section below.)

In the reverse situation, where data cannot be tied to a specific location on a map, the use of dot distribution can be misleading. [^meirelles]

## Alternatives

1. [Choropleth map](/choropleth map) shows data per geographic unit. It does not show individual data points but rather the average for the region.
2. [Bubble map](/bubble-map) show grouped data linked to a geographic location by scaling a symbol, usually a circle, proportionally to data value.


## Sources 

[^palsky]: ["La naissance de la démocartographie. Analyse historique et sémiologique" by Gilles Palsky. p.28](http://www.persee.fr/doc/espos_0755-7809_1984_num_2_2_956)

[^castillo]: ["Big Crisis Data: Social Media in Disasters and Time-Critical Situations" by Carlos Castillo.  Cambridge University Press, 2016., p. 140](https://books.google.com/books?id=c1KJDAAAQBAJ)

[^meirelles]: ["Design for Information: An Introduction to the Histories, Theories, and Best Practices Behind Effective Information Visualizations" by Isabel Meirelles. Rockport Publishers, 2013, p.130-131](https://books.google.fr/books?id=RFb0AwAAQBAJ)

