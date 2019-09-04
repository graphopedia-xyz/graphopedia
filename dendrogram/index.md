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
  - hierarchical clustering tree
  
---

is a type of a [tree diagram](tree-diagram) that represents hierarchies and clustering as connected nodes, starting with a root node at the top of the hierarchy and ending with leaf nodes.  

<!--more-->
The ***root node*** of the dendrogram represents the whole data set and the top of the hierarchy. Each consecutive node, called an ***internal node***, contains either one or two sub-trees. The end nodes are called ***leaf nodes***.  The leaf nodes represent the observations. 

Each node in a dendrogram splits into two lower-level nodes, making the dendrogram a binary tree. [^klemelä]

The distance between any two nodes along the ***scale axis*** reflects the degree of their dissimilarity. 

The purpose of a dendrogram is the display of hierarchies and clusters. It visualizes multivariate data showing the position of each data node within the hierarchy, the similarity of each node relative to other nodes, and the parent-child relationship for each node.

Dendrograms are used in genetics to show the pairing of genes. [Heatmaps](/heatmap) are often used in combination with dendrograms. 

Charts visually similar to dendrograms, also known as tournament bracket or bracket chart, are used in sports to illustrate the results of elimination tournaments.
  
The ordering of nodes within a dendrogram is called *seriation*. Typically, nodes representing similar items are placed near each other according to some metric without violating the hierarchy of the nodes. With large data sets, seriation becomes a problem worthy of an algorithmic solution. [^earle]
 
Dendrograms can have a horizontal or vertical orientation. The layout can be linear or circular.


## Sources

[^klemelä]: Klemelä, Jussi Sakari. [Smoothing of multivariate data: density estimation and visualization.](https://books.google.com/?id=FFb_yy3RkL0C&pg=PA199) Vol. 737. John Wiley & Sons, 2009.

[^earle]: Earle, Denise. [*Dendrogram seriation in data visualisation: algorithms and applications.*](http://mural.maynoothuniversity.ie/2442/) Diss. National University of Ireland Maynooth, 2010.
