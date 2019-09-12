---
title: alluvial diagram

tags:
- change over time
- network of relationships


related:
  - sankey-chart
  - chord-chart
  - parallel-coordinates

tools:
  - name:   Sankey Diagram Generator
    link:   https://sankey.csaladen.es
    
  - name:   Plotly
    link:   https://plot.ly/javascript/sankey-diagram/

  - name:   RAWGraphs
    link:   https://rawgraphs.io/learning/how-to-make-an-alluvial-diagram/
    
  - name:   GGAlluvial
    link:   https://github.com/corybrunson/ggalluvial

  - name:   D3 Sankey Diagram
    link:   https://beta.observablehq.com/@mbostock/d3-sankey-diagram 

examples:
  - title:  European Asylum Seeker Application Decisions
    author:  The Economist
    link:  https://www.economist.com/graphic-detail/2015/05/12/seeking-safety
    image:  asylum-seeker-applications.jpg

  - title:  Electric Vehicle Investment Flows By Country of Origin of Automaker
    author:  Thompson Reuters
    link:  http://graphics.reuters.com/AUTOS-INVESTMENT-ELECTRIC/010081ZB3HD/index.html
    image:  electric-vehicle-investment-by-country.png
    
  - title:  Pantheon the first 100 historical figures in order of influence
    author:  Valerio Pellegrini
    link:  https://www.behance.net/gallery/26338543/PANTHEON-Corriere-della-Sera-La-Lettura-181
    note: 
    image:  100-historical-figures-in-order-of-influence.jpg

  - title:  Dawn of Nanosats
    author: Valerio Pellegrini
    link:  https://www.behance.net/gallery/31057625/WIRED-UK-Dawn-of-the-Nanosats
    note: 
    image:  the-dawn-of-the-nano-sats.jpg

  - title:  The Complexity of the Climate Change Flow
    author:  DensityDesign Lab
    link:  https://www.flickr.com/photos/densitydesign/31613433722/in/album-72157677740884236/
    image:  the-complexity-of-the-climate-change-flow.jpg
  
synonyms:
  - parallel sets
  

---

is a type of graph that shows changes in the amount of flow between entities as the thickness of a line. Alluvial diagrams can be considered a type of [network diagram](/network-diagram) that shows changes in network structure over time. 
<!--more-->


In an alluvial diagram, ***categories*** are represented as boxes from which the flow lines originate. 

Each ***flow line*** represents a variable, and its thickness at any point - its value. Where flow lines re-***cluster***, a new box forms. All lines can both split and merge back into the flow. The box width is scaled according to the number of incoming flow lines and their widths. 
 
The X-axis and Y-axis are normally not shown with only the category labels appearing next to the bands. Typically, the direction of the flow lines represents time. Importantly, the clusters have to appear in the temporal order. [^borner]
The diagram begins and ends with the boxes reflecting the current composition of the categories.
 
The alluvial diagram first appeared in 2010[^rosvall] defined as showing "changes in the clustering structure from one period to the next are represented by the mergers and divergences that occur in the ribbons linking the blocks." 

Alluvial diagrams can also be considered a variant of [parallel coordinates plot](/parallel-coordinates) for categorical variables. [^kosara]

The terms *Sankey diagram* and *alluvial diagram* are sometimes used to refer to the same type of chart, for example by D3 creator Mick Bostock [^bostock] and author Andy Kirk. [^kirk]
Unlike [Sankey diagrams](/sankey-chart), alluvial diagrams can re-cluster the streams.

## Alternatives

1. [*Chord diagram*](/chord-diagram) represents weighted relationships between categories. Unlike the alluvial diagram, it does not show the change over time, but a single snapshot in time. Another requirement is that all categories have to be of the same type. For example, a chord diagram can show connections between countries but not between countries and cities.
2. [*Tree diagram*](/tree-diagram) displays a hierarchical structure consisting of nodes and links.

## Sources
[^borner]: Börner, Katy. [*Atlas of knowledge: Anyone can map.*](https://books.google.com/books?id=Fe-cBwAAQBAJ) MIT Press, 2015. p. 63.
[^rosvall]: Rosvall, Martin, and Carl T. Bergstrom. ["Mapping change in large networks."](https://doi.org/10.1371/journal.pone.0008694gatsby ) *PloS one 5.1* (2010): e8694. [PDF](https://arxiv.org/pdf/0812.1242.pdf)
[^kosara]: Bendix, Fabian, Robert Kosara, and Helwig Hauser. ["Parallel sets: visual analysis of categorical data."](https://doi.org/10.1145/1124772.1124891) *IEEE Symposium on Information Visualization, 2005. InfoVis 2005. IEEE*, 2005. [PDF](https://kosara.net/papers/2005/Bendix-InfoVis-2005.pdf)
[^bostock]: [Mike Bostock's D3 gallery website](https://bost.ocks.org/mike/sankey/)
[^kirk]: Kirk, Andy. [*Data visualisation: a handbook for data driven design.*](https://books.google.com/books?id=wNpsDAAAQBAJ) Sage, 2016. 
