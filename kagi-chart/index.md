---
title: Kagi chart
  
tags:

related:
  - candlestick-chart

tools:
  - name:   FusionCharts
    link:   https://www.fusioncharts.com/dev/chart-guide/standard-charts/kagi-chart
    
  - name:   D3
    link:   https://bl.ocks.org/arpitnarechania/41d53792f562df4a2ad6f704ef242af5

  - name:   Wolfram Mathematica
    link:   https://www.wolfram.com/mathematica/new-in-8/financial-visualization/kagichart.html

examples:
  - title:  2 hour Kagi Chart
    link:   https://www.flickr.com/photos/90790980@N02/10865647303/in/photolist-dRqmZN-hyahoB-9UXxeJ-fMUESf-Smfq2p-dS5PKT

---

shows price movements independently of time. This feature makes the Kagi a cleaner representation of the change in price and sentiment than the candlestick chart.
A Kagi chart is made of with a series of vertical lines connected by short horizontal lines. The color, thickness, and direction of the lines is based on the price. The thickness/color of the line changes when the price reaches the high or low of the previous vertical line.
The direction of the line changes when the price reaches a preset reversal amount, which is usually set at 4%. When a direction change occurs, a short horizontal line is drawn between the lines of opposite direction.

<!--more-->

## Origin
The Kagi chart originates from Japan where during the 1870s it was used in stock market started trading.

## Sources
1. [Sentiment Indicators: Renko, Price Break, Kagi, Point and Figure - What They Are and How to Use Them to Trade](https://books.google.com/books?id=9JZ6U7JZVyQC)
2. [Beyond Candlesticks: New Japanese Charting Techniques Revealed by Steve Nison](http://www.saham-indonesia.com/Ebooks/Technical%20Analysis/Steve%20Nison-%20Beyond%20Candlesticks.pdf)
