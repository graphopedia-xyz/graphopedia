---
title:  arc diagram

tags:
- network of relationships

related:
  - hive-plot
  - chord-chart  
  - sankey-chart

tools:
  - name:   D3.js
    link:   https://d3js.org/

  - name:   D3 code example by Robert Gove
    link:   https://bl.ocks.org/rpgove/53bb49d6ed762139f33bdaea1f3a9e1c

examples:
  - title:  Major Exporters of Goods to the U.S. in 2017
    author:  The Wall Street Journal
    link:   https://www.wsj.com/graphics/china-emergence-of-a-trade-leviathan/
    note:   This 3D arc diagram uses weighted arcs to represent the number of goods moving between the U.S. and other countries
    image:  major-exporters-of-goods-to-united-states.png
    
  - title:  Codebases- Millions of Lines of Code
    author: David McCandless 
    link:   https://informationisbeautiful.net/visualizations/million-lines-of-code/
    note:   Uses an arc diagram to show connections between two versions of the software
    image:  lines-of-code.png

  - title:  Bible Cross-References
    author: Chris Harrison
    link:   http://www.chrisharrison.net/index.php/Visualizations/BibleViz
    note:   An arc diagram showing 63,000 cross-references with a bar chart inverted at the bottom to indicate the number of connections in each node.
    image:  bible-cross-references.jpg

  - title:  Les Miserables
    author:  Gaston Sanchez
    link:   http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.707.9502&rep=rep1&type=pdf
    note:   An arc diagram showing connections between all characters in Les Miserables by Victor Hugo.
    image:  les-miserables.png
    
  - title:  Autodesk Command Frequency
    author:  Autodesk Research
    link:   http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.707.9502&rep=rep1&type=pdf
    note:   An arc diagram showing frequency and sequence of commands by users of Autodesk.
    image:  autodesk-command-frequency.png

  - title:  Email Reply Procrastination
    author:  Matthias Dittrich
    link:   http://www.matthiasdittrich.com/projekte/dliste/visualisations/index.html
    note:   An arc diagram showing the pairs on days on which an email was received and answered.
    image:  email-reply-procrastination.png
 
 


---

is a type of network diagram, also called "node and link" diagram.[^1] It shows connections between any two nodes out of multiple nodes positioned on a single axis.[^2] Any network diagram, which is a two-dimensional chart, can be represented as an arc diagram, which is a one-dimensional chart.

<!--more-->

An arc diagram consists of nodes, arcs, and an axis. The number of arc connections that come out of a single node appears as a bubble sized proportionally to the total number of links coming in and going out.[^3] In practice, an arc diagram usually does not show all possible connected pairs because of the resulting clutter, but rather it shows a subset of connections.

In 1964, mathematician Thomas Saaty proposed the first version of the arc diagram to show intersecting numbers.[^4] In 2001, the arc diagram was popularized by Martin Wattenberg who diagrammed songs in his project *The Shape of Song*.[^5]

The primary purpose of an arc diagram is in revealing the connections between a set of values and the clusters that they might form.

Node spacing along the X-axis is either equidistant or at distances based on the data, for example, representing the time elapsed or the geographic distances.[^6]
The order in which nodes appear on the axis is called *node seriation*.[^7] Node seriation can be already present in sorted data ordered by time or distance. 

Arcs can have a direction and a weight with directional arcs being either uni- or bi-directional. Arc weight shows the strength of connections between nodes. Weighted arcs tend to reveal clusters of connections between nearby nodes.

Any arc diagram can be represented as a [network diagram](/network-diagram)
![Network diagram and arc diagram of the same data set](network-diagram-arc-diagram-comparison.png)
Generally, arc diagrams are less useful for revealing clusters than network diagrams. Still, it is possible to order the nodes in a way that reveals clusters.

Arc connections typically use semi-circles or bezier curves, the latter being more space-saving. Color and transparency can encode an additional layer of data.

Arc diagrams can combine with other charts, for example, a [bar chart](/bar-chart) or a [bubble chart ](/bubble-chart) in which each bar or circle is proportional to the number of connections in a node.

Arc diagrams typically have a horizontal orientation with the arcs facing upward,[^8] but they can also appear on both sides of the axis.

## Alternatives
[Hive plot](/hive-plot) - hive plots are essentially arc diagrams with multiple axes. When there is a need to display connections between different categories of nodes, the hive plot can be an alternative to constructing multiple arc diagrams.

[Network diagram](/network-diagram) - functionally the same as an arc diagram, network diagrams use two-dimensional space, which makes them easier to read as long as they are uncluttered.

## References
[^1]: ["Visual Exploration of Multivariate Graphs" by Martin Wattenberg, IBM Research](http://hint.fm/papers/pivotgraph.pdf)
[^2]: ["Arc Diagrams: Visualizing Structure in Strings", IBM Research](http://ieg.ifs.tuwien.ac.at/~aigner/teaching/ws06/infovis_ue/papers/arcdiagram_01173155.pdf)
[^3]: ["Arc Diagrams in R: Les Miserables" by Gaston Sanchez](http://www.gastonsanchez.com/visually-enforced/got-plot/how-to/2013/02/02/Arc-Diagrams-in-R-Les-Miserables/)
[^4]: [The Minimum Number of Intersections in Complete Graphs](https://www.pnas.org/content/52/3/688)
[^5]: ["The Shape of Song" by Martin Wattenburg"](http://turbulence.org/Works/song/gallery/gallery.html)
[^6]: [A Visual Survey of Arc Diagrams by Till Nagel and Erik Duval](https://uclab.fh-potsdam.de/wp/wp-content/uploads/2013-a-visual-survey-of-arc-diagrams.pdf)
[^7]: [A Tour through the Visualization Zoo by Jeffrey Heer, Michael Bostock, and Vadim Ogievetsky](https://queue.acm.org/detail.cfm?searchterm=Mind+Maps&id=1805128) Section on Arc Diagrams. Retrieved Aug-1-2019
[^8]: [Graphs on Surfaces and Their Applications by Sergei K. Lando, Alexander K. Zvonkin, page 339](https://books.google.fr/books?id=nFnyCAAAQBAJ&pg=PA339&dq=arc+diagram&hl=en&sa=X&ved=0ahUKEwj3wNS_jZHhAhWi2uAKHQEgCi0Q6AEILTAB#v=onepage&q=arc%20diagram&f=false)

