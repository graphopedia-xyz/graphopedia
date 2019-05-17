---
title:  hive plot
  
tags:

related:
  - arc-diagram

tools:
  - name:   D3.js
    link:   https://bost.ocks.org/mike/hive/

  - name:   Python tutorial
    link:   https://github.com/hallamlab/HivePanelExplorer/wiki/Hive-Panel-Explorer-Beginner's-Guide
    
  - name:   HiveGraph
    link:   http://wodaklab.org/hivegraph/graph
    
examples:
  - title:  Genes of Interest
    author: Martin Krzywinski
    link:   http://www.hiveplot.com/img/web-title-large.png
    image:  genes-of-interest.png

---

is a visualization method for drawing networks where nodes are mapped to and located on radially positioned linear axes. Arcs called *edges* are drawn to show connections between nodes.

<!--more-->
The hive plot was conceived as an alternative to a [network diagram](network-diagram) for handling large datasets that display multiple connections in biostatistics.[^krzywinski] Functionally, the hive plot is a [parrallel coordinates plot](/parallel-coordinates) with the axes positioned radially. It is also similar to the [arc diagram](arc-diagram) if it had multiple axes. 

The axes in a hive plot can each have their own lengths or normalized lengths and own scale. The scale can be linear or logarithmic. 
The edges connect nodes via the shortest route. In plots with more than three axes it is not always possible to rout them without intersection. To avoid intersection, edges can be draw around the axes or the axes can be duplicated.

To prevent edges from intersecting, hive plots normally position axes at equal angles to each other. 
Hive plots are useful for revealing patterns and clusters. They are less useful for communicating specific values.


The hive plot was first introduced in 2011 by bioinformatics data scientist Martin Krzywinski.

## Sources
[^krzywinski]: Martin Krzywinski, Inanc Birol, Steven JM Jones, Marco A Marra, [Hive plots—rational approach to visualizing networks, Briefings in Bioinformatics,](https://academic.oup.com/bib/article/13/5/627/412507) Volume 13, Issue 5, September 2012, Pages 627–644, https://doi.org/10.1093/bib/bbr069
