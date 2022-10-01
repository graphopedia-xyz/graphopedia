---
title:  area chart
  
functions:
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

  - title:  Interest of the National Debt from the Revolution, 1786
    author: William Playfair
    link:   https://en.wikipedia.org/wiki/Area_chart#/media/File:1786_Playfair_-_25_Interest_of_the_national_Debt_from_the_Revolution.jpg
    image:  playfair-national-debt.jpg
    
  - title:  Breakdown of China's Population By Age Group
    author:  BBC
    link:   https://ourworldindata.org/wp-content/uploads/2018/09/Internet-users-by-world-region.png
    image:  china-population.png
    
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
    
order: 20

---

displays data as the area between the data curve and the horizontal axis. Area charts emphasize the change of a single variable by connecting individual data points. 


<!--more-->
The ***X-axis*** has a numeric or a categorical scale. The ***Y-axis*** is usually categorical. ***Value markers*** typically indicate individual data points when few of them appear in the chart.

The purpose of an area chart is visualizing the change of a single variable. Functionally, area charts are the same as [line charts](/line-chart). Visually, using the area instead of a line makes the shape of the data more noticeable. Especially for multi-line charts and stacked or grouped area charts the filled area below the data curve improves the chart's readability. 

Even though an area chart consists of individual data points, its purpose is not in communicating a set of specific values but in showing their relationships. For this reason, the data points typically do not have labels.

Area charts are used forindicating trends, comparing trends, their changes, and relationships between values. Color and texture can emphasize these relationships. [^harris]

Like [bar charts](/bar-chart), area charts emphasize change and trends. But an area chart can display more data points in the same space. 

Area charts can have three types of data curves depending on their data aggregation method: segmented, stepped, and smoothed.

William Playfair introduced area charts in 1786 in his book *The Commercial and Political Atlas*.

## Alternatives

1. [*Bar chart*](/line-chart) displays the relationship of a category to a numeric variable as the height a rectangle bar.

2. [*Line chart*](/line-chart), functionally the same as an area chart, a line chart is more suitable for cases where multiple line charts are displayed in the same graph space.

3. [*Streamgraph*](/stream-graph) is a type of stacked area chart aligned relative to central axis. Streamgraphs have a smoothed curve. They are normally oriented horizontally.

## Sources

[^harris]: Harris, Robert L. [*Information graphics: A comprehensive illustrated reference.*](https://books.google.com/books?hl=en&lr=&id=qusmDAAAQBAJ) Oxford University Press, 2000. p. 10
