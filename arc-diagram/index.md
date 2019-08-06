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
  - title:  Major Exporters of Goods to U.S. in 2017
    author:  The Wall Street Journal
    link:   https://www.wsj.com/graphics/china-emergence-of-a-trade-leviathan/
    note:   This 3D arc diagram uses weighted arcs to represent the amount of goods moving between U.S. and other countries
    image:  major-exporters-of-goods-to-united-states.png
    
  - title:  Codebases- Millions of Lines of Code
    author: David McCandless 
    link:   https://informationisbeautiful.net/visualizations/million-lines-of-code/
    note:   Uses an arc diagram to show connections between two versions of software
    image:  lines-of-code.png

  - title:  Bible Cross-References
    author: Chris Harrison
    link:   http://www.chrisharrison.net/index.php/Visualizations/BibleViz
    note:   An arc diagram showing 63,000 cross references with a bar chart inverted at bottom to show the number of connected in each node.
    image:  bible-cross-references.jpg

  - title:  Les Miserables
    author:  Gaston Sanchez
    link:   http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.707.9502&rep=rep1&type=pdf
    note:   An arc diagram showing connections between all characters in Les Misables by Victor Hugo.
    image:  les-miserables.png
    
  - title:  Autodesk Command Frequency
    author:  Autodesk Research
    link:   http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.707.9502&rep=rep1&type=pdf
    note:   An arc diagram showing frequency and sequence of commands by users of Autodesk.
    image:  autodesk-command-frequency.png

  - title:  Email Reply Procrastination
    author:  Matthias Dittich
    link:   http://www.matthiasdittrich.com/projekte/dliste/visualisations/index.html
    note:   An arc diagram showing the pairs on days on which an email was received and answered.
    image:  email-reply-procrastination.png
 
 


---

is a type of network diagram, also called "node and link" diagram. [^1] It shows connections between any two nodes out of multiple nodes positioned on a single axis.[^2] Any network diagram which is a two-dimensional chart can be represented as an arc diagram which is a one-dimensional chart.

<!--more-->

An arc diagram consists of nodes, arcs, and an axis. The number of arc connections that come out of a single node is usually represented as a bubble that is sized proportionally to the total number of connections come in and going out[^3]. In practice, an arc diagram usually does not show all possible connected pairs because of the resulting clutter, but rather it shows a subset of connections.

In 1964, mathematician Thomas Saaty proposed the first version of the arc diagram for the purpose of showing intersecting numbers.[^4] In 2001, the arc diagram was popularized by Martin Wattenberg who diagrammed songs in his project *The Shape of Song*.[^5]

The main purpose of an arc diagram is in revealing the connections between a set of values and the clusters that they might form.

Arc diagram nodes can be spaced along the axis either equidistantly based only on design considerations or based on data, for example, representing the time elapsed between events or the geographic distance represented by nodes.[^6]
The order in which nodes appear on the axis is called *node seriation*. Node seriation can be already present in the data if it is already sorted by time or distance. Otherwise, there is an option of artificially sorting data following one of the principles of information architecture, for example, alphabetically.

Arcs can have a direction and a weight. Directional arcs can be either uni- or bi-directional. Arc weight shows
the strength of connections between nodes. Weighted arcs tend to reveal clusters of connections between nearby nodes.

Arc diagrams are usually drawn on a horizontal line with the arcs facing upward[^7]. Although an arc diagram is not as effective at conveying the overall structure of data as a two-dimensional layout would be, it is possible to order the nodes in a way that reveals the clusters.
Arc connections are usually designed as semi-circles or bezier
curves, the latter being move space saving. Color and transparency can serve as visual encoding.

Arc diagrams can be integrated with other charts, for example, a bar chart or a bubble chart in which each bar or circle represents the number of connections in a node.

Arcs can be located on one or both sides of the axis.

Any arc diagram can be represented as a [network diagram](/network-diagram)
![Network diagram and arc diagram of the same data set](network-diagram-arc-diagram-comparison.png)

## Alternatives
[Hive plot](/hive-plot) - hive plots are essentially arc diagrams with multiple axes. When there is a need to display connections between different categories of nodes, the hive plot can be an alternative to constructing multiple arc diagrams.

[Network diagram](/network-diagram) - functionally the same as an arc diagram, network diagrams use two-dimensional space which makes them easier to read as long as they are uncluttered.

## References
[^1]: ["Visual Exploration of Multivariate Graphs" by Martin Wattenberg, IBM Research](http://hint.fm/papers/pivotgraph.pdf)
[^2]: ["Arc Diagrams: Visualizing Structure in Strings", IBM Research](http://ieg.ifs.tuwien.ac.at/~aigner/teaching/ws06/infovis_ue/papers/arcdiagram_01173155.pdf)
[^3]: ["Arc Diagrams in R: Les Miserables" by Gaston Sanchez](http://www.gastonsanchez.com/visually-enforced/got-plot/how-to/2013/02/02/Arc-Diagrams-in-R-Les-Miserables/)
[^4]: [The Minimum Number of Intersections in Complete Graphs](https://www.pnas.org/content/52/3/688)
[^5]: ["The Shape of Song" by Martin Wattenburg"](http://turbulence.org/Works/song/gallery/gallery.html)
[^6]: [A Visual Survey of Arc Diagrams by Till Nagel and Erik Duval](https://uclab.fh-potsdam.de/wp/wp-content/uploads/2013-a-visual-survey-of-arc-diagrams.pdf)
[^7]: [Graphs on Surfaces and Their Applications by Sergei K. Lando, Alexander K. Zvonkin, page 339](https://books.google.fr/books?id=nFnyCAAAQBAJ&pg=PA339&dq=arc+diagram&hl=en&sa=X&ved=0ahUKEwj3wNS_jZHhAhWi2uAKHQEgCi0Q6AEILTAB#v=onepage&q=arc%20diagram&f=false)
[^8]: [A Tour through the Visualization Zoo by Jeffrey Heer, Michael Bostock, and Vadim Ogievetsky](https://queue.acm.org/detail.cfm?searchterm=Mind+Maps&id=1805128)

