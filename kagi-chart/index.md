---
title: kagi chart
  
tags:
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
  - title:  2 hour Kagi Chart
    link:   https://www.flickr.com/photos/90790980@N02/10865647303/in/photolist-dRqmZN-hyahoB-9UXxeJ-fMUESf-Smfq2p-dS5PKT

---

shows price movements independently of time. This feature makes the Kagi a cleaner representation of the change in price and sentiment than the [candlestick chart](/candlestick-chart).

<!--more-->
Kagi charts are used in stock price analysis for tracking changes in the balance of power between buyers and sellers.[^confas]
A Kagi chart is made of with a series of vertical lines connected by short horizontal lines that reflect three variable of the price: color, thickness, and direction of the lines. The thickness/color of the line changes when the price reaches the high or low of the previous vertical line.

The direction of the line changes when the price reaches a preset reversal amount, which is usually set at 4%. Only the closing price is shown on the Kagi chart, unlike in the [candlestick chart](candlestick-chart) where both closing and opening prices are shown.

When a direction change occurs, a short horizontal line is drawn between the lines of opposite direction.

The Kagi chart originates from Japan where during the 1870s it was used in stock market started trading.

## Alternatives
1. [*Candlestick chart*](candlestick-chart) plots bullish and bearish sentiment.
2. *Renko chart*  represents price movements by using bricks. If a price has moved higher by a prescribed amount, a new brick is added.

## Sources
[^confas]: Confas, Abe [Sentiment Indicators: Renko, Price Break, Kagi, Point and Figure - What They Are and How to Use Them to Trade](https://books.google.com/books?id=9JZ6U7JZVyQC) John Wiley & Sons, 2010, p.148
