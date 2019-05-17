---
title:  network diagram
  
tags:

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
is a visualization of entities and their relationships that together form a structure. Each entity is represented by a node and each relationship by a link. Any node can be connected to any other node.

<!--more-->
A network diagram consists of any number of nodes that can be represented by a symbol or text and the connections between them. A node can have an unlimited number of connections. 

A connection is represented by a line. In *undirected network diagrams* connectors only show a relationship, not a direction is which it might move.  *Directed network diagrams* can show a one-way relationship or a two-way reciprocal relationship represented by arrows.

Nodes link to similar nodes forming groups by similarity. This follows the first law of geography: things that are closer are more similar. So two nodes should be linked via the shortest route. Clusters of similar nodes can also be combined into groups represented for example with color. [^saket]

Both nodes and links can have a weight that represents a value. Weighted nodes are proportional in size to their importance, number of connections or some other variable. Weighted links use the thinkness of the connecting line to represent importance or another variable.

Any network diagram can represented as a matrix. There is a debate about which of these types of visualization is more effective. Network diagrams are more effective for showing connections and clusters. The matrix is better for group analysis and finding specific values. [^okoe]  


## Sources
[^saket]: The effectiveness of node-link diagrams with with nodes in groups were found more effective in *Saket, Bahador & Simonetto, Paolo & Kobourov, Stephen & Borner, Katy. (2014). [Node, Node-Link, and Node-Link-Group Diagrams: An Evaluation.](https://arxiv.org/pdf/1404.1911.pdf) IEEE Transactions on Visualization and Computer Graphics. 20. 10.1109/TVCG.2014.2346422.*
[^okoe]: Comparison of human performance over 14 different tasks with network diagrams and matrices *Okoe, Mershack & Jianu, Radu & G. Kobourov, Stephen. (2018). [Node-link or Adjacency Matrices: Old Question, New Insights.](https://www2.cs.arizona.edu/~kobourov/NL-AM-TVCG18.pdf) IEEE Transactions on Visualization and Computer Graphics. PP. 1-1. 10.1109/TVCG.2018.2865940.*
