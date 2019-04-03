---
title: Alluvial Diagram

tags:

related:
  - sankey-chart
  - chord-chart
  - parallel-coordinates

tools:
  - name:   Sankey Diagram Generator <em>free tool</em>
    link:   https://sankey.csaladen.es/
    
  - name:   Plotly
    link:   https://plot.ly/javascript/sankey-diagram/

  - name:   RAWGraphs
    link:   https://rawgraphs.io/learning/how-to-make-an-alluvial-diagram/
    
  - name:   GGAlluvial
    link:   https://github.com/corybrunson/ggalluvial

  - name:   D3 Sankey Diagram
    link:   https://beta.observablehq.com/@mbostock/d3-sankey-diagram 

examples:
  - title:  Pantheon the first 100 historical figures in order of influence
    author: Valerio Pellegrini
    link:   https://www.behance.net/gallery/26338543/PANTHEON-Corriere-della-Sera-La-Lettura-181
    note: 

  - title:  The Complexity of the Climate Change Flow
    author: DensityDesign Lab
    link:   https://www.flickr.com/photos/densitydesign/31613433722/in/album-72157677740884236/

---

<dfn>Alluvial diagram</dfn> is a type of network diagram that shows changes of flow over time. Alluvial diagrams are a type of Sankey diagram. Both show the amount of flow between nodes using the width of the line. The difference between the two is that the alluvial diagram shows clusters arranged by time or stages.

<!--more-->

The alluvial diagram was first described in 2010[^1] and defined as showing "changes in the clustering structure from one time period to the next are represented by the mergers and divergences that occur in the ribbons linking the blocks". In other words, in alluvial diagrams, lines can both split and merge back into the flow. Importantly, the clusters have to be displayed in temporal order[^3].


The blocks in an alluvial diagram represent clusters of nodes. The stream lines between the blocks represent changes in the composition of these clusters over time. The height of a block represents the size of the cluster and the height of a stream line shows the size of the component.

Alluvial diagram can also be viewed as a variant of [Parallel Coordinates Plot](/parallel-coordinates) for categorical variables.[^4]

Note: You may see the terms *sankey diagram* and *alluvial diagram* used to refer to the same type of chart, for example by D3 creator Mick Bostock[^5] and author Andy Kirk[^6].
 
## Purpose
The alluvial diagram are designed to show connections between categories over time. The main purpose of this diagram is representation of splitting and merging of parts of categories into each other. 

## Usage
To create an alluvial diagram, at least two categories are needed and at least two time points at which we will show the how the connections between these parts have changed.

## Alternative Charts

[Chord chart](chord-chart) - a chord chart represents weighted relationships between categories. Unlike the alluvial diagram, it does not show the change over time, but a single snapshot in time. Another restriction is that all the categories in a cord chart have to be of the same type - for example all countries and not a combination of countries and cities.

## Sources:

[^1]: [Rosvall M, Bergstrom CT (2010) Mapping Change in Large Networks](https://arxiv.org/pdf/0812.1242.pdf)
[^2]: [M. Schmidt, Energy use in a passenger car](https://Www.Ifu.Com/En/e-Sankey/Sankey-Diagram/)
[^3]: [Atlas of Knowledge: Anyone Can Map by Katy Börner, page 63](https://books.google.com/books?id=Fe-cBwAAQBAJ&pg=PA63&lpg=PA63&dq=alluvial+diagram+ribbons&source=bl&ots=kELwexv5TN&sig=ACfU3U0C3u3tM4f7B3LTesoUHajwArSEVg&hl=en&sa=X&ved=2ahUKEwjlsv7Sz5DhAhUixIUKHYChAAI4ChDoATADegQICBAB#v=onepage&q=alluvial%20diagram%20ribbons&f=false)
[^4]: [Creating Alluvial Diagrams by Michał Bojanowski](https://cran.r-project.org/web/packages/alluvial/vignettes/alluvial.html)
[^5]: [Data Visualisation: A Handbook for Data Driven Design by Andy Kirk](https://books.google.com/books?id=wNpsDAAAQBAJ&lpg=PA190&dq=alluvial%20diagram&pg=PA190#v=onepage&q=alluvial%20diagram&f=false)
[^6]: [Mike Bostock's D3 gallery website](https://bost.ocks.org/mike/sankey/)
