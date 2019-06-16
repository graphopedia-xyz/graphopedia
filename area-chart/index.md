---
title:  area chart
  
tags:
- change over time

related:
  - line-graph
  - stream-graph

tools:
  - name:   D3.js
    link:   https://bl.ocks.org/mbostock/3883195

  - name:   Google Charts
    link:   https://developers.google.com/chart/interactive/docs/gallery/areachart

  - name:   Microsoft Excel
    link:   https://office.microsoft.com

  - name:   Apple Numbers
    link:   https://www.apple.com/numbers

  - name:   Google Docs
    link:   https://docs.google.com

  - name:   High Charts
    link:   https://www.highcharts.com/docs/chart-and-series-types/area-chart

  - name:   Adobe Illustrator (chart tool)
    link:   http://www.adobe.com/Illustrator

examples:
  - title:  Breakdown of China's Population By Age Group
    author:  BBC
    link:   https://ourworldindata.org/wp-content/uploads/2018/09/Internet-users-by-world-region.png
    image:  china-population.png

  - title:  Internet Users by Region
    author: Max Rosner
    link:  https://www.bbc.com/news/world-asia-china-46772503
    image:  internet-users-by-world-region.png
    
  - title:  When And How I Will Die
    author: Nathan Yau
    link:   https://flowingdata.com/2016/01/05/causes-of-death/
    image:  causes-of-death.png
    
  - title:  Thirty Years of Atlantic Hurricanes
    author: Axios
    link:   https://www.axios.com/thirty-years-of-atlantic-hurricanes-1513305322-8b3c056a-ff13-49dc-a95d-961481119907.html
    image: atlantic-hurricanes.png
    
  - title:  Percentage of People Who Are Married, By Age
    author: Nathan Yau
    link:   https://flowingdata.com/2013/09/25/the-most-unisex-names-in-us-history/
    image:  percentage-of-married people-by-age.png
  
  - title:  Where Are All The Fish?
    author: Thomas Porostocky
    link:   https://www.good.is/infographics/transparency-where-are-all-the-fish#open
    image:  fish-in-sea.jpg
    
  - title:  Interest of the National Debt from the Revolution, 1786
    author: William Playfair
    link:   https://en.wikipedia.org/wiki/Area_chart#/media/File:1786_Playfair_-_25_Interest_of_the_national_Debt_from_the_Revolution.jpg
    image:  playfair-national-debt.jpg
    

---

represents data as the area between the data curve and the horizontal axis. [^1] Area charts show the change of a single variable. The X axis can have a numeric or categorical scale, while the Y axis is usually categorical. Functionally, the area chart is the same as a [line chart](/line-chart).


William Playfair first introduced an area chart in 1786 in his book *The Commercial and Political Atlas*.

<!--more-->

## Purpose
Area charts show the change of a single variable. Generally, area charts are not used to show a specific value but rather emphasize a trend, a change or the relationship between values. For this purposes part of the area of in the chart can be colored or textured for emphasis.[^2]
## Usage
Area charts can have three types of curves depending on how the data was aggregated: segmented, stepped, and smoothed.

##Types

Stacked area chart - area charts that show multiple data curves and the area between them are stacked area charts. Normally, the curve with less variation should be shown at the bottom, closer to the X axis.[^5] Stacked area charts are known to be difficult to perceive because the human eye does not judge area shown relative to a curved line as well as relative to a straight line.[^6]



## Alternative Charts

[Line chart](/line-chart) - functionally similar to area charts, line charts can be stacked and grouped more easily than area charts.

[Streamgraph](/stream-graph) - a stream graph is a type of stacked area chart which is shown relative to a central axis. Stream graphs have a smoothed curve. They are normally oriented horizontally.


## Sources

[^1]: ["The Grammar of Graphics" by Leland Wilkinson, p. 87](https://books.google.com/books?id=ZiwLCAAAQBAJ&printsec=frontcover&dq=%22area+diagram%22+visualization&hl=en&sa=X&ved=0ahUKEwj6gIWivrPhAhWiyosBHfXzDPYQ6AEIKDAA#v=snippet&q=area%20chart&f=false)
[^2]: ["Information Graphics: A Comprehensive Illustrated Reference" by Robert L. Harris, p. 10](https://books.google.fr/books?id=qusmDAAAQBAJ&printsec=frontcover&dq=%22area+graph%22+visualization&hl=en&sa=X&ved=0ahUKEwjz_cjqv7PhAhW9yIsBHc6dDQMQ6AEIWzAJ#v=onepage&q=%22area%20graph%22%20visualization&f=false)
[^5]: ["Data Visualization Handbook" by Juuso Koponen and Jonatan Hilden, p. 210](https://shop.aalto.fi/p/971-data-visualization-handbook/)
[^6]: [Assessing the Readability of Stacked Graphs](https://hal.inria.fr/hal-01587962/document)
