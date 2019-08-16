---
title:  bubble chart

tags:
  - correlation
  - distribution
  - change over time

related:
  - scatter-plot
  - marimekko-chart

tools:
  - name:   Apple Keynote
    link:   https://support.apple.com/kb/ph16952
 
  - name:   Numbers for Mac
    link:   https://support.apple.com/kb/PH17003
 
  - name:   MS Excel
    link:   https://support.office.com/en-us/article/bubble-and-scatter-charts-in-power-view-bae4a433-afae-46eb-9a28-2fe09abb2a8d
    
  - name:   Gapminder (for animated bubble chart)
    link:   https://www.gapminder.org/tools-offline/

examples:

  - title:  Jobs Most At Risk From Automation
    author:  The Financial Times
    note:
    link:  https://www.ft.com/content/f64089c6-6681-11e9-9adc-98bf1d35a056
    image:  jobs-at-risk-from-automation.png

  - title:  Fortune 500 Through The Ages
    author: Nicolas Rapp
    note:   A bubble chart of top 500 American companies by revenue and by industry from 1780 to 2018.
    link:   https://nicolasrapp.com/studio/portfolio/the-fortune-500-through-the-ages
    image:  age-of-500.png
 
  - title:  China Overseas Investment
    author: Alberto Lucas Lopez
    note:
    link:   https://multimedia.scmp.com/china-overseas-investments/
    image:  china-overseas-investment.png
 
  - title:  The Language of the State of the Union
    author: The National Post graphics team
    note:   A bubble chart showing popular words in State of the Union Addresses for different presidents
    link:   https://nationalpostcom.files.wordpress.com/2012/01/fo0225_stateoftheunion-2.pdf
    image:  words-of-the-union.jpg
 
  - title:  Snake Oil Supplements?
    author: David McCandless
    note:   A bubble chart sorting food supplements into categories by evidence of usefulness.
    link:   http://informationisbeautiful.net/visualizations/snake-oil-scientific-evidence-for-nutritional-supplements-vizsweet
    image:  snake-oil-supplements.png
    
  - title:  Lunar Conversations 
    author: Nicholas Rougeux
    note:   A timeline of the conversations between Earth and the spacecraft of the Apollo 11 mission from liftoff to splashdown. The number of words spoken is visualized as a bubble chart along the timeline. 
    link:   https://www.c82.net/work/?id=368
    image:  lunar-chats.png
    
  - title:  Global Carbon Emissions
    author: Stanford Kay
    note:   Circle-packed bubble chart showing emissions per country
    link:   http://www.stanfordkaystudio.com/information.html
    image:  global-carbon-footprint.png
    
  - title:  Frequency of Sex Among Married and Unmarried Couples
    author: Nathan Yau
    note:   A bubble chart comparing the frequency of sex for married and unmarried people sorted by age
    link:   https://flowingdata.com/2017/07/03/married-people-sex
    image:  married-sex.png

  - title:  Money Race and Success
    author: The New York Times
    link:   https://www.nytimes.com/interactive/2016/04/29/upshot/money-race-and-success-how-your-school-district-compares.html?mtrref=undefined&mtrref=www.nytimes.com
    image:  school-district-income-race-success.png
 
  - title:  Debt Around the World 
    author: IMF
    note:
    link:   https://blogs.imf.org/2019/01/02/new-data-on-global-debt/
    image:  national-debt.png

synonyms:
  - bubble plot
  - bubble graph
---

is a type of [scatter plot](/scatter-plot) that displays three variables by using circles of varying size and their positions on the X and Y-axes. 

<!--more-->

Bubble charts are useful for showing correlations.[^1] The independent variable is usually shown on the X-axis and the dependent variable on the Y-axis. A third variable is represented as circle area. Importantly, it is always the circle area, not diameter or radius. Since the human eye cannot easily estimate the size of a circle, bubble charts are not suitable for communicating exact values.[^4]

It is possible to show more than three variables by color-coding circle groups and by animating the bubble chart.[^2] Clusters, outliers, and overall trends reveal themselves well on a bubble chart. However, bubble charts are easy to over-plot, reducing the readability.[^3]

The advantage of bubble charts is their ability to show trends in large data sets. Similar to a [scatter plot](/scatter-plot), the bubble chart makes the distribution shape and the outliers evident.

A disadvantage of the bubble chart is its lack of means for representing negative values and zero. Like scatter plots, they can become cluttered, in which case data can be grouped with each bubble representing an equal number of data points.


The [first bubble chart](https://en.wikipedia.org/wiki/Pie_chart#/media/File:Playfair_piecharts.jpg) appeared in William Playfair's <cite>Commercial and Political Atlas</cite> published in 1786.  Swedish statistician Hans Rosling famously used an animated bubble chart to explain [macro trends in world population](https://youtu.be/FACK2knC08E?t=452).

## Variations

### Semi-circle plot
<img src="semi-circle-plot.svg" alt="semi-circle plot" class="f-right-half" /> Since bubble charts with a lot of data points tend to become cluttered with overlapping circles, to [de-clutter a bubble chart](https://flowingdata.com/2017/10/26/how-to-make-a-semicircle-plot-in-r/), it is possible to show only half of each circle as shown in [this example from the New York Times](https://www.nytimes.com/interactive/2017/09/01/upshot/cost-of-hurricane-harvey-only-one-storm-comes-close.html?smid=tw-share&_r=0). This chart presumes that the entire circle area is perceived by the reader from seeing its half. This idea is similar to the bands that partially conceal time series graphs in a [horizon plot](/joy-plot#horizon-plot).

### Double semi-circle plot
<img src="comparative-half-bubble-plot.svg" alt="comparative half bubble plot" class="f-right-half" /> The double semi-circles allow comparison between two related numbers [displays two half-circles side by side](https://www.informationisbeautifulawards.com/showcase/604-the-analytical-tourism-map-of-piedmont) with the area of each circle being inferred from its half. Although semi-circles may be more difficult to compare visually, this variation increases the data density becoming a space-saving bubble chart variety. A similar technique is used in the [split violin plot](/violin-plot#split-violin-plot).


## Alternatives

1. [Marimekko chart](/marimekko-chart) shows categorical data as rectangles with their widths and lengths proportional to quantities and categories represented as columns. 

2. [Scatter plot](/scatter-plot) showing the distribution of two variables represented as dots along the horizontal and vertical axes. The dots can use color or shape to represent an additional variable.

2. [Proportional area chart](/proportional-area-chart) a type of one-dimensional chart that uses area of a shape to visualize a single variable without the use of axes. With few data points, a bubble chart can potentially be represented as one or a series of proportional area charts.
## Sources

[^1]: [Effectiveness of Animation in Trend Visualization](https://www.cc.gatech.edu/~stasko/papers/infovis08-anim.pdf)

[^2]: [Data Visualization: A Guide to Visual Storytelling for Libraries](https://books.google.com/books?id=wxrMDAAAQBAJ)

[^3]: [Visualization of Pareto Front Approximations in Evolutionary Multiobjective Optimization: A Critical Review and the Prosection Method](https://dis.ijs.si/tea/Publications/Tusar14tevc.pdf)

[^4]: [Graphical Perception and Graphical Methods for Analyzing Scientific Data](http://snoid.sv.vt.edu/~npolys/projects/safas/1695272.pdf)
