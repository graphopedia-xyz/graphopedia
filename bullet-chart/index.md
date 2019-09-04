---
title:  bullet chart

tags:
- comparison

related:

tools:
  - name:   Excel (using the stacked graph tool with a secondary axis for performance indicator)
    link:   https://www.anychart.com/products/anychart/gallery/Bullet_Charts/
      
  - name:   AnyChart
    link:   https://www.anychart.com/products/anychart/gallery/Bullet_Charts/

  - name:   D3
    link:   https://bl.ocks.org/mbostock/4061961
    
  - name:   Highcharts
    link:   https://www.highcharts.com/demo/bullet-graph
  
  - name:   Plot.ly
    link:   https://plot.ly/python/bullet-charts/

examples:

synonyms:
  - bullet graph

order: 250

---

is a variation of the [bar chart](/bar-chart) with an added symbol for the target value and a progress bar that approaches the target. The bullet chart includes qualitative ranges labeled from "bad" to "good," and "excellent." The bullet chart was created as an alternative to gauge charts used in dashboards. American author Stephen Few invented the bullet chart as a response to gauge charts.[^few] The bullet charts allow for easier comparison of values when positioned next to each other than the gauge charts.

<!--more-->

The purpose of the bullet chart is the comparison of value to its target. Several bullet charts that are aligned can be easily compared, making them more suitable for use in a dashboard or a multi-chart report than gauge charts.

The bullet chart is not designed to display a lot of data points. For a dashboard or an infographic with dozens of data points and their targets, it is better to use a [scatter plot](/scatter-plot) or its variations.
 
Bullet charts are relatively new, yet readers tend to understand them well because their shape reminds one of a thermometer.[^metoyer]
The bullet chart can display negative values, which are plotted to the left or towards the bottom. [^few2]
 
 
 ## Alternative charts
 1. [*Bar chart*](/bar-chart) shows values as lengths of bars. A stacked bar chart can reflect the target and current values similar to a bullet chart.
 
 2. *Gauge chart* shows values as a needle on a speedometer. The target value is usually marked.

## Sources
[^few]: [Information Dashboard Design by Stephen Few, p.151](https://the-eye.eu/public/Books/IT%20Various/information_dashboard_design.pdf)
[^metoyer]: [Understanding the Verbal Language and Structure of End-User Descriptions of Data Visualizations by Ronald Metoyer et. al., Proceedings of the SIGCHI Conference on Human Factors in Computing Systems,p.1661](https://www.microsoft.com/en-us/research/wp-content/uploads/2016/02/p1659-metoyer.pdf)
[^few2]: [Bullet Graph Design Specification by Stephen Few](https://www.perceptualedge.com/articles/misc/Bullet_Graph_Design_Spec.pdf)
