---
title:  barcode plot
  
tags:
- distribution

tools:

  - name:   R (code tutorial)
    link:   https://flowingdata.com/2017/12/04/compact-ways-to-visualize-distributions-in-r/

  - name:   Observable D3 (code)
    link:   https://observablehq.com/@d3/barcode-plot
    
  - name:   Matplotlib (code)
    link:   https://matplotlib.org/3.1.0/gallery/images_contours_and_fields/barcode_demo.html

examples:
  - title:  Warming Stripes
    author:  Ed Hawkins
    link:   http://www.climate-lab-book.ac.uk/2018/warming-stripes/
    note:   
    image:  climate-change-bar-code-chart.png

  - title:  Average Annual temperature in Canadian Cities
    author:  CBS News
    link:   https://www.cbc.ca/news/technology/charts-climate-change-bar-codes-1.4802293
    note:   
    image:  annual-temperature-canadian-cities.png
    
  - title:  The Most Typical City in America
    author:  Karl Sluis
    link:   https://shift.newco.co/2017/01/17/Lynchburg--Virginia--The-Most-Typical-City-in-America/
    note:   
    image:  most-typical-city-in-america.png



synonyms:
 - barcode chart
 - rug plot
---

shows a distribution of a single variable. The lines represent individual data points on a single axis.

<!--more-->
Bar code plots are one-dimensional charts that show distribution by representing every observation with a line. The axis along which the lines appears is usually not drawn.
The axis usually shows numbers, percentages or categories. 

Barcode plots a usually used to plot a categorical and a numeric variable. [^hilfiger]

Because of its compactness, the barcode plot is often used in [small multiples](/small-multiples) that compare multiple distributions.

Barcode plots are similar in function to [strip plot](/strip-plots) and are sometimes referred to by that name.

## Sources
[^hilfiger]: Hilfiger, John Jay. [Graphing Data with R: An Introduction.](https://www.amazon.com/dp/1491922613/) O'Reilly Media, Inc., 2015,  p.197.
