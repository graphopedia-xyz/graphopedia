---
title:  slopegraph

functions:
  - change over time
  - correlation

visualizationPrinciples:
  - positioning on a coordinate axis
  - connecting

axisDirections:
  - vertical

related:

synonyms:
  - slope graph
  - ladder graph


tools:
  - name:   D3.js example by Cale Tilford
    link:   https://bl.ocks.org/tlfrd/042b2318c8767bad7a485098fbf760fc/df83d66e55cf7c03ef726b1e2edea4243c00fa2f


examples:
  - title:  Infant Mortality
    author:  The New York Times
    link:   https://archive.nytimes.com/www.nytimes.com/imagepages/2009/04/06/health/infant_stats.html
    image:  infant-mortality.png
    
  - title:  City Liveability Index
    author:  The Economist
    link:   https://www.economist.com/graphic-detail/2014/08/19/the-best-places-to-live
    note:   
    image:  city-liveability-index.png

  - title: The Latin America and Caribbean Countries in The Global Competitiveness Report
    author:  
    link:   https://flowingdata.com/2016/12/07/fields-of-study-ranked-over-past-few-decades/
    image:  latin-america-competitiveness.png

  - title: Missing Opportunities
    author:  The Economist
    link:   https://www.economist.com/graphic-detail/2018/09/20/citizens-basic-needs-are-being-met-but-they-lack-opportunities
    image:  social-progress.png

order: 190

---
is a type of [line graph](/line-graph) for multiple categories that are ranked, usually over time or at equal intervals. Slopegraphs visualize a change in rank along two axes using a connecting line and comparing those changes across multiple categories. 

<!--more-->
The charts start with a list of ***initial ranks*** for all the variables. The ***time intervals*** run along the horizontal axis, although the axis is not displayed. The change in rank for each time interval is displayed as a ***slope line*** and either a dot or a numeric value indicating the value for that time period. The positions of each value shift on along their numeric axis, even though the axis itself is not displayed.  The ***final rank*** is shown as a list.

Edward Tufte introduced Slopegraphs in his book *The Visual Display of Quantitative Information* (1983), calling it a "table-graphic" that organizes data both vertically and horizontally. [^tufte]

A list of categories appears vertically followed by ranked categories based on the initial data point. 

Slopegraphs compare changes, usually over time or at equal intervals.  At least one two-point line slope appears in each category in the graph. Multiple slope lines per category are also possible. At each interval, categories appear in the order of their current rank. Their numeric values show up along the Y-axis although the axis itself does not necessarily appear.

Slopegraphs are a concise way of showing a lot of layers of data. The category hierarchy, specific number values, change of category rank over time, change compared to changes of other categories, and the overall pattern of change can all comprise the information layers of a slopegraph.

Slopegraphs are similar to [bump charts](/bump-chart) that itself be considered a type of slopegraph. Both display ranked categories. The difference is that in a bump chart, numeric values do not appear on the Y-axis with only the rank reflected.

Slopegraphs are suitable for use as [small multiples](/small-multiples), even without the axes such that the comparison is only between the angles of the slopes. [^tufte2]

Slopegraphs are also similar to [parallel coordinates plots](/parallel-coordinates) except that the vertical axes in parallel coordinates each represent a different type of variable, possibly with a different scale. The slopegraph vertical axes are always time or interval axes and with the same scale.


## References
[^tufte]: Tufte, Edward R. [*The visual display of quantitative information.*](https://www.edwardtufte.com/tufte/books_vdqi) Vol. 2. Cheshire, CT: Graphics press, 2001. p. 158-159.
[^tufte2]: [Edward Tufte forum](https://www.edwardtufte.com/bboard/q-and-a-fetch-msg?msg_id=0003nk). Retrieved May 24, 2019.
