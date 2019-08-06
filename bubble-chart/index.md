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

  - title:  National Debt 
    author:  Bloomberg
    note:
    link:  https://www.bloomberg.com/graphics/2019-decade-of-debt
    image:  national-debt-comparison.png

  - title:  Debt Around the World 
    author: IMF
    note:
    link:   https://blogs.imf.org/2019/01/02/new-data-on-global-debt/
    image:  national-debt.png

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

synonyms:
  - bubble plot
---

is a type of [scatter plot](/scatter-plot) that represents three variables by using circles that vary in size and their position on the x and y axes. 

<!--more-->

Bubble charts are useful for showing *correlation*.[^1] The independent variable is usually shown on the horizontal axis and the dependent variable on the vertical axis.

Importantly, bubble size always means the circle area, not diameter or radius. Since the human eye cannot easily interpret the size of a circle into a number, bubble charts are not used in cases where readers need to see the precise numbers. <sup>3</sup>

The minimum number of variables for a bubble chart is three. For example, weight, height, and foot size. Another example, age, occupation, and the number of children. As you notice, the variables have to be dependent. An anti-example would be age, income, and nose size. Since nose size does not change with income, these data points are not dependent and cannot be used in a bubble chart.

You can show more than three variables on a bubble chart.[^2] First, the circles can be grouped using color to represent the fourth variable, for example, a categorical one. Second, a bubble chart can be animated to show the fifth variable such as time, for example.

Clusters, outliers, and overall trends reveal themselves well on a bubble chart. To maximize this effect, overplotting should be avoided. [^3]

The [first bubble chart](https://en.wikipedia.org/wiki/Pie_chart#/media/File:Playfair_piecharts.jpg) appeared in William Playfair's <cite>Commercial and Political Atlas</cite> published in 1786.

The main advantage of bubble charts is their ability to show large trends in your data. The overall shape created by the bubbles reveals the data trends, similar to a [scatter plot](/scatter-plot).

A known problem of bubble charts, as well as all types of information graphics that use circles, is that circle sizes are difficult to compare. For this reason, bubble charts are not used for comparing precise values but to show a general trend in the data and the outliers. [^4]

Another disadvantage of bubble charts is their lack of means of representing negative values or zero. Like scatter plots, they can become cluttered. Over-plotting is another issue with bubble charts that comes up when a lot of values are concentrated in one area of the chart or when there are too many data points. Making the circles partially transparent can solve this problem for overlap of two to three circles.

You can use a bubble chart if you have at least 3 variables, also called *data series*. 

The bubble chart was famously used by Swedish statistician Hans Rosling who showed macro trends in world population in his widely popular videos. In [this video called "Don't Panic"](https://youtu.be/FACK2knC08E?t=452) Rosling shows how life expectancy impacts the number of children a woman has and how both are connected to population size. Countries are grouped and colored  by continent. His bubble chart is animated which allows him to show a fifth variable which is time.

The use of circle area makes creating bubble charts by hand difficult. For example, if you want to compare two bubble where the first one show 1 and the other shows 2, you cannot do that by making circles with radius one and two. So, when making a bubble chart it is best to use a tool, such as MS Excel, MS PowerPoint, or Apple Numbers, that will apply the circle area formula for circle area for you.


## Variations

### Semi-circle plot
<img src="semi-circle-plot.svg" alt="semi-circle plot" class="f-right-half" /> Since bubble charts with a lot of data points tend to become cluttered with overlapping circles, to [de-clutter a bubble chart](https://flowingdata.com/2017/10/26/how-to-make-a-semicircle-plot-in-r/), it is possible to show only half of each circle as shown in [this example from the New York Times](https://www.nytimes.com/interactive/2017/09/01/upshot/cost-of-hurricane-harvey-only-one-storm-comes-close.html?smid=tw-share&_r=0).

### Comparative half-bubble 
<img src="comparative-half-bubble-plot.svg" alt="comparative half bubble plot" class="f-right-half" /> Another variation with the semi-circles that allows comparision between two related numbers [displays two half-circles side by side](https://www.informationisbeautifulawards.com/showcase/604-the-analytical-tourism-map-of-piedmont).


## Alternatives

An alternative to bubble charts is the [Marimekko chart](marimekko-chart). Because in a Marimekko chart we are comparing areas of rectangles, we can read precise values off the chart as well as quickly approximate with how the shapes compare in size.

Another alternative for bubble charts with groups can be a [tree map](tree-map).

## Sources

[^1]: [Effectiveness of Animation in Trend Visualization](https://www.cc.gatech.edu/~stasko/papers/infovis08-anim.pdf)

[^2]: [Data Visualization: A Guide to Visual Storytelling for Libraries](https://books.google.com/books?id=wxrMDAAAQBAJ)

[^3]: [Visualization of Pareto Front Approximations in Evolutionary Multiobjective Optimization: A Critical Review and the Prosection Method](https://dis.ijs.si/tea/Publications/Tusar14tevc.pdf)

[^4]: [Graphical Perception and Graphical Methods for Analyzing Scientific Data](http://snoid.sv.vt.edu/~npolys/projects/safas/1695272.pdf)

