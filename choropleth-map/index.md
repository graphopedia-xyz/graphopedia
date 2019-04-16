---
title:  choropleth map
  
tags:

related:
  - dot-distribution-map
  - dasymetric-map

tools:
  - name:   amChart
    link:   http://www.amcharts.com/demos/us-heat-map/?theme=frozen
    
  - name:   D3
    link:   https://beta.observablehq.com/@mbostock/d3-choropleth

  - name:   Datamatic
    link:   https://datamatic.io/index.html
 
  - name:   Datawrapper
    link:   https://app.datawrapper.de/map/drYHO/basemap

  - name:   Carto
    link:   https://carto.com/help/building-maps/your-first-choropleth-map

  - name:   Kartograph
    link:   http://kartograph.org/showcase/choropleth
  
  - name:   Landline
    link:   https://propublica.github.io/landline/

  - name:   Python and SVG Tutorial
    link:   https://flowingdata.com/2009/11/12/how-to-make-a-us-county-thematic-map-using-free-tools/
    

examples:
  - title:  When Americans Leave For Work
    author: Nathan Yau
    link:   https://flowingdata.com/2015/02/04/when-do-americans-leave-for-work/
    image:  when-americans-leave-for-work.png
    
  - title:  U.S. White Population Density
    author: Radical Cartography
    link:   http://www.radicalcartography.net/index.html?wikicensus
    image:  us-white-population-density.png
    
  - title:  The Smoking Divide
    author: The New York Times
    link:   https://www.nytimes.com/interactive/2014/03/25/us/smoking-rate-map.html
    image:  the-smoking-divide-united-states.png
  
  - title:  Where the IRS Audits More
    author: Paul Kiel and Hannah Fresques
    link:   https://projects.propublica.org/graphics/eitc-audit
    image:  where-irs-audits-more.png

---

is a type of thematic map in which areas are colored to represent the measurement of a variable proportional to the colored area.

<!--more-->

The first choropleth map was introduced by Baron Pierre Charles Dupin in 1826. The term "choropleth map" appeared in 1938 in <cite>Problems in Population Mapping</cite> by the geographer John Kirtland Wright.

***Purpose***: showing how data changes across geographic regions.

***Data type***: univariate (one variable) and normalized (rates or ratios)

## Usage
To make a choropleth map, you need one variable and a color value scale that will encode the values of your variable. It is possible to create a bivariate, or two variable choropleth map by creating two color scales, making them semi transparent and overlaying them. [^stevens]

Color in choropleth maps is especially important because
1. colors influence readers' perception of patterns in the map or make them see patterns where there are none);
2. readers can misinterpret the symbolism of colors used in a map. [^brewer] Colors should also be is a logical relationship with the data they represent. For example, showing density of population, it makes to show lower density as a less saturated hue and higher density as a more saturated hue of the same color. This [coloring tool](http://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3) chooses the colors automatically based on the data.

With a greyscale color scheme, one has to adjust for the tendency of the human eye to underestimate the lightness and darkness of a colors. In other words, there should be more difference between grey than when using chromatic colors. [^kemp]

The disadvantage of a choropleth map is that it tends to visually over-represent areas that happen to be geographically larger but are not as important in terms of the data that is being shown. An example of this, is population maps that show densely populated areas such as New York, Hong Kong, or Singapore as barely visible areas. 

[Cartograms](/cartogram) solve this problem by distorting the land area to represent population density or any other data.

There are two problems with choropleth maps in terms of statistical accuracy:
1. *Normalization* - using raw data (for example total population per state) rather than showing normalized data (in this case population for square mile).
2. *Ecological fallacy* also known as *aggregation bias* - assumes that data measured at a group level is also true at the individual level. For example, a state can be shown as having a high crime rate whereas in reality only one city in that state hass an unusually crime rate that drove up the crime rate of the entire state.

## Alternatives

1. [*Heatmap*](/heatmap) uses color to represent grouped data, however it does not overlay the data on a map.
2. [*Cartogram*](/cartogram) uses distortion of land area to represent data.
3. [*Bubble map*](/bubble-map) shows data as proportionally sized symbols, usually circles, overlaid over a map.
4. [*Dot map*](/dot-map) shows individual data points represents as dots overlaid over a map.
5. [*Dasymetric map*](/dasymetric-map) represents a statistical surface of density, most commonly population density.

## Sources

[^brewer]: [Mapping Mortality: Evaluating Color Schemes for Choropleth Maps by Cynthia A. Brewer et.al., nnals of the Association of American Geographers, Vol. 87, No. 3 (Sep., 1997), p. 411 ](https://www.jstor.org/stable/2564061?seq=1#page_scan_tab_contents)

[^kemp]: [Encyclopedia of Geographic Information Science by Karen Kemp, p. 37-38](https://books.google.fr/books?id=FrUQHIzXK6EC&pg=PT63&dq=choropleth&hl=en&sa=X&ved=0ahUKEwivhuO7-tHhAhXJxosBHV7-Cf0Q6AEIOzAD#v=onepage&q=choropleth&f=false)

[^scolum]: "Thematic Cartography and Geovisualization" by T. Slocum, et.al., 2009, 3rd ed, pages 85–86. Pearson Prentice Hall: Upper Saddle River, NJ.

[^stevens]: [Bivariate Choropleth Maps: A How-to Guide by Joshua Steves](http://www.joshuastevens.net/cartography/make-a-bivariate-choropleth-map/)

