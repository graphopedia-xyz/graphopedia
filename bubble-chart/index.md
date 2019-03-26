---
layout: post

title:  Bubble Chart

image:
  featured: bubble-chart.png
  main: bubble-chart.png
  anatomy: bubble-chart.svg
  
tags:
  - correlation

related:
  - title: Scatter plot
    link: scatter-plot
    image: scatter-plot.png
  - title: Marimekko chart
    link: marimekko-chart
    image: marimekko-chart.png

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

  - title:  <cite>The Wealth & Health of Nations</cite> recreation by Mike Bostock of the Hans Rosling original chart
    link:   https://bost.ocks.org/mike/nations/

  - title:  <cite>The Language of the State of the Union</cite> by The National Post graphics team
    link:   https://nationalpostcom.files.wordpress.com/2012/01/fo0225_stateoftheunion-2.pdf
 
  - title:  <cite>Share with mental or substance disorders males vs females</cite> by Our World In Data
    link:   https://ourworldindata.org/grapher/share-with-mental-or-substance-disorders-males-vs-females
    
  - title:  <cite>Lunar Conversations. A timeline of the conversations between Earth and the spacecraft of the Apollo 11 mission from liftoff to splashdown.</cite> by Nicholas Rougeux
    link:   https://ourworldindata.org/grapher/share-with-mental-or-substance-disorders-males-vs-females
    
  - title:  <cite>Global Carbon Emissions</cite> by Stanford Kay
    link:   http://www.stanfordkaystudio.com/information.html
    
    
    
     
---

Alternative name: bubble plot

A <dfn>bubble chart</dfn> is a type of [scatter plot](/scatter-plot) that represents three variables by using circles that vary in size and their position on the x and y axes. 



Bubble charts are useful for showing *correlation*.[^1] The independent variable is usually shown on the horizontal axis and the dependent variable on the vertical axis.

Importantly, bubble size always means the circle area, not diameter or radius. Since the human eye cannot easily interpret the size of a circle into a number, bubble charts are not used in cases where readers need to see the precise numbers. <sup>3</sup>

The minimum number of variables for a bubble chart is three. For example, weight, height, and foot size. Another example, age, occupation, and number of children. As you notice, the variables have to be dependent. An anti-example would be age, income, and nose size. Since nose size does not change with income, these data points are not dependent and cannot be used in a bubble chart.

You can show more than three variables on a bubble chart.[^2] First, the circles can be grouped using color to represent a fourth variable, for example a category. Second, a bubble chart can be animated to show a fifth variable such as time, for example.

Clusters, outliers, and overall trends reveal themselves well on a bubble chart. To maximize this effect, overplotting should be avoided. [^3]

The [first bubble chart](https://en.wikipedia.org/wiki/Pie_chart#/media/File:Playfair_piecharts.jpg) appeared in William Playfair's <cite>Commercial and Political Atlas</cite> published in 1786.


### Purpose
The main advantage of bubble charts is their ability to show large trends in your data. The overall shape created by the bubbles reveals the data trends, similar to a [scatter plot](/scatter-plot).

A known problem of bubble charts, as well as all types of information graphics that use circles, is that circle sizes are difficult to compare. For this reason, bubble charts are not used for comparing precise values but to show a general trend in the data and the outliers. [^4]

Another disadvantage of bubble charts is their lack of means of representing negative values or zero. Like scatter plots, they can become cluttered. Over-plotting is another issue with bubble charts that comes up when a lor of values are concentrated in one area of the chart or when there are simple too many data points. Making the circles partially transparent can solve this problem for overlap of two to three circles.

### Usage
You can use a bubble chart if you have at least 3 variables, also called *data series*. 

For example, we can show the connection between life expectancy with the state of the economy in their country and the population size. The steps of making a bubble chart for this data would look like this:


1. On the X axis, we plot the Gross Domestic Product (GDP), from lowest to highest. 
2. On the Y axis, we plot the life expectancy, from 1 to 100. (We plot life expectancy on the Y axis because there is less of a range in numbers. Life expectancy cannot have a wide range. But GDP can vary a lot by country.) 
3. We use population size data to create circles with the area that represents those numbers.
4. (Optional) If we want to add one more variable, for example, to divide countries by continent, then we can use color to group the circles by continent.
5. (Optional) If we can animate the bubble chart or make it interactive, we could add a fifth variable, for example time. Each frame could show a one-year snapshot in the animation.

The bubble chart was used by Swedish statistician Hans Rosling who showed macro trends in world population in his widely popular videos. In [this video called "Don't Panic"](https://youtu.be/FACK2knC08E?t=452) Rosling shows how life expectancy impacts the number of children a woman has and how both are connected to population size. Countries are grouped and colored  by continent. His bubble chart is animated which allows him to show a fifth variable which is time.

The use of circle area makes creating bubble charts by hand difficult. For example, if you want to compare two bubble where the first one show 1 and the other shows 2, you cannot do that by making circles with radius one and two. So, when making a bubble chart it is best to use a tool, such as MS Excel, MS PowerPoint, or Apple Numbers, that will apply the circle area formula for circle area for you.

Bubble charts can be created using templates in MS PowerPoint, MS Excel, Apple Keynote and Apple Numbers. These common programs already have pre-built tools that create bubble charts. 
An interactive bubble chart can be created on Gapminder, which is free desktop software used by Hans Rosling.


### Alternative Charts

An alternative to bubble charts is the [Marimekko chart](marimekko-chart). Because in a Marimekko chart we are comparing areas of rectangles, we can read precise values off the chart as well as quickly approximate with how the shapes compare in size.

Another alternative for bubble charts with groups can be a [tree map](tree-map).


### Variations

1. Semi-circle plot - since bubble charts with a lot of data points tend to become cluttered with overlapping circles, to [de-clutter a bubble chart](https://flowingdata.com/2017/10/26/how-to-make-a-semicircle-plot-in-r/), it is possible to show only half of each circle as shown in [this example from the New York Times](https://www.nytimes.com/interactive/2017/09/01/upshot/cost-of-hurricane-harvey-only-one-storm-comes-close.html?smid=tw-share&_r=0).
2. Comparative half-bubble - another variation with the semi-circles that allows comparision between two related numbers [displays two half-circles side by side](https://www.informationisbeautifulawards.com/showcase/604-the-analytical-tourism-map-of-piedmont).git 

#### Sources

[^1]: [Effectiveness of Animation in Trend Visualization](https://www.cc.gatech.edu/~stasko/papers/infovis08-anim.pdf)

[^2]: [Data Visualization: A Guide to Visual Storytelling for Libraries](https://books.google.com/books?id=wxrMDAAAQBAJ)

[^3]: [Visualization of Pareto Front Approximations in Evolutionary Multiobjective Optimization: A Critical Review and the Prosection Method](https://dis.ijs.si/tea/Publications/Tusar14tevc.pdf)

[^4]: [Graphical Perception and Graphical Methods for Analyzing Scientific Data](http://snoid.sv.vt.edu/~npolys/projects/safas/1695272.pdf)

