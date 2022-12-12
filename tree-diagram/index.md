---
title:  tree diagram
  
functions:
  - part-to-whole relationship
  - hierarchy

visualizationTechniques:
  - connecting

related:
  - flow-map

tools:
  - name:   JS Charting
    link:   https://jscharting.com/Samples/Javascript_OrgSimpleStyling_Chart

  - name:   Zoom Charts
    link:   https://demo.zoomcharts.com/net-chart/examples/layout/layout-hierarchy

examples:
  - title:  King George VI Royal Family Tree
    link:   https://www.businessinsider.com/royal-family-tree-british-monarchy-house-of-windsor-2018-5
    image:  king-george-VI-royal-family-tree.jpeg
  - title:  Ministry of Finance The Luxembourg Government
    note:   Organization chart of ministry of finance of the luxembourg government
    link:   https://igf.gouvernement.lu/en/service/organigramme.html
    image:  ministry-of-finance-luxembourg-government.png 
  - title:  The World Religions Tree
    author: The 40 Foundation
    link:   http://silenced.co/wp-content/uploads/2014/10/religions_tree.jpg
    image:  world-religions-tree.jpg 
  - title:  The Tree of Life
    author: Leonard Eisenberg
    link:   https://www.evogeneao.com/learn/tree-of-life
    image:  tree-of-life-evolution.png 

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


## Alternatives
1. [*Flow chart*](/flow-chart) is a tree diagram that depicts the steps of a process or an algorithm.
2. [*Sankey chart*](/sankey-chart) represents a change in flow, usually over time, as the width of a flowing line that is proportional to a quantity. Sankey diagrams emphasize the transfers in a system by splitting the flow line. They can also reflect a hierarchy with weighted connections.


## Further reading
- [Tree structure](https://en.wikipedia.org/wiki/Tree_structure) article on Wikipedia.

## References
[^harris]: Harris, Robert L. [*Information graphics: A comprehensive illustrated reference.*](https://books.google.com/books?id=LT1RXREvkGIC) Oxford University Press, 2000, p.680-81. This reference gives a general definition of tree diagrams.
