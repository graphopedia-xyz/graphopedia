---
title: candlestick chart

related:
  - kagi-chart
  - box-plot

tools:
  - name:   Plotly
    link:   https://plot.ly/r/candlestick-charts/

  - name:   D3
    link:   https://beta.observablehq.com/@mbostock/d3-candlestick-chart
    
  - name:   Fusion Charts
    link:   https://www.fusioncharts.com/resources/chart-primers/candlestick-chart

examples:
  - title:  Painters in the Making 
    author: Accurat
    link:   https://cdn-images-1.medium.com/max/2000/1*P03I3M4jaE4F8T3N67G39w.jpeg
    
  - title:  Zoomable Candlestick Chart
    link:   https://bl.ocks.org/tompiler/6045b80d2164077faaf96e0304531bba

---

shows price movements over time of a security, derivative, or currency. Usually one candlestick shows a single day.
Candlestick chart are similar to [box plots](/box-plot) in that both show maximum and minimum values. Box plots, however, carry more information showing the values in between. 

<!--more-->

Candlestick charts were first described by a wealthy Japanese rice trader Munehisa Homma, who wrote 160 rules describing various patterns of trading.[^nison]


Today the Japanese Candlestick chart is still widely used in financial trading. To gain the skill of analyzing a lot of data fast, traders study the patterns that candlestick charts can form. In infographics and data visualization, candlestick charts can be used with large data sets when it is important to show the median values and how they change over time.


The data needed for creating a candlestick is similar to that of a stock price bar chart:  open, high, low, and close prices. [^morris]
Candlestick charts are used to discover patterns in the change of values. Such patterns have been extensively studied and many of them have specific names.

*Doji pattern* resembles a plus sign or a cross. It has no real body (or a very small one), and its shadows vary in length. A Doji means indecision.

*Hanging Man* appers at the upper end of the trading range with a small body, a long lower shadow, and no upper shadow. It means an upcoming reversal during an upward trend. The longer its lower shadow, the more likely the reversal.

*Harami* a long-bodied candle that is the same color as the current trend during an upward or downward trend, followed by a small candle of the opposite color that opens and closes within the first candle’s body. There is both a bullish and a bearish form of the Harami pattern.

*Engulfing* When a second candle (of opposing color) “engulfs” the first candle by opening higher than the previous day’s open and closing lower than the previous day’s close, Engulfing pattern forms. This signal can be bearish or bullish, depending on the colors of the candles. When you spot an Engulfing pattern, a reversal is likely just around the corner.


## Sources
[^morris]: [Candlestick Charting Explained: Timeless Techniques for Trading Stocks and Futures](http://wordpress1.rm7mills.com/notasaham/wp-content/uploads/sites/3/2017/08/Candlestick-Charting-Explained-Gregory-Morris.pdf)
[^nison]: [Japanese Candlestick Charting Techniques by Steve Nison](https://www.forexfactory.com/attachment.php/2269015?attachmentid=2269015&d=1492350521)
