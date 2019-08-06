---
title:  network diagram
  
tags:
- network of relationships

related:


tools:

examples:

  - title: Chart of Neural Networks
    author: Fjodor Van Veen
    link: http://www.asimovinstitute.org
    image: types-of-neural-networks.png

  - title: The Strengths of Nations
    author: Kevin Boyack, Dick Klavans, W. Bradford Paley
    link: http://wbpaley.com/brad/mapOfScience/index.html
    image: the-strengths-of-nations.jpg
    
  - title: How Scientific Paradigms Relate
    author: Kevin Boyack, Dick Klavans, W. Bradford Paley
    link: http://wbpaley.com/brad/mapOfScience/index.html
    image: how-scientific-paradigms-relate.jpg

  - title: Most Common Family Types in America
    author: Nathan Yau
    link: https://flowingdata.com/2016/07/20/modern-family-structure/
    image: family-types.png
 

    
synonyms:
  - node-link diagram
  - vertex-edge diagram
  - network graph
---
is a visualization of entities and their relationships that together form a network structure. Each entity is a node, and each connection between nodes is a link. Any node can connect to any other node. There is no limit on the number of connects a node can have.

<!--more-->
A network diagram consists of any number of nodes that visually appear as a symbol or a block of text and the connections between them that appear as connecting lines. A node can have an unlimited number of connections. 

A line between nodes represents a connection. In *undirected network diagrams* connectors only show a relationship, not a direction in which it might move.  *Directed network diagrams* can show a one-way relationship or a two-way reciprocal relationship represented by arrows.

Nodes link to similar nodes forming groups by similarity. This kind of grouping follows the first law of geography: near things are more alike than distant things. Therefore, any two nodes should be linked via the shortest route. Clusters of similar nodes can form larger groups that can be marked with color, for example. [^saket]

Both nodes and links can have a weight that represents a value. Weighted nodes are proportional in size to their importance, number of connections, or some other variable. Weighted links use the thickness of the connecting lines to represent importance or another variable.

Any network diagram can be represented as a matrix. The relative effectiveness of network diagrams versus matrices is a matter of a long-standing debate. In short, network diagrams are more useful for showing connections and clusters. The matrix is better for group analysis and finding specific values. [^okoe]


## Sources
[^saket]: The effectiveness of node-link diagrams with nodes in groups were found more effective in *Saket, Bahador & Simonetto, Paolo & Kobourov, Stephen & Borner, Katy. (2014). [Node, Node-Link, and Node-Link-Group Diagrams: An Evaluation.](https://arxiv.org/pdf/1404.1911.pdf) IEEE Transactions on Visualization and Computer Graphics. 20. 10.1109/TVCG.2014.2346422.*
[^okoe]: Comparison of human performance over 14 different tasks with network diagrams and matrices *Okoe, Mershack & Jianu, Radu & G. Kobourov, Stephen. (2018). [Node-link or Adjacency Matrices: Old Question, New Insights.](https://www2.cs.arizona.edu/~kobourov/NL-AM-TVCG18.pdf) IEEE Transactions on Visualization and Computer Graphics. PP. 1-1. 10.1109/TVCG.2018.2865940.*
