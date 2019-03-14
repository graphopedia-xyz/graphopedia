---
layout: post

title: Alluvial Diagram

image:
  featured: alluvial-diagram.png
  main: alluvial-diagram.svg
  
tags:
  - lorem
  - dolor
  - sit-amet

related:
  - title: Sankey Chart
    link: sankey-chart
    image: sankey-chart.png
  - title: Chord Chart
    link: chord-chart
    image: chord-chart.png

tools:
  - name:   Sankey Diagram Generator <em>free tool</em>
    link:   https://sankey.csaladen.es/
    
  - name:   Plotly
    link:   https://plot.ly/javascript/sankey-diagram/

  - name:   RAWGraphs
    link:   https://rawgraphs.io/learning/how-to-make-an-alluvial-diagram/
    
  - name:   D3 Sankey Diagram
    link:   https://beta.observablehq.com/@mbostock/d3-sankey-diagram
    
    

examples:
  - title:  <cite>Pantheon the first 100 historical figures in order of influence</cite> by Valerio Pellegrini
    link:   https://www.behance.net/gallery/26338543/PANTHEON-Corriere-della-Sera-La-Lettura-181

  - title:  <cite>The Complexity of the Climate Change Flow</cite> by DensityDesign Lab
    link:   https://www.flickr.com/photos/densitydesign/31613433722/in/album-72157677740884236/


---

<dfn>Alluvial diagram</dfn> is a type of network diagram that shows the change of flow structure over time as well as its magnituge at any point in time. Alluvial diagram is similar to Sankey diagram in that both show the amount of flow between nodes using the width of the line. The difference between the two being is that an alluvial diagram allows for re-clustering of nodes.
Alluvial diagram is a variant of a [Parallel Coordinates Plot](/parallel-coordinates) but for categorical variables. Variables are assigned to vertical axes that are parallel. Values are represented with blocks on each axis. Observations are represented with alluvia (sing. “alluvium”) spanning across all the axes. 

The blocks in an alluvial diagram represent clusters of nodes. The stream lines between the blocks represent changes in the composition of these clusters over time. The height of a block represents the size of the cluster and the height of a stream line shows the size of the component.

Note: You may see the terms <dfn>sankey diagram<dfn> and <dfn>alluvial diagram</dfn> [used to refer](https://bost.ocks.org/mike/sankey/) to the same type of chart.  



Sources:
1. [Rosvall M, Bergstrom CT (2010) Mapping Change in Large Networks](https://arxiv.org/pdf/0812.1242.pdf)
2. [M. Schmidt, Energy use in a passenger car](https://Www.Ifu.Com/En/e-Sankey/Sankey-Diagram/)
