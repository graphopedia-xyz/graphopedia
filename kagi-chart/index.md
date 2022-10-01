---
title: Kagi chart
  
functions:
- range

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
  - title:  2-Hour Kagi Chart
    link:   https://www.flickr.com/photos/90790980@N02/10865647303/in/photolist-dRqmZN-hyahoB-9UXxeJ-fMUESf-Smfq2p-dS5PKT

order: 230

---

shows price movements independently of time. This feature makes the Kagi a cleaner representation of the change in price and sentiment than the [candlestick chart](/candlestick-chart).

<!--more-->
In stock price analysis, Kagi charts track changes in the balance of power between buyers and sellers.[^confas]
A Kagi chart consists of with a series of vertical lines connected by short horizontal lines that reflect three variable of the price: color, thickness, and direction of the lines. The thickness and color of the line change each time the price reaches the high or low of the previous vertical line.

The direction of the line changes each time the price reaches a preset reversal amount, usually set at 4%. Only the closing price appears on a Kagi chart, unlike in the [candlestick chart](candlestick-chart) where both closing and opening prices appear.

When a direction change occurs, a short horizontal line connects the lines of the opposite direction.

The Kagi chart originates from Japan where during the 1870s it was used in stock trading.

## Alternatives
1. [*Candlestick chart*](candlestick-chart) plots bullish and bearish sentiment.
2. *Renko chart*  represents price movements by using bricks. Each time a price increases by a preset amount, a new brick appears.

## Sources
[^confas]: Confas, Abe [*Sentiment Indicators: Renko, Price Break, Kagi, Point, and Figure - What They Are and How to Use Them to Trade*](https://books.google.com/books?id=9JZ6U7JZVyQC) John Wiley & Sons, 2010, p.148.
