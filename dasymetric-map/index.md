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
  - title:  Dasymetric map of London's population density
    author:  James Gleeson
    link:   https://jamesjgleeson.wordpress.com/2013/01/23/dasymetric-map-of-londons-population-density-2011/
    image: london-population-density.png

  - title:  Europe Population Density Map
    author:  Dan Cookson
    link:  https://dancooksonresearch.carto.com/u/dancookson/viz/49ca276c-adf9-454a-8f64-0ccf0e46eed0/embed_map
    image: europe-population-density-map.png
    

---

is a technique of thematic mapping that divides map regions into equally sized units and shows density data per unit. It is most commonly used to display population density.

<!--more-->

Dasymetric maps are a solution to a known problem of *over-generalization* in [choropleth maps](/choropleth-map). Since choropleth maps only show density per geographic or political region, they can hide variations of data inside regions. This can lead readers to assume that the entire region is uniform. [^kostelnick]

This kind of visual statistical misrepresentation is known as the *ecological fallacy* which is the assumption that something true about a population is also accurate about an individual.

Dasymetric maps show the variation inside the region by using colored symbols, usually rectangles. Color represents a change in value by varying the hue, transparency, or chroma.

As with choropleth maps, the color scheme should follow color logic. Readers associate denser or darker colors with higher population densities, for example. Certain colors are perceived to have an inherent meaning: red is negative, green is positive; red is hotter than yellow and orange.

The dasymetric map was developed in 1911 by Benjamin Semenov-Tyan-Shansk. American geographer J.K. Wright later popularized it.

## Alternatives
1. [*Choropleth map*](/choropleth-map) represents data by coloring an entire region.
2. [*Dot map*](/dot-map) shows individual data points represented as dots overlaid over a map.
2. [*Bubble map*](/bubble-map) displays data as scaled symbols, usually circles, per map region.
4. [*Cartogram*](/cartogram) uses the distortion of land area to represent data.

## Sources

[^kostelnick]: ["Visible Numbers: Essays on the History of Statistical Graphics" by Charles Kostelnick et. al](https://books.google.fr/books?id=gCMxDwAAQBAJ&pg=PT140&dq=dasymetric+map&hl=en&sa=X&ved=0ahUKEwiUvIjCodLhAhUEKBoKHWbGAtIQ6AEIMjAC#v=onepage&q=dasymetric%20map&f=false)
