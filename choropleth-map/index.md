---
title:  choropleth map
  
tags:
- geospatial data

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
is a type of thematic map in which areas are colored to represent a variable proportionally to the colored area. A color legend links colors with values or value ranges.

<!--more-->
A choropleth map shows in data by geographic region. For this, the data needs to be normalized, which means the data must be expressed in rates or ratios.

To create a choropleth map, one needs a single variable and a color value scale that encodes the values of that variable. It is possible to make a two-variable (bivariate) choropleth map by creating two color scales, then making each semi-transparent and overlaying them. [^stevens]

The choice of a choropleth map color scheme has to follow a color logic that avoids these known perception issues:
1. certain combinations of colors influence a reader's perception of map patterns, making readers see patterns where none exist;
2. readers can misinterpret the symbolism of colors used in a map,[^brewer] for example, associating green with positive trends and red with negative trends. 

Colors are expected to have a logical relationship with the data they represent. For example, when showing population density, it makes sense to display lower densities as less saturated hues and higher densities as more saturated hues of the same color. The ColorBrewer [coloring tool](http://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3) is a widely used tool for choosing colors based on data.

With a greyscale color scheme,  there should be more difference between grey than when using chromatic colors. [^kemp]  The human eye tends to underestimate the lightness and darkness of monochromatic areas.

A disadvantage of choropleth maps is the tendency to visually over-represent areas that are less significant in the context of the data but happen to be geographically larger. An example of this is a population map showing densely-populated places like Hong Kong or Singapore as barely visible areas on a world map. 

[Cartograms](/cartogram) solve this problem by distorting the land area to represent population density or any other data variable.

Choropleth maps also have problems in terms of statistical accuracy:
1. *Normalization* - using raw data rather than showing normalized data leads to a false comparison. For example, comparing the total state population does not make sense since states have different land areas. Instead, the data should be normalized as population per square kilometer.
2. *Ecological fallacy* also known as *aggregation bias* assumes that data measured at a group level is also accurate at the individual level. Since choropleth maps show data per geographic region, they do not show the variation inside that region. For example, a region appears to have a high crime rate, but in reality, it has only one unusually high-crime city driving up the numbers of the entire region. The [dasymetric map](/dasymetric-map) solves the ecological fallacy problem by dividing regions into sub-areas of the same size.

Baron Pierre Charles Dupin introduced the choropleth map in 1826. The term "choropleth map" appeared in 1938 in <cite>Problems in Population Mapping</cite> by the geographer John Kirtland Wright.

## Alternatives

1. [*Dasymetric map*](/dasymetric-map) uses color to represent data per unit of area. Regions are divided into equally-sized units.
2. [*Cartogram*](/cartogram) uses the distortion of land area to represent data.
3. [*Bubble map*](/bubble-map) shows data as proportionally sized symbols overlaid over a map, and displaying a single data point per region.
4. [*Dot map*](/dot-map) shows individual data points represented as dots overlaid on a map.

## Sources

[^brewer]: [Mapping Mortality: Evaluating Color Schemes for Choropleth Maps by Cynthia A. Brewer et al., Annals of the Association of American Geographers, Vol. 87, No. 3 (Sep. 1997), p. 411 ](https://www.jstor.org/stable/2564061?seq=1#page_scan_tab_contents)

[^kemp]: [Encyclopedia of Geographic Information Science by Karen Kemp, p. 37-38](https://books.google.fr/books?id=FrUQHIzXK6EC&pg=PT63&dq=choropleth&hl=en&sa=X&ved=0ahUKEwivhuO7-tHhAhXJxosBHV7-Cf0Q6AEIOzAD#v=onepage&q=choropleth&f=false)

[^scolum]: "Thematic Cartography and Geovisualization" by T. Slocum et al., 2009, 3rd ed, pages 85–86. Pearson Prentice Hall: Upper Saddle River, NJ.

[^stevens]: [Bivariate Choropleth Maps: A How-to Guide by Joshua Steves](http://www.joshuastevens.net/cartography/make-a-bivariate-choropleth-map/)
