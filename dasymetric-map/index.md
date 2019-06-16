---
title: dasymetric map

tags:
- geospatial data

related:
  - choropleth-map
  - bubble-map

tools:
  - name:   Carto
    link:   https://carto.com/platform/location-data-streams

examples:
  - title:  Dasymetric map of London’s population density
    author:  James Gleeson
    link:   https://jamesjgleeson.wordpress.com/2013/01/23/dasymetric-map-of-londons-population-density-2011/
    image: london-population-density.png

  - title:  Europe Population Density Map
    author:  Dan Cookson
    link:  https://dancooksonresearch.carto.com/u/dancookson/viz/49ca276c-adf9-454a-8f64-0ccf0e46eed0/embed_map
    image: europe-population-density-map.png
    

---

is a technique of thematic mapping that represents density across the entire statistical surface, meaning showing a data point per each unit, most commonly population density.

<!--more-->

The dasymetric map was developed in 1911 by Benjamin Semenov-Tyan-Shansky and popularized by American geographer J.K. Wright.

Dasymetric maps are a solution to a known problem of over generalization in choropleth maps. Since choropleth maps only show density at the scale of a geographic or political region and not inside, they can hide the variation within that geographic region which leads readers to assume that the entire region has that density. [^kostelnick] This kind of statistical misrepresentation is known as *ecological fallacy*.

Dasymetric maps show the variation inside the region by using colored symbols, usually rectangles, color to represent change in value by changing color or color hue.

## Alternatives

1. [*Dot map*](/dot-map) shows individual data points represented as dots overlaid over a map.
2. [*Cartogram*](/cartogram) uses distortion of land area to represent data.

## Sources

[^kostelnick]: ["Visible Numbers: Essays on the History of Statistical Graphics" by Charles Kostelnick et. al,  ](https://books.google.fr/books?id=gCMxDwAAQBAJ&pg=PT140&dq=dasymetric+map&hl=en&sa=X&ved=0ahUKEwiUvIjCodLhAhUEKBoKHWbGAtIQ6AEIMjAC#v=onepage&q=dasymetric%20map&f=false)
