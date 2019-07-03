---
title:  slopegraph

tags:

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



---
is a type of [line graph](/line-graph) for multiple categories that are ranked, usually over time or at equal intervals . Slopegraphs are a way of showing change along two axes by means of a connecting line and comparing those changes across multiple categories. 

<!--more-->
Slopegraphs were introduced by Edward Tufte in his book *The Visual Display of Quantitative Information* (1983), calling is a "table-graphic" that organizes data both vertically and horizontally. [^tufte]

A list of categories appears vertically followed with categories ranked based on the initial data point. 

Slopegraphs compare changes, usually over time or at equal intervals.  A two-point line slope is displayed for each category. Multiple slopes can be presented per category. Next the categories are reordered in the list on the right based on their rank. The numeric values for each interval is marked as number. The numbers are positioned along the Y axis but the axis itself may or may not be shown. 

Slopegraphs are a laconic way of showing a lot of data: the hierarchy of the categories, the specific number values associated with each, the change of each category over time, how that change compares to changes of other categories, any abnormal patterns.

Slopegraphs are similar to [bump charts](bump-chart) and bump charts can be considered a type of slopegraph. Both display categories in a ranked order. The difference is that in a bump chart numeric values are not positioned on the Y axis but only the rank is reflected.

Slopegraphs can be used as [small multiples](/small-multiples), even without the axes such that only the slope angle is compared. [^tufte2]

Slopegraph are also similar to [parallel coordinates plot](/parallel-coordinates) but the vertical axes in parallel coordinates each represent a different type of variable that can even have different scales, while the slopegraph vertical axes are all time or interval axes with the same scale.


## Sources
[^tufte]: Edward Tufte (1983). The Visual Display of Quantitative Information. Graphics Press. p. 158-159
[^tufte2]: [Edward Tufte forum](https://www.edwardtufte.com/bboard/q-and-a-fetch-msg?msg_id=0003nk). Retrieved May 24, 2019.

