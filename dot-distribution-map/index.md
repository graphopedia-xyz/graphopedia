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
  
order: 400

---
is a map type that uses a dot symbol to show the presence of a feature emphasizing the distribution of values through the scatter pattern similar to a scatter plot.

<!--more-->
Dot distribution maps use dots or another symbol to mark the location of specific data points.

There are two types of dot distribution maps:

1. One-to-one dot distribution shows a single dot per data point.

2. One-to-many dot distribution allows a single dot to represent equal groups of data points per dot. This process is called *subsampling*. [^castillo]

The advantage of a dot distribution map is in displaying the pattern formed by the data point, similar to a [scatter plot](/scatter-plot). 

A historically significant dot distribution map made by John Snow revealed a pattern in a London cholera outbreak connected to the location of water pumps. The map appears in the example section below.

In the reverse situation, where data does not refer to specific locations on a map, the use of dot distribution can be misleading. [^meirelles]

The dot distribution map was first introduced in the early 1830s by a French monk Armand Joseph Frère de Montizon. The map showed the population of France by administrative district. [^palsky]

## Alternatives

1. [*Choropleth map*](/choropleth map) shows data per geographic unit. It does not show individual data points but rather the average for the region.
2. [*Cartogram*](/cartogram) uses the distortion of land area to represent data.
3. [*Bubble map*](/bubble-map) shows data as proportionally sized symbols, typically circles, overlaid over a map.
4. [*Dasymetric map*](/dasymetric-map) represents a statistical surface of density, most commonly population density.

## Sources 


[^castillo]: ["Big Crisis Data: Social Media in Disasters and Time-Critical Situations" by Carlos Castillo.  Cambridge University Press, 2016., p. 140](https://books.google.com/books?id=c1KJDAAAQBAJ)

[^meirelles]: ["Design for Information: An Introduction to the Histories, Theories, and Best Practices Behind Effective Information Visualizations" by Isabel Meirelles. Rockport Publishers, 2013, p.130-131](https://books.google.fr/books?id=RFb0AwAAQBAJ)

[^palsky]: ["La naissance de la démocartographie. Analyse historique et sémiologique" by Gilles Palsky. p.28](http://www.persee.fr/doc/espos_0755-7809_1984_num_2_2_956)
