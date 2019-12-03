---
title:  tree diagram
  
tags:
- part-to-whole relationship
- hierarchy

related:
  - flow-map

tools:
  - name:   JS Charting
    link:   https://jscharting.com/Samples/Javascript_OrgSimpleStyling_Chart

  - name:   Zoom Charts
    link:   https://demo.zoomcharts.com/net-chart/examples/layout/layout-hierarchy

examples:
  - title:  The Tree of Life
    author: Leonard Eisenberg
    link:   https://www.evogeneao.com/learn/tree-of-life
    image:  tree-of-life-evolution.png
    
  - title:  The World Religions Tree
    author: The 40 Foundation
    link:   http://silenced.co/wp-content/uploads/2014/10/religions_tree.jpg
    image:  world-religions-tree.jpg
  
  - title:  The World Religions Tree
    author: Minna Sundberg
    link:   http://www.sssscomic.com/comic.php?page=196
    image:  world-languages-tree.jpg

  - title:  The Tree of Knowledge Obfuscation
    author:  The Ethical Skeptic
    link:  https://i0.wp.com/theethicalskeptic.com/wp-content/uploads/2017/07/Tree-of-Knowledge-Obfuscation.png?ssl=1
    image:  tree-of-knowledge-obfuscation.png
 
  - title:  The Cognitive Bias Codex
    author: John Manoogian III
    link:   https://commons.wikimedia.org/wiki/File:Cognitive_bias_codex_en.svg
    image:  cognitive-bias-codex.png
    note:   Radial tree diagram of the cognitive biases   
    

synonyms:
  - tree chart
  - tree structure
  - tree structure diagram

order: 510

---

is a schematic representation of a hierarchy consisting of entities and their connections. Tree diagrams are [network diagrams](/network-diagram) with a hierarchical structure.

<!--more-->
A tree diagram usually starts with a single entity that represents the top of the hierarchy. 

The root node connects to its children via a *path*, also called *connector*, *branch*, *connecting line*, *link* or *arm*. The point at which a path subdivides is called a *node* or *junction*. Nodes that are at the same level of the hierarchy and sharing a parent are called *sibling nodes*. The terminal nodes of the diagram are called *leaf nodes*.

The orientation of a tree diagram can be
1. *divergent* - starting with one node and branching out into many
2. *convergent* - starting with many and merging into one
3. *radial* - showing the top of the hierarchy at the center of a circle with the lower levels that branch out.[^harris]

In addition to the orientation, a tree diagram can run horizontally from left to right or vertically from top to bottom.

The connecting lines can take on different forms: straight line, arc, or bezier curve. The nodes can have the form of rectangles, circles, or symbols. Despite its name, the tree in tree diagrams typically runs upside down or sideways.


Common uses of the tree diagram include the organizational charts, or "org charts," displaying the hierarchy of management within an organization; a family tree reflecting the genealogical tree, and a taxonomy tree showing the hierarchy of categories and terminology.

## Variations

### Radial tree diagram
Orients the tree radially with the top of the hierarchy shown at the center of the circle and the lower levels of the hierarchy branching outward. This is a space-saving layout allowing for more data density. The drawback of the radial layout is the low readability for data labels.
<!-- TODO: review -->
The radial tree (also known as radial map) is a type of a tree structure used in information graphics expands radially outward. It is one of many ways of display a tree. The chart starts at the center in the highest-order node that typically has numerous child nodes. Each child node is positioned in the next outer orbit from its parent. A radial tree has an advantage over a linear tree in terms of use of space. In a radial tree nodes are evenly distributed, whereas in a linear tree there are usually more nodes than levels which makes the entire tree occupy a rectangle much wider than its length. However, radial tree may be less effective in terms of interpretation for the viewer as one eye tracking study showed, people are more likely to scan branches of a linear tree2.

<!--
Sources
[^harris]: Harris, Robert L. [*Information graphics: A comprehensive illustrated reference.*](https://books.google.com/books?id=LT1RXREvkGIC) Oxford University Press, 2000, p.680-81. This reference gives a general definition of tree diagrams.
[^lima]: Lima, Manuel. [*The book of trees: Visualizing branches of knowledge.*] Princeton Architectural Press, 2014. This historical overview gives numerous examples of illustrated tree diagrams.
-->


### Metaphorical tree

The tree structure in information graphics is used as a metaphor to depict the hierarchies of concepts and ideas. The most common of the metaphorical trees are *the knowledge tree* and *the tree of life*. In this case, the tree diagram is often stylized to resemble trees, rivers, roots, or other natural objects, especially where the illustration fits the subject matter. [^lima]

## Alternatives
1. [*Flow chart*](/flow-chart) is a tree diagram that depicts the steps of a process or an algorithm.


2. [*Sankey chart*](/sankey-chart) represents a change in flow, usually over time, as the width of a flowing line that is proportional to a quantity. Sankey diagrams emphasize the transfers in a system by splitting the flow line. They can also reflect a hierarchy with weighted connections.


## Sources
[^harris]: Harris, Robert L. [*Information graphics: A comprehensive illustrated reference.*](https://books.google.com/books?id=LT1RXREvkGIC) Oxford University Press, 2000, p.680-81. This reference gives a general definition of tree diagrams.
[^lima]: Lima, Manuel. [*The book of trees: Visualizing branches of knowledge.*] Princeton Architectural Press, 2014. This historical overview gives numerous examples of illustrated tree diagrams.

