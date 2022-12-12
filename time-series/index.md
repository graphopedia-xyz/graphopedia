---
title: time series
  
functions:
  - change over time
  - correlation

related:
  - line-graph

tools:
  - name:   Microsoft Excel tutorial
    link:   https://serc.carleton.edu/hydromodules/steps/td1.html

  - name:   Plotly
    link:   https://plot.ly/javascript/time-series/

examples:
  - title:  How the Recession Reshaped the Economy in 255 Charts
    author: The New York Times
    link:   https://www.nytimes.com/interactive/2014/06/05/upshot/how-the-recession-reshaped-the-economy-in-255-charts.html
    image:  how-recession-reshaped-economy-in-255-charts.png
    
  - title: Earth's Relentless Warming Sets a Brutal New Record in 2017
    author: Bloomberg
    link:   https://www.bloomberg.com/graphics/hottest-year-on-record/
    image:  hottest-year-on-record.png
    
  - title:  Alone Time
    author:  Nathan Yau
    link:  https://flowingdata.com/2017/06/26/alone-time
    image:  people-who-are-alone.png

order: 90

---

is a type of [line chart](/line-chart) that shows discrete data points in chronological order connected with line. 

<!--more-->
A time-series graph is drawn on the horizontal and vertical axes. The time appears on the horizontal axis. Typically, the time is plotted at equal intervals unless the chart covers a very long period, in which case a logarithmic scale is more useful. [^harris]The X-axis represents time. Time units can cover minutes, hours, days, weeks, and years. The Y-axis represents a quantitative value. The vertical axis can display percentages, ratios, duration, and repetition.


Depending on the underlying data, a time series can be *continuous* or *discrete*. A time series is continuous when observations are recorded and plotted without interruptions in time. A time series is discrete when observations are taken at specific points in time, even if they are equally spaced. 

The most common use case of a time-series is displaying equally spaced data points and the line of best fit. 

<!-- from variations -->
Time series variations involve positioning multiple time series in the same graph space. Another possibility is arranging separate time-series graphs in a grid or a row for comparison.[^javed]


## Further reading
1. [Time series](https://en.wikipedia.org/wiki/Time_series) article on Wikipedia.

## References
[^harris]: Harris, Robert L. [*Information graphics: A comprehensive illustrated reference.*](https://books.google.com/books?id=LT1RXREvkGIC) Oxford University Press, 2000. p. 920.
[^javed]: Javed, Waqas, Bryan McDonnel, and Niklas Elmqvist. ["Graphical perception of multiple time series."](https://doi.org/10.1109/TVCG.2010.162) *IEEE transactions on visualization and computer graphics* 16.6 (2010): 927-934. [PDF](https://engineering.purdue.edu/~elm/projects/multilinevis/multilinevis.pdf)

