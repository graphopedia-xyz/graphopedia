---
title:  hive plot
  
tags:
- network of relationships

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
The hive plot was designed as an alternative to the [network diagram](/network-diagram) for handling large datasets that display multiple connections in biostatistics.[^krzywinski] Functionally, the hive plot is the same as a [parrallel coordinates plot](/parallel-coordinates) only with the axes positioned radially. It is also similar to the [arc diagram](arc-diagram)  if the latter could have multiple axes. 

The axes in a hive plot can each have different lengths and scales, or the lengths and scales can be normalized. The scale can be linear or logarithmic. 

The edges connect nodes via the shortest route, optimally without intersecting. Positioning the axes at equal angles to each other helps prevent intersecting edges. In plots with more than three axes, it is not always possible to route them without intersecting. To maximize separation between the edges, they can be drawn around the axes, or the axes can be duplicated.

Hive plots are useful for revealing patterns and clusters. They are less useful for communicating specific values.

The hive plot was first introduced in 2011 by bioinformatics data scientist Martin Krzywinski.

## Sources
[^krzywinski]: Martin Krzywinski, Inanc Birol, Steven JM Jones, Marco A Marra, [Hive plots—a rational approach to visualizing networks, Briefings in Bioinformatics,](https://academic.oup.com/bib/article/13/5/627/412507) Volume 13, Issue 5, September 2012, Pages 627–644, https://doi.org/10.1093/bib/bbr069
