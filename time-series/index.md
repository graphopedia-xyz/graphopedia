---
title: time series
  
tags:
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
    
  - title:  Earth’s Relentless Warming Sets a Brutal New Record in 2017
    author: Bloomberg
    link:   https://www.bloomberg.com/graphics/hottest-year-on-record/
    image:  hottest-year-on-record.png
    
  - title:  Alone Time
    author:  Nathan Yau
    link:  https://flowingdata.com/2017/06/26/alone-time
    image:  people-who-are-alone.png
  
  - title:  How Americans Spend Their Day
    author:  The New York Times
    link:  https://flowingdata.com/2017/06/26/alone-time
    image:  how-americans-spend-their-day.jpg

---

is a type of [line chart](/line-chart) that shows discrete data points in chronological order. The most common use case is displaying equally spaced data points and the line of best fit. The time is plotted on the horizontal axis. Normally, the time is plotted at equal intervals unless the chart covers a very long period of time, in which case a logarithmic scale is used. [^harris]

<!--more-->
A time series graph consists of two axes, the horizontal and vertical. The X axis represents a time. Time units can cover minutes, hours, days, weeks, and years. The Y axis represents a quantitative value, respectively. The vertical axis can display percentages, ratios, duration and repetition.
Depending on the underlying data, a time series can be *continuous* or *discrete*. A time series is continuous when observations are recorded and plotted continuously in time, without gaps. A time series is discrete when observations are taken at specific times, even if they are equally spaced. 

## Variations
Time series variations involve the position of multiple time series relative to others in the same graph space or positioning them in their own graph space but such that it is easy to compare them.[^javed]

### Stacked time series
<img src="stacked-time-series.svg" alt="stacked time series" class="f-right-half" /> Uses the same graph space to plot multiple time series.

### Horizon chart
<img src="horizon-chart.svg" alt="horizon chart" class="f-right-half" />  Uses the concept of *virtual resolution* by limiting the graph space using the bands that make only the part of the graph visible.

### Braided time series 
<img src="braided-time-series.svg" alt="braided time series" class="f-right-half" /> Solves the problem by identifying the intersection points in time where two time series change value ordering.
<!-- @anna please check this graph type -->

### Radial time series
<img src="radial-time-series.svg" alt="radial time series" class="f-right-half" />  Use polar coordinates instead of the traditional coordinates. It is useful for showing cyclical events.

### Spiral time series
<img src="spiral-time-series.svg" alt="spiral time series" class="f-right-half" /> Uses polar coordinates for events that following a repeating pattern but are not necessarily cyclical.

###  Fan chart (time series)
<img src="fan-chart-time-series.svg" alt="fan chart (time series)" class="f-right-half" />  In time series analysis, a fan chart is a chart that joins a simple line chart for observed past data, by showing ranges for possible values of future data together with a line showing a central estimate or most likely value for the future outcomes.
<!-- @anna rewrite this text, copy-paste from wikipedia -->


## Sources
[^harris]:[Robert L. Harris. 1999. Information Graphics: A Comprehensive Illustrated Reference. Oxford University Press, Inc., New York, NY, USA. p. 920](https://books.google.com/books?id=LT1RXREvkGIC&printsec=frontcover&source=gbs_ViewAPI&redir_esc=y#v=onepage&q&f=false)
[^javed]: [W. Javed, B. McDonnel and N. Elmqvist, "Graphical Perception of Multiple Time Series," in IEEE Transactions on Visualization and Computer Graphics, vol. 16, no. 6, pp. 927-934, Nov.-Dec. 2010.
 doi: 10.1109/TVCG.2010.162](https://engineering.purdue.edu/~elm/projects/multilinevis/multilinevis.pdf)
