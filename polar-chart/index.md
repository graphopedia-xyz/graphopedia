---
title:  polar area chart 

tags:
- change over time
- comparison


related:
  - pie-chart

tools:
  - name:   Chart js
    link:   https://www.chartjs.org/docs/latest/charts/polar.html

  - name:   Plotly
    link:   https://plot.ly/r/polar-chart/

examples:
  - title:  Diagram of The Causes of Mortality
    author:  Florence Nightingale
    link:   
    image:  nightingale-mortality.jpg
    
  - title: Coastal Fisheries Success Factors
    author:  Threestory Studio
    link: http://fisheriesviz.issuelab.org/
    image:  fisheries.png
  

  - title:  Number of Electoral Votes in 2012 Election
    author: Alex Bordens
    link:   http://alexbordens.com/img/pdf/election-results.pdf
    image:  election-results-2012.png
    
  - title:  Street Orientations in U.S. cities
    author: Geoff Boeing
    link:  https://geoffboeing.com/2018/07/comparing-city-street-orientations/
    image:  city-street-orientations-usa.png
  
  - title:  Pollution Profile by Country
    author:  Alberto Lucas López
    link:  https://www.scmp.com/infographics/article/1674099/infographic-pollution-profile
    image:  pollution-profile-by-country.png
    
synonyms: 
  - coxcomb chart
  - polar area diagram
  - polar area graph
  - Nightingale chart
  - Nightingale rose graph
  - windrose chart
  - rose chart

---

is a type of [pie chart](/pie-chart) in which all sectors have equal angles differing only in how far each segment extends from the center of the circle. [^friendly]  The data is represented as the area, not the height, of a sector.

<!--more-->
The polar area chart is used to plot circular data[^fisher]. Each segment of a polar area chart represents a value through its area, not arc length or radius. The segments can be stacked, similar to a stacked bar chart, only presented in polar coordinates.

Cyclical phenomena, such as monthly weather patterns, are the best use case of the polar area chart. However, the drawback of the polar chart is that it makes the outer segments seem more significant. 

The difficulty in interpreting this chart comes from the limits of human perception to correctly estimate areas of circles and their sectors.

The polar area chart is not to be confused with a [radial bar chart](/bar-chart#radial-bar-chart). It also laid out radially, but it uses the bar length, not the area, to represent a value.


## Sources
[^friendly]:Friendly, Michael. ["The golden age of statistical graphics."](https://www.jstor.org/stable/20697655) *Statistical Science* (2008): 502-535. [PDF](https://arxiv.org/pdf/0906.3979.pdf)
[^fisher]: Fisher, Nicholas I. [*Statistical analysis of circular data.*](https://books.google.com/books?id=wGPj3EoFdJwC) cambridge university press, 1995. p.5.
