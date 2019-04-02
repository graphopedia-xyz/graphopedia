---
layout: post

title:  Arc Diagram

image:
  featured: arc-diagram.png
  main: arc-diagram.svg

tags:

related:
  - title: Hive Plot
    link: hive-plot
    image: hive-plot.png

  - title: Chord Chart
    link: chord-chart
    image: chord-chart.png
    
  - title: Sankey Chart
    link: sankey-chart
    image: sankey-chart.png


tools:
  - name:   D3.js
    link:   https://d3js.org/
    
  - name:   D3 code example by Robert Gove
    link:   https://bl.ocks.org/rpgove/53bb49d6ed762139f33bdaea1f3a9e1c



examples:
  - title:  <cite>Codebases millions of lines of code</cite> by InformationisBeautiful 
    link:   https://informationisbeautiful.net/visualizations/million-lines-of-code/
    note:   This is a tape diagram that uses an arc diagram to show connections between two versions of software where the thinkness of the arc shows the amount of re-used code


  - title:  <cite>Bible Cross-References</cite> by Chris Harrison
    link:   http://www.chrisharrison.net/index.php/Visualizations/BibleViz
    note:   An arc diagram showing 63,000 cross references with a bar chart inverted at bottom to show the number of connected in each node.
     
---

An arc diagram shows connections between any two nodes out of multiple nodes positioned on a single axis.[^1] The number of arc connections that come out of a single node is usually represented as a bubble that is sized proportionally to the total number of connections come in and going out[^2]. In practice, an arc diagram usually does not show all possible connected pairs because of the resulting clutter, but rather it shows a subset of connections.
In visualizations made for the web, showing more than about a hundred nodes is impractical.

In 1964, mathematician Thomas Saaty proposed the first version of the arc diagram for the purpose of showing intersecting numbers.[^3] In 2001, the arc diagram was popularized by Martin Wattenberg who diagrammed pieces of music in his project *The Shape of Song*.[^4]
###Purpose
The main purpose of a arc diagram lies in revealing the connections between a set of values adn the clusters that they might form.

And arc diagram consists of nodes, arcs, and an axis.

The nodes can be spaced along the axis either equidistantly based only on design considerations or based on data, for example, representing time that elapsed between events or geo-spatial distance represented by nodes.[^7]
The order in which nodes appear on the axis is called <dfn>node seriation</dfn>. Node seriation can be already present in the data if it is already sorted by time or distance. Otherwise, there is an option of artificially sorting data following one of the principles of information architecture, for example alphabetically.

Arcs can have a direction and a weight. Directional arcs can be either uni- or bi-directional. Arc weight shows
the strength of connections between nodes. Weighted arcs tend to reveal clusters of connections between nearby nodes.

###Usage
Arc diagrams are usually drawn on a horizontal line with the arcs facing upward[^8]. Although an arc diagram is not as effective at conveying the overall structure of data as a two-dimensional layout would be, it is possible to order the nodes in a way that reveals the clusters.
Arc connections are usually designed as semi-circles or bezier
curves, the latter being move space saving. Color and transparency can serve as visual encoding.

Arc diagrams can be integrated with other charts, for example a bar chart or a bubble chart in which each bar or circle represents the number of connections in a node.

Arcs can be located on one or both sides of the axis.

###Alternatives
[Hive plot](/hive-plot) - hive plots are essentially arc diagrams with multiple axes. When there is a need to display connections between different categories of nodes, the hive plot can be an alternative to constructing multiple arc diagrams.
Network diagram - functionally the same as an arc diagram, network diagrams use two-dimentional space which makes them easier to perceive as long as they are uncluttered.

Sources:

[^1]: ["Arc Diagrams: Visualizing Structure in Strings", IBM Research](http://ieg.ifs.tuwien.ac.at/~aigner/teaching/ws06/infovis_ue/papers/arcdiagram_01173155.pdf)
[^2]: ["Arc Diagrams in R: Les Miserables" by Gaston Sanchez](http://www.gastonsanchez.com/visually-enforced/got-plot/how-to/2013/02/02/Arc-Diagrams-in-R-Les-Miserables/)
[^3]: [The Minimum Number of Intersections in Complete Graphs](https://www.pnas.org/content/52/3/688)
[^4]: ["The Shape of Song" by Martin Wattenburg"](http://turbulence.org/Works/song/gallery/gallery.html)
[^5]: [A Visual Survey of Arc Diagrams by Till Nagel and Erik Duval](https://uclab.fh-potsdam.de/wp/wp-content/uploads/2013-a-visual-survey-of-arc-diagrams.pdf)
[^6]: [Graphs on Surfaces and Their Applications by Sergei K. Lando, Alexander K. Zvonkin, page 339](https://books.google.fr/books?id=nFnyCAAAQBAJ&pg=PA339&dq=arc+diagram&hl=en&sa=X&ved=0ahUKEwj3wNS_jZHhAhWi2uAKHQEgCi0Q6AEILTAB#v=onepage&q=arc%20diagram&f=false)
[^7]: [A Tour through the Visualization Zoo by Jeffrey Heer, Michael Bostock, and Vadim Ogievetsky](https://queue.acm.org/detail.cfm?searchterm=Mind+Maps&id=1805128)

