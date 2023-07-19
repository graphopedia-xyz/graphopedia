---
title:  hive plot
  
functions:
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

order: 360

---

is a visualization method for drawing networks where nodes are mapped to and located on radially positioned linear axes.

<!--more-->

The ***axes*** in a hive plot can each have different lengths and scales, or the lengths and scales can be normalized. The scale can be linear or logarithmic. Each value is indicated along its axis as a dot which also serves as a ***node*** connected to other nodes via edges.

Arcs called ***edges*** are drawn to show connections between nodes. The edges connect nodes via the shortest route, ideally without intersecting. Positioning the axes at equal angles to each other helps prevent intersecting edges. In plots with more than three axes, it is not always possible to route them without intersecting. To maximize separation between the edges, they can be drawn around the axes, or the axes can be duplicated.

The hive plot was designed as an alternative to the [network diagram](/network-diagram) for handling large datasets that display multiple connections in biostatistics.[^krzywinski] Functionally, the hive plot is the same as a [parrallel coordinates plot](/parallel-coordinates) only with the axes positioned radially. It is also similar to the [arc diagram](arc-diagram)  if the latter could have multiple axes. 

Hive plots are useful for revealing patterns and clusters. They are less useful for communicating specific values.

The hive plot was first introduced in 2011 by bioinformatics data scientist Martin Krzywinski.

## References
[^krzywinski]: Krzywinski, Martin, et al. ["Hive plots—rational approach to visualizing networks."](https://academic.oup.com/bib/article/13/5/627/412507) *Briefings in bioinformatics* 13.5 (2011): 627-644.
