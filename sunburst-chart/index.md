
---
title:  sunburst chart

tags:
- hierarchy
- network of relationships

related:
  - tree-diagram

tools:
  - name:   Adobe Illustrator
    link:   https://helpx.adobe.com/illustrator/using/graphs.html
    
  - name:   D3
    link:   https://beta.observablehq.com/@mbostock/d3-sunburst

  - name:   Microsoft Excel
    link:   https://support.office.com/en-us/article/create-a-sunburst-chart-in-office-4a127977-62cd-4c11-b8c7-65b84a358e0c

examples:
  - title:  Coffee Taster Flavor Wheel
    author:  World Coffee Research
    link:  https://www.scanews.coffee/wp-content/uploads/2016/01/SCAA_FlavorWheel.01.18.15.jpg
    image:  coffee-flavor-wheel.jpg

  - title: Sunburst organisational structure
    link:  https://blog.orgvue.com/is-restructuring-the-right-move/sunburst-organisational-structure/
    image:  organizational-structure.png

  - title:  Visualizing Document Content Using Language Structure
    author:  Christopher Collins
    link:  http://vialab.science.uoit.ca/portfolio/docuburst
    image:  docuburst-idea-search.png

synonyms:
  - ring chart
  - multi-level pie chart
  - radial treemap
  - nested pie chart
  - stacked pie chart
  
---

is a type of [tree map](/tree-map) in a radial layout for displaying hierarchical data. Each level of hierarchy appears as a concentric circle. The outermost circle represents the bottom of the hierarchy. The highest level of the hierarchy is the center of the sunburst chart. Any sunburst chart can also be redrawn as a treemap or as a tree diagram.


<!--more-->
The function of a sunburst chart is the representation of hierarchies and clusters. One can think of it as a tree diagram where each node becomes a sector of a circle. The linear version of the sunburst chart is the *icicle plot*. [^herbert]

 In a sunburst chart, the area between two adjacent circles represents one level in a tree structure that is one level in the hierarchy. The center serves as the root node with the hierarchy moving outward. From the root node outward each nodes appears as a segment with child nodes fitting into the angle created by their parent node.
 
Initially used for visualizing disk space usage, sunburst charts can cover a broad range of topics involving any hierarchy.
 
 When compared to a treemap, a similar chart that uses rectangles sized proportionally to values, people prefer the radial layout of the sunburst chart, which makes the hierarchy more obvious. [^stasko]

## Sources
[^herbert]: [Herbert, Ric & Webber, Richard & Jiang, Wei. (2006). Space-filling Techniques in Visualizing Output from Computer-Based Economic Models. Society for Computational Economics, Computing in Economics and Finance 2006. ](https://www.academia.edu/25926410/Space-filling_Techniques_in_Visualizing_Output_from_Computer_Based_Economic_Models)
[^stasko]: [Information Interfaces: SunBurst. by John Stasko. Retrieved May 10, 2019](https://www.cc.gatech.edu/gvu/ii/sunburst/)
