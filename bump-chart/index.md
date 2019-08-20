---
title:  bump chart

tags:
- change over time

related:

synonyms:
- bumps chart
- bubble sort
- sinking sort

tools:
  - name:   D3.js
    link:   https://d3js.org/

  - name:   D3 code example by Robert Gove
    link:   https://bl.ocks.org/rpgove/53bb49d6ed762139f33bdaea1f3a9e1c

examples:
  - title:  22 Years of Bumps Races (Women)
    author:  Tim Granger
    link:   http://www.mcshane.org/bumps/images/mays_women.png
    image:  women-bump-race.png
    
  - title:  Ranking China's provinces by GDP per capita, 1978-2017
    author:  Trivium China
    link:   https://triviumchina.com/data-viz/40-years-of-growth-ranking-chinas-provinces-by-gdp-per-capita-1978-2017/
    note:   
    image:  provincial-rank-gdp-per-capita-1979-2017-1.jpg

  - title:  Most Popular Fields of Study, Since 1970
    author:  Nathan Yau
    link:   https://flowingdata.com/2016/12/07/fields-of-study-ranked-over-past-few-decades/
    image:  most-popular-fields-of-study-since-1970.png

  
---

is a type of [line chart](/line-graph) for multiple categories that are ranked, usually through time.

<!--more-->
The "bumps chart" was created by Tim Granger using 14 years of data from the Cambridge "Bumps" races which is a rowing team tournament. In his book *Beautiful Evidence*, Edward Tufte cites this particular chart as an example of "800 interwoven [sparklines](/sparkline)" meaning this chart is data-rich.[^tufte]

In software packages such as Tableau, the chart is now called "bump chart." [^sleeper]

Bump charts have no axes, unlike a stacked line graph. Categories are labeled at the begining and end of each row so that the initial and final rankings are evident. The time intervals are labeled for each vertical. The line graph for each category is reordered according to the rank for each time interval.

Bump charts emphasize ranking through time. The time is normally displayed at equal intervals. Bump charts can also be thought of as [slopegraphs](/slopegraph) with a time dimension.

The dots or circles drawn at each point where the line graph passes through the time vertical are not required.

## Sources
[^tufte]: Edward Tufte (2006). Beautiful Evidence. Graphics Press. p. 56 ↩
[^sleeper]: Sleeper, Ryan. [Practical Tableau: 100 Tips, Tutorials, and Strategies from a Tableau Zen Master.](https://books.google.fr/books?id=mfhTDwAAQBAJ) "O'Reilly Media, Inc.," 2018. p. 271.
