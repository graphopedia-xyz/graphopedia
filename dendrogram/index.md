---
title:  dendrogram
  
tags:
- hierarchy

related:
  - tree-diagram
  - heatmap

tools:
  - name:   Challonge Tournament Bracket Generator
    link:   https://challonge.com/tournaments/bracket_generator
 
  - name:   Displayr
    link:  https://www.displayr.com/what-is-dendrogram/

  - name:   Plotly using Python
    link:   https://plot.ly/python/dendrogram/

  - name:   R dendrogram tutorial
    link:   https://uc-r.github.io/hc_clustering

examples:
  - title:  Insect Tree of Life
    author: Valerio Pellegrini
    link:   https://www.behance.net/gallery/72731351/TERRA-MATER-Ahnenforschung
    image:  insects-tree-of-life.jpg

  - title:  The Circle of Life Forms
    author: Martin Krzywinski
    link:   https://www.sactownmag.com/biogenome_v09_outlines.jpg
    image:  biogenome.jpg

  - title:  Cladogram of Cetacea within Artiodactyla
    link:   https://en.wikipedia.org/wiki/File:Cladogram_of_Cetacea_within_Artiodactyla.png
    image:  cladogram-of-cetacea-within-artiodactyla.png
    
  - title:  Hierarchical Cluster Analysis Map of IA competencies
    link:   https://www.iainstitute.org/sites/default/files/ia.comptencies.graphs.pdf
    image:  ia-competencies.png
    
synonyms:
  - tournament bracket
  - bracket chart
  
---

is a type of a tree diagram that represents hierarchies and clustering. The root node of the dendrogram represents the whole data set and the top of the hierarchy. Each leaf node is one step lower in the hierarchy. 
The intermediate nodes between any two levels of the hierarchy describe the extent that the nodes are removed from each other in the hierarchy which reflects the degree of their dissimilarity. The height of the dendrogram represents the distance between each pair of clusters.

<!--more-->

The purpose of a dendrogram is the display of hierarchies and clusters. It visualizes multivariate data showing the position of each data node within the hierarchy, the similarity of each node relative to other nodes, and the parent-child relationship for each node.

Dendrograms are used in genetics to show the pairing of genes. [Heatmaps](/heatmap) are often used in combination with dendrograms. Charts visually similar to dendrograms are used in sports to illustrate the results of elimination tournaments.
 
 
 The ordering of nodes within a dendrogram is called *seriation*. Normally, nodes representing similar items are placed near each other according to some metric without violating the hierarchy of the nodes. With large data sets, seriation becomes a problem worthy of an algorithmic solution.[^earle]
 
 Dendrograms can have a horizontal or vertical orientation. The layout can be linear or circular.


## Sources

[^earle]: [Earle, Denise. Dendrogram seriation in data visualisation: algorithms and applications. Diss. National University of Ireland Maynooth, 2010.](http://mural.maynoothuniversity.ie/2442/)

